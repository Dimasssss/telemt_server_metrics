# Server Metrics 2026-03-04 20:57:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 246.5 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5655
telemt_handshake_timeouts_total 24
telemt_upstream_connect_attempt_total 87
telemt_upstream_connect_success_total 80
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 80
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 386
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_user_connections_total{user="hello"} 3622
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 371550608 (354.34 MB)
telemt_user_octets_to_client{user="hello"} 712926152 (679.90 MB)
telemt_user_unique_ips_current{user="hello"} 76
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 241.3 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1637
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 99
telemt_upstream_connect_success_total 93
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 93
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 19
telemt_me_route_drop_no_conn_total 230
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1442
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 5696784 (5.43 MB)
telemt_user_octets_to_client{user="hello"} 284208108 (271.04 MB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 237.9 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3677
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 89
telemt_upstream_connect_success_total 86
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 86
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 610
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_user_connections_total{user="hello"} 3352
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 34473324 (32.88 MB)
telemt_user_octets_to_client{user="hello"} 385088396 (367.25 MB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 32286.1 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474717
telemt_connections_bad_total 59172
telemt_handshake_timeouts_total 14552
telemt_upstream_connect_attempt_total 13444
telemt_upstream_connect_success_total 13444
telemt_upstream_connect_attempts_per_request{bucket="1"} 13444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 1779
telemt_me_reconnect_success_total 1770
telemt_me_reader_eof_total 1796
telemt_me_idle_close_by_peer_total 1796
telemt_me_route_drop_no_conn_total 165794
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 628
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 11
telemt_pool_force_close_total 363
telemt_me_writer_removed_unexpected_total 1797
telemt_me_writer_restored_same_endpoint_total 1746
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 375620
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 5437136148 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 143466632644 (133.61 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 32645.4 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481686
telemt_connections_bad_total 3749
telemt_handshake_timeouts_total 5286
telemt_upstream_connect_attempt_total 18282
telemt_upstream_connect_success_total 18190
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 18190
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 268
telemt_me_reconnect_attempts_total 3594
telemt_me_reconnect_success_total 3585
telemt_me_reader_eof_total 3711
telemt_me_idle_close_by_peer_total 3711
telemt_me_route_drop_no_conn_total 216710
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 815
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 521
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 7
telemt_pool_force_close_total 338
telemt_pool_stale_pick_total 170
telemt_me_writer_removed_unexpected_total 3712
telemt_me_writer_restored_same_endpoint_total 3564
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 433628
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 6885122360 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 141214505848 (131.52 GB)
telemt_user_unique_ips_current{user="hello"} 35
```