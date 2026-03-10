# Server Metrics 2026-03-10 19:20:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 17599.0 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557172
telemt_connections_bad_total 7988
telemt_handshake_timeouts_total 3603
telemt_upstream_connect_attempt_total 3551
telemt_upstream_connect_success_total 3542
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 13051
telemt_me_reconnect_success_total 2591
telemt_me_reader_eof_total 2927
telemt_me_idle_close_by_peer_total 2927
telemt_me_route_drop_no_conn_total 232255
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526257
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2756
telemt_desync_full_logged_total 746
telemt_desync_suppressed_total 2010
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 1057
telemt_desync_frames_bucket_total{bucket="gt_10"} 964
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2929
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2585
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 526163
telemt_user_connections_current{user="hello"} 1100
telemt_user_octets_from_client{user="hello"} 7861915092 (7.32 GB)
telemt_user_octets_to_client{user="hello"} 152440593292 (141.97 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17655.9 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241533
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 16494
telemt_upstream_connect_attempt_total 8851
telemt_upstream_connect_success_total 6107
telemt_upstream_connect_fail_total 2744
telemt_upstream_connect_attempts_per_request{bucket="1"} 8851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1880
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2744
telemt_me_keepalive_timeout_total 707
telemt_me_reconnect_attempts_total 3979
telemt_me_reconnect_success_total 3195
telemt_me_reader_eof_total 3339
telemt_me_idle_close_by_peer_total 3337
telemt_me_route_drop_no_conn_total 131134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204599
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 918
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 321
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3253
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3174
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 206556
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 2203542382 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 49867364350 (46.44 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 17662.7 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400928
telemt_connections_bad_total 1333
telemt_handshake_timeouts_total 32046
telemt_upstream_connect_attempt_total 5407
telemt_upstream_connect_success_total 5324
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 5407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 6789
telemt_me_reconnect_success_total 3340
telemt_me_reader_eof_total 3556
telemt_me_idle_close_by_peer_total 3556
telemt_me_route_drop_no_conn_total 136055
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342530
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1097
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 793
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 371
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3507
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3329
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 343482
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 4803220785 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 108938602333 (101.46 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 17656.2 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263634
telemt_connections_bad_total 17464
telemt_handshake_timeouts_total 23328
telemt_upstream_connect_attempt_total 4839
telemt_upstream_connect_success_total 4839
telemt_upstream_connect_attempts_per_request{bucket="1"} 4839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 4925
telemt_me_reconnect_success_total 3911
telemt_me_reader_eof_total 4088
telemt_me_idle_close_by_peer_total 4088
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 86437
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211882
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 559
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3982
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 3898
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 211655
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 3423070224 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 61893063164 (57.64 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17655.7 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278268
telemt_connections_bad_total 820
telemt_handshake_timeouts_total 1870
telemt_upstream_connect_attempt_total 5371
telemt_upstream_connect_success_total 5352
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 5371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 4438
telemt_me_reconnect_success_total 4405
telemt_me_reader_eof_total 4534
telemt_me_idle_close_by_peer_total 4534
telemt_me_route_drop_no_conn_total 103499
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263047
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1457
telemt_desync_full_logged_total 531
telemt_desync_suppressed_total 926
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4468
telemt_me_writer_restored_same_endpoint_total 4405
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 262976
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 5367062548 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 82970244656 (77.27 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 81
```