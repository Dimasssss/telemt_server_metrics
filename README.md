# Server Metrics 2026-03-11 05:40:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 54830.8 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1070776
telemt_connections_bad_total 12623
telemt_handshake_timeouts_total 37518
telemt_upstream_connect_attempt_total 11656
telemt_upstream_connect_success_total 11647
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 547
telemt_me_reconnect_attempts_total 20552
telemt_me_reconnect_success_total 8873
telemt_me_reader_eof_total 9657
telemt_me_idle_close_by_peer_total 9657
telemt_me_route_drop_no_conn_total 394534
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 960780
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4399
telemt_desync_full_logged_total 1248
telemt_desync_suppressed_total 3151
telemt_desync_frames_bucket_total{bucket="1_2"} 1217
telemt_desync_frames_bucket_total{bucket="3_10"} 1659
telemt_desync_frames_bucket_total{bucket="gt_10"} 1523
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9320
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8867
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 960484
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 12951072896 (12.06 GB)
telemt_user_octets_to_client{user="hello"} 280244126220 (261.00 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 54887.5 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413480
telemt_connections_bad_total 3197
telemt_handshake_timeouts_total 19571
telemt_upstream_connect_attempt_total 20216
telemt_upstream_connect_success_total 17309
telemt_upstream_connect_fail_total 2907
telemt_upstream_connect_attempts_per_request{bucket="1"} 20216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2907
telemt_me_keepalive_timeout_total 1792
telemt_me_reconnect_attempts_total 12443
telemt_me_reconnect_success_total 11622
telemt_me_reader_eof_total 12277
telemt_me_idle_close_by_peer_total 12275
telemt_me_route_drop_no_conn_total 193138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355278
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1877
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 1314
telemt_desync_frames_bucket_total{bucket="1_2"} 594
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 11756
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11601
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 357549
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 3570287410 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 87733566636 (81.71 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 54887.5 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706606
telemt_connections_bad_total 5986
telemt_handshake_timeouts_total 38606
telemt_upstream_connect_attempt_total 14791
telemt_upstream_connect_success_total 14596
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 14791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 575
telemt_me_reconnect_attempts_total 21855
telemt_me_reconnect_success_total 10783
telemt_me_reader_eof_total 11645
telemt_me_idle_close_by_peer_total 11645
telemt_me_route_drop_no_conn_total 238007
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631105
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1782
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1259
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 635
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11271
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10772
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 631962
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 7650266701 (7.12 GB)
telemt_user_octets_to_client{user="hello"} 187783121353 (174.89 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 54887.9 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537998
telemt_connections_bad_total 51552
telemt_handshake_timeouts_total 55998
telemt_upstream_connect_attempt_total 15774
telemt_upstream_connect_success_total 15774
telemt_upstream_connect_attempts_per_request{bucket="1"} 15774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 498
telemt_me_reconnect_attempts_total 14079
telemt_me_reconnect_success_total 13036
telemt_me_reader_eof_total 13823
telemt_me_idle_close_by_peer_total 13823
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 159006
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415789
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 891
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 524
telemt_desync_frames_bucket_total{bucket="1_2"} 328
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13186
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13014
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 415387
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 5045333944 (4.70 GB)
telemt_user_octets_to_client{user="hello"} 114410269312 (106.55 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 54887.4 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561507
telemt_connections_bad_total 5956
telemt_handshake_timeouts_total 3796
telemt_upstream_connect_attempt_total 15704
telemt_upstream_connect_success_total 15639
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 15704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 564
telemt_me_reconnect_attempts_total 16641
telemt_me_reconnect_success_total 12858
telemt_me_reader_eof_total 13561
telemt_me_idle_close_by_peer_total 13561
telemt_me_route_drop_no_conn_total 183321
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512845
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2507
telemt_desync_full_logged_total 970
telemt_desync_suppressed_total 1537
telemt_desync_frames_bucket_total{bucket="1_2"} 908
telemt_desync_frames_bucket_total{bucket="3_10"} 1067
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 13138
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12858
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 512466
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 9140884784 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 179828933648 (167.48 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 66
```