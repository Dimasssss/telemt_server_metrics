# Server Metrics 2026-03-11 23:26:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 6119.6 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56389
telemt_connections_bad_total 734
telemt_handshake_timeouts_total 191
telemt_upstream_connect_attempt_total 1485
telemt_upstream_connect_success_total 1485
telemt_upstream_connect_attempts_per_request{bucket="1"} 1485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1157
telemt_me_reconnect_success_total 1154
telemt_me_reader_eof_total 1195
telemt_me_idle_close_by_peer_total 1195
telemt_me_route_drop_no_conn_total 21097
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52684
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1171
telemt_me_writer_restored_same_endpoint_total 1138
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 52659
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 311058272 (296.65 MB)
telemt_user_octets_to_client{user="hello"} 13635902356 (12.70 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 6120.3 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20190
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 183
telemt_upstream_connect_attempt_total 1741
telemt_upstream_connect_success_total 1741
telemt_upstream_connect_attempts_per_request{bucket="1"} 1741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 905
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1408
telemt_me_reconnect_success_total 1398
telemt_me_reader_eof_total 1453
telemt_me_idle_close_by_peer_total 1453
telemt_me_route_drop_no_conn_total 5201
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19217
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1403
telemt_me_writer_restored_same_endpoint_total 1389
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 19215
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 524446428 (500.15 MB)
telemt_user_octets_to_client{user="hello"} 8787180772 (8.18 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 6120.1 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46788
telemt_connections_bad_total 500
telemt_handshake_timeouts_total 3905
telemt_upstream_connect_attempt_total 2280
telemt_upstream_connect_success_total 2278
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1626
telemt_me_reconnect_success_total 1584
telemt_me_reader_eof_total 1545
telemt_me_idle_close_by_peer_total 1545
telemt_me_route_drop_no_conn_total 9398
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31512
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1510
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1543
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 31860
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 253630496 (241.88 MB)
telemt_user_octets_to_client{user="hello"} 17683864413 (16.47 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 6120.5 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30504
telemt_connections_bad_total 94
telemt_handshake_timeouts_total 377
telemt_upstream_connect_attempt_total 1883
telemt_upstream_connect_success_total 1873
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1541
telemt_me_reconnect_success_total 1533
telemt_me_reader_eof_total 1575
telemt_me_idle_close_by_peer_total 1575
telemt_me_route_drop_no_conn_total 9556
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29624
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1539
telemt_me_writer_restored_same_endpoint_total 1512
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 29623
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 163639908 (156.06 MB)
telemt_user_octets_to_client{user="hello"} 10630753316 (9.90 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6120.5 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38450
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 2881
telemt_upstream_connect_success_total 2853
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 2881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 3993
telemt_me_reconnect_success_total 2507
telemt_me_reader_eof_total 2539
telemt_me_idle_close_by_peer_total 2539
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 8933
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35967
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 52
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 2564
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 2502
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 35964
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 212597304 (202.75 MB)
telemt_user_octets_to_client{user="hello"} 10613628120 (9.88 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 28
```