# Server Metrics 2026-03-03 21:32:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 1306.2 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14943
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 334
telemt_upstream_connect_success_total 329
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 329
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 147
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 25
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 5964
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 14280
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 109145804 (104.09 MB)
telemt_user_octets_to_client{user="hello"} 6862815512 (6.39 GB)
telemt_user_unique_ips_current{user="hello"} 72
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 1302.7 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5571
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 771
telemt_upstream_connect_attempt_total 331
telemt_upstream_connect_success_total 291
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 291
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 2198
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 28
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 4672
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 21645596 (20.64 MB)
telemt_user_octets_to_client{user="hello"} 1225005532 (1.14 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 1301.7 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14633
telemt_connections_bad_total 3503
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 364
telemt_upstream_connect_success_total 350
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 350
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 2826
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 10561
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 85691564 (81.72 MB)
telemt_user_octets_to_client{user="hello"} 2952441516 (2.75 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 1300.8 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6166
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 440
telemt_upstream_connect_success_total 431
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 431
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 25
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 3251
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 6084
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 47773852 (45.56 MB)
telemt_user_octets_to_client{user="hello"} 1303524760 (1.21 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 1299.3 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16509
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 3545
telemt_upstream_connect_attempt_total 350
telemt_upstream_connect_success_total 329
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 329
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 25
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 18089
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 12585
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 39310840 (37.49 MB)
telemt_user_octets_to_client{user="hello"} 1419594296 (1.32 GB)
telemt_user_unique_ips_current{user="hello"} 36
```