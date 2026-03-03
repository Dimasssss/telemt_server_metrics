# Server Metrics 2026-03-03 22:59:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 6528.3 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55320
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 3215
telemt_upstream_connect_success_total 3192
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3192
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 332
telemt_me_reconnect_success_total 343
telemt_me_reader_eof_total 327
telemt_me_idle_close_by_peer_total 327
telemt_me_route_drop_no_conn_total 21162
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_pool_force_close_total 39
telemt_me_writer_removed_unexpected_total 327
telemt_me_writer_restored_same_endpoint_total 323
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 53373
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 483359688 (460.97 MB)
telemt_user_octets_to_client{user="hello"} 18127191400 (16.88 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 6524.9 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25436
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 4986
telemt_upstream_connect_attempt_total 7680
telemt_upstream_connect_success_total 7509
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 7509
telemt_upstream_connect_attempts_per_request{bucket="2"} 82
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 2940
telemt_me_reconnect_success_total 2952
telemt_me_reader_eof_total 2986
telemt_me_idle_close_by_peer_total 2985
telemt_me_route_drop_no_conn_total 9277
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 56
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_me_writer_removed_unexpected_total 2986
telemt_me_writer_restored_same_endpoint_total 2932
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 20102
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 118654380 (113.16 MB)
telemt_user_octets_to_client{user="hello"} 8561756244 (7.97 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 6523.6 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61426
telemt_connections_bad_total 17778
telemt_handshake_timeouts_total 1683
telemt_upstream_connect_attempt_total 6482
telemt_upstream_connect_success_total 6440
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 6440
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 1855
telemt_me_reconnect_success_total 1866
telemt_me_reader_eof_total 1931
telemt_me_idle_close_by_peer_total 1930
telemt_me_route_drop_no_conn_total 12946
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 133
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 1932
telemt_me_writer_restored_same_endpoint_total 1845
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 40865
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 292378580 (278.83 MB)
telemt_user_octets_to_client{user="hello"} 12633881256 (11.77 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 6522.5 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26802
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 431
telemt_upstream_connect_attempt_total 3702
telemt_upstream_connect_success_total 3681
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3681
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 340
telemt_me_reconnect_success_total 355
telemt_me_reader_eof_total 338
telemt_me_idle_close_by_peer_total 338
telemt_me_route_drop_no_conn_total 10451
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 338
telemt_me_writer_restored_same_endpoint_total 336
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 25951
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 209867176 (200.14 MB)
telemt_user_octets_to_client{user="hello"} 8620148720 (8.03 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 6521.2 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59915
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 21493
telemt_upstream_connect_attempt_total 3794
telemt_upstream_connect_success_total 3742
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 3742
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 741
telemt_me_reconnect_success_total 758
telemt_me_reader_eof_total 756
telemt_me_idle_close_by_peer_total 756
telemt_me_route_drop_no_conn_total 29490
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 758
telemt_me_writer_restored_same_endpoint_total 734
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 37407
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 192782512 (183.85 MB)
telemt_user_octets_to_client{user="hello"} 8923985120 (8.31 GB)
telemt_user_unique_ips_current{user="hello"} 29
```