# Server Metrics 2026-03-05 22:34:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 798.1 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4874
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 47
telemt_upstream_connect_attempt_total 207
telemt_upstream_connect_success_total 199
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 199
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 794
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 18
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 4666
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 194316028 (185.31 MB)
telemt_user_octets_to_client{user="hello"} 1846613084 (1.72 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 793.5 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1953
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 342
telemt_upstream_connect_success_total 340
telemt_upstream_connect_attempts_per_request{bucket="1"} 340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 270
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 10
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 1875
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 57438304 (54.78 MB)
telemt_user_octets_to_client{user="hello"} 254808296 (243.00 MB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 790.9 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3457
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 231
telemt_upstream_connect_success_total 219
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 219
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 569
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 3411
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 229248904 (218.63 MB)
telemt_user_octets_to_client{user="hello"} 1133771468 (1.06 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 787.2 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3159
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 79
telemt_upstream_connect_attempt_total 245
telemt_upstream_connect_success_total 238
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 238
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 678
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 10
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 3015
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 69091456 (65.89 MB)
telemt_user_octets_to_client{user="hello"} 2955961448 (2.75 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 786.4 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3532
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 260
telemt_upstream_connect_success_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 1115
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 3449
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 129102548 (123.12 MB)
telemt_user_octets_to_client{user="hello"} 5499648652 (5.12 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```