# Server Metrics 2026-03-06 20:43:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 9335.9 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199006
telemt_connections_bad_total 2198
telemt_handshake_timeouts_total 8673
telemt_upstream_connect_attempt_total 14282
telemt_upstream_connect_success_total 14138
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 14190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 887
telemt_me_reconnect_attempts_total 4328
telemt_me_reconnect_success_total 4301
telemt_me_reader_eof_total 5578
telemt_me_idle_close_by_peer_total 5578
telemt_me_route_drop_no_conn_total 77971
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 677
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 479
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 2
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 5685
telemt_me_writer_restored_same_endpoint_total 4295
telemt_me_writer_removed_unexpected_minus_restored_total 1390
telemt_user_connections_total{user="hello"} 175194
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 2726392452 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 62886061032 (58.57 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 9335.9 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74464
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 3630
telemt_upstream_connect_attempt_total 18186
telemt_upstream_connect_success_total 18185
telemt_upstream_connect_attempts_per_request{bucket="1"} 18185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 305
telemt_me_reconnect_attempts_total 6701
telemt_me_reconnect_success_total 6693
telemt_me_reader_eof_total 9425
telemt_me_idle_close_by_peer_total 9423
telemt_me_route_drop_no_conn_total 26717
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 338
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 35
telemt_me_writer_removed_unexpected_total 9425
telemt_me_writer_restored_same_endpoint_total 6691
telemt_me_writer_removed_unexpected_minus_restored_total 2734
telemt_user_connections_total{user="hello"} 65969
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 1133496104 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 22479497396 (20.94 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 9335.6 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143754
telemt_connections_bad_total 358
telemt_handshake_timeouts_total 1756
telemt_upstream_connect_attempt_total 13733
telemt_upstream_connect_success_total 13632
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 13660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 663
telemt_me_reconnect_attempts_total 3610
telemt_me_reconnect_success_total 3591
telemt_me_reader_eof_total 4928
telemt_me_idle_close_by_peer_total 4925
telemt_me_route_drop_no_conn_total 59454
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 677
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 518
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 5005
telemt_me_writer_restored_same_endpoint_total 3584
telemt_me_writer_removed_unexpected_minus_restored_total 1421
telemt_user_connections_total{user="hello"} 132326
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 7028283084 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 37694221048 (35.11 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 9336.3 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152981
telemt_connections_bad_total 48253
telemt_handshake_timeouts_total 11685
telemt_upstream_connect_attempt_total 13799
telemt_upstream_connect_success_total 13764
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 13781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 4245
telemt_me_reconnect_success_total 4235
telemt_me_reader_eof_total 5394
telemt_me_idle_close_by_peer_total 5394
telemt_me_route_drop_no_conn_total 37459
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 114
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 5
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 5396
telemt_me_writer_restored_same_endpoint_total 4230
telemt_me_writer_removed_unexpected_minus_restored_total 1166
telemt_user_connections_total{user="hello"} 90237
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 1199213804 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 29351032432 (27.34 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 9334.6 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120996
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 761
telemt_upstream_connect_attempt_total 14626
telemt_upstream_connect_success_total 14533
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 14549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 608
telemt_me_reconnect_attempts_total 4467
telemt_me_reconnect_success_total 4447
telemt_me_reader_eof_total 6123
telemt_me_idle_close_by_peer_total 6122
telemt_me_route_drop_no_conn_total 45555
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 577
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 437
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 115
telemt_me_writer_removed_unexpected_total 6181
telemt_me_writer_restored_same_endpoint_total 4445
telemt_me_writer_removed_unexpected_minus_restored_total 1736
telemt_user_connections_total{user="hello"} 114940
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 8777161792 (8.17 GB)
telemt_user_octets_to_client{user="hello"} 39606332120 (36.89 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 64
```