# Server Metrics 2026-03-07 07:36:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.7

telemt_uptime_seconds 1690.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32838
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 222
telemt_upstream_connect_attempt_total 480
telemt_upstream_connect_success_total 480
telemt_upstream_connect_attempts_per_request{bucket="1"} 480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 10283
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 187
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 31108
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 506104412 (482.66 MB)
telemt_user_octets_to_client{user="hello"} 12653182800 (11.78 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.7

telemt_uptime_seconds 1689.7 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11623
telemt_connections_bad_total 1056
telemt_handshake_timeouts_total 348
telemt_upstream_connect_attempt_total 535
telemt_upstream_connect_success_total 532
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 3672
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 13
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 9714
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 144960024 (138.24 MB)
telemt_user_octets_to_client{user="hello"} 3882782024 (3.62 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.7

telemt_uptime_seconds 1689.6 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22483
telemt_connections_bad_total 1136
telemt_handshake_timeouts_total 851
telemt_upstream_connect_attempt_total 801
telemt_upstream_connect_success_total 794
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 14
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 13
telemt_me_idle_close_by_peer_total 13
telemt_me_route_drop_no_conn_total 6786
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 23
telemt_desync_total 93
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 13
telemt_me_writer_restored_same_endpoint_total 13
telemt_user_connections_total{user="hello"} 20063
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 1637145708 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 10354305052 (9.64 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server4

```
telemt 3.3.7

telemt_uptime_seconds 1690.1 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15099
telemt_connections_bad_total 1553
telemt_handshake_timeouts_total 408
telemt_upstream_connect_attempt_total 825
telemt_upstream_connect_success_total 821
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 6344
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_restored_same_endpoint_total 8
telemt_user_connections_total{user="hello"} 12373
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 107630840 (102.64 MB)
telemt_user_octets_to_client{user="hello"} 4787443032 (4.46 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.7

telemt_uptime_seconds 1689.7 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20900
telemt_connections_bad_total 161
telemt_handshake_timeouts_total 447
telemt_upstream_connect_attempt_total 544
telemt_upstream_connect_success_total 529
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 6960
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 192
telemt_me_adaptive_floor_global_cap_effective 192
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 72
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 18540
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 325990580 (310.89 MB)
telemt_user_octets_to_client{user="hello"} 5620641612 (5.23 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 74
```