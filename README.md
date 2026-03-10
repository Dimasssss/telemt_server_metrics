# Server Metrics 2026-03-10 14:50:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1376.3 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50421
telemt_connections_bad_total 236
telemt_handshake_timeouts_total 449
telemt_upstream_connect_attempt_total 318
telemt_upstream_connect_success_total 317
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 204
telemt_me_reconnect_success_total 199
telemt_me_reader_eof_total 157
telemt_me_idle_close_by_peer_total 157
telemt_me_route_drop_no_conn_total 21746
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47387
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_restored_same_endpoint_total 193
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_user_connections_total{user="hello"} 47383
telemt_user_connections_current{user="hello"} 1341
telemt_user_octets_from_client{user="hello"} 586913784 (559.72 MB)
telemt_user_octets_to_client{user="hello"} 13603410160 (12.67 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 1433.0 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24482
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 5011
telemt_upstream_connect_attempt_total 264
telemt_upstream_connect_success_total 263
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 149
telemt_me_reconnect_success_total 148
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 4639
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17430
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_writer_removed_unexpected_total 141
telemt_me_writer_restored_same_endpoint_total 127
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 17429
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 214674912 (204.73 MB)
telemt_user_octets_to_client{user="hello"} 5792405756 (5.39 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 1432.9 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34009
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 703
telemt_upstream_connect_attempt_total 1262
telemt_upstream_connect_success_total 1242
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 110
telemt_me_reconnect_success_total 91
telemt_me_reader_eof_total 78
telemt_me_idle_close_by_peer_total 78
telemt_me_route_drop_no_conn_total 10326
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31082
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 100
telemt_me_writer_restored_same_endpoint_total 80
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 32083
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 335479157 (319.94 MB)
telemt_user_octets_to_client{user="hello"} 11359467557 (10.58 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 1433.3 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23152
telemt_connections_bad_total 1316
telemt_handshake_timeouts_total 1459
telemt_upstream_connect_attempt_total 247
telemt_upstream_connect_success_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 93
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 136
telemt_me_reconnect_success_total 136
telemt_me_reader_eof_total 110
telemt_me_idle_close_by_peer_total 110
telemt_me_route_drop_no_conn_total 6762
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18988
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 57
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 130
telemt_me_writer_restored_same_endpoint_total 125
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 18961
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 201109332 (191.79 MB)
telemt_user_octets_to_client{user="hello"} 4070068864 (3.79 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1433.0 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27008
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 360
telemt_upstream_connect_success_total 359
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 245
telemt_me_reconnect_success_total 244
telemt_me_reader_eof_total 215
telemt_me_idle_close_by_peer_total 215
telemt_me_route_drop_no_conn_total 7121
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25092
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 153
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_me_writer_removed_unexpected_total 235
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 25070
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 179771064 (171.44 MB)
telemt_user_octets_to_client{user="hello"} 6216312732 (5.79 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 96
```