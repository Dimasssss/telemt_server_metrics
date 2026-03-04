# Server Metrics 2026-03-04 23:26:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 9162.7 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88111
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 591
telemt_upstream_connect_attempt_total 10052
telemt_upstream_connect_success_total 9913
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9912
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3440
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 474
telemt_me_reconnect_attempts_total 3930
telemt_me_reconnect_success_total 3927
telemt_me_reader_eof_total 4039
telemt_me_idle_close_by_peer_total 4038
telemt_me_route_drop_no_conn_total 23542
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 4098
telemt_me_writer_restored_same_endpoint_total 3907
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 75444
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 2765718768 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 45346132616 (42.23 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 9157.5 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32217
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 224
telemt_upstream_connect_attempt_total 10193
telemt_upstream_connect_success_total 10034
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 10031
telemt_upstream_connect_attempts_per_request{bucket="2"} 42
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 556
telemt_me_reconnect_attempts_total 4087
telemt_me_reconnect_success_total 4078
telemt_me_reader_eof_total 4159
telemt_me_idle_close_by_peer_total 4158
telemt_me_route_drop_no_conn_total 10085
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 129
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_removed_unexpected_total 4214
telemt_me_writer_restored_same_endpoint_total 4059
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 30349
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 263950616 (251.72 MB)
telemt_user_octets_to_client{user="hello"} 8772514204 (8.17 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 9154.2 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76539
telemt_connections_bad_total 1092
telemt_handshake_timeouts_total 572
telemt_upstream_connect_attempt_total 3765
telemt_upstream_connect_success_total 3723
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3723
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 238
telemt_me_reconnect_success_total 250
telemt_me_reader_eof_total 239
telemt_me_idle_close_by_peer_total 239
telemt_me_route_drop_no_conn_total 22879
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 3
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 239
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 70686
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 971167660 (926.18 MB)
telemt_user_octets_to_client{user="hello"} 24871870252 (23.16 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 41202.4 (11h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535636
telemt_connections_bad_total 74543
telemt_handshake_timeouts_total 14705
telemt_upstream_connect_attempt_total 17426
telemt_upstream_connect_success_total 17426
telemt_upstream_connect_attempts_per_request{bucket="1"} 17426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 228
telemt_me_reconnect_attempts_total 2189
telemt_me_reconnect_success_total 2174
telemt_me_reader_eof_total 2216
telemt_me_idle_close_by_peer_total 2216
telemt_me_route_drop_no_conn_total 181802
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 166
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
telemt_me_writer_removed_unexpected_total 2217
telemt_me_writer_restored_same_endpoint_total 2147
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 418008
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 5763098432 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 156432237808 (145.69 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 41561.8 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527945
telemt_connections_bad_total 3822
telemt_handshake_timeouts_total 5825
telemt_upstream_connect_attempt_total 27126
telemt_upstream_connect_success_total 26980
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 26980
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 6388
telemt_me_reconnect_success_total 6369
telemt_me_reader_eof_total 6611
telemt_me_idle_close_by_peer_total 6610
telemt_me_route_drop_no_conn_total 232999
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 168
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 9
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6616
telemt_me_writer_restored_same_endpoint_total 6348
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 477640
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 7328311840 (6.83 GB)
telemt_user_octets_to_client{user="hello"} 158862853860 (147.95 GB)
telemt_user_unique_ips_current{user="hello"} 26
```