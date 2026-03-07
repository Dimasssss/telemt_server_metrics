# Server Metrics 2026-03-07 16:51:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.10

telemt_uptime_seconds 365.1 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8749
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 168
telemt_upstream_connect_success_total 165
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 3
telemt_me_route_drop_no_conn_total 2010
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
telemt_me_writers_active_current 43
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_user_connections_total{user="hello"} 8207
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 120300032 (114.73 MB)
telemt_user_octets_to_client{user="hello"} 2407219892 (2.24 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server2

```
telemt 3.3.10

telemt_uptime_seconds 365.0 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3882
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 184
telemt_upstream_connect_success_total 183
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 2
telemt_me_route_drop_no_conn_total 527
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
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_user_connections_total{user="hello"} 3393
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 25832252 (24.64 MB)
telemt_user_octets_to_client{user="hello"} 922745140 (880.00 MB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.10

telemt_uptime_seconds 364.9 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9806
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 200
telemt_upstream_connect_attempt_total 173
telemt_upstream_connect_success_total 163
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 1989
telemt_me_single_endpoint_shadow_rotate_total 7
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
telemt_desync_total 19
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 6772
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 322953600 (307.99 MB)
telemt_user_octets_to_client{user="hello"} 1204535436 (1.12 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.10

telemt_uptime_seconds 365.7 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3803
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 24
telemt_upstream_connect_attempt_total 188
telemt_upstream_connect_success_total 180
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 80
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_route_drop_no_conn_total 1154
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
telemt_desync_total 6
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_user_connections_total{user="hello"} 3376
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 21851360 (20.84 MB)
telemt_user_octets_to_client{user="hello"} 629925108 (600.74 MB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.10

telemt_uptime_seconds 365.2 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4718
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 215
telemt_upstream_connect_success_total 203
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 1114
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
telemt_desync_total 7
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 4507
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 45916268 (43.79 MB)
telemt_user_octets_to_client{user="hello"} 1260588440 (1.17 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 95
```