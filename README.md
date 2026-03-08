# Server Metrics 2026-03-08 07:14:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.13

telemt_uptime_seconds 328.3 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7620
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 195
telemt_upstream_connect_success_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 1224
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7240
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
telemt_desync_total 58
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_user_connections_total{user="hello"} 7240
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 82524672 (78.70 MB)
telemt_user_octets_to_client{user="hello"} 1865376948 (1.74 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server2

```
telemt 3.3.13

telemt_uptime_seconds 328.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4063
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 235
telemt_upstream_connect_success_total 229
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 413
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2530
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
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_user_connections_total{user="hello"} 2530
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 68560388 (65.38 MB)
telemt_user_octets_to_client{user="hello"} 896511976 (854.98 MB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.13

telemt_uptime_seconds 328.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10727
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 914
telemt_upstream_connect_attempt_total 210
telemt_upstream_connect_success_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_route_drop_no_conn_total 1591
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6521
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
telemt_desync_total 12
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 6520
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 242157252 (230.94 MB)
telemt_user_octets_to_client{user="hello"} 1884854924 (1.76 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.13

telemt_uptime_seconds 327.8 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3103
telemt_connections_bad_total 656
telemt_upstream_connect_attempt_total 249
telemt_upstream_connect_success_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 115
telemt_me_keepalive_timeout_total 2
telemt_me_route_drop_no_conn_total 702
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2378
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
telemt_desync_total 7
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_user_connections_total{user="hello"} 2378
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 21852024 (20.84 MB)
telemt_user_octets_to_client{user="hello"} 565781060 (539.57 MB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.13

telemt_uptime_seconds 328.3 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4542
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 232
telemt_upstream_connect_success_total 225
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4437
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_desync_total 10
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_user_connections_total{user="hello"} 4438
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 25853912 (24.66 MB)
telemt_user_octets_to_client{user="hello"} 1409856480 (1.31 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 74
```