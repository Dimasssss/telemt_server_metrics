# Server Metrics 2026-03-08 07:19:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.13

telemt_uptime_seconds 635.4 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13856
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 288
telemt_upstream_connect_success_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 2966
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13265
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
telemt_desync_total 92
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_user_connections_total{user="hello"} 13263
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 157099032 (149.82 MB)
telemt_user_octets_to_client{user="hello"} 4142924196 (3.86 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server2

```
telemt 3.3.13

telemt_uptime_seconds 635.2 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10375
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 366
telemt_upstream_connect_success_total 360
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 1200
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4795
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
telemt_desync_total 6
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_user_connections_total{user="hello"} 4795
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 149308444 (142.39 MB)
telemt_user_octets_to_client{user="hello"} 1668665040 (1.55 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.13

telemt_uptime_seconds 635.2 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18645
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 1213
telemt_upstream_connect_attempt_total 323
telemt_upstream_connect_success_total 322
telemt_upstream_connect_attempts_per_request{bucket="1"} 322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 4
telemt_me_route_drop_no_conn_total 3177
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10801
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
telemt_desync_total 37
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_user_connections_total{user="hello"} 10798
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 520138028 (496.04 MB)
telemt_user_octets_to_client{user="hello"} 3804317240 (3.54 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.13

telemt_uptime_seconds 634.8 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6190
telemt_connections_bad_total 1672
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 416
telemt_upstream_connect_success_total 416
telemt_upstream_connect_attempts_per_request{bucket="1"} 416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 198
telemt_me_keepalive_timeout_total 3
telemt_me_route_drop_no_conn_total 1423
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4394
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
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
telemt_user_connections_total{user="hello"} 4394
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 40027700 (38.17 MB)
telemt_user_octets_to_client{user="hello"} 1048216280 (999.66 MB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.13

telemt_uptime_seconds 635.3 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8244
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 374
telemt_upstream_connect_success_total 367
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 2122
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7967
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 256
telemt_me_adaptive_floor_global_cap_effective 256
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 256
telemt_me_adaptive_floor_active_cap_effective 256
telemt_me_adaptive_floor_warm_cap_configured 256
telemt_me_adaptive_floor_warm_cap_effective 256
telemt_me_writers_active_current 44
telemt_desync_total 44
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_user_connections_total{user="hello"} 7968
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 75988700 (72.47 MB)
telemt_user_octets_to_client{user="hello"} 2959507432 (2.76 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 75
```