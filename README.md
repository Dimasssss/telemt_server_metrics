# Server Metrics 2026-03-07 02:12:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 29065.4 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328783
telemt_connections_bad_total 3885
telemt_handshake_timeouts_total 9593
telemt_upstream_connect_attempt_total 95386
telemt_upstream_connect_success_total 92557
telemt_upstream_connect_fail_total 2687
telemt_upstream_connect_attempts_per_request{bucket="1"} 95244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2687
telemt_me_keepalive_timeout_total 1964
telemt_me_reconnect_attempts_total 59387
telemt_me_reconnect_success_total 56793
telemt_me_reader_eof_total 59147
telemt_me_idle_close_by_peer_total 59144
telemt_me_route_drop_no_conn_total 123452
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1114
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 809
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 14
telemt_pool_force_close_total 627
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 59260
telemt_me_writer_restored_same_endpoint_total 56629
telemt_me_writer_restored_fallback_total 158
telemt_me_async_recovery_trigger_total 51742
telemt_me_writer_removed_unexpected_minus_restored_total 2473
telemt_user_connections_total{user="hello"} 299256
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 4437213180 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 129294121928 (120.41 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 29065.4 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144136
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 19255
telemt_upstream_connect_attempt_total 196719
telemt_upstream_connect_success_total 196717
telemt_upstream_connect_attempts_per_request{bucket="1"} 196717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 151355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1524
telemt_me_reconnect_attempts_total 154699
telemt_me_reconnect_success_total 154256
telemt_me_reader_eof_total 139250
telemt_me_idle_close_by_peer_total 139245
telemt_me_route_drop_no_conn_total 44385
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 255
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 835
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 22
telemt_pool_force_close_total 1440
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 139291
telemt_me_writer_restored_same_endpoint_total 154254
telemt_me_async_recovery_trigger_total 51736
telemt_user_connections_total{user="hello"} 117651
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 1598707000 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 39853614620 (37.12 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 29065.3 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256663
telemt_connections_bad_total 1445
telemt_handshake_timeouts_total 4350
telemt_upstream_connect_attempt_total 149254
telemt_upstream_connect_success_total 149030
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 149112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 2704
telemt_me_reconnect_attempts_total 112639
telemt_me_reconnect_success_total 112551
telemt_me_reader_eof_total 114009
telemt_me_idle_close_by_peer_total 114004
telemt_me_route_drop_no_conn_total 94321
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1092
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 16
telemt_pool_force_close_total 405
telemt_pool_stale_pick_total 127
telemt_me_writer_removed_unexpected_total 114200
telemt_me_writer_restored_same_endpoint_total 112544
telemt_me_async_recovery_trigger_total 154957
telemt_me_writer_removed_unexpected_minus_restored_total 1656
telemt_user_connections_total{user="hello"} 239838
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 23360332016 (21.76 GB)
telemt_user_octets_to_client{user="hello"} 67595192204 (62.95 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 29065.5 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266179
telemt_connections_bad_total 82647
telemt_handshake_timeouts_total 17221
telemt_upstream_connect_attempt_total 57017
telemt_upstream_connect_success_total 56927
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 56970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1085
telemt_me_reconnect_attempts_total 20238
telemt_me_reconnect_success_total 20206
telemt_me_reader_eof_total 27407
telemt_me_idle_close_by_peer_total 27405
telemt_me_route_drop_no_conn_total 72135
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 246
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 256
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 14
telemt_pool_force_close_total 498
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 27412
telemt_me_writer_restored_same_endpoint_total 20201
telemt_me_writer_removed_unexpected_minus_restored_total 7211
telemt_user_connections_total{user="hello"} 162086
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 1791906020 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 51405697528 (47.88 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 29064.1 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223390
telemt_connections_bad_total 517
telemt_handshake_timeouts_total 2867
telemt_upstream_connect_attempt_total 49264
telemt_upstream_connect_success_total 49078
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 49102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1322
telemt_me_reconnect_attempts_total 14504
telemt_me_reconnect_success_total 14463
telemt_me_reader_eof_total 19945
telemt_me_idle_close_by_peer_total 19943
telemt_me_route_drop_no_conn_total 73626
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 813
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 18
telemt_pool_force_close_total 486
telemt_pool_stale_pick_total 218
telemt_me_writer_removed_unexpected_total 20014
telemt_me_writer_restored_same_endpoint_total 14455
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5555
telemt_user_connections_total{user="hello"} 205181
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 10291876908 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 72538438624 (67.56 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 26
```