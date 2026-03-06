# Server Metrics 2026-03-06 03:57:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 20148.1 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140405
telemt_connections_bad_total 15926
telemt_handshake_timeouts_total 2837
telemt_upstream_connect_attempt_total 22783
telemt_upstream_connect_success_total 22606
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 22606
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 8668
telemt_me_reconnect_success_total 8640
telemt_me_reader_eof_total 8953
telemt_me_idle_close_by_peer_total 8953
telemt_me_route_drop_no_conn_total 38846
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 352
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 8953
telemt_me_writer_restored_same_endpoint_total 8634
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 114058
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 1757483500 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 43739893792 (40.74 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 20142.5 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47897
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 665
telemt_upstream_connect_attempt_total 16920
telemt_upstream_connect_success_total 16917
telemt_upstream_connect_attempts_per_request{bucket="1"} 16917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 3463
telemt_me_reconnect_success_total 3448
telemt_me_reader_eof_total 3504
telemt_me_idle_close_by_peer_total 3504
telemt_me_route_drop_no_conn_total 14143
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 157
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 3505
telemt_me_writer_restored_same_endpoint_total 3442
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 46246
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 331172384 (315.83 MB)
telemt_user_octets_to_client{user="hello"} 11521514712 (10.73 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 20139.9 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83457
telemt_connections_bad_total 792
telemt_handshake_timeouts_total 1629
telemt_upstream_connect_attempt_total 19221
telemt_upstream_connect_success_total 19059
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 19059
telemt_upstream_connect_attempts_per_request{bucket="2"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 233
telemt_me_reconnect_attempts_total 5860
telemt_me_reconnect_success_total 5839
telemt_me_reader_eof_total 6108
telemt_me_idle_close_by_peer_total 6108
telemt_me_route_drop_no_conn_total 23216
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 174
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6112
telemt_me_writer_restored_same_endpoint_total 5831
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 78190
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 810286256 (772.75 MB)
telemt_user_octets_to_client{user="hello"} 26193520436 (24.39 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 20136.5 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70286
telemt_connections_bad_total 1509
telemt_handshake_timeouts_total 4193
telemt_upstream_connect_attempt_total 13495
telemt_upstream_connect_success_total 13448
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 13448
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 2675
telemt_me_reconnect_success_total 2656
telemt_me_reader_eof_total 2758
telemt_me_idle_close_by_peer_total 2758
telemt_me_route_drop_no_conn_total 25013
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 196
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 7
telemt_pool_force_close_total 148
telemt_me_writer_removed_unexpected_total 2758
telemt_me_writer_restored_same_endpoint_total 2649
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 60909
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 659368064 (628.82 MB)
telemt_user_octets_to_client{user="hello"} 26108608208 (24.32 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 20135.4 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82119
telemt_connections_bad_total 874
telemt_handshake_timeouts_total 540
telemt_upstream_connect_attempt_total 14023
telemt_upstream_connect_success_total 13996
telemt_upstream_connect_attempts_per_request{bucket="1"} 13996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 2287
telemt_me_reconnect_success_total 2280
telemt_me_reader_eof_total 2355
telemt_me_idle_close_by_peer_total 2355
telemt_me_route_drop_no_conn_total 27164
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 2357
telemt_me_writer_restored_same_endpoint_total 2274
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 79433
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 15067121048 (14.03 GB)
telemt_user_octets_to_client{user="hello"} 47101174620 (43.87 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 34
```