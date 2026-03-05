# Server Metrics 2026-03-05 23:20:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 3561.7 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31965
telemt_connections_bad_total 11501
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 2113
telemt_upstream_connect_success_total 2088
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2088
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 382
telemt_me_reconnect_success_total 382
telemt_me_reader_eof_total 388
telemt_me_idle_close_by_peer_total 388
telemt_me_route_drop_no_conn_total 5251
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 65
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 388
telemt_me_writer_restored_same_endpoint_total 378
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 19573
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 382612736 (364.89 MB)
telemt_user_octets_to_client{user="hello"} 7987824660 (7.44 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 3557.2 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8905
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 170
telemt_upstream_connect_attempt_total 1974
telemt_upstream_connect_success_total 1972
telemt_upstream_connect_attempts_per_request{bucket="1"} 1972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 140
telemt_me_reconnect_success_total 142
telemt_me_reader_eof_total 139
telemt_me_idle_close_by_peer_total 139
telemt_me_route_drop_no_conn_total 2992
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 29
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_pool_force_close_total 8
telemt_me_writer_removed_unexpected_total 140
telemt_me_writer_restored_same_endpoint_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 8460
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 76916576 (73.35 MB)
telemt_user_octets_to_client{user="hello"} 1337447280 (1.25 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 3554.5 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14589
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 2333
telemt_upstream_connect_success_total 2301
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2301
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 428
telemt_me_reconnect_success_total 429
telemt_me_reader_eof_total 441
telemt_me_idle_close_by_peer_total 441
telemt_me_route_drop_no_conn_total 4612
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 442
telemt_me_writer_restored_same_endpoint_total 424
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 14276
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 307431940 (293.19 MB)
telemt_user_octets_to_client{user="hello"} 4817675632 (4.49 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 3551.3 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12548
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 299
telemt_upstream_connect_attempt_total 1845
telemt_upstream_connect_success_total 1836
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1836
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 735
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 248
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 246
telemt_me_idle_close_by_peer_total 246
telemt_me_route_drop_no_conn_total 5759
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 47
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 246
telemt_me_writer_restored_same_endpoint_total 241
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 11424
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 155697724 (148.48 MB)
telemt_user_octets_to_client{user="hello"} 13478049132 (12.55 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 3550.2 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14771
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 2273
telemt_upstream_connect_success_total 2272
telemt_upstream_connect_attempts_per_request{bucket="1"} 2272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 400
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 6689
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 406
telemt_me_writer_restored_same_endpoint_total 398
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 14465
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 9470795392 (8.82 GB)
telemt_user_octets_to_client{user="hello"} 14031121616 (13.07 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 34
```