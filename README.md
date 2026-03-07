# Server Metrics 2026-03-07 07:30:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.7

telemt_uptime_seconds 1381.6 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27595
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 191
telemt_upstream_connect_attempt_total 374
telemt_upstream_connect_success_total 374
telemt_upstream_connect_attempts_per_request{bucket="1"} 374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 8142
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 170
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 26010
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 450751016 (429.87 MB)
telemt_user_octets_to_client{user="hello"} 10217386324 (9.52 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server2

```
telemt 3.3.7

telemt_uptime_seconds 1381.6 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9698
telemt_connections_bad_total 1055
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 415
telemt_upstream_connect_success_total 411
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 2935
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
telemt_user_connections_total{user="hello"} 7962
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 132312548 (126.18 MB)
telemt_user_octets_to_client{user="hello"} 3155414888 (2.94 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server3

```
telemt 3.3.7

telemt_uptime_seconds 1381.6 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18403
telemt_connections_bad_total 929
telemt_handshake_timeouts_total 723
telemt_upstream_connect_attempt_total 645
telemt_upstream_connect_success_total 638
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 13
telemt_me_reconnect_success_total 13
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 5264
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 85
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 12
telemt_user_connections_total{user="hello"} 16408
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 1363923192 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 9225004016 (8.59 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server4

```
telemt 3.3.7

telemt_uptime_seconds 1381.9 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12265
telemt_connections_bad_total 1232
telemt_handshake_timeouts_total 398
telemt_upstream_connect_attempt_total 664
telemt_upstream_connect_success_total 661
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 5380
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 18
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 7
telemt_user_connections_total{user="hello"} 9954
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 94408708 (90.04 MB)
telemt_user_octets_to_client{user="hello"} 4287907604 (3.99 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server5

```
telemt 3.3.7

telemt_uptime_seconds 1381.6 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17171
telemt_connections_bad_total 160
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 420
telemt_upstream_connect_success_total 406
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 5598
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 192
telemt_me_adaptive_floor_global_cap_effective 192
telemt_me_adaptive_floor_target_writers_total 27
telemt_desync_total 69
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 15252
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 288113520 (274.77 MB)
telemt_user_octets_to_client{user="hello"} 4283996016 (3.99 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 78
```