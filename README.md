# Server Metrics 2026-03-15 00:49:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 9289.5 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121995
telemt_connections_bad_total 1392
telemt_handshake_timeouts_total 456
telemt_upstream_connect_attempt_total 1978
telemt_upstream_connect_success_total 1969
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1476
telemt_me_reconnect_success_total 1468
telemt_me_reader_eof_total 1537
telemt_me_idle_close_by_peer_total 1537
telemt_me_route_drop_no_conn_total 38563
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106392
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 281
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1488
telemt_me_writer_restored_same_endpoint_total 1457
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 106384
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 1085404948 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 37363202420 (34.80 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 9290.2 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48642
telemt_connections_bad_total 8378
telemt_handshake_timeouts_total 2144
telemt_upstream_connect_attempt_total 2916
telemt_upstream_connect_success_total 2900
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2101
telemt_me_reconnect_success_total 2086
telemt_me_reader_eof_total 2163
telemt_me_idle_close_by_peer_total 2163
telemt_me_route_drop_no_conn_total 9977
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36579
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 99
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2055
telemt_me_writer_restored_same_endpoint_total 2078
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 36875
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1374747743 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 8705110680 (8.11 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 9290.3 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77398
telemt_connections_bad_total 1454
telemt_handshake_timeouts_total 5441
telemt_upstream_connect_attempt_total 2116
telemt_upstream_connect_success_total 2106
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1609
telemt_me_reconnect_success_total 1604
telemt_me_reader_eof_total 1681
telemt_me_idle_close_by_peer_total 1681
telemt_me_route_drop_no_conn_total 18689
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69085
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1620
telemt_me_writer_restored_same_endpoint_total 1585
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 69004
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 759128724 (723.96 MB)
telemt_user_octets_to_client{user="hello"} 17882507992 (16.65 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 9290.2 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74118
telemt_connections_bad_total 21714
telemt_handshake_timeouts_total 957
telemt_upstream_connect_attempt_total 3364
telemt_upstream_connect_success_total 3281
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 3364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4079
telemt_me_reconnect_success_total 2774
telemt_me_reader_eof_total 2889
telemt_me_idle_close_by_peer_total 2889
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 12759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50194
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 82
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2837
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2760
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 50197
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 299732500 (285.85 MB)
telemt_user_octets_to_client{user="hello"} 10645567372 (9.91 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 9291.1 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41579
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 650
telemt_upstream_connect_attempt_total 2001
telemt_upstream_connect_success_total 1992
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1497
telemt_me_reconnect_success_total 1490
telemt_me_reader_eof_total 1567
telemt_me_idle_close_by_peer_total 1567
telemt_me_route_drop_no_conn_total 10592
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39895
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1504
telemt_me_writer_restored_same_endpoint_total 1482
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 39895
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 311488056 (297.06 MB)
telemt_user_octets_to_client{user="hello"} 16030773416 (14.93 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 31
```