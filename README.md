# Server Metrics 2026-03-06 03:21:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 17997.2 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123395
telemt_connections_bad_total 15918
telemt_handshake_timeouts_total 2469
telemt_upstream_connect_attempt_total 18375
telemt_upstream_connect_success_total 18213
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 18213
telemt_upstream_connect_attempts_per_request{bucket="2"} 76
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 191
telemt_me_reconnect_attempts_total 6221
telemt_me_reconnect_success_total 6198
telemt_me_reader_eof_total 6409
telemt_me_idle_close_by_peer_total 6409
telemt_me_route_drop_no_conn_total 33351
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 329
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 2
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 6409
telemt_me_writer_restored_same_endpoint_total 6192
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 98230
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 1305610668 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 38340545348 (35.71 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 17992.6 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40740
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 535
telemt_upstream_connect_attempt_total 13681
telemt_upstream_connect_success_total 13679
telemt_upstream_connect_attempts_per_request{bucket="1"} 13679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 2277
telemt_me_reconnect_success_total 2267
telemt_me_reader_eof_total 2294
telemt_me_idle_close_by_peer_total 2294
telemt_me_route_drop_no_conn_total 12098
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 123
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 2295
telemt_me_writer_restored_same_endpoint_total 2261
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 39448
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 263739536 (251.52 MB)
telemt_user_octets_to_client{user="hello"} 9713539512 (9.05 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 17990.0 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73848
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 1560
telemt_upstream_connect_attempt_total 17023
telemt_upstream_connect_success_total 16882
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 16882
telemt_upstream_connect_attempts_per_request{bucket="2"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 201
telemt_me_reconnect_attempts_total 5048
telemt_me_reconnect_success_total 5030
telemt_me_reader_eof_total 5263
telemt_me_idle_close_by_peer_total 5263
telemt_me_route_drop_no_conn_total 20496
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 5267
telemt_me_writer_restored_same_endpoint_total 5023
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 68954
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 677699964 (646.31 MB)
telemt_user_octets_to_client{user="hello"} 24093176288 (22.44 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 17986.7 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59435
telemt_connections_bad_total 275
telemt_handshake_timeouts_total 3939
telemt_upstream_connect_attempt_total 12348
telemt_upstream_connect_success_total 12311
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 12311
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 2567
telemt_me_reconnect_success_total 2551
telemt_me_reader_eof_total 2651
telemt_me_idle_close_by_peer_total 2651
telemt_me_route_drop_no_conn_total 22296
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2651
telemt_me_writer_restored_same_endpoint_total 2544
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 51943
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 503916944 (480.57 MB)
telemt_user_octets_to_client{user="hello"} 24162114104 (22.50 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 17985.7 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72240
telemt_connections_bad_total 869
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 11056
telemt_upstream_connect_success_total 11032
telemt_upstream_connect_attempts_per_request{bucket="1"} 11032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 1279
telemt_me_reconnect_success_total 1274
telemt_me_reader_eof_total 1301
telemt_me_idle_close_by_peer_total 1301
telemt_me_route_drop_no_conn_total 22908
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 75
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1301
telemt_me_writer_restored_same_endpoint_total 1268
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 69806
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 12120629992 (11.29 GB)
telemt_user_octets_to_client{user="hello"} 39850562752 (37.11 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 36
```