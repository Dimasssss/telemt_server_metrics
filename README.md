# Server Metrics 2026-03-06 08:49:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 1041.9 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25261
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 223
telemt_upstream_connect_success_total 221
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 6117
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 174
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 23099
telemt_user_connections_current{user="hello"} 1022
telemt_user_octets_from_client{user="hello"} 343621948 (327.70 MB)
telemt_user_octets_to_client{user="hello"} 7694226764 (7.17 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 1039.4 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11023
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 809
telemt_upstream_connect_attempt_total 193
telemt_upstream_connect_success_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 109
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 3204
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 48
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 9567
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 121828096 (116.18 MB)
telemt_user_octets_to_client{user="hello"} 3515750376 (3.27 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 1022.5 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22157
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 3525
telemt_upstream_connect_attempt_total 262
telemt_upstream_connect_success_total 260
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 5125
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 16869
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 212398380 (202.56 MB)
telemt_user_octets_to_client{user="hello"} 4715906840 (4.39 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 1007.1 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17236
telemt_connections_bad_total 913
telemt_handshake_timeouts_total 4344
telemt_upstream_connect_attempt_total 264
telemt_upstream_connect_success_total 258
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 5262
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 11367
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 249483320 (237.93 MB)
telemt_user_octets_to_client{user="hello"} 3697744464 (3.44 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 948.9 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14114
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 226
telemt_upstream_connect_success_total 218
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 4806
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 25
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 13605
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 149955420 (143.01 MB)
telemt_user_octets_to_client{user="hello"} 4972846044 (4.63 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 82
```