# Server Metrics 2026-03-06 22:06:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 14281.2 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246385
telemt_connections_bad_total 2218
telemt_handshake_timeouts_total 9038
telemt_upstream_connect_attempt_total 22481
telemt_upstream_connect_success_total 22315
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 22375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1033
telemt_me_reconnect_attempts_total 6817
telemt_me_reconnect_success_total 6783
telemt_me_reader_eof_total 8887
telemt_me_idle_close_by_peer_total 8887
telemt_me_route_drop_no_conn_total 94541
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 813
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 162
telemt_me_writer_removed_unexpected_total 8994
telemt_me_writer_restored_same_endpoint_total 6777
telemt_me_writer_removed_unexpected_minus_restored_total 2217
telemt_user_connections_total{user="hello"} 221520
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 3326269952 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 85067517924 (79.23 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 14281.1 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97691
telemt_connections_bad_total 93
telemt_handshake_timeouts_total 7586
telemt_upstream_connect_attempt_total 27387
telemt_upstream_connect_success_total 27386
telemt_upstream_connect_attempts_per_request{bucket="1"} 27386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 9303
telemt_me_reconnect_success_total 9290
telemt_me_reader_eof_total 13074
telemt_me_idle_close_by_peer_total 13072
telemt_me_route_drop_no_conn_total 35556
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 624
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 286
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 13074
telemt_me_writer_restored_same_endpoint_total 9288
telemt_me_writer_removed_unexpected_minus_restored_total 3786
telemt_user_connections_total{user="hello"} 84649
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 1320396676 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 26971408972 (25.12 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 14281.0 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188611
telemt_connections_bad_total 612
telemt_handshake_timeouts_total 3045
telemt_upstream_connect_attempt_total 21893
telemt_upstream_connect_success_total 21749
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 21788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1021
telemt_me_reconnect_attempts_total 6192
telemt_me_reconnect_success_total 6164
telemt_me_reader_eof_total 8219
telemt_me_idle_close_by_peer_total 8216
telemt_me_route_drop_no_conn_total 72148
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 859
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 649
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 8320
telemt_me_writer_restored_same_endpoint_total 6157
telemt_me_writer_removed_unexpected_minus_restored_total 2163
telemt_user_connections_total{user="hello"} 174616
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 11423397764 (10.64 GB)
telemt_user_octets_to_client{user="hello"} 52558960352 (48.95 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 14281.4 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189512
telemt_connections_bad_total 52819
telemt_handshake_timeouts_total 14362
telemt_upstream_connect_attempt_total 23097
telemt_upstream_connect_success_total 23028
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 23050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 442
telemt_me_reconnect_attempts_total 7193
telemt_me_reconnect_success_total 7177
telemt_me_reader_eof_total 9525
telemt_me_idle_close_by_peer_total 9524
telemt_me_route_drop_no_conn_total 47961
telemt_me_single_endpoint_shadow_rotate_total 118
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
telemt_me_writer_removed_unexpected_total 9530
telemt_me_writer_restored_same_endpoint_total 7172
telemt_me_writer_removed_unexpected_minus_restored_total 2358
telemt_user_connections_total{user="hello"} 119065
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 1587803308 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 36636983904 (34.12 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 14280.2 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161270
telemt_connections_bad_total 456
telemt_handshake_timeouts_total 1145
telemt_upstream_connect_attempt_total 21871
telemt_upstream_connect_success_total 21747
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 21766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 773
telemt_me_reconnect_attempts_total 6706
telemt_me_reconnect_success_total 6678
telemt_me_reader_eof_total 9039
telemt_me_idle_close_by_peer_total 9038
telemt_me_route_drop_no_conn_total 57364
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 729
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 6
telemt_pool_force_close_total 261
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 9101
telemt_me_writer_restored_same_endpoint_total 6676
telemt_me_writer_removed_unexpected_minus_restored_total 2425
telemt_user_connections_total{user="hello"} 148116
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 9402340232 (8.76 GB)
telemt_user_octets_to_client{user="hello"} 50234390116 (46.78 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 26
```