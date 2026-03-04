# Server Metrics 2026-03-04 23:46:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 10390.8 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93797
telemt_connections_bad_total 1394
telemt_handshake_timeouts_total 660
telemt_upstream_connect_attempt_total 12423
telemt_upstream_connect_success_total 12275
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 12274
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 501
telemt_me_reconnect_attempts_total 5284
telemt_me_reconnect_success_total 5280
telemt_me_reader_eof_total 5441
telemt_me_idle_close_by_peer_total 5440
telemt_me_route_drop_no_conn_total 25020
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 5500
telemt_me_writer_restored_same_endpoint_total 5260
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 80937
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 2809849856 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 47051501964 (43.82 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 10385.7 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35710
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 275
telemt_upstream_connect_attempt_total 11060
telemt_upstream_connect_success_total 10805
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 10798
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 874
telemt_me_reconnect_attempts_total 4265
telemt_me_reconnect_success_total 4245
telemt_me_reader_eof_total 4307
telemt_me_idle_close_by_peer_total 4306
telemt_me_route_drop_no_conn_total 10986
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 4393
telemt_me_writer_restored_same_endpoint_total 4225
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 32580
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 281899884 (268.84 MB)
telemt_user_octets_to_client{user="hello"} 9201116112 (8.57 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 10382.3 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83514
telemt_connections_bad_total 1282
telemt_handshake_timeouts_total 607
telemt_upstream_connect_attempt_total 4432
telemt_upstream_connect_success_total 4390
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4390
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 250
telemt_me_reconnect_success_total 262
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 24494
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 251
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 77190
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 998207144 (951.96 MB)
telemt_user_octets_to_client{user="hello"} 25776318544 (24.01 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 42430.5 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 541630
telemt_connections_bad_total 76608
telemt_handshake_timeouts_total 14710
telemt_upstream_connect_attempt_total 18034
telemt_upstream_connect_success_total 18032
telemt_upstream_connect_attempts_per_request{bucket="1"} 18032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 2232
telemt_me_reconnect_success_total 2215
telemt_me_reader_eof_total 2257
telemt_me_idle_close_by_peer_total 2257
telemt_me_route_drop_no_conn_total 183469
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 172
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
telemt_me_writer_removed_unexpected_total 2258
telemt_me_writer_restored_same_endpoint_total 2188
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 421886
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 5787099220 (5.39 GB)
telemt_user_octets_to_client{user="hello"} 157564544700 (146.74 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 42789.6 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531684
telemt_connections_bad_total 3824
telemt_handshake_timeouts_total 5829
telemt_upstream_connect_attempt_total 27617
telemt_upstream_connect_success_total 27468
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27468
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 423
telemt_me_reconnect_attempts_total 6395
telemt_me_reconnect_success_total 6376
telemt_me_reader_eof_total 6618
telemt_me_idle_close_by_peer_total 6617
telemt_me_route_drop_no_conn_total 234118
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 173
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
telemt_me_writer_removed_unexpected_total 6623
telemt_me_writer_restored_same_endpoint_total 6354
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 481343
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 7355538736 (6.85 GB)
telemt_user_octets_to_client{user="hello"} 160499404792 (149.48 GB)
telemt_user_unique_ips_current{user="hello"} 26
```