# Server Metrics 2026-03-07 07:25:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.7

telemt_uptime_seconds 1073.9 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21208
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 107
telemt_upstream_connect_attempt_total 260
telemt_upstream_connect_success_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 5966
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 27
telemt_desync_total 142
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 20402
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 307937240 (293.67 MB)
telemt_user_octets_to_client{user="hello"} 8058966372 (7.51 GB)
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server2

```
telemt 3.3.7

telemt_uptime_seconds 1074.2 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7753
telemt_connections_bad_total 902
telemt_handshake_timeouts_total 290
telemt_upstream_connect_attempt_total 283
telemt_upstream_connect_success_total 280
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 2258
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 8
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 6281
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 110640052 (105.51 MB)
telemt_user_octets_to_client{user="hello"} 2448679412 (2.28 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.7

telemt_uptime_seconds 1074.2 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14631
telemt_connections_bad_total 723
telemt_handshake_timeouts_total 468
telemt_upstream_connect_attempt_total 476
telemt_upstream_connect_success_total 471
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 3930
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 68
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 7
telemt_user_connections_total{user="hello"} 13111
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 1069390568 (1019.85 MB)
telemt_user_octets_to_client{user="hello"} 8220568656 (7.66 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.7

telemt_uptime_seconds 1074.5 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9653
telemt_connections_bad_total 933
telemt_handshake_timeouts_total 367
telemt_upstream_connect_attempt_total 495
telemt_upstream_connect_success_total 492
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 4229
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 7763
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 67987964 (64.84 MB)
telemt_user_octets_to_client{user="hello"} 3624096824 (3.38 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.7

telemt_uptime_seconds 1073.6 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12933
telemt_connections_bad_total 160
telemt_handshake_timeouts_total 289
telemt_upstream_connect_attempt_total 300
telemt_upstream_connect_success_total 287
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 4373
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 192
telemt_me_adaptive_floor_global_cap_effective 192
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 55
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 11567
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 250008556 (238.43 MB)
telemt_user_octets_to_client{user="hello"} 3447830148 (3.21 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 87
```