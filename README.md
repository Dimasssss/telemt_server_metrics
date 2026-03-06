# Server Metrics 2026-03-06 23:17:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 18590.5 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274151
telemt_connections_bad_total 2749
telemt_handshake_timeouts_total 9261
telemt_upstream_connect_attempt_total 39485
telemt_upstream_connect_success_total 38735
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 39349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 1295
telemt_me_reconnect_attempts_total 17333
telemt_me_reconnect_success_total 16760
telemt_me_reader_eof_total 19415
telemt_me_idle_close_by_peer_total 19415
telemt_me_route_drop_no_conn_total 108497
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 863
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 614
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 346
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 6
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 19525
telemt_me_writer_restored_same_endpoint_total 16721
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 10081
telemt_me_writer_removed_unexpected_minus_restored_total 2771
telemt_user_connections_total{user="hello"} 247792
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 3946231980 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 112635633196 (104.90 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 18590.4 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113577
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 11137
telemt_upstream_connect_attempt_total 59996
telemt_upstream_connect_success_total 59993
telemt_upstream_connect_attempts_per_request{bucket="1"} 59993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 783
telemt_me_reconnect_attempts_total 35060
telemt_me_reconnect_success_total 34920
telemt_me_reader_eof_total 35330
telemt_me_idle_close_by_peer_total 35326
telemt_me_route_drop_no_conn_total 39219
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 701
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 514
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 10
telemt_pool_force_close_total 519
telemt_pool_stale_pick_total 54
telemt_me_writer_removed_unexpected_total 35352
telemt_me_writer_restored_same_endpoint_total 34918
telemt_me_async_recovery_trigger_total 10073
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 96554
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1467388332 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 35395320620 (32.96 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 18590.3 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211799
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 3508
telemt_upstream_connect_attempt_total 46126
telemt_upstream_connect_success_total 45967
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 46017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1445
telemt_me_reconnect_attempts_total 24642
telemt_me_reconnect_success_total 24596
telemt_me_reader_eof_total 26120
telemt_me_idle_close_by_peer_total 26117
telemt_me_route_drop_no_conn_total 81023
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 965
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 723
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 10
telemt_pool_force_close_total 298
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 26273
telemt_me_writer_restored_same_endpoint_total 24589
telemt_me_async_recovery_trigger_total 30078
telemt_me_writer_removed_unexpected_minus_restored_total 1684
telemt_user_connections_total{user="hello"} 196804
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 14866084120 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 58633748936 (54.61 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 18590.7 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211206
telemt_connections_bad_total 56672
telemt_handshake_timeouts_total 16166
telemt_upstream_connect_attempt_total 31471
telemt_upstream_connect_success_total 31392
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 629
telemt_me_reconnect_attempts_total 9947
telemt_me_reconnect_success_total 9927
telemt_me_reader_eof_total 13360
telemt_me_idle_close_by_peer_total 13359
telemt_me_route_drop_no_conn_total 56086
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 177
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 10
telemt_pool_force_close_total 367
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 13366
telemt_me_writer_restored_same_endpoint_total 9922
telemt_me_writer_removed_unexpected_minus_restored_total 3444
telemt_user_connections_total{user="hello"} 134793
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 1648869460 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 42435225272 (39.52 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 18589.1 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183834
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 1683
telemt_upstream_connect_attempt_total 28985
telemt_upstream_connect_success_total 28847
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 28866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 922
telemt_me_reconnect_attempts_total 8524
telemt_me_reconnect_success_total 8494
telemt_me_reader_eof_total 11499
telemt_me_idle_close_by_peer_total 11498
telemt_me_route_drop_no_conn_total 62731
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 751
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 10
telemt_pool_force_close_total 351
telemt_pool_stale_pick_total 211
telemt_me_writer_removed_unexpected_total 11566
telemt_me_writer_restored_same_endpoint_total 8490
telemt_me_writer_removed_unexpected_minus_restored_total 3076
telemt_user_connections_total{user="hello"} 168284
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 10043725740 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 57366719840 (53.43 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```