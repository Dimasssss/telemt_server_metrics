# Server Metrics 2026-03-07 07:15:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.7

telemt_uptime_seconds 457.3 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9815
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 112
telemt_upstream_connect_success_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_route_drop_no_conn_total 2036
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 27
telemt_desync_total 40
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_user_connections_total{user="hello"} 9342
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 113330392 (108.08 MB)
telemt_user_octets_to_client{user="hello"} 3696567788 (3.44 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.7

telemt_uptime_seconds 457.1 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3414
telemt_connections_bad_total 412
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 134
telemt_upstream_connect_success_total 132
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 888
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
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 2814
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 31036408 (29.60 MB)
telemt_user_octets_to_client{user="hello"} 707707424 (674.92 MB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.7

telemt_uptime_seconds 457.1 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6453
telemt_connections_bad_total 294
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 213
telemt_upstream_connect_success_total 211
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 1469
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 23
telemt_desync_total 22
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_user_connections_total{user="hello"} 5976
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 450384288 (429.52 MB)
telemt_user_octets_to_client{user="hello"} 4226596544 (3.94 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server4

```
telemt 3.3.7

telemt_uptime_seconds 457.5 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4154
telemt_connections_bad_total 383
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 218
telemt_upstream_connect_success_total 216
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 1105
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_user_connections_total{user="hello"} 3339
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 33915872 (32.34 MB)
telemt_user_octets_to_client{user="hello"} 830751176 (792.27 MB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server5

```
telemt 3.3.7

telemt_uptime_seconds 457.0 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5231
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 138
telemt_upstream_connect_success_total 129
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 1616
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 192
telemt_me_adaptive_floor_global_cap_effective 192
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 17
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_user_connections_total{user="hello"} 4772
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 106959624 (102.00 MB)
telemt_user_octets_to_client{user="hello"} 1137147876 (1.06 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 84
```