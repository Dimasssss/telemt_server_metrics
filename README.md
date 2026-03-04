# Server Metrics 2026-03-04 09:34:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 44636.6 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604724
telemt_connections_bad_total 10885
telemt_handshake_timeouts_total 7109
telemt_upstream_connect_attempt_total 29058
telemt_upstream_connect_success_total 28931
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 28931
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 6339
telemt_me_reconnect_success_total 6296
telemt_me_reader_eof_total 6483
telemt_me_idle_close_by_peer_total 6483
telemt_me_route_drop_no_conn_total 212493
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1057
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 686
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 6483
telemt_me_writer_restored_same_endpoint_total 6275
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 498633
telemt_user_connections_current{user="hello"} 987
telemt_user_octets_from_client{user="hello"} 5552612604 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 146530637844 (136.47 GB)
telemt_user_unique_ips_current{user="hello"} 97
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 44633.2 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238795
telemt_connections_bad_total 2020
telemt_handshake_timeouts_total 25313
telemt_upstream_connect_attempt_total 92472
telemt_upstream_connect_success_total 91168
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 91162
telemt_upstream_connect_attempts_per_request{bucket="2"} 620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 53592
telemt_me_reconnect_success_total 53511
telemt_me_reader_eof_total 54876
telemt_me_idle_close_by_peer_total 54875
telemt_me_route_drop_no_conn_total 113173
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 192
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 516
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 2
telemt_pool_force_close_total 140
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 54956
telemt_me_writer_restored_same_endpoint_total 53486
telemt_me_writer_removed_unexpected_minus_restored_total 1470
telemt_user_connections_total{user="hello"} 182250
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 2097946264 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 63514683652 (59.15 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 44632.1 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496763
telemt_connections_bad_total 137004
telemt_handshake_timeouts_total 15104
telemt_upstream_connect_attempt_total 64090
telemt_upstream_connect_success_total 63685
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 63684
telemt_upstream_connect_attempts_per_request{bucket="2"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 852
telemt_me_reconnect_attempts_total 28877
telemt_me_reconnect_success_total 28799
telemt_me_reader_eof_total 30378
telemt_me_idle_close_by_peer_total 30375
telemt_me_route_drop_no_conn_total 166550
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 773
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 491
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 4
telemt_pool_force_close_total 200
telemt_me_writer_removed_unexpected_total 30389
telemt_me_writer_restored_same_endpoint_total 28778
telemt_me_writer_removed_unexpected_minus_restored_total 1611
telemt_user_connections_total{user="hello"} 328839
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 3332913100 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 118276096692 (110.15 GB)
telemt_user_unique_ips_current{user="hello"} 65
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 44630.8 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319371
telemt_connections_bad_total 22252
telemt_handshake_timeouts_total 52109
telemt_upstream_connect_attempt_total 32581
telemt_upstream_connect_success_total 32450
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 32450
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 373
telemt_me_reconnect_attempts_total 6585
telemt_me_reconnect_success_total 6564
telemt_me_reader_eof_total 6689
telemt_me_idle_close_by_peer_total 6689
telemt_me_route_drop_no_conn_total 90401
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 13
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6543
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 223964
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 2484371304 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 77957605056 (72.60 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 44629.6 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448662
telemt_connections_bad_total 6487
telemt_handshake_timeouts_total 132141
telemt_upstream_connect_attempt_total 67948
telemt_upstream_connect_success_total 67523
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 67523
telemt_upstream_connect_attempts_per_request{bucket="2"} 200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26793
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 894
telemt_me_reconnect_attempts_total 33512
telemt_me_reconnect_success_total 33483
telemt_me_reader_eof_total 35161
telemt_me_idle_close_by_peer_total 35160
telemt_me_route_drop_no_conn_total 136438
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 385
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 5
telemt_pool_force_close_total 233
telemt_pool_stale_pick_total 2862
telemt_me_writer_removed_unexpected_total 35173
telemt_me_writer_restored_same_endpoint_total 33458
telemt_me_writer_removed_unexpected_minus_restored_total 1715
telemt_user_connections_total{user="hello"} 290668
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 4029196260 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 72320315272 (67.35 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 38
```