# Server Metrics 2026-03-06 21:35:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 12430.1 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233294
telemt_connections_bad_total 2208
telemt_handshake_timeouts_total 8955
telemt_upstream_connect_attempt_total 18862
telemt_upstream_connect_success_total 18705
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 18763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 966
telemt_me_reconnect_attempts_total 5564
telemt_me_reconnect_success_total 5532
telemt_me_reader_eof_total 7164
telemt_me_idle_close_by_peer_total 7164
telemt_me_route_drop_no_conn_total 89143
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 786
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 7271
telemt_me_writer_restored_same_endpoint_total 5526
telemt_me_writer_removed_unexpected_minus_restored_total 1745
telemt_user_connections_total{user="hello"} 208735
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 3095548456 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 76696473952 (71.43 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 12429.9 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90148
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 6121
telemt_upstream_connect_attempt_total 22392
telemt_upstream_connect_success_total 22390
telemt_upstream_connect_attempts_per_request{bucket="1"} 22390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 7372
telemt_me_reconnect_success_total 7361
telemt_me_reader_eof_total 10296
telemt_me_idle_close_by_peer_total 10294
telemt_me_route_drop_no_conn_total 32783
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 537
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 388
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 10296
telemt_me_writer_restored_same_endpoint_total 7359
telemt_me_writer_removed_unexpected_minus_restored_total 2937
telemt_user_connections_total{user="hello"} 78786
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 1259296400 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 26013634168 (24.23 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 12430.0 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173913
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 2459
telemt_upstream_connect_attempt_total 18959
telemt_upstream_connect_success_total 18824
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 18861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 5340
telemt_me_reconnect_success_total 5314
telemt_me_reader_eof_total 7126
telemt_me_idle_close_by_peer_total 7123
telemt_me_route_drop_no_conn_total 68487
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 792
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 6
telemt_pool_force_close_total 223
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 7227
telemt_me_writer_restored_same_endpoint_total 5307
telemt_me_writer_removed_unexpected_minus_restored_total 1920
telemt_user_connections_total{user="hello"} 160975
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 9461571976 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 45873036296 (42.72 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 12430.3 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178477
telemt_connections_bad_total 51145
telemt_handshake_timeouts_total 13848
telemt_upstream_connect_attempt_total 19906
telemt_upstream_connect_success_total 19863
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 396
telemt_me_reconnect_attempts_total 6323
telemt_me_reconnect_success_total 6309
telemt_me_reader_eof_total 8258
telemt_me_idle_close_by_peer_total 8258
telemt_me_route_drop_no_conn_total 44504
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 6
telemt_pool_force_close_total 247
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 8263
telemt_me_writer_restored_same_endpoint_total 6304
telemt_me_writer_removed_unexpected_minus_restored_total 1959
telemt_user_connections_total{user="hello"} 110334
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 1540974308 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 35006283960 (32.60 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 12428.8 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147858
telemt_connections_bad_total 453
telemt_handshake_timeouts_total 1048
telemt_upstream_connect_attempt_total 19354
telemt_upstream_connect_success_total 19235
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 718
telemt_me_reconnect_attempts_total 6044
telemt_me_reconnect_success_total 6018
telemt_me_reader_eof_total 8175
telemt_me_idle_close_by_peer_total 8174
telemt_me_route_drop_no_conn_total 51598
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 707
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 5
telemt_pool_force_close_total 222
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 8237
telemt_me_writer_restored_same_endpoint_total 6016
telemt_me_writer_removed_unexpected_minus_restored_total 2221
telemt_user_connections_total{user="hello"} 136759
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 9200005828 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 46722774232 (43.51 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 35
```