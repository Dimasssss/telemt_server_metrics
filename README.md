# Server Metrics 2026-03-06 00:22:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 7247.6 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52879
telemt_connections_bad_total 14117
telemt_handshake_timeouts_total 457
telemt_upstream_connect_attempt_total 4612
telemt_upstream_connect_success_total 4567
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4567
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 845
telemt_me_reconnect_success_total 841
telemt_me_reader_eof_total 860
telemt_me_idle_close_by_peer_total 860
telemt_me_route_drop_no_conn_total 9803
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 860
telemt_me_writer_restored_same_endpoint_total 836
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 37334
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 489972072 (467.27 MB)
telemt_user_octets_to_client{user="hello"} 14022215052 (13.06 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 7242.8 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16382
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 243
telemt_upstream_connect_attempt_total 6208
telemt_upstream_connect_success_total 6206
telemt_upstream_connect_attempts_per_request{bucket="1"} 6206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 1431
telemt_me_reconnect_success_total 1428
telemt_me_reader_eof_total 1439
telemt_me_idle_close_by_peer_total 1439
telemt_me_route_drop_no_conn_total 5278
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 45
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1440
telemt_me_writer_restored_same_endpoint_total 1424
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 15757
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 119097112 (113.58 MB)
telemt_user_octets_to_client{user="hello"} 3309494100 (3.08 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 7240.4 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28740
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 125
telemt_upstream_connect_attempt_total 8335
telemt_upstream_connect_success_total 8275
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 8275
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 3022
telemt_me_reconnect_success_total 3015
telemt_me_reader_eof_total 3170
telemt_me_idle_close_by_peer_total 3170
telemt_me_route_drop_no_conn_total 7927
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 77
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 3171
telemt_me_writer_restored_same_endpoint_total 3010
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 27986
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 411024840 (391.98 MB)
telemt_user_octets_to_client{user="hello"} 9122906120 (8.50 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 7236.9 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22387
telemt_connections_bad_total 161
telemt_handshake_timeouts_total 592
telemt_upstream_connect_attempt_total 3558
telemt_upstream_connect_success_total 3543
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 3543
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1493
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 335
telemt_me_reconnect_success_total 331
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 9787
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 336
telemt_me_writer_restored_same_endpoint_total 326
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 20424
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 200398224 (191.11 MB)
telemt_user_octets_to_client{user="hello"} 15934706976 (14.84 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 7236.0 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30365
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 4255
telemt_upstream_connect_success_total 4249
telemt_upstream_connect_attempts_per_request{bucket="1"} 4249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 661
telemt_me_reconnect_success_total 661
telemt_me_reader_eof_total 671
telemt_me_idle_close_by_peer_total 671
telemt_me_route_drop_no_conn_total 11121
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 13
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 2
telemt_pool_force_close_total 42
telemt_me_writer_removed_unexpected_total 671
telemt_me_writer_restored_same_endpoint_total 656
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 29793
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 10960844588 (10.21 GB)
telemt_user_octets_to_client{user="hello"} 17560181088 (16.35 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```