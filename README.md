# Server Metrics 2026-03-04 12:23:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 54785.7 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 934892
telemt_connections_bad_total 12159
telemt_handshake_timeouts_total 14445
telemt_upstream_connect_attempt_total 32884
telemt_upstream_connect_success_total 32741
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 32741
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 367
telemt_me_reconnect_attempts_total 7090
telemt_me_reconnect_success_total 7042
telemt_me_reader_eof_total 7261
telemt_me_idle_close_by_peer_total 7261
telemt_me_route_drop_no_conn_total 341694
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1519
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1005
telemt_desync_frames_bucket_total{bucket="1_2"} 430
telemt_desync_frames_bucket_total{bucket="3_10"} 582
telemt_desync_frames_bucket_total{bucket="gt_10"} 507
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7261
telemt_me_writer_restored_same_endpoint_total 7020
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 737931
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 7876841576 (7.34 GB)
telemt_user_octets_to_client{user="hello"} 227895817252 (212.24 GB)
telemt_user_unique_ips_current{user="hello"} 97
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 54782.1 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368427
telemt_connections_bad_total 3233
telemt_handshake_timeouts_total 27945
telemt_upstream_connect_attempt_total 101784
telemt_upstream_connect_success_total 100216
telemt_upstream_connect_fail_total 746
telemt_upstream_connect_attempts_per_request{bucket="1"} 100210
telemt_upstream_connect_attempts_per_request{bucket="2"} 752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 746
telemt_me_keepalive_timeout_total 1412
telemt_me_reconnect_attempts_total 57030
telemt_me_reconnect_success_total 56941
telemt_me_reader_eof_total 58378
telemt_me_idle_close_by_peer_total 58377
telemt_me_route_drop_no_conn_total 151111
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 230
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 667
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 444
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58458
telemt_me_writer_restored_same_endpoint_total 56916
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 278006
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 3675800508 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 88007399392 (81.96 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 54781.0 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701263
telemt_connections_bad_total 163716
telemt_handshake_timeouts_total 22858
telemt_upstream_connect_attempt_total 80023
telemt_upstream_connect_success_total 79546
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 79545
telemt_upstream_connect_attempts_per_request{bucket="2"} 230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 1041
telemt_me_reconnect_attempts_total 37272
telemt_me_reconnect_success_total 37179
telemt_me_reader_eof_total 39155
telemt_me_idle_close_by_peer_total 39151
telemt_me_route_drop_no_conn_total 261473
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 228
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1227
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 789
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 459
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 39167
telemt_me_writer_restored_same_endpoint_total 37157
telemt_me_writer_removed_unexpected_minus_restored_total 2010
telemt_user_connections_total{user="hello"} 487401
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 11372164500 (10.59 GB)
telemt_user_octets_to_client{user="hello"} 162303893940 (151.16 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 1458.3 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16489
telemt_connections_bad_total 1640
telemt_handshake_timeouts_total 485
telemt_upstream_connect_attempt_total 488
telemt_upstream_connect_success_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 157
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 41
telemt_me_reader_eof_total 21
telemt_me_idle_close_by_peer_total 21
telemt_me_route_drop_no_conn_total 5939
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 21
telemt_me_writer_restored_same_endpoint_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 14131
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 147726816 (140.88 MB)
telemt_user_octets_to_client{user="hello"} 9129816352 (8.50 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 1817.6 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31168
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 611
telemt_upstream_connect_attempt_total 466
telemt_upstream_connect_success_total 461
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 461
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 24
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 9500
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 92
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 26293
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 291318920 (277.82 MB)
telemt_user_octets_to_client{user="hello"} 7954554176 (7.41 GB)
telemt_user_unique_ips_current{user="hello"} 48
```