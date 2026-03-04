# Server Metrics 2026-03-04 22:55:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 7316.0 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78048
telemt_connections_bad_total 1346
telemt_handshake_timeouts_total 489
telemt_upstream_connect_attempt_total 7048
telemt_upstream_connect_success_total 6959
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6958
telemt_upstream_connect_attempts_per_request{bucket="2"} 29
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 268
telemt_me_reconnect_attempts_total 2283
telemt_me_reconnect_success_total 2289
telemt_me_reader_eof_total 2339
telemt_me_idle_close_by_peer_total 2338
telemt_me_route_drop_no_conn_total 19916
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 2374
telemt_me_writer_restored_same_endpoint_total 2269
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 65782
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 2614760756 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 35919972644 (33.45 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 7310.8 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27514
telemt_connections_bad_total 701
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 8024
telemt_upstream_connect_success_total 7892
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 7889
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 508
telemt_me_reconnect_attempts_total 3008
telemt_me_reconnect_success_total 3004
telemt_me_reader_eof_total 3066
telemt_me_idle_close_by_peer_total 3065
telemt_me_route_drop_no_conn_total 8762
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 3120
telemt_me_writer_restored_same_endpoint_total 2985
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 25856
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 230034776 (219.38 MB)
telemt_user_octets_to_client{user="hello"} 7670707016 (7.14 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 7307.5 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61884
telemt_connections_bad_total 1045
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 3237
telemt_upstream_connect_success_total 3205
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3205
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 227
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 228
telemt_me_idle_close_by_peer_total 228
telemt_me_route_drop_no_conn_total 20519
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 146
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 228
telemt_me_writer_restored_same_endpoint_total 219
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 56991
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 925263596 (882.40 MB)
telemt_user_octets_to_client{user="hello"} 23323545980 (21.72 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 39355.7 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525651
telemt_connections_bad_total 71383
telemt_handshake_timeouts_total 14684
telemt_upstream_connect_attempt_total 16938
telemt_upstream_connect_success_total 16938
telemt_upstream_connect_attempts_per_request{bucket="1"} 16938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 2187
telemt_me_reconnect_success_total 2171
telemt_me_reader_eof_total 2213
telemt_me_idle_close_by_peer_total 2213
telemt_me_route_drop_no_conn_total 179879
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 699
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 15
telemt_pool_force_close_total 456
telemt_pool_stale_pick_total 20
telemt_me_writer_removed_unexpected_total 2214
telemt_me_writer_restored_same_endpoint_total 2145
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 411278
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 5723955360 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 155133782496 (144.48 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 39714.9 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522417
telemt_connections_bad_total 3772
telemt_handshake_timeouts_total 5758
telemt_upstream_connect_attempt_total 24214
telemt_upstream_connect_success_total 24080
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 24080
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 5112
telemt_me_reconnect_success_total 5097
telemt_me_reader_eof_total 5284
telemt_me_idle_close_by_peer_total 5284
telemt_me_route_drop_no_conn_total 230395
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 827
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 5287
telemt_me_writer_restored_same_endpoint_total 5076
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 472299
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 7279728924 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 155332172576 (144.66 GB)
telemt_user_unique_ips_current{user="hello"} 28
```