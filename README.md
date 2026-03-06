# Server Metrics 2026-03-06 10:16:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 6274.5 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180326
telemt_connections_bad_total 401
telemt_handshake_timeouts_total 1848
telemt_upstream_connect_attempt_total 1891
telemt_upstream_connect_success_total 1883
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 859
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 50
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 76251
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 971
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 725
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 50
telemt_me_writer_restored_same_endpoint_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 142719
telemt_user_connections_current{user="hello"} 1081
telemt_user_octets_from_client{user="hello"} 2506619564 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 61623425108 (57.39 GB)
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 6271.8 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89416
telemt_connections_bad_total 348
telemt_handshake_timeouts_total 30051
telemt_upstream_connect_attempt_total 4214
telemt_upstream_connect_success_total 4213
telemt_upstream_connect_attempts_per_request{bucket="1"} 4213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1995
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 562
telemt_me_reconnect_success_total 556
telemt_me_reader_eof_total 574
telemt_me_idle_close_by_peer_total 574
telemt_me_route_drop_no_conn_total 25752
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 251
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_restored_same_endpoint_total 556
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 57814
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 833734200 (795.11 MB)
telemt_user_octets_to_client{user="hello"} 18994583884 (17.69 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 6255.0 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129376
telemt_connections_bad_total 492
telemt_handshake_timeouts_total 12243
telemt_upstream_connect_attempt_total 4102
telemt_upstream_connect_success_total 4080
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 676
telemt_me_reconnect_success_total 665
telemt_me_reader_eof_total 677
telemt_me_idle_close_by_peer_total 676
telemt_me_route_drop_no_conn_total 44168
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 316
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 225
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_restored_same_endpoint_total 665
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 111050
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 1930114148 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 30193365184 (28.12 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 6239.6 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95320
telemt_connections_bad_total 5647
telemt_handshake_timeouts_total 14047
telemt_upstream_connect_attempt_total 3332
telemt_upstream_connect_success_total 3311
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 515
telemt_me_reconnect_success_total 509
telemt_me_reader_eof_total 515
telemt_me_idle_close_by_peer_total 515
telemt_me_route_drop_no_conn_total 34399
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 233
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 515
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 72516
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 1077785128 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 21177610460 (19.72 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 6181.5 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90609
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 468
telemt_upstream_connect_attempt_total 4531
telemt_upstream_connect_success_total 4496
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 4528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 1213
telemt_me_reconnect_success_total 1208
telemt_me_reader_eof_total 1250
telemt_me_idle_close_by_peer_total 1250
telemt_me_route_drop_no_conn_total 57016
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 143
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_me_writer_removed_unexpected_total 1254
telemt_me_writer_restored_same_endpoint_total 1203
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 85133
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 2974524780 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 37820063688 (35.22 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 90
```