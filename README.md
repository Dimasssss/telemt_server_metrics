# Server Metrics 2026-03-06 22:11:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 14588.5 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248339
telemt_connections_bad_total 2218
telemt_handshake_timeouts_total 9054
telemt_upstream_connect_attempt_total 22938
telemt_upstream_connect_success_total 22762
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 22831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1041
telemt_me_reconnect_attempts_total 6920
telemt_me_reconnect_success_total 6885
telemt_me_reader_eof_total 9015
telemt_me_idle_close_by_peer_total 9015
telemt_me_route_drop_no_conn_total 95088
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 813
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 164
telemt_me_writer_removed_unexpected_total 9123
telemt_me_writer_restored_same_endpoint_total 6879
telemt_me_writer_removed_unexpected_minus_restored_total 2244
telemt_user_connections_total{user="hello"} 223417
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 3348217560 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 86446992220 (80.51 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 14588.4 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98932
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 7834
telemt_upstream_connect_attempt_total 28274
telemt_upstream_connect_success_total 28273
telemt_upstream_connect_attempts_per_request{bucket="1"} 28273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 468
telemt_me_reconnect_attempts_total 9643
telemt_me_reconnect_success_total 9631
telemt_me_reader_eof_total 13550
telemt_me_idle_close_by_peer_total 13547
telemt_me_route_drop_no_conn_total 36004
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 128
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 638
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 13550
telemt_me_writer_restored_same_endpoint_total 9629
telemt_me_writer_removed_unexpected_minus_restored_total 3921
telemt_user_connections_total{user="hello"} 85619
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 1324394212 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 27192585868 (25.33 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 14588.2 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190904
telemt_connections_bad_total 613
telemt_handshake_timeouts_total 3078
telemt_upstream_connect_attempt_total 22470
telemt_upstream_connect_success_total 22323
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 22365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1028
telemt_me_reconnect_attempts_total 6370
telemt_me_reconnect_success_total 6342
telemt_me_reader_eof_total 8430
telemt_me_idle_close_by_peer_total 8427
telemt_me_route_drop_no_conn_total 72676
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 861
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 650
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 8531
telemt_me_writer_restored_same_endpoint_total 6335
telemt_me_writer_removed_unexpected_minus_restored_total 2196
telemt_user_connections_total{user="hello"} 176854
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 11683226928 (10.88 GB)
telemt_user_octets_to_client{user="hello"} 52953770252 (49.32 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 14588.9 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190925
telemt_connections_bad_total 53092
telemt_handshake_timeouts_total 14362
telemt_upstream_connect_attempt_total 23959
telemt_upstream_connect_success_total 23887
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 23911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 456
telemt_me_reconnect_attempts_total 7557
telemt_me_reconnect_success_total 7540
telemt_me_reader_eof_total 10059
telemt_me_idle_close_by_peer_total 10058
telemt_me_route_drop_no_conn_total 48745
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 157
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 7
telemt_pool_force_close_total 271
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 10064
telemt_me_writer_restored_same_endpoint_total 7535
telemt_me_writer_removed_unexpected_minus_restored_total 2529
telemt_user_connections_total{user="hello"} 120169
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 1591077612 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 36740551496 (34.22 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 14587.3 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163121
telemt_connections_bad_total 456
telemt_handshake_timeouts_total 1172
telemt_upstream_connect_attempt_total 22531
telemt_upstream_connect_success_total 22403
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 22422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 787
telemt_me_reconnect_attempts_total 6938
telemt_me_reconnect_success_total 6910
telemt_me_reader_eof_total 9366
telemt_me_idle_close_by_peer_total 9365
telemt_me_route_drop_no_conn_total 57852
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 729
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 7
telemt_pool_force_close_total 261
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 9429
telemt_me_writer_restored_same_endpoint_total 6908
telemt_me_writer_removed_unexpected_minus_restored_total 2521
telemt_user_connections_total{user="hello"} 149661
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 9432614800 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 50872038320 (47.38 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 24
```