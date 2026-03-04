# Server Metrics 2026-03-04 23:36:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 9776.4 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90856
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 612
telemt_upstream_connect_attempt_total 11118
telemt_upstream_connect_success_total 10980
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10979
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 488
telemt_me_reconnect_attempts_total 4534
telemt_me_reconnect_success_total 4531
telemt_me_reader_eof_total 4660
telemt_me_idle_close_by_peer_total 4659
telemt_me_route_drop_no_conn_total 24456
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 4719
telemt_me_writer_restored_same_endpoint_total 4511
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 78109
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 2793658364 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 46516028128 (43.32 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 9771.3 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34520
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 267
telemt_upstream_connect_attempt_total 10604
telemt_upstream_connect_success_total 10386
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10380
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 705
telemt_me_reconnect_attempts_total 4156
telemt_me_reconnect_success_total 4139
telemt_me_reader_eof_total 4209
telemt_me_idle_close_by_peer_total 4208
telemt_me_route_drop_no_conn_total 10639
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 129
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_removed_unexpected_total 4286
telemt_me_writer_restored_same_endpoint_total 4120
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 31419
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 278456764 (265.56 MB)
telemt_user_octets_to_client{user="hello"} 9025128800 (8.41 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 9767.9 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80213
telemt_connections_bad_total 1264
telemt_handshake_timeouts_total 603
telemt_upstream_connect_attempt_total 4185
telemt_upstream_connect_success_total 4143
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4143
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 248
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 249
telemt_me_idle_close_by_peer_total 249
telemt_me_route_drop_no_conn_total 23782
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 3
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 249
telemt_me_writer_restored_same_endpoint_total 240
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 74016
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 982502104 (936.99 MB)
telemt_user_octets_to_client{user="hello"} 25251912052 (23.52 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 41816.3 (11h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538739
telemt_connections_bad_total 75578
telemt_handshake_timeouts_total 14705
telemt_upstream_connect_attempt_total 17700
telemt_upstream_connect_success_total 17700
telemt_upstream_connect_attempts_per_request{bucket="1"} 17700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 230
telemt_me_reconnect_attempts_total 2210
telemt_me_reconnect_success_total 2194
telemt_me_reader_eof_total 2236
telemt_me_idle_close_by_peer_total 2236
telemt_me_route_drop_no_conn_total 182621
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 170
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
telemt_me_writer_removed_unexpected_total 2237
telemt_me_writer_restored_same_endpoint_total 2167
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 420047
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 5774230540 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 157106095664 (146.32 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 42175.5 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529838
telemt_connections_bad_total 3823
telemt_handshake_timeouts_total 5828
telemt_upstream_connect_attempt_total 27309
telemt_upstream_connect_success_total 27163
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 27163
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 420
telemt_me_reconnect_attempts_total 6391
telemt_me_reconnect_success_total 6372
telemt_me_reader_eof_total 6613
telemt_me_idle_close_by_peer_total 6612
telemt_me_route_drop_no_conn_total 233483
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 169
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
telemt_me_writer_removed_unexpected_total 6618
telemt_me_writer_restored_same_endpoint_total 6350
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 479519
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 7347040160 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 159883824488 (148.90 GB)
telemt_user_unique_ips_current{user="hello"} 26
```