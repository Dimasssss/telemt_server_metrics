# Server Metrics 2026-03-07 01:46:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 27525.7 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321279
telemt_connections_bad_total 3702
telemt_handshake_timeouts_total 9545
telemt_upstream_connect_attempt_total 87410
telemt_upstream_connect_success_total 84897
telemt_upstream_connect_fail_total 2376
telemt_upstream_connect_attempts_per_request{bucket="1"} 87273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 95
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2376
telemt_me_keepalive_timeout_total 1850
telemt_me_reconnect_attempts_total 53498
telemt_me_reconnect_success_total 51199
telemt_me_reader_eof_total 53732
telemt_me_idle_close_by_peer_total 53730
telemt_me_route_drop_no_conn_total 121418
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 226
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1055
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 769
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 295
telemt_pool_swap_total 13
telemt_pool_force_close_total 603
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 53845
telemt_me_writer_restored_same_endpoint_total 51053
telemt_me_writer_restored_fallback_total 140
telemt_me_async_recovery_trigger_total 45618
telemt_me_writer_removed_unexpected_minus_restored_total 2652
telemt_user_connections_total{user="hello"} 292287
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 4398221952 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 127144448752 (118.41 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 27525.5 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139262
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 17739
telemt_upstream_connect_attempt_total 179054
telemt_upstream_connect_success_total 179052
telemt_upstream_connect_attempts_per_request{bucket="1"} 179052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1412
telemt_me_reconnect_attempts_total 139358
telemt_me_reconnect_success_total 138993
telemt_me_reader_eof_total 125909
telemt_me_idle_close_by_peer_total 125904
telemt_me_route_drop_no_conn_total 43724
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 239
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 833
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 413
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 20
telemt_pool_force_close_total 1316
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 125941
telemt_me_writer_restored_same_endpoint_total 138991
telemt_me_async_recovery_trigger_total 45610
telemt_user_connections_total{user="hello"} 114674
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 1587361128 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 38962375960 (36.29 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 27525.5 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249284
telemt_connections_bad_total 1442
telemt_handshake_timeouts_total 3669
telemt_upstream_connect_attempt_total 132177
telemt_upstream_connect_success_total 131964
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 132042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 2510
telemt_me_reconnect_attempts_total 97635
telemt_me_reconnect_success_total 97553
telemt_me_reader_eof_total 99309
telemt_me_idle_close_by_peer_total 99304
telemt_me_route_drop_no_conn_total 93194
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 228
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1076
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 798
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 15
telemt_pool_force_close_total 391
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 99499
telemt_me_writer_restored_same_endpoint_total 97546
telemt_me_async_recovery_trigger_total 136604
telemt_me_writer_removed_unexpected_minus_restored_total 1953
telemt_user_connections_total{user="hello"} 233201
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 22380361688 (20.84 GB)
telemt_user_octets_to_client{user="hello"} 65843411792 (61.32 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 27525.7 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258192
telemt_connections_bad_total 78478
telemt_handshake_timeouts_total 16964
telemt_upstream_connect_attempt_total 53270
telemt_upstream_connect_success_total 53182
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 53223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 1008
telemt_me_reconnect_attempts_total 18692
telemt_me_reconnect_success_total 18661
telemt_me_reader_eof_total 25451
telemt_me_idle_close_by_peer_total 25449
telemt_me_route_drop_no_conn_total 69836
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 240
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 25456
telemt_me_writer_restored_same_endpoint_total 18656
telemt_me_writer_removed_unexpected_minus_restored_total 6800
telemt_user_connections_total{user="hello"} 158596
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 1766154592 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 50929591812 (47.43 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 27524.1 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218156
telemt_connections_bad_total 516
telemt_handshake_timeouts_total 2731
telemt_upstream_connect_attempt_total 46740
telemt_upstream_connect_success_total 46560
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 46584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 310
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1270
telemt_me_reconnect_attempts_total 14034
telemt_me_reconnect_success_total 13994
telemt_me_reader_eof_total 19330
telemt_me_idle_close_by_peer_total 19328
telemt_me_route_drop_no_conn_total 72502
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
telemt_me_writer_removed_unexpected_total 19399
telemt_me_writer_restored_same_endpoint_total 13986
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5409
telemt_user_connections_total{user="hello"} 200349
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 10250844364 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 70617540540 (65.77 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```