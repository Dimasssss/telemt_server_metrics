# Server Metrics 2026-03-05 22:45:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 1411.8 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10388
telemt_connections_bad_total 2088
telemt_handshake_timeouts_total 91
telemt_upstream_connect_attempt_total 469
telemt_upstream_connect_success_total 457
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 457
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 13
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 1672
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 37
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_restored_same_endpoint_total 10
telemt_user_connections_total{user="hello"} 7937
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 296622944 (282.88 MB)
telemt_user_octets_to_client{user="hello"} 3385742876 (3.15 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 1407.2 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3306
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 603
telemt_upstream_connect_success_total 601
telemt_upstream_connect_attempts_per_request{bucket="1"} 601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 239
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 579
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 7
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_restored_same_endpoint_total 8
telemt_user_connections_total{user="hello"} 3182
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 60907132 (58.09 MB)
telemt_user_octets_to_client{user="hello"} 358231780 (341.64 MB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 1404.6 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6076
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 479
telemt_upstream_connect_success_total 462
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 462
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 13
telemt_me_idle_close_by_peer_total 13
telemt_me_route_drop_no_conn_total 1422
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 13
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 6009
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 258273588 (246.31 MB)
telemt_user_octets_to_client{user="hello"} 2035780076 (1.90 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 1401.2 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5201
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 539
telemt_upstream_connect_success_total 531
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 531
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 29
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 1651
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 30
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 25
telemt_me_writer_restored_same_endpoint_total 25
telemt_user_connections_total{user="hello"} 4939
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 92495580 (88.21 MB)
telemt_user_octets_to_client{user="hello"} 4589710380 (4.27 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 1400.2 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6472
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 559
telemt_upstream_connect_success_total 558
telemt_upstream_connect_attempts_per_request{bucket="1"} 558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 20
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 19
telemt_me_idle_close_by_peer_total 19
telemt_me_route_drop_no_conn_total 2832
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_restored_same_endpoint_total 19
telemt_user_connections_total{user="hello"} 6344
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 151296736 (144.29 MB)
telemt_user_octets_to_client{user="hello"} 9022688832 (8.40 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```