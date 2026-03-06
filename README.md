# Server Metrics 2026-03-06 02:20:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 14311.6 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95514
telemt_connections_bad_total 15902
telemt_handshake_timeouts_total 907
telemt_upstream_connect_attempt_total 12229
telemt_upstream_connect_success_total 12118
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12118
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 131
telemt_me_reconnect_attempts_total 3390
telemt_me_reconnect_success_total 3373
telemt_me_reader_eof_total 3498
telemt_me_idle_close_by_peer_total 3498
telemt_me_route_drop_no_conn_total 24623
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 219
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 2
telemt_pool_force_close_total 90
telemt_me_writer_removed_unexpected_total 3498
telemt_me_writer_restored_same_endpoint_total 3367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 74975
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 876246592 (835.65 MB)
telemt_user_octets_to_client{user="hello"} 26245972484 (24.44 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 14307.0 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31918
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 412
telemt_upstream_connect_attempt_total 10283
telemt_upstream_connect_success_total 10281
telemt_upstream_connect_attempts_per_request{bucket="1"} 10281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 1691
telemt_me_reconnect_success_total 1683
telemt_me_reader_eof_total 1700
telemt_me_idle_close_by_peer_total 1700
telemt_me_route_drop_no_conn_total 9195
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 6
telemt_pool_force_close_total 68
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1701
telemt_me_writer_restored_same_endpoint_total 1677
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 30949
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 195838924 (186.77 MB)
telemt_user_octets_to_client{user="hello"} 6718647052 (6.26 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 14304.4 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57954
telemt_connections_bad_total 532
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 13359
telemt_upstream_connect_success_total 13240
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13240
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 4017
telemt_me_reconnect_success_total 4004
telemt_me_reader_eof_total 4195
telemt_me_idle_close_by_peer_total 4195
telemt_me_route_drop_no_conn_total 16244
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4196
telemt_me_writer_restored_same_endpoint_total 3997
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 54475
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 590277068 (562.93 MB)
telemt_user_octets_to_client{user="hello"} 19969377592 (18.60 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 14301.0 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45786
telemt_connections_bad_total 248
telemt_handshake_timeouts_total 2876
telemt_upstream_connect_attempt_total 9757
telemt_upstream_connect_success_total 9728
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 9728
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 2073
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 2156
telemt_me_idle_close_by_peer_total 2156
telemt_me_route_drop_no_conn_total 18757
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 142
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 5
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 2156
telemt_me_writer_restored_same_endpoint_total 2054
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 40222
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 359252220 (342.61 MB)
telemt_user_octets_to_client{user="hello"} 20378470596 (18.98 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 14299.9 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57571
telemt_connections_bad_total 580
telemt_handshake_timeouts_total 395
telemt_upstream_connect_attempt_total 8512
telemt_upstream_connect_success_total 8493
telemt_upstream_connect_attempts_per_request{bucket="1"} 8493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 983
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 999
telemt_me_idle_close_by_peer_total 999
telemt_me_route_drop_no_conn_total 17737
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 52
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 5
telemt_pool_force_close_total 79
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_restored_same_endpoint_total 973
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 55759
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 11091406316 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 21859701440 (20.36 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```