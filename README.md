# Server Metrics 2026-03-06 21:14:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 11193.8 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222703
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 8791
telemt_upstream_connect_attempt_total 17019
telemt_upstream_connect_success_total 16867
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 16924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 936
telemt_me_reconnect_attempts_total 5145
telemt_me_reconnect_success_total 5114
telemt_me_reader_eof_total 6614
telemt_me_idle_close_by_peer_total 6614
telemt_me_route_drop_no_conn_total 85662
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 763
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 543
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 6721
telemt_me_writer_restored_same_endpoint_total 5108
telemt_me_writer_removed_unexpected_minus_restored_total 1613
telemt_user_connections_total{user="hello"} 198423
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 2960495548 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 71870821272 (66.93 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 11193.6 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84489
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 5133
telemt_upstream_connect_attempt_total 20801
telemt_upstream_connect_success_total 20800
telemt_upstream_connect_attempts_per_request{bucket="1"} 20800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 338
telemt_me_reconnect_attempts_total 7215
telemt_me_reconnect_success_total 7206
telemt_me_reader_eof_total 10112
telemt_me_idle_close_by_peer_total 10110
telemt_me_route_drop_no_conn_total 30060
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 481
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 5
telemt_pool_force_close_total 231
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 10112
telemt_me_writer_restored_same_endpoint_total 7204
telemt_me_writer_removed_unexpected_minus_restored_total 2908
telemt_user_connections_total{user="hello"} 74263
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1213334888 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 25053368392 (23.33 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 11193.7 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162628
telemt_connections_bad_total 388
telemt_handshake_timeouts_total 2023
telemt_upstream_connect_attempt_total 16800
telemt_upstream_connect_success_total 16668
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 16703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 934
telemt_me_reconnect_attempts_total 4682
telemt_me_reconnect_success_total 4657
telemt_me_reader_eof_total 6265
telemt_me_idle_close_by_peer_total 6262
telemt_me_route_drop_no_conn_total 65259
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 747
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_pool_swap_total 5
telemt_pool_force_close_total 190
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 6366
telemt_me_writer_restored_same_endpoint_total 4650
telemt_me_writer_removed_unexpected_minus_restored_total 1716
telemt_user_connections_total{user="hello"} 150591
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 8507985300 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 43094449976 (40.13 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 11194.0 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168910
telemt_connections_bad_total 49911
telemt_handshake_timeouts_total 12980
telemt_upstream_connect_attempt_total 17495
telemt_upstream_connect_success_total 17451
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 17470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 340
telemt_me_reconnect_attempts_total 5440
telemt_me_reconnect_success_total 5427
telemt_me_reader_eof_total 7023
telemt_me_idle_close_by_peer_total 7023
telemt_me_route_drop_no_conn_total 42146
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 143
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 5
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 7028
telemt_me_writer_restored_same_endpoint_total 5422
telemt_me_writer_removed_unexpected_minus_restored_total 1606
telemt_user_connections_total{user="hello"} 102985
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 1360991824 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 32353458992 (30.13 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 11192.6 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138290
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 936
telemt_upstream_connect_attempt_total 16448
telemt_upstream_connect_success_total 16339
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 16355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 657
telemt_me_reconnect_attempts_total 4832
telemt_me_reconnect_success_total 4811
telemt_me_reader_eof_total 6541
telemt_me_idle_close_by_peer_total 6540
telemt_me_route_drop_no_conn_total 49347
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 655
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 493
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 5
telemt_pool_force_close_total 222
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 6601
telemt_me_writer_restored_same_endpoint_total 4809
telemt_me_writer_removed_unexpected_minus_restored_total 1792
telemt_user_connections_total{user="hello"} 129505
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 9146596180 (8.52 GB)
telemt_user_octets_to_client{user="hello"} 43807470220 (40.80 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 52
```