# Server Metrics 2026-03-05 22:39:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 1104.7 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6879
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 330
telemt_upstream_connect_success_total 318
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 318
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 1169
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 24
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 6319
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 283580612 (270.44 MB)
telemt_user_octets_to_client{user="hello"} 2773228628 (2.58 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 1100.2 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2679
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 493
telemt_upstream_connect_success_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 186
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 414
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_pool_swap_total 1
telemt_pool_force_close_total 7
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 2587
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 59396880 (56.65 MB)
telemt_user_octets_to_client{user="hello"} 325654548 (310.57 MB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 1097.6 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4748
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 342
telemt_upstream_connect_success_total 326
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 326
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 866
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 4692
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 245802848 (234.42 MB)
telemt_user_octets_to_client{user="hello"} 1689251688 (1.57 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 1094.3 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4137
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 384
telemt_upstream_connect_success_total 377
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 377
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 1123
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 23
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_restored_same_endpoint_total 10
telemt_user_connections_total{user="hello"} 3939
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 86027768 (82.04 MB)
telemt_user_octets_to_client{user="hello"} 4161890196 (3.88 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 1093.2 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4941
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 410
telemt_upstream_connect_success_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 18
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 1708
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 15
telemt_user_connections_total{user="hello"} 4825
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 139662916 (133.19 MB)
telemt_user_octets_to_client{user="hello"} 7466720576 (6.95 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```