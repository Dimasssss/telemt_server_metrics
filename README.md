# Server Metrics 2026-03-04 23:56:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 11005.0 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96298
telemt_connections_bad_total 1395
telemt_handshake_timeouts_total 697
telemt_upstream_connect_attempt_total 13834
telemt_upstream_connect_success_total 13676
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 13675
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 512
telemt_me_reconnect_attempts_total 6092
telemt_me_reconnect_success_total 6087
telemt_me_reader_eof_total 6282
telemt_me_idle_close_by_peer_total 6281
telemt_me_route_drop_no_conn_total 25896
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 6341
telemt_me_writer_restored_same_endpoint_total 6067
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 83382
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 2821638576 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 47395617608 (44.14 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 10999.7 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37108
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 282
telemt_upstream_connect_attempt_total 11533
telemt_upstream_connect_success_total 11245
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 11235
telemt_upstream_connect_attempts_per_request{bucket="2"} 56
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1008
telemt_me_reconnect_attempts_total 4392
telemt_me_reconnect_success_total 4366
telemt_me_reader_eof_total 4422
telemt_me_idle_close_by_peer_total 4421
telemt_me_route_drop_no_conn_total 11577
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 4526
telemt_me_writer_restored_same_endpoint_total 4341
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 33927
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 288916944 (275.53 MB)
telemt_user_octets_to_client{user="hello"} 9991845012 (9.31 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 10996.5 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86594
telemt_connections_bad_total 1287
telemt_handshake_timeouts_total 607
telemt_upstream_connect_attempt_total 4538
telemt_upstream_connect_success_total 4486
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4486
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 252
telemt_me_reconnect_success_total 263
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 25102
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 171
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_restored_same_endpoint_total 243
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 79436
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 1014496048 (967.50 MB)
telemt_user_octets_to_client{user="hello"} 26275916808 (24.47 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 43044.7 (11h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544429
telemt_connections_bad_total 77641
telemt_handshake_timeouts_total 14714
telemt_upstream_connect_attempt_total 18581
telemt_upstream_connect_success_total 18579
telemt_upstream_connect_attempts_per_request{bucket="1"} 18579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 236
telemt_me_reconnect_attempts_total 2363
telemt_me_reconnect_success_total 2346
telemt_me_reader_eof_total 2392
telemt_me_idle_close_by_peer_total 2392
telemt_me_route_drop_no_conn_total 183948
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 174
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
telemt_me_writer_removed_unexpected_total 2393
telemt_me_writer_restored_same_endpoint_total 2319
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 423618
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 5800778432 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 157990676000 (147.14 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 43403.8 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532990
telemt_connections_bad_total 3824
telemt_handshake_timeouts_total 5832
telemt_upstream_connect_attempt_total 28000
telemt_upstream_connect_success_total 27844
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 27844
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 426
telemt_me_reconnect_attempts_total 6405
telemt_me_reconnect_success_total 6386
telemt_me_reader_eof_total 6628
telemt_me_idle_close_by_peer_total 6627
telemt_me_route_drop_no_conn_total 234867
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
telemt_me_writer_removed_unexpected_total 6633
telemt_me_writer_restored_same_endpoint_total 6364
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 482630
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 7364008840 (6.86 GB)
telemt_user_octets_to_client{user="hello"} 161692627204 (150.59 GB)
telemt_user_unique_ips_current{user="hello"} 26
```