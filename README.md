# Server Metrics 2026-03-06 00:27:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 7554.5 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54617
telemt_connections_bad_total 14124
telemt_handshake_timeouts_total 459
telemt_upstream_connect_attempt_total 4898
telemt_upstream_connect_success_total 4849
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4849
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 889
telemt_me_reconnect_success_total 884
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_route_drop_no_conn_total 10286
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 908
telemt_me_writer_restored_same_endpoint_total 879
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 38840
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 511097504 (487.42 MB)
telemt_user_octets_to_client{user="hello"} 14237655532 (13.26 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 7550.0 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16927
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 256
telemt_upstream_connect_attempt_total 6436
telemt_upstream_connect_success_total 6434
telemt_upstream_connect_attempts_per_request{bucket="1"} 6434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 1446
telemt_me_reconnect_success_total 1442
telemt_me_reader_eof_total 1456
telemt_me_idle_close_by_peer_total 1456
telemt_me_route_drop_no_conn_total 5359
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1457
telemt_me_writer_restored_same_endpoint_total 1438
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 16284
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 122457500 (116.78 MB)
telemt_user_octets_to_client{user="hello"} 3329076008 (3.10 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 7547.3 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30049
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 8681
telemt_upstream_connect_success_total 8617
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 8617
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3158
telemt_me_reconnect_success_total 3152
telemt_me_reader_eof_total 3313
telemt_me_idle_close_by_peer_total 3313
telemt_me_route_drop_no_conn_total 8272
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 77
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3314
telemt_me_writer_restored_same_endpoint_total 3146
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 29278
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 419578316 (400.14 MB)
telemt_user_octets_to_client{user="hello"} 10847454232 (10.10 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 7544.0 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23250
telemt_connections_bad_total 161
telemt_handshake_timeouts_total 621
telemt_upstream_connect_attempt_total 3744
telemt_upstream_connect_success_total 3727
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3727
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1572
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 349
telemt_me_reconnect_success_total 344
telemt_me_reader_eof_total 350
telemt_me_idle_close_by_peer_total 350
telemt_me_route_drop_no_conn_total 10226
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 350
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 21251
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 229452992 (218.82 MB)
telemt_user_octets_to_client{user="hello"} 16057656912 (14.95 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 7542.9 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31444
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 134
telemt_upstream_connect_attempt_total 4469
telemt_upstream_connect_success_total 4463
telemt_upstream_connect_attempts_per_request{bucket="1"} 4463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 673
telemt_me_reconnect_success_total 673
telemt_me_reader_eof_total 685
telemt_me_idle_close_by_peer_total 685
telemt_me_route_drop_no_conn_total 11456
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 13
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 2
telemt_pool_force_close_total 42
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_restored_same_endpoint_total 668
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 30859
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 10962845224 (10.21 GB)
telemt_user_octets_to_client{user="hello"} 17607271824 (16.40 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 28
```