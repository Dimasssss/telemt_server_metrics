# Server Metrics 2026-03-07 01:41:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 27216.1 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319449
telemt_connections_bad_total 3695
telemt_handshake_timeouts_total 9537
telemt_upstream_connect_attempt_total 86133
telemt_upstream_connect_success_total 83698
telemt_upstream_connect_fail_total 2296
telemt_upstream_connect_attempts_per_request{bucket="1"} 85994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 95
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2296
telemt_me_keepalive_timeout_total 1832
telemt_me_reconnect_attempts_total 52553
telemt_me_reconnect_success_total 50333
telemt_me_reader_eof_total 52914
telemt_me_idle_close_by_peer_total 52913
telemt_me_route_drop_no_conn_total 121172
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 226
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1042
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 761
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 13
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 53027
telemt_me_writer_restored_same_endpoint_total 50192
telemt_me_writer_restored_fallback_total 135
telemt_me_async_recovery_trigger_total 44387
telemt_me_writer_removed_unexpected_minus_restored_total 2700
telemt_user_connections_total{user="hello"} 290560
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 4390273668 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 126297471032 (117.62 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 27216.0 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138422
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 17535
telemt_upstream_connect_attempt_total 175356
telemt_upstream_connect_success_total 175354
telemt_upstream_connect_attempts_per_request{bucket="1"} 175354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 1395
telemt_me_reconnect_attempts_total 136125
telemt_me_reconnect_success_total 135769
telemt_me_reader_eof_total 122962
telemt_me_idle_close_by_peer_total 122957
telemt_me_route_drop_no_conn_total 43634
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 239
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 817
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 599
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 409
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 20
telemt_pool_force_close_total 1316
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 122993
telemt_me_writer_restored_same_endpoint_total 135767
telemt_me_async_recovery_trigger_total 44379
telemt_user_connections_total{user="hello"} 114073
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 1585067148 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 38872408268 (36.20 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 27215.9 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247881
telemt_connections_bad_total 1413
telemt_handshake_timeouts_total 3610
telemt_upstream_connect_attempt_total 128820
telemt_upstream_connect_success_total 128611
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 128687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 2471
telemt_me_reconnect_attempts_total 94657
telemt_me_reconnect_success_total 94577
telemt_me_reader_eof_total 96291
telemt_me_idle_close_by_peer_total 96286
telemt_me_route_drop_no_conn_total 92992
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 227
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1076
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 798
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 15
telemt_pool_force_close_total 372
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 96481
telemt_me_writer_restored_same_endpoint_total 94570
telemt_me_async_recovery_trigger_total 132914
telemt_me_writer_removed_unexpected_minus_restored_total 1911
telemt_user_connections_total{user="hello"} 231919
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 22186412076 (20.66 GB)
telemt_user_octets_to_client{user="hello"} 65618958460 (61.11 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 27216.3 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256487
telemt_connections_bad_total 77492
telemt_handshake_timeouts_total 16963
telemt_upstream_connect_attempt_total 52021
telemt_upstream_connect_success_total 51933
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 51974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 983
telemt_me_reconnect_attempts_total 17949
telemt_me_reconnect_success_total 17919
telemt_me_reader_eof_total 24518
telemt_me_idle_close_by_peer_total 24516
telemt_me_route_drop_no_conn_total 69488
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 228
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 24523
telemt_me_writer_restored_same_endpoint_total 17914
telemt_me_writer_removed_unexpected_minus_restored_total 6609
telemt_user_connections_total{user="hello"} 157900
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 1764406636 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 50870081152 (47.38 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 27214.7 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217153
telemt_connections_bad_total 516
telemt_handshake_timeouts_total 2700
telemt_upstream_connect_attempt_total 46395
telemt_upstream_connect_success_total 46218
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 46242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1261
telemt_me_reconnect_attempts_total 14032
telemt_me_reconnect_success_total 13992
telemt_me_reader_eof_total 19328
telemt_me_idle_close_by_peer_total 19326
telemt_me_route_drop_no_conn_total 72348
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 227
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 807
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 597
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 16
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 216
telemt_me_writer_removed_unexpected_total 19397
telemt_me_writer_restored_same_endpoint_total 13984
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5409
telemt_user_connections_total{user="hello"} 199416
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 10248717148 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 70446801916 (65.61 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 15
```