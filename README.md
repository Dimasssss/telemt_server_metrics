# Server Metrics 2026-03-08 23:23:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.14

telemt_uptime_seconds 215.6 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1627
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 187
telemt_upstream_connect_success_total 185
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 250
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1578
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
telemt_me_writers_active_current 44
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_user_connections_total{user="hello"} 1578
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 10597168 (10.11 MB)
telemt_user_octets_to_client{user="hello"} 552750844 (527.14 MB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.14

telemt_uptime_seconds 216.7 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1038
telemt_upstream_connect_attempt_total 193
telemt_upstream_connect_success_total 185
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 997
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
telemt_desync_total 16
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_user_connections_total{user="hello"} 997
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 7284504 (6.95 MB)
telemt_user_octets_to_client{user="hello"} 227348556 (216.82 MB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.14

telemt_uptime_seconds 211.3 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1612
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 185
telemt_upstream_connect_success_total 179
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 209
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1386
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
telemt_user_connections_total{user="hello"} 1386
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 155962032 (148.74 MB)
telemt_user_octets_to_client{user="hello"} 625963824 (596.97 MB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.14

telemt_uptime_seconds 207.3 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1297
telemt_connections_bad_total 158
telemt_upstream_connect_attempt_total 186
telemt_upstream_connect_success_total 180
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 112
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1090
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
telemt_user_connections_total{user="hello"} 1090
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 17718152 (16.90 MB)
telemt_user_octets_to_client{user="hello"} 714673068 (681.57 MB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.14

telemt_uptime_seconds 211.5 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1611
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 186
telemt_upstream_connect_success_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_me_route_drop_no_conn_total 194
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1489
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 230
telemt_me_adaptive_floor_global_cap_effective 230
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_active_cap_effective 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_me_adaptive_floor_warm_cap_effective 230
telemt_me_writers_active_current 44
telemt_user_connections_total{user="hello"} 1488
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 3286436 (3.13 MB)
telemt_user_octets_to_client{user="hello"} 134285984 (128.07 MB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 39
```