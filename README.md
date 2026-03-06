# Server Metrics 2026-03-06 08:44:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 734.6 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17548
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 139
telemt_upstream_connect_success_total 137
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 4248
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 144
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 16930
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 261803468 (249.68 MB)
telemt_user_octets_to_client{user="hello"} 5971542236 (5.56 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 732.0 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7363
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 259
telemt_upstream_connect_attempt_total 114
telemt_upstream_connect_success_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 71
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 1991
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 38
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 6838
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 91391360 (87.16 MB)
telemt_user_octets_to_client{user="hello"} 2748498084 (2.56 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 715.2 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14489
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 1849
telemt_upstream_connect_attempt_total 175
telemt_upstream_connect_success_total 174
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 3471
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 29
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 11937
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 100847768 (96.18 MB)
telemt_user_octets_to_client{user="hello"} 3316684352 (3.09 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 699.8 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11767
telemt_connections_bad_total 623
telemt_handshake_timeouts_total 3012
telemt_upstream_connect_attempt_total 177
telemt_upstream_connect_success_total 172
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 2360
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 36
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 7821
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 184230644 (175.70 MB)
telemt_user_octets_to_client{user="hello"} 2712749920 (2.53 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 641.5 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9881
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 162
telemt_upstream_connect_success_total 156
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_success_total 5
telemt_me_route_drop_no_conn_total 3153
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_user_connections_total{user="hello"} 9520
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 103915116 (99.10 MB)
telemt_user_octets_to_client{user="hello"} 3242958160 (3.02 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 92
```