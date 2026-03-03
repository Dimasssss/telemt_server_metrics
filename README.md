# Server Metrics 2026-03-03 21:52:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 2535.5 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26342
telemt_connections_bad_total 262
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 961
telemt_upstream_connect_success_total 954
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 954
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 58
telemt_me_reconnect_success_total 73
telemt_me_reader_eof_total 54
telemt_me_idle_close_by_peer_total 54
telemt_me_route_drop_no_conn_total 10750
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 57
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_restored_same_endpoint_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 25320
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 265612320 (253.31 MB)
telemt_user_octets_to_client{user="hello"} 11928532816 (11.11 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 2532.2 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10732
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 1665
telemt_upstream_connect_attempt_total 1192
telemt_upstream_connect_success_total 1113
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 1113
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 153
telemt_me_reconnect_success_total 168
telemt_me_reader_eof_total 152
telemt_me_idle_close_by_peer_total 152
telemt_me_route_drop_no_conn_total 4120
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 36
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 152
telemt_me_writer_restored_same_endpoint_total 148
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 8892
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 41404960 (39.49 MB)
telemt_user_octets_to_client{user="hello"} 2481103364 (2.31 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 2530.9 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26366
telemt_connections_bad_total 6961
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 1160
telemt_upstream_connect_success_total 1145
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1145
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 74
telemt_me_reconnect_success_total 91
telemt_me_reader_eof_total 71
telemt_me_idle_close_by_peer_total 71
telemt_me_route_drop_no_conn_total 5448
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 73
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 71
telemt_me_writer_restored_same_endpoint_total 70
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 18473
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 152733604 (145.66 MB)
telemt_user_octets_to_client{user="hello"} 8883353932 (8.27 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 2529.9 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11858
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 1148
telemt_upstream_connect_success_total 1139
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1139
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 475
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 62
telemt_me_reader_eof_total 44
telemt_me_idle_close_by_peer_total 44
telemt_me_route_drop_no_conn_total 5313
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 43
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 11388
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 94873160 (90.48 MB)
telemt_user_octets_to_client{user="hello"} 4397420352 (4.10 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 2528.8 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26467
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 6477
telemt_upstream_connect_attempt_total 1080
telemt_upstream_connect_success_total 1057
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1057
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 143
telemt_me_reconnect_success_total 160
telemt_me_reader_eof_total 140
telemt_me_idle_close_by_peer_total 140
telemt_me_route_drop_no_conn_total 22532
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 140
telemt_me_writer_restored_same_endpoint_total 139
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 19560
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 83609188 (79.74 MB)
telemt_user_octets_to_client{user="hello"} 3114408952 (2.90 GB)
telemt_user_unique_ips_current{user="hello"} 32
```