# Server Metrics 2026-03-07 01:51:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 27832.9 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322945
telemt_connections_bad_total 3884
telemt_handshake_timeouts_total 9559
telemt_upstream_connect_attempt_total 89010
telemt_upstream_connect_success_total 86430
telemt_upstream_connect_fail_total 2442
telemt_upstream_connect_attempts_per_request{bucket="1"} 88872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2442
telemt_me_keepalive_timeout_total 1876
telemt_me_reconnect_attempts_total 54633
telemt_me_reconnect_success_total 52271
telemt_me_reader_eof_total 54846
telemt_me_idle_close_by_peer_total 54844
telemt_me_route_drop_no_conn_total 121932
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 226
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1064
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 775
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 480
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 13
telemt_pool_force_close_total 603
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 54959
telemt_me_writer_restored_same_endpoint_total 52121
telemt_me_writer_restored_fallback_total 144
telemt_me_async_recovery_trigger_total 46840
telemt_me_writer_removed_unexpected_minus_restored_total 2694
telemt_user_connections_total{user="hello"} 293709
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 4410818972 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 127645307252 (118.88 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 27832.9 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140119
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 17936
telemt_upstream_connect_attempt_total 182858
telemt_upstream_connect_success_total 182855
telemt_upstream_connect_attempts_per_request{bucket="1"} 182855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1433
telemt_me_reconnect_attempts_total 142682
telemt_me_reconnect_success_total 142306
telemt_me_reader_eof_total 129213
telemt_me_idle_close_by_peer_total 129208
telemt_me_route_drop_no_conn_total 43894
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 240
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 834
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 20
telemt_pool_force_close_total 1316
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 129249
telemt_me_writer_restored_same_endpoint_total 142304
telemt_me_async_recovery_trigger_total 46833
telemt_user_connections_total{user="hello"} 115302
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 1590281428 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 39046115632 (36.36 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 27832.9 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250857
telemt_connections_bad_total 1443
telemt_handshake_timeouts_total 3869
telemt_upstream_connect_attempt_total 135737
telemt_upstream_connect_success_total 135522
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 135601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44280
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 271
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 2551
telemt_me_reconnect_attempts_total 100753
telemt_me_reconnect_success_total 100669
telemt_me_reader_eof_total 102514
telemt_me_idle_close_by_peer_total 102509
telemt_me_route_drop_no_conn_total 93403
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 228
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1077
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 798
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 15
telemt_pool_force_close_total 391
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 102704
telemt_me_writer_restored_same_endpoint_total 100662
telemt_me_async_recovery_trigger_total 140268
telemt_me_writer_removed_unexpected_minus_restored_total 2042
telemt_user_connections_total{user="hello"} 234556
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 22636881980 (21.08 GB)
telemt_user_octets_to_client{user="hello"} 66138339052 (61.60 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 27833.2 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259966
telemt_connections_bad_total 79460
telemt_handshake_timeouts_total 16964
telemt_upstream_connect_attempt_total 54556
telemt_upstream_connect_success_total 54468
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 54509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 1035
telemt_me_reconnect_attempts_total 19472
telemt_me_reconnect_success_total 19440
telemt_me_reader_eof_total 26430
telemt_me_idle_close_by_peer_total 26428
telemt_me_route_drop_no_conn_total 70209
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 249
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 26435
telemt_me_writer_restored_same_endpoint_total 19435
telemt_me_writer_removed_unexpected_minus_restored_total 7000
telemt_user_connections_total{user="hello"} 159373
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 1767708676 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 50986933520 (47.49 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 27831.7 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219137
telemt_connections_bad_total 516
telemt_handshake_timeouts_total 2769
telemt_upstream_connect_attempt_total 47303
telemt_upstream_connect_success_total 47123
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 47147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1279
telemt_me_reconnect_attempts_total 14154
telemt_me_reconnect_success_total 14113
telemt_me_reader_eof_total 19477
telemt_me_idle_close_by_peer_total 19475
telemt_me_route_drop_no_conn_total 72737
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 228
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 807
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 597
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 16
telemt_pool_force_close_total 467
telemt_pool_stale_pick_total 217
telemt_me_writer_removed_unexpected_total 19546
telemt_me_writer_restored_same_endpoint_total 14105
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5437
telemt_user_connections_total{user="hello"} 201239
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 10253435408 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 70743856812 (65.89 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 15
```