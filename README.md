# Server Metrics 2026-03-06 02:45:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 15847.3 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106158
telemt_connections_bad_total 15904
telemt_handshake_timeouts_total 1148
telemt_upstream_connect_attempt_total 14284
telemt_upstream_connect_success_total 14166
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 14166
telemt_upstream_connect_attempts_per_request{bucket="2"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 4084
telemt_me_reconnect_success_total 4067
telemt_me_reader_eof_total 4203
telemt_me_idle_close_by_peer_total 4203
telemt_me_route_drop_no_conn_total 27728
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 276
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 2
telemt_pool_force_close_total 91
telemt_me_writer_removed_unexpected_total 4203
telemt_me_writer_restored_same_endpoint_total 4061
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 84295
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 1006125612 (959.52 MB)
telemt_user_octets_to_client{user="hello"} 32804423888 (30.55 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 15842.7 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35195
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 445
telemt_upstream_connect_attempt_total 11259
telemt_upstream_connect_success_total 11257
telemt_upstream_connect_attempts_per_request{bucket="1"} 11257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 1745
telemt_me_reconnect_success_total 1736
telemt_me_reader_eof_total 1753
telemt_me_idle_close_by_peer_total 1753
telemt_me_route_drop_no_conn_total 10483
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1754
telemt_me_writer_restored_same_endpoint_total 1730
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 34125
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 223986408 (213.61 MB)
telemt_user_octets_to_client{user="hello"} 7868785744 (7.33 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 15840.0 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63946
telemt_connections_bad_total 542
telemt_handshake_timeouts_total 939
telemt_upstream_connect_attempt_total 14307
telemt_upstream_connect_success_total 14186
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 14186
telemt_upstream_connect_attempts_per_request{bucket="2"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 165
telemt_me_reconnect_attempts_total 4116
telemt_me_reconnect_success_total 4102
telemt_me_reader_eof_total 4296
telemt_me_idle_close_by_peer_total 4296
telemt_me_route_drop_no_conn_total 17868
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4297
telemt_me_writer_restored_same_endpoint_total 4095
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 60030
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 632619740 (603.31 MB)
telemt_user_octets_to_client{user="hello"} 21022311524 (19.58 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 15836.7 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50414
telemt_connections_bad_total 265
telemt_handshake_timeouts_total 2970
telemt_upstream_connect_attempt_total 10357
telemt_upstream_connect_success_total 10323
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 10323
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 2108
telemt_me_reconnect_success_total 2095
telemt_me_reader_eof_total 2190
telemt_me_idle_close_by_peer_total 2190
telemt_me_route_drop_no_conn_total 20240
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2190
telemt_me_writer_restored_same_endpoint_total 2088
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 44488
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 389869068 (371.81 MB)
telemt_user_octets_to_client{user="hello"} 21979399436 (20.47 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 15835.9 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62960
telemt_connections_bad_total 585
telemt_handshake_timeouts_total 420
telemt_upstream_connect_attempt_total 9365
telemt_upstream_connect_success_total 9343
telemt_upstream_connect_attempts_per_request{bucket="1"} 9343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 1037
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 1054
telemt_me_idle_close_by_peer_total 1054
telemt_me_route_drop_no_conn_total 19380
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 70
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1054
telemt_me_writer_restored_same_endpoint_total 1027
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 61021
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 11999826320 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 24542001016 (22.86 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```