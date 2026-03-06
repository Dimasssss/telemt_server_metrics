# Server Metrics 2026-03-06 21:24:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 11813.5 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228581
telemt_connections_bad_total 2208
telemt_handshake_timeouts_total 8917
telemt_upstream_connect_attempt_total 17639
telemt_upstream_connect_success_total 17482
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 17540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 949
telemt_me_reconnect_attempts_total 5228
telemt_me_reconnect_success_total 5195
telemt_me_reader_eof_total 6716
telemt_me_idle_close_by_peer_total 6716
telemt_me_route_drop_no_conn_total 87382
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 780
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 6823
telemt_me_writer_restored_same_endpoint_total 5189
telemt_me_writer_removed_unexpected_minus_restored_total 1634
telemt_user_connections_total{user="hello"} 204129
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 3015798612 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 73861604868 (68.79 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 11813.4 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87398
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 5617
telemt_upstream_connect_attempt_total 21606
telemt_upstream_connect_success_total 21605
telemt_upstream_connect_attempts_per_request{bucket="1"} 21605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 348
telemt_me_reconnect_attempts_total 7315
telemt_me_reconnect_success_total 7305
telemt_me_reader_eof_total 10229
telemt_me_idle_close_by_peer_total 10227
telemt_me_route_drop_no_conn_total 32070
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 519
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 376
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 6
telemt_pool_force_close_total 231
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 10229
telemt_me_writer_restored_same_endpoint_total 7303
telemt_me_writer_removed_unexpected_minus_restored_total 2926
telemt_user_connections_total{user="hello"} 76635
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 1248964508 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 25685932824 (23.92 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 11813.3 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168278
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 2143
telemt_upstream_connect_attempt_total 18303
telemt_upstream_connect_success_total 18168
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 18204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 948
telemt_me_reconnect_attempts_total 5298
telemt_me_reconnect_success_total 5272
telemt_me_reader_eof_total 7074
telemt_me_idle_close_by_peer_total 7071
telemt_me_route_drop_no_conn_total 66890
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 779
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 592
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 5
telemt_pool_force_close_total 190
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 7175
telemt_me_writer_restored_same_endpoint_total 5265
telemt_me_writer_removed_unexpected_minus_restored_total 1910
telemt_user_connections_total{user="hello"} 155952
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 8920458644 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 44539657284 (41.48 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 11813.8 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173298
telemt_connections_bad_total 50467
telemt_handshake_timeouts_total 13081
telemt_upstream_connect_attempt_total 19311
telemt_upstream_connect_success_total 19268
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 382
telemt_me_reconnect_attempts_total 6302
telemt_me_reconnect_success_total 6288
telemt_me_reader_eof_total 8229
telemt_me_idle_close_by_peer_total 8229
telemt_me_route_drop_no_conn_total 43443
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 151
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 5
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 8234
telemt_me_writer_restored_same_endpoint_total 6283
telemt_me_writer_removed_unexpected_minus_restored_total 1951
telemt_user_connections_total{user="hello"} 106610
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 1506254328 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 33825031880 (31.50 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 11812.2 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143396
telemt_connections_bad_total 453
telemt_handshake_timeouts_total 993
telemt_upstream_connect_attempt_total 17729
telemt_upstream_connect_success_total 17617
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 681
telemt_me_reconnect_attempts_total 5345
telemt_me_reconnect_success_total 5323
telemt_me_reader_eof_total 7197
telemt_me_idle_close_by_peer_total 7196
telemt_me_route_drop_no_conn_total 50448
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 700
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 5
telemt_pool_force_close_total 222
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 7259
telemt_me_writer_restored_same_endpoint_total 5321
telemt_me_writer_removed_unexpected_minus_restored_total 1938
telemt_user_connections_total{user="hello"} 133488
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 9181545712 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 45084848324 (41.99 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 35
```