# Server Metrics 2026-03-11 08:28:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 64899.6 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1339537
telemt_connections_bad_total 15722
telemt_handshake_timeouts_total 39929
telemt_upstream_connect_attempt_total 13408
telemt_upstream_connect_success_total 13399
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 749
telemt_me_reconnect_attempts_total 21796
telemt_me_reconnect_success_total 10111
telemt_me_reader_eof_total 10976
telemt_me_idle_close_by_peer_total 10976
telemt_me_route_drop_no_conn_total 493779
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1213602
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5997
telemt_desync_full_logged_total 1662
telemt_desync_suppressed_total 4335
telemt_desync_frames_bucket_total{bucket="1_2"} 1574
telemt_desync_frames_bucket_total{bucket="3_10"} 2283
telemt_desync_frames_bucket_total{bucket="gt_10"} 2140
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10575
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10105
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1213263
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 16235292624 (15.12 GB)
telemt_user_octets_to_client{user="hello"} 352538769224 (328.33 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64956.4 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519459
telemt_connections_bad_total 8011
telemt_handshake_timeouts_total 28954
telemt_upstream_connect_attempt_total 22473
telemt_upstream_connect_success_total 19549
telemt_upstream_connect_fail_total 2924
telemt_upstream_connect_attempts_per_request{bucket="1"} 22473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2924
telemt_me_keepalive_timeout_total 2059
telemt_me_reconnect_attempts_total 14162
telemt_me_reconnect_success_total 13331
telemt_me_reader_eof_total 14103
telemt_me_idle_close_by_peer_total 14101
telemt_me_route_drop_no_conn_total 220800
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439634
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2128
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1476
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13487
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13309
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 441876
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 4310767486 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 118185216808 (110.07 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 64956.3 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 878289
telemt_connections_bad_total 7187
telemt_handshake_timeouts_total 57938
telemt_upstream_connect_attempt_total 17619
telemt_upstream_connect_success_total 17404
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 17619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 753
telemt_me_reconnect_attempts_total 25417
telemt_me_reconnect_success_total 13058
telemt_me_reader_eof_total 14049
telemt_me_idle_close_by_peer_total 14049
telemt_me_route_drop_no_conn_total 295754
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 776508
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2239
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1577
telemt_desync_frames_bucket_total{bucket="1_2"} 532
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 895
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 13609
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13047
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 551
telemt_user_connections_total{user="hello"} 777289
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 9204222189 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 234987673653 (218.85 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 64956.6 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662956
telemt_connections_bad_total 60756
telemt_handshake_timeouts_total 64559
telemt_upstream_connect_attempt_total 18038
telemt_upstream_connect_success_total 18038
telemt_upstream_connect_attempts_per_request{bucket="1"} 18038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 683
telemt_me_reconnect_attempts_total 15825
telemt_me_reconnect_success_total 14773
telemt_me_reader_eof_total 15697
telemt_me_idle_close_by_peer_total 15696
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 206056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516418
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1233
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 14947
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14751
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 515794
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 6066786020 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 141841735116 (132.10 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64956.4 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697065
telemt_connections_bad_total 5976
telemt_handshake_timeouts_total 6656
telemt_upstream_connect_attempt_total 17912
telemt_upstream_connect_success_total 17840
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 723
telemt_me_reconnect_attempts_total 18248
telemt_me_reconnect_success_total 14457
telemt_me_reader_eof_total 15284
telemt_me_idle_close_by_peer_total 15284
telemt_me_route_drop_no_conn_total 235212
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633566
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2815
telemt_desync_full_logged_total 1062
telemt_desync_suppressed_total 1753
telemt_desync_frames_bucket_total{bucket="1_2"} 985
telemt_desync_frames_bucket_total{bucket="3_10"} 1178
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 14759
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14457
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 633259
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 10362895511 (9.65 GB)
telemt_user_octets_to_client{user="hello"} 230415708086 (214.59 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 87
```