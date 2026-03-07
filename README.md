# Server Metrics 2026-03-07 16:30:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.9

telemt_uptime_seconds 191.6 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5698
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 47
telemt_upstream_connect_attempt_total 124
telemt_upstream_connect_success_total 120
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 63
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 1011
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
telemt_me_writers_active_current 43
telemt_desync_total 19
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 5325
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 48481192 (46.24 MB)
telemt_user_octets_to_client{user="hello"} 1694647512 (1.58 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server2

```
telemt 3.3.9

telemt_uptime_seconds 191.6 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2280
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 135
telemt_upstream_connect_success_total 133
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 437
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
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_user_connections_total{user="hello"} 2016
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 22844300 (21.79 MB)
telemt_user_octets_to_client{user="hello"} 306288752 (292.10 MB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.9

telemt_uptime_seconds 191.4 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6405
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 135
telemt_upstream_connect_success_total 130
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 1178
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
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 4162
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 195754624 (186.69 MB)
telemt_user_octets_to_client{user="hello"} 711689004 (678.72 MB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server4

```
telemt 3.3.9

telemt_uptime_seconds 192.0 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2069
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 146
telemt_upstream_connect_success_total 138
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 397
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
telemt_user_connections_total{user="hello"} 1788
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 21969532 (20.95 MB)
telemt_user_octets_to_client{user="hello"} 406729784 (387.89 MB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.9

telemt_uptime_seconds 191.8 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2736
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 141
telemt_upstream_connect_success_total 138
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 559
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 256
telemt_me_adaptive_floor_global_cap_effective 256
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 256
telemt_me_adaptive_floor_active_cap_effective 256
telemt_me_adaptive_floor_warm_cap_configured 256
telemt_me_adaptive_floor_warm_cap_effective 256
telemt_me_writers_active_current 44
telemt_user_connections_total{user="hello"} 2561
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 37125100 (35.41 MB)
telemt_user_octets_to_client{user="hello"} 487491012 (464.91 MB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 106
```