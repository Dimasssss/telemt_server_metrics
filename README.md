# Server Metrics 2026-03-07 07:51:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.7

telemt_uptime_seconds 2619.8 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50019
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 373
telemt_upstream_connect_attempt_total 906
telemt_upstream_connect_success_total 906
telemt_upstream_connect_attempts_per_request{bucket="1"} 906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 17
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 21
telemt_me_idle_close_by_peer_total 21
telemt_me_route_drop_no_conn_total 16882
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 298
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_me_writer_removed_unexpected_total 21
telemt_me_writer_restored_same_endpoint_total 15
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 47618
telemt_user_connections_current{user="hello"} 830
telemt_user_octets_from_client{user="hello"} 803167784 (765.96 MB)
telemt_user_octets_to_client{user="hello"} 19306350040 (17.98 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server2

```
telemt 3.3.7

telemt_uptime_seconds 2619.8 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18780
telemt_connections_bad_total 1060
telemt_handshake_timeouts_total 1140
telemt_upstream_connect_attempt_total 1072
telemt_upstream_connect_success_total 1067
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 38
telemt_me_reader_eof_total 37
telemt_me_idle_close_by_peer_total 37
telemt_me_route_drop_no_conn_total 6625
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 54
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_me_writer_removed_unexpected_total 37
telemt_me_writer_restored_same_endpoint_total 37
telemt_user_connections_total{user="hello"} 15903
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 201325628 (192.00 MB)
telemt_user_octets_to_client{user="hello"} 5604111408 (5.22 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server3

```
telemt 3.3.7

telemt_uptime_seconds 2619.6 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35774
telemt_connections_bad_total 1964
telemt_handshake_timeouts_total 1531
telemt_upstream_connect_attempt_total 1450
telemt_upstream_connect_success_total 1442
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 85
telemt_me_reconnect_success_total 84
telemt_me_reader_eof_total 87
telemt_me_idle_close_by_peer_total 87
telemt_me_route_drop_no_conn_total 11493
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 27
telemt_desync_total 149
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_restored_same_endpoint_total 83
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 31690
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 2576901776 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 15280797552 (14.23 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.7

telemt_uptime_seconds 2620.3 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22967
telemt_connections_bad_total 2508
telemt_handshake_timeouts_total 489
telemt_upstream_connect_attempt_total 1595
telemt_upstream_connect_success_total 1590
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 554
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 126
telemt_me_reconnect_success_total 126
telemt_me_reader_eof_total 130
telemt_me_idle_close_by_peer_total 130
telemt_me_route_drop_no_conn_total 9700
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 27
telemt_desync_total 21
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 130
telemt_me_writer_restored_same_endpoint_total 125
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 18944
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 197623204 (188.47 MB)
telemt_user_octets_to_client{user="hello"} 6197358416 (5.77 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.7

telemt_uptime_seconds 2619.9 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31355
telemt_connections_bad_total 175
telemt_handshake_timeouts_total 512
telemt_upstream_connect_attempt_total 1081
telemt_upstream_connect_success_total 1060
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 48
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 47
telemt_me_idle_close_by_peer_total 47
telemt_me_route_drop_no_conn_total 11217
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 192
telemt_me_adaptive_floor_global_cap_effective 192
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 97
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_me_writer_removed_unexpected_total 47
telemt_me_writer_restored_same_endpoint_total 47
telemt_user_connections_total{user="hello"} 27549
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 461256156 (439.89 MB)
telemt_user_octets_to_client{user="hello"} 9574680440 (8.92 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 57
```