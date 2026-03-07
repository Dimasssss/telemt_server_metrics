# Server Metrics 2026-03-07 07:41:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.7

telemt_uptime_seconds 1999.1 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38800
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 312
telemt_upstream_connect_attempt_total 640
telemt_upstream_connect_success_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 19
telemt_me_idle_close_by_peer_total 19
telemt_me_route_drop_no_conn_total 12583
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 236
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_restored_same_endpoint_total 13
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 36833
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 615399124 (586.89 MB)
telemt_user_octets_to_client{user="hello"} 15417730668 (14.36 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server2

```
telemt 3.3.7

telemt_uptime_seconds 1999.0 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13928
telemt_connections_bad_total 1057
telemt_handshake_timeouts_total 491
telemt_upstream_connect_attempt_total 736
telemt_upstream_connect_success_total 731
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 23
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 21
telemt_me_idle_close_by_peer_total 21
telemt_me_route_drop_no_conn_total 4737
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 34
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 21
telemt_me_writer_restored_same_endpoint_total 21
telemt_user_connections_total{user="hello"} 11820
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 156879748 (149.61 MB)
telemt_user_octets_to_client{user="hello"} 4467984940 (4.16 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.7

telemt_uptime_seconds 1999.0 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27080
telemt_connections_bad_total 1544
telemt_handshake_timeouts_total 1460
telemt_upstream_connect_attempt_total 1033
telemt_upstream_connect_success_total 1025
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 38
telemt_me_reconnect_success_total 38
telemt_me_reader_eof_total 40
telemt_me_idle_close_by_peer_total 40
telemt_me_route_drop_no_conn_total 8125
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 109
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_restored_same_endpoint_total 37
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 23626
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 1933126116 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 12137938204 (11.30 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.7

telemt_uptime_seconds 1999.6 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17656
telemt_connections_bad_total 1874
telemt_handshake_timeouts_total 425
telemt_upstream_connect_attempt_total 1053
telemt_upstream_connect_success_total 1048
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 23
telemt_me_idle_close_by_peer_total 23
telemt_me_route_drop_no_conn_total 7448
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 23
telemt_desync_total 20
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 14505
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 143926492 (137.26 MB)
telemt_user_octets_to_client{user="hello"} 5317676024 (4.95 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.7

telemt_uptime_seconds 1999.0 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24246
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 736
telemt_upstream_connect_success_total 718
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 16
telemt_me_reconnect_success_total 19
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 8574
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 192
telemt_me_adaptive_floor_global_cap_effective 192
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 89
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 15
telemt_user_connections_total{user="hello"} 21445
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 357400112 (340.84 MB)
telemt_user_octets_to_client{user="hello"} 7055018288 (6.57 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 62
```