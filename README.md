# Server Metrics 2026-03-05 23:31:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 4176.0 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35348
telemt_connections_bad_total 11571
telemt_handshake_timeouts_total 307
telemt_upstream_connect_attempt_total 2805
telemt_upstream_connect_success_total 2774
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2774
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 576
telemt_me_reconnect_success_total 575
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 6024
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 72
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 584
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 22748
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 402226044 (383.59 MB)
telemt_user_octets_to_client{user="hello"} 8563206920 (7.98 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 4171.6 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10555
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 182
telemt_upstream_connect_attempt_total 2610
telemt_upstream_connect_success_total 2608
telemt_upstream_connect_attempts_per_request{bucket="1"} 2608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 252
telemt_me_reconnect_success_total 253
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 255
telemt_me_route_drop_no_conn_total 3339
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 37
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_pool_force_close_total 9
telemt_me_writer_removed_unexpected_total 256
telemt_me_writer_restored_same_endpoint_total 249
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 10082
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 85381964 (81.43 MB)
telemt_user_octets_to_client{user="hello"} 1584110384 (1.48 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 4168.9 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17187
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 3097
telemt_upstream_connect_success_total 3054
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3054
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 643
telemt_me_reconnect_success_total 643
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 5313
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 665
telemt_me_writer_restored_same_endpoint_total 638
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 16779
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 342406548 (326.54 MB)
telemt_user_octets_to_client{user="hello"} 5444755060 (5.07 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 4165.7 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14274
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 366
telemt_upstream_connect_attempt_total 2167
telemt_upstream_connect_success_total 2156
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2156
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 882
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 257
telemt_me_reconnect_success_total 254
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 6371
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 259
telemt_me_writer_restored_same_endpoint_total 250
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 13040
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 160731560 (153.29 MB)
telemt_user_octets_to_client{user="hello"} 13667850596 (12.73 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 4164.5 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17615
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 2585
telemt_upstream_connect_success_total 2583
telemt_upstream_connect_attempts_per_request{bucket="1"} 2583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 457
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 466
telemt_me_idle_close_by_peer_total 466
telemt_me_route_drop_no_conn_total 7529
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_restored_same_endpoint_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 17219
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 10921460552 (10.17 GB)
telemt_user_octets_to_client{user="hello"} 15275130552 (14.23 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 24
```