# Server Metrics 2026-03-15 04:18:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 21813.7 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272617
telemt_connections_bad_total 3684
telemt_handshake_timeouts_total 1356
telemt_upstream_connect_attempt_total 4661
telemt_upstream_connect_success_total 4643
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3546
telemt_me_reconnect_success_total 3528
telemt_me_reader_eof_total 3731
telemt_me_idle_close_by_peer_total 3731
telemt_me_route_drop_no_conn_total 85461
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241596
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 629
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3568
telemt_me_writer_restored_same_endpoint_total 3517
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 241567
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 2563303452 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 86377394716 (80.45 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 21814.0 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109122
telemt_connections_bad_total 18081
telemt_handshake_timeouts_total 4296
telemt_upstream_connect_attempt_total 6506
telemt_upstream_connect_success_total 6479
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5076
telemt_me_reconnect_success_total 5051
telemt_me_reader_eof_total 5340
telemt_me_idle_close_by_peer_total 5340
telemt_me_route_drop_no_conn_total 22106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84046
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5051
telemt_me_writer_restored_same_endpoint_total 5043
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 84342
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 1745953847 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 24748224056 (23.05 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 21814.3 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191026
telemt_connections_bad_total 3607
telemt_handshake_timeouts_total 20352
telemt_upstream_connect_attempt_total 5109
telemt_upstream_connect_success_total 5087
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3985
telemt_me_reconnect_success_total 3965
telemt_me_reader_eof_total 4195
telemt_me_idle_close_by_peer_total 4195
telemt_me_route_drop_no_conn_total 41420
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163307
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 291
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4007
telemt_me_writer_restored_same_endpoint_total 3946
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 163182
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 1350998784 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 50886007976 (47.39 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 21814.1 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149117
telemt_connections_bad_total 32783
telemt_handshake_timeouts_total 7543
telemt_upstream_connect_attempt_total 7772
telemt_upstream_connect_success_total 7601
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 7772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11026
telemt_me_reconnect_success_total 6480
telemt_me_reader_eof_total 6822
telemt_me_idle_close_by_peer_total 6822
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 30649
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106688
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 150
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6679
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 6460
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 106693
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 882446668 (841.57 MB)
telemt_user_octets_to_client{user="hello"} 35022032836 (32.62 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 21815.1 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91494
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 1092
telemt_upstream_connect_attempt_total 5063
telemt_upstream_connect_success_total 5039
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 3936
telemt_me_reconnect_success_total 3920
telemt_me_reader_eof_total 4182
telemt_me_idle_close_by_peer_total 4182
telemt_me_route_drop_no_conn_total 24240
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87479
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 367
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3957
telemt_me_writer_restored_same_endpoint_total 3912
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 87477
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 741758868 (707.40 MB)
telemt_user_octets_to_client{user="hello"} 27710037840 (25.81 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 53
```