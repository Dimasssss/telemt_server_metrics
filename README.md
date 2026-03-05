# Server Metrics 2026-03-05 23:46:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 5097.2 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42151
telemt_connections_bad_total 14114
telemt_handshake_timeouts_total 377
telemt_upstream_connect_attempt_total 3463
telemt_upstream_connect_success_total 3432
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3432
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 747
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 759
telemt_me_idle_close_by_peer_total 759
telemt_me_route_drop_no_conn_total 6982
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 73
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 759
telemt_me_writer_restored_same_endpoint_total 741
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 26878
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 428747560 (408.89 MB)
telemt_user_octets_to_client{user="hello"} 10450864812 (9.73 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 5092.6 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12274
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 207
telemt_upstream_connect_attempt_total 3783
telemt_upstream_connect_success_total 3781
telemt_upstream_connect_attempts_per_request{bucket="1"} 3781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 611
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 614
telemt_me_idle_close_by_peer_total 614
telemt_me_route_drop_no_conn_total 3929
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_pool_force_close_total 9
telemt_me_writer_removed_unexpected_total 615
telemt_me_writer_restored_same_endpoint_total 608
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 11756
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 94339352 (89.97 MB)
telemt_user_octets_to_client{user="hello"} 2525530800 (2.35 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 5090.1 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20373
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 4385
telemt_upstream_connect_success_total 4338
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4338
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1090
telemt_me_reconnect_success_total 1087
telemt_me_reader_eof_total 1126
telemt_me_idle_close_by_peer_total 1126
telemt_me_route_drop_no_conn_total 6045
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 1127
telemt_me_writer_restored_same_endpoint_total 1082
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 19807
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 362391404 (345.60 MB)
telemt_user_octets_to_client{user="hello"} 6084063544 (5.67 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 5086.6 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16715
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 442
telemt_upstream_connect_attempt_total 2581
telemt_upstream_connect_success_total 2570
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2570
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1072
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 270
telemt_me_reconnect_success_total 267
telemt_me_reader_eof_total 272
telemt_me_idle_close_by_peer_total 272
telemt_me_route_drop_no_conn_total 7867
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_restored_same_endpoint_total 263
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 15255
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 169134152 (161.30 MB)
telemt_user_octets_to_client{user="hello"} 14891508720 (13.87 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 5085.5 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21337
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 105
telemt_upstream_connect_attempt_total 2975
telemt_upstream_connect_success_total 2973
telemt_upstream_connect_attempts_per_request{bucket="1"} 2973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 475
telemt_me_reconnect_success_total 477
telemt_me_reader_eof_total 483
telemt_me_idle_close_by_peer_total 483
telemt_me_route_drop_no_conn_total 8345
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 10
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_removed_unexpected_total 483
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 20884
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 10930541880 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 15925579308 (14.83 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 24
```