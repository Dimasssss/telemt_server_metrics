# Server Metrics 2026-03-04 21:07:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 860.6 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15363
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 152
telemt_upstream_connect_success_total 145
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 145
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 2204
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 29
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 11288
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 793657556 (756.89 MB)
telemt_user_octets_to_client{user="hello"} 2844532284 (2.65 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 855.3 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4916
telemt_connections_bad_total 672
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 190
telemt_upstream_connect_success_total 184
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 184
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 1194
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 30
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 4181
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 34338232 (32.75 MB)
telemt_user_octets_to_client{user="hello"} 1302115960 (1.21 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 852.0 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11004
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 167
telemt_upstream_connect_success_total 164
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 164
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 2653
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 10271
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 77707324 (74.11 MB)
telemt_user_octets_to_client{user="hello"} 2621266868 (2.44 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 32900.2 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480048
telemt_connections_bad_total 60354
telemt_handshake_timeouts_total 14561
telemt_upstream_connect_attempt_total 13922
telemt_upstream_connect_success_total 13921
telemt_upstream_connect_attempts_per_request{bucket="1"} 13921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 186
telemt_me_reconnect_attempts_total 1877
telemt_me_reconnect_success_total 1867
telemt_me_reader_eof_total 1896
telemt_me_idle_close_by_peer_total 1896
telemt_me_route_drop_no_conn_total 167462
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 628
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 11
telemt_pool_force_close_total 363
telemt_me_writer_removed_unexpected_total 1897
telemt_me_writer_restored_same_endpoint_total 1843
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 379555
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 5483143952 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 145632824980 (135.63 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 33259.6 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485567
telemt_connections_bad_total 3750
telemt_handshake_timeouts_total 5336
telemt_upstream_connect_attempt_total 18810
telemt_upstream_connect_success_total 18718
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 18718
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 3686
telemt_me_reconnect_success_total 3677
telemt_me_reader_eof_total 3803
telemt_me_idle_close_by_peer_total 3803
telemt_me_route_drop_no_conn_total 218527
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 819
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 524
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 7
telemt_pool_force_close_total 339
telemt_pool_stale_pick_total 177
telemt_me_writer_removed_unexpected_total 3804
telemt_me_writer_restored_same_endpoint_total 3656
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 437331
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 6908537040 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 141802520444 (132.06 GB)
telemt_user_unique_ips_current{user="hello"} 32
```