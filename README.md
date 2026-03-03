# Server Metrics 2026-03-03 21:58:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 2842.5 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28864
telemt_connections_bad_total 262
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 1165
telemt_upstream_connect_success_total 1156
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1156
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 64
telemt_me_reconnect_success_total 78
telemt_me_reader_eof_total 59
telemt_me_idle_close_by_peer_total 59
telemt_me_route_drop_no_conn_total 11502
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 58
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_me_writer_removed_unexpected_total 59
telemt_me_writer_restored_same_endpoint_total 58
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 27787
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 274884568 (262.15 MB)
telemt_user_octets_to_client{user="hello"} 12757726356 (11.88 GB)
telemt_user_unique_ips_current{user="hello"} 53
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 2839.2 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11747
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 1866
telemt_upstream_connect_attempt_total 1498
telemt_upstream_connect_success_total 1417
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 1417
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 229
telemt_me_reconnect_success_total 244
telemt_me_reader_eof_total 228
telemt_me_idle_close_by_peer_total 227
telemt_me_route_drop_no_conn_total 4442
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 37
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 228
telemt_me_writer_restored_same_endpoint_total 224
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 9693
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 46143908 (44.01 MB)
telemt_user_octets_to_client{user="hello"} 2671184740 (2.49 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 2838.0 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29277
telemt_connections_bad_total 7819
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 1425
telemt_upstream_connect_success_total 1409
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1409
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 115
telemt_me_reconnect_success_total 132
telemt_me_reader_eof_total 112
telemt_me_idle_close_by_peer_total 112
telemt_me_route_drop_no_conn_total 5828
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 78
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 112
telemt_me_writer_restored_same_endpoint_total 111
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 20508
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 161635640 (154.15 MB)
telemt_user_octets_to_client{user="hello"} 9236464404 (8.60 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 2836.9 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13082
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 223
telemt_upstream_connect_attempt_total 1385
telemt_upstream_connect_success_total 1372
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1372
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 574
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 63
telemt_me_reconnect_success_total 80
telemt_me_reader_eof_total 62
telemt_me_idle_close_by_peer_total 62
telemt_me_route_drop_no_conn_total 5761
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 62
telemt_me_writer_restored_same_endpoint_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 12604
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 125183952 (119.38 MB)
telemt_user_octets_to_client{user="hello"} 5709878964 (5.32 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 2835.6 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28588
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 6883
telemt_upstream_connect_attempt_total 1299
telemt_upstream_connect_success_total 1270
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1270
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 186
telemt_me_reconnect_success_total 203
telemt_me_reader_eof_total 186
telemt_me_idle_close_by_peer_total 186
telemt_me_route_drop_no_conn_total 23267
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 186
telemt_me_writer_restored_same_endpoint_total 182
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 21239
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 126592496 (120.73 MB)
telemt_user_octets_to_client{user="hello"} 4064855908 (3.79 GB)
telemt_user_unique_ips_current{user="hello"} 26
```