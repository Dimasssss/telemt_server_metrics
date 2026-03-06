# Server Metrics 2026-03-06 18:14:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 394.2 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12990
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 136
telemt_upstream_connect_attempt_total 164
telemt_upstream_connect_success_total 145
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 82
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 3786
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 94
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 11874
telemt_user_connections_current{user="hello"} 952
telemt_user_octets_from_client{user="hello"} 592505108 (565.06 MB)
telemt_user_octets_to_client{user="hello"} 2520296276 (2.35 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 394.0 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4201
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 244
telemt_upstream_connect_success_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 35
telemt_me_reconnect_success_total 37
telemt_me_reader_eof_total 44
telemt_me_idle_close_by_peer_total 44
telemt_me_route_drop_no_conn_total 1139
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 17
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 4054
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 117490024 (112.05 MB)
telemt_user_octets_to_client{user="hello"} 854610184 (815.02 MB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 393.9 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7291
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 212
telemt_upstream_connect_attempt_total 310
telemt_upstream_connect_success_total 305
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 7
telemt_me_route_drop_no_conn_total 1402
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 37
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_user_connections_total{user="hello"} 6772
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 175590232 (167.46 MB)
telemt_user_octets_to_client{user="hello"} 1090628588 (1.02 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 394.5 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7145
telemt_connections_bad_total 1338
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 205
telemt_upstream_connect_success_total 194
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 1371
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5423
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 24974900 (23.82 MB)
telemt_user_octets_to_client{user="hello"} 2232688736 (2.08 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 392.9 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8328
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 181
telemt_upstream_connect_success_total 169
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 1665
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 26
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_user_connections_total{user="hello"} 7470
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 72535328 (69.18 MB)
telemt_user_octets_to_client{user="hello"} 2543055624 (2.37 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 86
```