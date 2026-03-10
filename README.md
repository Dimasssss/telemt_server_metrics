# Server Metrics 2026-03-10 14:44:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1070.0 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40007
telemt_connections_bad_total 236
telemt_handshake_timeouts_total 413
telemt_upstream_connect_attempt_total 237
telemt_upstream_connect_success_total 236
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 123
telemt_me_reconnect_success_total 120
telemt_me_reader_eof_total 77
telemt_me_idle_close_by_peer_total 77
telemt_me_route_drop_no_conn_total 17931
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37421
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 99
telemt_me_writer_restored_same_endpoint_total 114
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_user_connections_total{user="hello"} 37418
telemt_user_connections_current{user="hello"} 1395
telemt_user_octets_from_client{user="hello"} 475873972 (453.83 MB)
telemt_user_octets_to_client{user="hello"} 11233623096 (10.46 GB)
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 1126.7 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19766
telemt_connections_bad_total 430
telemt_handshake_timeouts_total 3463
telemt_upstream_connect_attempt_total 218
telemt_upstream_connect_success_total 217
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 103
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 71
telemt_me_idle_close_by_peer_total 71
telemt_me_route_drop_no_conn_total 3425
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13615
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 93
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 13614
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 169183660 (161.35 MB)
telemt_user_octets_to_client{user="hello"} 4613341296 (4.30 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 1126.7 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27700
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 534
telemt_upstream_connect_attempt_total 1218
telemt_upstream_connect_success_total 1198
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 66
telemt_me_reconnect_success_total 47
telemt_me_reader_eof_total 34
telemt_me_idle_close_by_peer_total 34
telemt_me_route_drop_no_conn_total 8193
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25035
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 47
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 56
telemt_me_writer_restored_same_endpoint_total 36
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 26037
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 298347129 (284.53 MB)
telemt_user_octets_to_client{user="hello"} 9526115241 (8.87 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 1127.1 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18621
telemt_connections_bad_total 1039
telemt_handshake_timeouts_total 1176
telemt_upstream_connect_attempt_total 194
telemt_upstream_connect_success_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 72
telemt_me_reconnect_attempts_total 83
telemt_me_reconnect_success_total 83
telemt_me_reader_eof_total 57
telemt_me_idle_close_by_peer_total 57
telemt_me_route_drop_no_conn_total 5196
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15192
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 77
telemt_me_writer_restored_same_endpoint_total 72
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 15166
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 173307216 (165.28 MB)
telemt_user_octets_to_client{user="hello"} 3099007040 (2.89 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1126.7 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21332
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 292
telemt_upstream_connect_success_total 291
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 177
telemt_me_reconnect_success_total 176
telemt_me_reader_eof_total 147
telemt_me_idle_close_by_peer_total 147
telemt_me_route_drop_no_conn_total 5406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19619
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 118
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_me_writer_removed_unexpected_total 165
telemt_me_writer_restored_same_endpoint_total 176
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 19597
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 149229572 (142.32 MB)
telemt_user_octets_to_client{user="hello"} 4837365260 (4.51 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 126
```