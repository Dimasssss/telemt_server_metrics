# Server Metrics 2026-03-06 08:54:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 1351.8 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34429
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 323
telemt_upstream_connect_success_total 320
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 7962
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 231
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 29561
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 523858932 (499.59 MB)
telemt_user_octets_to_client{user="hello"} 9590332000 (8.93 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 1349.1 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15995
telemt_connections_bad_total 287
telemt_handshake_timeouts_total 2930
telemt_upstream_connect_attempt_total 297
telemt_upstream_connect_success_total 297
telemt_upstream_connect_attempts_per_request{bucket="1"} 297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 4286
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 74
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 12103
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 165028420 (157.38 MB)
telemt_user_octets_to_client{user="hello"} 4393345096 (4.09 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 1332.4 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27899
telemt_connections_bad_total 179
telemt_handshake_timeouts_total 4613
telemt_upstream_connect_attempt_total 384
telemt_upstream_connect_success_total 382
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 6822
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 21740
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 444510972 (423.92 MB)
telemt_user_octets_to_client{user="hello"} 6555466868 (6.11 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 1316.9 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23342
telemt_connections_bad_total 1185
telemt_handshake_timeouts_total 6646
telemt_upstream_connect_attempt_total 394
telemt_upstream_connect_success_total 388
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 9061
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 64
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 15059
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 277511652 (264.66 MB)
telemt_user_octets_to_client{user="hello"} 4652952836 (4.33 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 1258.7 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18006
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 57
telemt_upstream_connect_attempt_total 368
telemt_upstream_connect_success_total 357
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 6973
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 25
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 7
telemt_user_connections_total{user="hello"} 17406
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 190444188 (181.62 MB)
telemt_user_octets_to_client{user="hello"} 6516563380 (6.07 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 83
```