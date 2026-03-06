# Server Metrics 2026-03-06 11:07:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 2751.0 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97775
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 615
telemt_upstream_connect_attempt_total 608
telemt_upstream_connect_success_total 604
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 21886
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 220
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 67907
telemt_user_connections_current{user="hello"} 1131
telemt_user_octets_from_client{user="hello"} 2367058992 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 23514981608 (21.90 GB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 2750.8 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28289
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 564
telemt_upstream_connect_attempt_total 660
telemt_upstream_connect_success_total 658
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 11586
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_restored_same_endpoint_total 9
telemt_user_connections_total{user="hello"} 27026
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 263399768 (251.20 MB)
telemt_user_octets_to_client{user="hello"} 8435950012 (7.86 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 2750.7 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50082
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 1452
telemt_upstream_connect_attempt_total 968
telemt_upstream_connect_success_total 960
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 436
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 31
telemt_me_reader_eof_total 32
telemt_me_idle_close_by_peer_total 32
telemt_me_route_drop_no_conn_total 20102
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 54
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_restored_same_endpoint_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 47345
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 570667300 (544.23 MB)
telemt_user_octets_to_client{user="hello"} 11344421396 (10.57 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 2066.7 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22755
telemt_connections_bad_total 1843
telemt_handshake_timeouts_total 460
telemt_upstream_connect_attempt_total 847
telemt_upstream_connect_success_total 847
telemt_upstream_connect_attempts_per_request{bucket="1"} 847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 336
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 40
telemt_me_reconnect_success_total 39
telemt_me_reader_eof_total 41
telemt_me_idle_close_by_peer_total 41
telemt_me_route_drop_no_conn_total 8436
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 30
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_writer_removed_unexpected_total 41
telemt_me_writer_restored_same_endpoint_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 19929
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 185280168 (176.70 MB)
telemt_user_octets_to_client{user="hello"} 5008656860 (4.66 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 2751.2 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54836
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 1247
telemt_upstream_connect_attempt_total 326
telemt_upstream_connect_success_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 2
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 16889
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 44
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 50788
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 11022937388 (10.27 GB)
telemt_user_octets_to_client{user="hello"} 20521290424 (19.11 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 99
```