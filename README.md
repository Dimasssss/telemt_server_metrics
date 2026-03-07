# Server Metrics 2026-03-07 07:10:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.7

telemt_uptime_seconds 150.1 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4334
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 85
telemt_upstream_connect_success_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 85
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_route_drop_no_conn_total 624
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 27
telemt_desync_total 19
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_user_connections_total{user="hello"} 3978
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 16611276 (15.84 MB)
telemt_user_octets_to_client{user="hello"} 1345257220 (1.25 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.7

telemt_uptime_seconds 150.0 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1294
telemt_handshake_timeouts_total 24
telemt_upstream_connect_attempt_total 91
telemt_upstream_connect_success_total 89
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 247
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_user_connections_total{user="hello"} 1189
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 4067220 (3.88 MB)
telemt_user_octets_to_client{user="hello"} 183565648 (175.06 MB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.7

telemt_uptime_seconds 149.7 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2485
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 111
telemt_upstream_connect_success_total 109
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 387
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_user_connections_total{user="hello"} 2320
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 133715736 (127.52 MB)
telemt_user_octets_to_client{user="hello"} 1338770296 (1.25 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.7

telemt_uptime_seconds 150.5 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1334
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 109
telemt_upstream_connect_success_total 107
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 166
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_user_connections_total{user="hello"} 1123
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 5403028 (5.15 MB)
telemt_user_octets_to_client{user="hello"} 228857516 (218.26 MB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.7

telemt_uptime_seconds 150.0 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1700
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 100
telemt_upstream_connect_success_total 92
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 279
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 192
telemt_me_adaptive_floor_global_cap_effective 192
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 6
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 1550
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 9968360 (9.51 MB)
telemt_user_octets_to_client{user="hello"} 318625256 (303.86 MB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 73
```