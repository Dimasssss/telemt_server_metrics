# Server Metrics 2026-03-12 06:30:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1901.9 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54556
telemt_connections_bad_total 846
telemt_handshake_timeouts_total 424
telemt_upstream_connect_attempt_total 433
telemt_upstream_connect_success_total 431
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 277
telemt_me_reconnect_success_total 276
telemt_me_reader_eof_total 246
telemt_me_idle_close_by_peer_total 246
telemt_me_route_drop_no_conn_total 17291
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52105
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 296
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_me_writer_removed_unexpected_total 268
telemt_me_writer_restored_same_endpoint_total 263
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 52076
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 1396055560 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 13753706900 (12.81 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 31522.4 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128053
telemt_connections_bad_total 1694
telemt_handshake_timeouts_total 4631
telemt_upstream_connect_attempt_total 8311
telemt_upstream_connect_success_total 8306
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 6585
telemt_me_reconnect_success_total 6548
telemt_me_reader_eof_total 6962
telemt_me_idle_close_by_peer_total 6962
telemt_me_route_drop_no_conn_total 37991
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114516
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6603
telemt_me_writer_restored_same_endpoint_total 6539
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 114704
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 1745869691 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 49214852570 (45.83 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 31522.2 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459814
telemt_connections_bad_total 2277
telemt_handshake_timeouts_total 33696
telemt_upstream_connect_attempt_total 8595
telemt_upstream_connect_success_total 8593
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3727
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6730
telemt_me_reconnect_success_total 6666
telemt_me_reader_eof_total 6983
telemt_me_idle_close_by_peer_total 6983
telemt_me_route_drop_no_conn_total 72075
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216974
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 927
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 627
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 463
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6648
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6625
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 217279
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 2282278712 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 68986147929 (64.25 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 31522.7 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191881
telemt_connections_bad_total 1735
telemt_handshake_timeouts_total 12638
telemt_upstream_connect_attempt_total 9039
telemt_upstream_connect_success_total 9000
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 245
telemt_me_reconnect_attempts_total 7459
telemt_me_reconnect_success_total 7431
telemt_me_reader_eof_total 7888
telemt_me_idle_close_by_peer_total 7888
telemt_me_route_drop_no_conn_total 61437
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159054
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 233
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7474
telemt_me_writer_restored_same_endpoint_total 7410
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 158920
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 1827947332 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 48324995396 (45.01 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 31522.4 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206570
telemt_connections_bad_total 309
telemt_handshake_timeouts_total 1253
telemt_upstream_connect_attempt_total 10797
telemt_upstream_connect_success_total 10676
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 10797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5063
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 10607
telemt_me_reconnect_success_total 9097
telemt_me_reader_eof_total 9481
telemt_me_idle_close_by_peer_total 9481
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 63460
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196722
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 756
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 504
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 9228
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9078
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 196676
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 1728541804 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 45326222056 (42.21 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 93
```