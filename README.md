# Server Metrics 2026-03-11 23:21:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5813.6 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53899
telemt_connections_bad_total 613
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 1435
telemt_upstream_connect_success_total 1435
telemt_upstream_connect_attempts_per_request{bucket="1"} 1435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 1107
telemt_me_reconnect_success_total 1104
telemt_me_reader_eof_total 1145
telemt_me_idle_close_by_peer_total 1145
telemt_me_route_drop_no_conn_total 20225
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50356
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
telemt_me_writer_removed_unexpected_total 1121
telemt_me_writer_restored_same_endpoint_total 1088
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 50331
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 303641304 (289.57 MB)
telemt_user_octets_to_client{user="hello"} 12983519768 (12.09 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 5814.3 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19304
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 1676
telemt_upstream_connect_success_total 1676
telemt_upstream_connect_attempts_per_request{bucket="1"} 1676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 864
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1343
telemt_me_reconnect_success_total 1333
telemt_me_reader_eof_total 1388
telemt_me_idle_close_by_peer_total 1388
telemt_me_route_drop_no_conn_total 4992
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1338
telemt_me_writer_restored_same_endpoint_total 1324
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 18357
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 519317276 (495.26 MB)
telemt_user_octets_to_client{user="hello"} 8327679228 (7.76 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 5814.2 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45536
telemt_connections_bad_total 500
telemt_handshake_timeouts_total 3801
telemt_upstream_connect_attempt_total 2204
telemt_upstream_connect_success_total 2202
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 1550
telemt_me_reconnect_success_total 1509
telemt_me_reader_eof_total 1468
telemt_me_idle_close_by_peer_total 1468
telemt_me_route_drop_no_conn_total 9064
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30565
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1433
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1468
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 30913
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 246093932 (234.69 MB)
telemt_user_octets_to_client{user="hello"} 17191178741 (16.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 5814.6 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29389
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 329
telemt_upstream_connect_attempt_total 1827
telemt_upstream_connect_success_total 1817
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 1485
telemt_me_reconnect_success_total 1478
telemt_me_reader_eof_total 1520
telemt_me_idle_close_by_peer_total 1520
telemt_me_route_drop_no_conn_total 8952
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28572
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
telemt_me_writer_removed_unexpected_total 1484
telemt_me_writer_restored_same_endpoint_total 1457
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 28571
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 161001528 (153.54 MB)
telemt_user_octets_to_client{user="hello"} 10506512604 (9.78 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 5814.4 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36489
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 2736
telemt_upstream_connect_success_total 2708
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 2736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 3848
telemt_me_reconnect_success_total 2363
telemt_me_reader_eof_total 2394
telemt_me_idle_close_by_peer_total 2394
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 8085
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34220
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 36
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_writer_removed_unexpected_total 2419
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 2358
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 34217
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 208167884 (198.52 MB)
telemt_user_octets_to_client{user="hello"} 10138977324 (9.44 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 30
```