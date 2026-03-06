# Server Metrics 2026-03-06 20:38:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 9026.9 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194973
telemt_connections_bad_total 2138
telemt_handshake_timeouts_total 8532
telemt_upstream_connect_attempt_total 13661
telemt_upstream_connect_success_total 13519
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 13569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 366
telemt_me_reconnect_attempts_total 4186
telemt_me_reconnect_success_total 4159
telemt_me_reader_eof_total 5417
telemt_me_idle_close_by_peer_total 5417
telemt_me_route_drop_no_conn_total 76472
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 643
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 2
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 5524
telemt_me_writer_restored_same_endpoint_total 4153
telemt_me_writer_removed_unexpected_minus_restored_total 1371
telemt_user_connections_total{user="hello"} 171393
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 2685162808 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 61382118912 (57.17 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 9026.7 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72505
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 3465
telemt_upstream_connect_attempt_total 17932
telemt_upstream_connect_success_total 17930
telemt_upstream_connect_attempts_per_request{bucket="1"} 17930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 6661
telemt_me_reconnect_success_total 6653
telemt_me_reader_eof_total 9381
telemt_me_idle_close_by_peer_total 9379
telemt_me_route_drop_no_conn_total 26194
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 299
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 3
telemt_pool_force_close_total 166
telemt_pool_stale_pick_total 32
telemt_me_writer_removed_unexpected_total 9381
telemt_me_writer_restored_same_endpoint_total 6651
telemt_me_writer_removed_unexpected_minus_restored_total 2730
telemt_user_connections_total{user="hello"} 64270
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 1113172388 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 21700989468 (20.21 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 9026.7 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140533
telemt_connections_bad_total 357
telemt_handshake_timeouts_total 1577
telemt_upstream_connect_attempt_total 13007
telemt_upstream_connect_success_total 12929
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 12954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 632
telemt_me_reconnect_attempts_total 3354
telemt_me_reconnect_success_total 3340
telemt_me_reader_eof_total 4517
telemt_me_idle_close_by_peer_total 4514
telemt_me_route_drop_no_conn_total 58303
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 670
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 514
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 4582
telemt_me_writer_restored_same_endpoint_total 3333
telemt_me_writer_removed_unexpected_minus_restored_total 1249
telemt_user_connections_total{user="hello"} 129270
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 6786229260 (6.32 GB)
telemt_user_octets_to_client{user="hello"} 36705606260 (34.18 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 9027.1 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149832
telemt_connections_bad_total 47977
telemt_handshake_timeouts_total 11423
telemt_upstream_connect_attempt_total 13401
telemt_upstream_connect_success_total 13366
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 13382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 236
telemt_me_reconnect_attempts_total 4138
telemt_me_reconnect_success_total 4128
telemt_me_reader_eof_total 5243
telemt_me_idle_close_by_peer_total 5243
telemt_me_route_drop_no_conn_total 36755
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 100
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 4
telemt_pool_force_close_total 157
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 5245
telemt_me_writer_restored_same_endpoint_total 4124
telemt_me_writer_removed_unexpected_minus_restored_total 1121
telemt_user_connections_total{user="hello"} 87686
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 1169972128 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 28665864544 (26.70 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 9025.6 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117984
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 743
telemt_upstream_connect_attempt_total 14270
telemt_upstream_connect_success_total 14188
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 14203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 547
telemt_me_reconnect_attempts_total 4386
telemt_me_reconnect_success_total 4368
telemt_me_reader_eof_total 6000
telemt_me_idle_close_by_peer_total 5999
telemt_me_route_drop_no_conn_total 44713
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 544
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 412
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 3
telemt_pool_force_close_total 147
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 6049
telemt_me_writer_restored_same_endpoint_total 4366
telemt_me_writer_removed_unexpected_minus_restored_total 1683
telemt_user_connections_total{user="hello"} 112013
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 8755829480 (8.15 GB)
telemt_user_octets_to_client{user="hello"} 39095724928 (36.41 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 53
```