# Server Metrics 2026-03-04 22:29:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 5780.4 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65523
telemt_connections_bad_total 1345
telemt_handshake_timeouts_total 436
telemt_upstream_connect_attempt_total 4680
telemt_upstream_connect_success_total 4623
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4623
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 1152
telemt_me_reconnect_success_total 1162
telemt_me_reader_eof_total 1173
telemt_me_idle_close_by_peer_total 1173
telemt_me_route_drop_no_conn_total 16128
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 1173
telemt_me_writer_restored_same_endpoint_total 1142
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 54904
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 2279591056 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 27709727744 (25.81 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 5775.1 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23596
telemt_connections_bad_total 676
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 5213
telemt_upstream_connect_success_total 5155
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5155
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1434
telemt_me_reconnect_success_total 1443
telemt_me_reader_eof_total 1462
telemt_me_idle_close_by_peer_total 1462
telemt_me_route_drop_no_conn_total 6989
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 1462
telemt_me_writer_restored_same_endpoint_total 1424
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 22043
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 200423220 (191.14 MB)
telemt_user_octets_to_client{user="hello"} 5708337168 (5.32 GB)
telemt_user_unique_ips_current{user="hello"} 11
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 5771.8 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53797
telemt_connections_bad_total 973
telemt_handshake_timeouts_total 238
telemt_upstream_connect_attempt_total 1902
telemt_upstream_connect_success_total 1880
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1880
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 37
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 36
telemt_me_idle_close_by_peer_total 36
telemt_me_route_drop_no_conn_total 16195
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 137
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 36
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 49068
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 687240044 (655.40 MB)
telemt_user_octets_to_client{user="hello"} 20081204364 (18.70 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 37820.0 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515750
telemt_connections_bad_total 68801
telemt_handshake_timeouts_total 14657
telemt_upstream_connect_attempt_total 16472
telemt_upstream_connect_success_total 16472
telemt_upstream_connect_attempts_per_request{bucket="1"} 16472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 2172
telemt_me_reconnect_success_total 2157
telemt_me_reader_eof_total 2197
telemt_me_idle_close_by_peer_total 2197
telemt_me_route_drop_no_conn_total 177496
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 696
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 13
telemt_pool_force_close_total 423
telemt_me_writer_removed_unexpected_total 2198
telemt_me_writer_restored_same_endpoint_total 2133
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 404090
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 5685638252 (5.30 GB)
telemt_user_octets_to_client{user="hello"} 154065613748 (143.48 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 38179.4 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517071
telemt_connections_bad_total 3759
telemt_handshake_timeouts_total 5753
telemt_upstream_connect_attempt_total 22496
telemt_upstream_connect_success_total 22374
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 22374
telemt_upstream_connect_attempts_per_request{bucket="2"} 51
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 4615
telemt_me_reconnect_success_total 4601
telemt_me_reader_eof_total 4768
telemt_me_idle_close_by_peer_total 4768
telemt_me_route_drop_no_conn_total 228176
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 826
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4771
telemt_me_writer_restored_same_endpoint_total 4580
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 467016
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 7202499856 (6.71 GB)
telemt_user_octets_to_client{user="hello"} 150471114624 (140.14 GB)
telemt_user_unique_ips_current{user="hello"} 37
```