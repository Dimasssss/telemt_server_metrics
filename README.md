# Server Metrics 2026-03-05 00:01:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 11312.0 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97918
telemt_connections_bad_total 1395
telemt_handshake_timeouts_total 718
telemt_upstream_connect_attempt_total 14494
telemt_upstream_connect_success_total 14336
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 14335
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 520
telemt_me_reconnect_attempts_total 6468
telemt_me_reconnect_success_total 6462
telemt_me_reader_eof_total 6682
telemt_me_idle_close_by_peer_total 6681
telemt_me_route_drop_no_conn_total 26302
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 6741
telemt_me_writer_restored_same_endpoint_total 6442
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 84929
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 2840156044 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 47899991700 (44.61 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 11306.9 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37877
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 529
telemt_upstream_connect_attempt_total 11849
telemt_upstream_connect_success_total 11561
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 11551
telemt_upstream_connect_attempts_per_request{bucket="2"} 56
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1010
telemt_me_reconnect_attempts_total 4507
telemt_me_reconnect_success_total 4481
telemt_me_reader_eof_total 4540
telemt_me_idle_close_by_peer_total 4539
telemt_me_route_drop_no_conn_total 11773
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 4644
telemt_me_writer_restored_same_endpoint_total 4456
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 34440
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 299613496 (285.73 MB)
telemt_user_octets_to_client{user="hello"} 10052113064 (9.36 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 11303.6 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88173
telemt_connections_bad_total 1289
telemt_handshake_timeouts_total 611
telemt_upstream_connect_attempt_total 4674
telemt_upstream_connect_success_total 4622
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4622
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 252
telemt_me_reconnect_success_total 263
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 25597
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 172
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_restored_same_endpoint_total 243
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 80963
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1020224112 (972.96 MB)
telemt_user_octets_to_client{user="hello"} 26895207748 (25.05 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 43351.5 (12h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545773
telemt_connections_bad_total 78154
telemt_handshake_timeouts_total 14718
telemt_upstream_connect_attempt_total 18909
telemt_upstream_connect_success_total 18907
telemt_upstream_connect_attempts_per_request{bucket="1"} 18907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 2447
telemt_me_reconnect_success_total 2430
telemt_me_reader_eof_total 2477
telemt_me_idle_close_by_peer_total 2477
telemt_me_route_drop_no_conn_total 184792
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 720
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 17
telemt_pool_force_close_total 484
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2478
telemt_me_writer_restored_same_endpoint_total 2403
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 424437
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 5808472312 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 158345004100 (147.47 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 43710.8 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533742
telemt_connections_bad_total 3839
telemt_handshake_timeouts_total 5839
telemt_upstream_connect_attempt_total 28290
telemt_upstream_connect_success_total 28135
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 28135
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 6458
telemt_me_reconnect_success_total 6438
telemt_me_reader_eof_total 6680
telemt_me_idle_close_by_peer_total 6679
telemt_me_route_drop_no_conn_total 235078
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 9
telemt_pool_force_close_total 409
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6685
telemt_me_writer_restored_same_endpoint_total 6416
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 483337
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 7368360160 (6.86 GB)
telemt_user_octets_to_client{user="hello"} 162061751164 (150.93 GB)
telemt_user_unique_ips_current{user="hello"} 30
```