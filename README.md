# Server Metrics 2026-03-04 21:33:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 2400.6 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30619
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 898
telemt_upstream_connect_success_total 881
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 881
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 39
telemt_me_reconnect_success_total 55
telemt_me_reader_eof_total 35
telemt_me_idle_close_by_peer_total 35
telemt_me_route_drop_no_conn_total 6864
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 77
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 35
telemt_me_writer_restored_same_endpoint_total 35
telemt_user_connections_total{user="hello"} 25643
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 2037302612 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 11583058568 (10.79 GB)
telemt_user_unique_ips_current{user="hello"} 57
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 2395.3 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11926
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 966
telemt_upstream_connect_success_total 948
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 948
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 430
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 67
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 3179
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_restored_same_endpoint_total 48
telemt_user_connections_total{user="hello"} 10704
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 114779524 (109.46 MB)
telemt_user_octets_to_client{user="hello"} 3024994328 (2.82 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 2392.1 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25436
telemt_connections_bad_total 416
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 697
telemt_upstream_connect_success_total 683
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 683
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 6641
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 58
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 23397
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 183075720 (174.59 MB)
telemt_user_octets_to_client{user="hello"} 8461289936 (7.88 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 34440.3 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493148
telemt_connections_bad_total 63128
telemt_handshake_timeouts_total 14625
telemt_upstream_connect_attempt_total 14670
telemt_upstream_connect_success_total 14670
telemt_upstream_connect_attempts_per_request{bucket="1"} 14670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 198
telemt_me_reconnect_attempts_total 2009
telemt_me_reconnect_success_total 1997
telemt_me_reader_eof_total 2027
telemt_me_idle_close_by_peer_total 2027
telemt_me_route_drop_no_conn_total 171113
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 654
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 374
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 12
telemt_pool_force_close_total 397
telemt_me_writer_removed_unexpected_total 2028
telemt_me_writer_restored_same_endpoint_total 1973
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 387472
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 5554335944 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 149979422532 (139.68 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 34799.5 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493748
telemt_connections_bad_total 3752
telemt_handshake_timeouts_total 5368
telemt_upstream_connect_attempt_total 20812
telemt_upstream_connect_success_total 20700
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 20700
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 4333
telemt_me_reconnect_success_total 4321
telemt_me_reader_eof_total 4476
telemt_me_idle_close_by_peer_total 4476
telemt_me_route_drop_no_conn_total 221689
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 822
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 7
telemt_pool_force_close_total 339
telemt_pool_stale_pick_total 186
telemt_me_writer_removed_unexpected_total 4479
telemt_me_writer_restored_same_endpoint_total 4300
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 445345
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 7035942604 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 144291611308 (134.38 GB)
telemt_user_unique_ips_current{user="hello"} 29
```