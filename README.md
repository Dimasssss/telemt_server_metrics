# Server Metrics 2026-03-05 23:10:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 2947.8 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28245
telemt_connections_bad_total 10783
telemt_handshake_timeouts_total 203
telemt_upstream_connect_attempt_total 1521
telemt_upstream_connect_success_total 1496
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1496
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 179
telemt_me_reconnect_success_total 180
telemt_me_reader_eof_total 177
telemt_me_idle_close_by_peer_total 177
telemt_me_route_drop_no_conn_total 4327
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 58
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 177
telemt_me_writer_restored_same_endpoint_total 176
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 16738
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 364961016 (348.05 MB)
telemt_user_octets_to_client{user="hello"} 6520338632 (6.07 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 2943.2 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7557
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 151
telemt_upstream_connect_attempt_total 1400
telemt_upstream_connect_success_total 1398
telemt_upstream_connect_attempts_per_request{bucket="1"} 1398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 40
telemt_me_reconnect_success_total 43
telemt_me_reader_eof_total 40
telemt_me_idle_close_by_peer_total 40
telemt_me_route_drop_no_conn_total 2579
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 27
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_pool_force_close_total 8
telemt_me_writer_removed_unexpected_total 41
telemt_me_writer_restored_same_endpoint_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 7150
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 71995740 (68.66 MB)
telemt_user_octets_to_client{user="hello"} 1087937684 (1.01 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 2940.6 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12045
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 1625
telemt_upstream_connect_success_total 1595
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1595
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 230
telemt_me_reconnect_success_total 231
telemt_me_reader_eof_total 233
telemt_me_idle_close_by_peer_total 233
telemt_me_route_drop_no_conn_total 3585
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 233
telemt_me_writer_restored_same_endpoint_total 226
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 11900
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 294371688 (280.73 MB)
telemt_user_octets_to_client{user="hello"} 4118411536 (3.84 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 2937.2 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10620
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 248
telemt_upstream_connect_attempt_total 1686
telemt_upstream_connect_success_total 1677
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1677
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 665
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 245
telemt_me_reconnect_success_total 243
telemt_me_reader_eof_total 244
telemt_me_idle_close_by_peer_total 244
telemt_me_route_drop_no_conn_total 5427
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 41
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 1
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 244
telemt_me_writer_restored_same_endpoint_total 239
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 9786
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 127705984 (121.79 MB)
telemt_user_octets_to_client{user="hello"} 11653877268 (10.85 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 2936.4 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12490
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 1646
telemt_upstream_connect_success_total 1645
telemt_upstream_connect_attempts_per_request{bucket="1"} 1645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 186
telemt_me_reconnect_success_total 188
telemt_me_reader_eof_total 187
telemt_me_idle_close_by_peer_total 187
telemt_me_route_drop_no_conn_total 5978
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 187
telemt_me_writer_restored_same_endpoint_total 185
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 12228
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 5079645384 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 13648002616 (12.71 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 24
```