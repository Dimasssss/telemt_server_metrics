# Server Metrics 2026-03-04 23:21:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 8856.0 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86625
telemt_connections_bad_total 1383
telemt_handshake_timeouts_total 580
telemt_upstream_connect_attempt_total 9561
telemt_upstream_connect_success_total 9425
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9424
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 471
telemt_me_reconnect_attempts_total 3677
telemt_me_reconnect_success_total 3675
telemt_me_reader_eof_total 3781
telemt_me_idle_close_by_peer_total 3780
telemt_me_route_drop_no_conn_total 22796
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 3840
telemt_me_writer_restored_same_endpoint_total 3655
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 73999
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 2748091336 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 43287639372 (40.31 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 8846.3 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31385
telemt_connections_bad_total 711
telemt_handshake_timeouts_total 223
telemt_upstream_connect_attempt_total 10088
telemt_upstream_connect_success_total 9950
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 9947
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 525
telemt_me_reconnect_attempts_total 4084
telemt_me_reconnect_success_total 4077
telemt_me_reader_eof_total 4159
telemt_me_idle_close_by_peer_total 4158
telemt_me_route_drop_no_conn_total 9892
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 121
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_removed_unexpected_total 4213
telemt_me_writer_restored_same_endpoint_total 4058
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 29597
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 256566388 (244.68 MB)
telemt_user_octets_to_client{user="hello"} 8668265632 (8.07 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 8843.0 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74741
telemt_connections_bad_total 1052
telemt_handshake_timeouts_total 540
telemt_upstream_connect_attempt_total 3603
telemt_upstream_connect_success_total 3565
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 3565
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 238
telemt_me_reconnect_success_total 250
telemt_me_reader_eof_total 239
telemt_me_idle_close_by_peer_total 239
telemt_me_route_drop_no_conn_total 22504
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 37
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
telemt_user_connections_total{user="hello"} 69002
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 966637116 (921.86 MB)
telemt_user_octets_to_client{user="hello"} 24717791524 (23.02 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 40891.3 (11h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533981
telemt_connections_bad_total 74007
telemt_handshake_timeouts_total 14702
telemt_upstream_connect_attempt_total 17340
telemt_upstream_connect_success_total 17340
telemt_upstream_connect_attempts_per_request{bucket="1"} 17340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 2188
telemt_me_reconnect_success_total 2172
telemt_me_reader_eof_total 2214
telemt_me_idle_close_by_peer_total 2214
telemt_me_route_drop_no_conn_total 181581
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
telemt_me_writer_removed_unexpected_total 2215
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 416912
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 5752311912 (5.36 GB)
telemt_user_octets_to_client{user="hello"} 156294870416 (145.56 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 41250.4 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527103
telemt_connections_bad_total 3776
telemt_handshake_timeouts_total 5818
telemt_upstream_connect_attempt_total 26647
telemt_upstream_connect_success_total 26501
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 26501
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 402
telemt_me_reconnect_attempts_total 6184
telemt_me_reconnect_success_total 6165
telemt_me_reader_eof_total 6400
telemt_me_idle_close_by_peer_total 6399
telemt_me_route_drop_no_conn_total 232713
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6405
telemt_me_writer_restored_same_endpoint_total 6144
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 476857
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 7322036784 (6.82 GB)
telemt_user_octets_to_client{user="hello"} 158244928324 (147.38 GB)
telemt_user_unique_ips_current{user="hello"} 24
```