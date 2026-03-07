# Server Metrics 2026-03-07 16:35:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.9

telemt_uptime_seconds 498.9 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12444
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 83
telemt_upstream_connect_attempt_total 195
telemt_upstream_connect_success_total 191
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 2980
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
telemt_desync_total 41
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_user_connections_total{user="hello"} 11678
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 125764640 (119.94 MB)
telemt_user_octets_to_client{user="hello"} 4341513776 (4.04 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.9

telemt_uptime_seconds 498.8 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5653
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 234
telemt_upstream_connect_success_total 232
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 1320
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
telemt_desync_total 30
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_user_connections_total{user="hello"} 4801
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 43820600 (41.79 MB)
telemt_user_octets_to_client{user="hello"} 1011118120 (964.28 MB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.9

telemt_uptime_seconds 498.9 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13181
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 243
telemt_upstream_connect_success_total 228
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 3236
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
telemt_desync_total 28
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_user_connections_total{user="hello"} 8655
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 489260556 (466.60 MB)
telemt_user_octets_to_client{user="hello"} 1772097664 (1.65 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server4

```
telemt 3.3.9

telemt_uptime_seconds 499.4 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5368
telemt_connections_bad_total 691
telemt_handshake_timeouts_total 156
telemt_upstream_connect_attempt_total 258
telemt_upstream_connect_success_total 243
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 93
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 1502
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
telemt_user_connections_total{user="hello"} 4422
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 45030588 (42.94 MB)
telemt_user_octets_to_client{user="hello"} 1356698128 (1.26 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.9

telemt_uptime_seconds 499.0 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7158
telemt_handshake_timeouts_total 94
telemt_upstream_connect_attempt_total 256
telemt_upstream_connect_success_total 240
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 2751
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
telemt_desync_total 7
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_user_connections_total{user="hello"} 6623
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 60747700 (57.93 MB)
telemt_user_octets_to_client{user="hello"} 1619113412 (1.51 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 75
```