# Server Metrics 2026-03-06 02:50:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 16154.3 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108640
telemt_connections_bad_total 15905
telemt_handshake_timeouts_total 1297
telemt_upstream_connect_attempt_total 14762
telemt_upstream_connect_success_total 14644
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 14644
telemt_upstream_connect_attempts_per_request{bucket="2"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 4306
telemt_me_reconnect_success_total 4287
telemt_me_reader_eof_total 4429
telemt_me_idle_close_by_peer_total 4429
telemt_me_route_drop_no_conn_total 28823
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 299
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 2
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 4429
telemt_me_writer_restored_same_endpoint_total 4281
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 86241
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 1027955192 (980.33 MB)
telemt_user_octets_to_client{user="hello"} 34811820612 (32.42 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 16149.8 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35829
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 452
telemt_upstream_connect_attempt_total 11516
telemt_upstream_connect_success_total 11514
telemt_upstream_connect_attempts_per_request{bucket="1"} 11514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 1774
telemt_me_reconnect_success_total 1765
telemt_me_reader_eof_total 1782
telemt_me_idle_close_by_peer_total 1782
telemt_me_route_drop_no_conn_total 10680
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 92
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1783
telemt_me_writer_restored_same_endpoint_total 1759
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 34739
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 228422568 (217.84 MB)
telemt_user_octets_to_client{user="hello"} 8518869332 (7.93 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 16147.2 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65460
telemt_connections_bad_total 555
telemt_handshake_timeouts_total 1047
telemt_upstream_connect_attempt_total 14559
telemt_upstream_connect_success_total 14437
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 14437
telemt_upstream_connect_attempts_per_request{bucket="2"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 4167
telemt_me_reconnect_success_total 4152
telemt_me_reader_eof_total 4348
telemt_me_idle_close_by_peer_total 4348
telemt_me_route_drop_no_conn_total 18169
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4349
telemt_me_writer_restored_same_endpoint_total 4145
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 61398
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 638868844 (609.27 MB)
telemt_user_octets_to_client{user="hello"} 21445997112 (19.97 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 16144.0 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51618
telemt_connections_bad_total 269
telemt_handshake_timeouts_total 2995
telemt_upstream_connect_attempt_total 10526
telemt_upstream_connect_success_total 10493
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 10493
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 2133
telemt_me_reconnect_success_total 2120
telemt_me_reader_eof_total 2215
telemt_me_idle_close_by_peer_total 2215
telemt_me_route_drop_no_conn_total 20461
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2215
telemt_me_writer_restored_same_endpoint_total 2113
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 45526
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 400281808 (381.74 MB)
telemt_user_octets_to_client{user="hello"} 22304526648 (20.77 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 16142.7 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64162
telemt_connections_bad_total 586
telemt_handshake_timeouts_total 427
telemt_upstream_connect_attempt_total 9521
telemt_upstream_connect_success_total 9499
telemt_upstream_connect_attempts_per_request{bucket="1"} 9499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 1040
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 1057
telemt_me_idle_close_by_peer_total 1057
telemt_me_route_drop_no_conn_total 19645
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 70
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 62200
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 12008486636 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 25986241180 (24.20 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 28
```