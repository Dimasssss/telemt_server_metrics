# Server Metrics 2026-03-07 01:36:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 26908.3 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318023
telemt_connections_bad_total 3695
telemt_handshake_timeouts_total 9524
telemt_upstream_connect_attempt_total 84508
telemt_upstream_connect_success_total 82145
telemt_upstream_connect_fail_total 2225
telemt_upstream_connect_attempts_per_request{bucket="1"} 84370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2225
telemt_me_keepalive_timeout_total 1803
telemt_me_reconnect_attempts_total 51372
telemt_me_reconnect_success_total 49218
telemt_me_reader_eof_total 51978
telemt_me_idle_close_by_peer_total 51978
telemt_me_route_drop_no_conn_total 120682
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 218
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1023
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 12
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 52091
telemt_me_writer_restored_same_endpoint_total 49081
telemt_me_writer_restored_fallback_total 131
telemt_me_async_recovery_trigger_total 43163
telemt_me_writer_removed_unexpected_minus_restored_total 2879
telemt_user_connections_total{user="hello"} 289199
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 4371834904 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 125366867316 (116.76 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 26908.4 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137547
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 17340
telemt_upstream_connect_attempt_total 171880
telemt_upstream_connect_success_total 171878
telemt_upstream_connect_attempts_per_request{bucket="1"} 171878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 133095
telemt_me_reconnect_success_total 132750
telemt_me_reader_eof_total 120631
telemt_me_idle_close_by_peer_total 120626
telemt_me_route_drop_no_conn_total 43527
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 231
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 813
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 19
telemt_pool_force_close_total 1236
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 120661
telemt_me_writer_restored_same_endpoint_total 132748
telemt_me_async_recovery_trigger_total 43156
telemt_user_connections_total{user="hello"} 113421
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 1581975960 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 38793916988 (36.13 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 26908.2 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246683
telemt_connections_bad_total 1274
telemt_handshake_timeouts_total 3610
telemt_upstream_connect_attempt_total 125384
telemt_upstream_connect_success_total 125178
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 125252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 2439
telemt_me_reconnect_attempts_total 91685
telemt_me_reconnect_success_total 91606
telemt_me_reader_eof_total 94069
telemt_me_idle_close_by_peer_total 94064
telemt_me_route_drop_no_conn_total 92756
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1069
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 793
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 436
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 14
telemt_pool_force_close_total 372
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 94259
telemt_me_writer_restored_same_endpoint_total 91599
telemt_me_async_recovery_trigger_total 129245
telemt_me_writer_removed_unexpected_minus_restored_total 2660
telemt_user_connections_total{user="hello"} 230881
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 22175776924 (20.65 GB)
telemt_user_octets_to_client{user="hello"} 65497951520 (61.00 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 26908.7 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254909
telemt_connections_bad_total 76511
telemt_handshake_timeouts_total 16962
telemt_upstream_connect_attempt_total 50837
telemt_upstream_connect_success_total 50749
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 50790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 976
telemt_me_reconnect_attempts_total 17295
telemt_me_reconnect_success_total 17265
telemt_me_reader_eof_total 23661
telemt_me_idle_close_by_peer_total 23659
telemt_me_route_drop_no_conn_total 68583
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 225
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 23666
telemt_me_writer_restored_same_endpoint_total 17260
telemt_me_writer_removed_unexpected_minus_restored_total 6406
telemt_user_connections_total{user="hello"} 157316
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 1762091680 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 50792820464 (47.30 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 26906.9 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216327
telemt_connections_bad_total 516
telemt_handshake_timeouts_total 2665
telemt_upstream_connect_attempt_total 45767
telemt_upstream_connect_success_total 45594
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 45617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 299
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 1248
telemt_me_reconnect_attempts_total 13797
telemt_me_reconnect_success_total 13758
telemt_me_reader_eof_total 18973
telemt_me_idle_close_by_peer_total 18971
telemt_me_route_drop_no_conn_total 72171
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 220
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 807
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 597
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 15
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 19042
telemt_me_writer_restored_same_endpoint_total 13750
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5288
telemt_user_connections_total{user="hello"} 198662
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 10240996592 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 70333548876 (65.50 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 20
```