# Server Metrics 2026-03-08 23:28:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.14

telemt_uptime_seconds 522.3 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3557
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 338
telemt_upstream_connect_success_total 336
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 570
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3457
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_user_connections_total{user="hello"} 3457
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 32756040 (31.24 MB)
telemt_user_octets_to_client{user="hello"} 1617947676 (1.51 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.14

telemt_uptime_seconds 523.5 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2085
telemt_connections_bad_total 14
telemt_upstream_connect_attempt_total 353
telemt_upstream_connect_success_total 345
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 229
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2006
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 17
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_user_connections_total{user="hello"} 2003
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 12610204 (12.03 MB)
telemt_user_octets_to_client{user="hello"} 660326348 (629.74 MB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.14

telemt_uptime_seconds 518.2 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3326
telemt_connections_bad_total 471
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 357
telemt_upstream_connect_success_total 351
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 465
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2781
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 2781
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 422243432 (402.68 MB)
telemt_user_octets_to_client{user="hello"} 1226894756 (1.14 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.14

telemt_uptime_seconds 514.2 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2774
telemt_connections_bad_total 441
telemt_upstream_connect_attempt_total 349
telemt_upstream_connect_success_total 343
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 470
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2272
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 3
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 2272
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 24200196 (23.08 MB)
telemt_user_octets_to_client{user="hello"} 2056774764 (1.92 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.14

telemt_uptime_seconds 518.2 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3468
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 349
telemt_upstream_connect_success_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 192
telemt_me_keepalive_timeout_total 6
telemt_me_route_drop_no_conn_total 560
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3188
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 230
telemt_me_adaptive_floor_global_cap_effective 230
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_active_cap_effective 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_me_adaptive_floor_warm_cap_effective 230
telemt_me_writers_active_current 44
telemt_user_connections_total{user="hello"} 3186
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 6546848 (6.24 MB)
telemt_user_octets_to_client{user="hello"} 218861056 (208.72 MB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 32
```