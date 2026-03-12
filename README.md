# Server Metrics 2026-03-12 22:40:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 60081.7 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1924978
telemt_connections_bad_total 26062
telemt_handshake_timeouts_total 21078
telemt_upstream_connect_attempt_total 11838
telemt_upstream_connect_success_total 11770
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 602
telemt_me_reconnect_attempts_total 17609
telemt_me_reconnect_success_total 8753
telemt_me_reader_eof_total 9457
telemt_me_idle_close_by_peer_total 9456
telemt_me_route_drop_no_conn_total 751956
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1790933
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8514
telemt_desync_full_logged_total 2219
telemt_desync_suppressed_total 6295
telemt_desync_frames_bucket_total{bucket="1_2"} 2240
telemt_desync_frames_bucket_total{bucket="3_10"} 3062
telemt_desync_frames_bucket_total{bucket="gt_10"} 3212
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9154
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8740
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 1790407
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 27004029040 (25.15 GB)
telemt_user_octets_to_client{user="hello"} 638962952420 (595.08 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89702.1 (24h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797330
telemt_connections_bad_total 11706
telemt_handshake_timeouts_total 31332
telemt_upstream_connect_attempt_total 22689
telemt_upstream_connect_success_total 22660
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3413
telemt_me_reconnect_attempts_total 16631
telemt_me_reconnect_success_total 16535
telemt_me_reader_eof_total 17597
telemt_me_idle_close_by_peer_total 17597
telemt_me_route_drop_no_conn_total 257937
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720351
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 2068
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16703
telemt_me_writer_restored_same_endpoint_total 16526
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 722231
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 12074619080 (11.25 GB)
telemt_user_octets_to_client{user="hello"} 279253965779 (260.08 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 89701.9 (24h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1659685
telemt_connections_bad_total 8032
telemt_handshake_timeouts_total 113288
telemt_upstream_connect_attempt_total 20879
telemt_upstream_connect_success_total 20873
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1222
telemt_me_reconnect_attempts_total 17290
telemt_me_reconnect_success_total 16040
telemt_me_reader_eof_total 16955
telemt_me_idle_close_by_peer_total 16954
telemt_me_route_drop_no_conn_total 545522
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1293031
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4968
telemt_desync_full_logged_total 1524
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 16194
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15999
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 1292637
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 19736458484 (18.38 GB)
telemt_user_octets_to_client{user="hello"} 477135966613 (444.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 89702.4 (24h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021951
telemt_connections_bad_total 13002
telemt_handshake_timeouts_total 71445
telemt_upstream_connect_attempt_total 22973
telemt_upstream_connect_success_total 22880
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 22973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1691
telemt_me_reconnect_attempts_total 26140
telemt_me_reconnect_success_total 18409
telemt_me_reader_eof_total 19666
telemt_me_idle_close_by_peer_total 19666
telemt_me_route_drop_no_conn_total 365804
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 890742
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 18796
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18388
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 890088
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 14217796428 (13.24 GB)
telemt_user_octets_to_client{user="hello"} 354886762132 (330.51 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 89702.2 (24h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1143154
telemt_connections_bad_total 12536
telemt_handshake_timeouts_total 9205
telemt_upstream_connect_attempt_total 27457
telemt_upstream_connect_success_total 27114
telemt_upstream_connect_fail_total 342
telemt_upstream_connect_attempts_per_request{bucket="1"} 27456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 342
telemt_me_keepalive_timeout_total 1446
telemt_me_reconnect_attempts_total 33671
telemt_me_reconnect_success_total 22630
telemt_me_reader_eof_total 23796
telemt_me_idle_close_by_peer_total 23796
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 427509
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1052739
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3949
telemt_desync_full_logged_total 1376
telemt_desync_suppressed_total 2573
telemt_desync_frames_bucket_total{bucket="1_2"} 1157
telemt_desync_frames_bucket_total{bucket="3_10"} 1304
telemt_desync_frames_bucket_total{bucket="gt_10"} 1488
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 23237
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22586
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 607
telemt_user_connections_total{user="hello"} 1052598
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 13126778120 (12.23 GB)
telemt_user_octets_to_client{user="hello"} 373575892892 (347.92 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 47
```