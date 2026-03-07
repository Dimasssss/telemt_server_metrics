# Server Metrics 2026-03-07 07:46:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.7

telemt_uptime_seconds 2306.8 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44306
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 787
telemt_upstream_connect_success_total 786
telemt_upstream_connect_attempts_per_request{bucket="1"} 786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 19
telemt_me_idle_close_by_peer_total 19
telemt_me_route_drop_no_conn_total 14541
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 262
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 202
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_restored_same_endpoint_total 13
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 42089
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 699005544 (666.62 MB)
telemt_user_octets_to_client{user="hello"} 17272940896 (16.09 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server2

```
telemt 3.3.7

telemt_uptime_seconds 2306.7 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16238
telemt_connections_bad_total 1059
telemt_handshake_timeouts_total 630
telemt_upstream_connect_attempt_total 924
telemt_upstream_connect_success_total 919
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 464
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 36
telemt_me_reconnect_success_total 35
telemt_me_reader_eof_total 34
telemt_me_idle_close_by_peer_total 34
telemt_me_route_drop_no_conn_total 5987
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 27
telemt_desync_total 41
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 34
telemt_me_writer_restored_same_endpoint_total 34
telemt_user_connections_total{user="hello"} 13835
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 169658984 (161.80 MB)
telemt_user_octets_to_client{user="hello"} 4914976676 (4.58 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.7

telemt_uptime_seconds 2306.7 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31241
telemt_connections_bad_total 1752
telemt_handshake_timeouts_total 1498
telemt_upstream_connect_attempt_total 1245
telemt_upstream_connect_success_total 1237
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 10006
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 135
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_me_writer_removed_unexpected_total 61
telemt_me_writer_restored_same_endpoint_total 58
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 27477
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 2255801148 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 13978406120 (13.02 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.7

telemt_uptime_seconds 2307.0 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20290
telemt_connections_bad_total 2191
telemt_handshake_timeouts_total 442
telemt_upstream_connect_attempt_total 1303
telemt_upstream_connect_success_total 1298
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 441
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 58
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 59
telemt_me_idle_close_by_peer_total 59
telemt_me_route_drop_no_conn_total 8631
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 23
telemt_desync_total 21
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 59
telemt_me_writer_restored_same_endpoint_total 58
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 16701
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 163835320 (156.25 MB)
telemt_user_octets_to_client{user="hello"} 5702037260 (5.31 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.7

telemt_uptime_seconds 2306.8 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27998
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 504
telemt_upstream_connect_attempt_total 915
telemt_upstream_connect_success_total 895
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 32
telemt_me_reconnect_success_total 35
telemt_me_reader_eof_total 31
telemt_me_idle_close_by_peer_total 31
telemt_me_route_drop_no_conn_total 9863
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 192
telemt_me_adaptive_floor_global_cap_effective 192
telemt_me_adaptive_floor_target_writers_total 27
telemt_desync_total 93
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_me_writer_removed_unexpected_total 31
telemt_me_writer_restored_same_endpoint_total 31
telemt_user_connections_total{user="hello"} 24699
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 399283932 (380.79 MB)
telemt_user_octets_to_client{user="hello"} 8394331268 (7.82 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 63
```