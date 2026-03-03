# Server Metrics 2026-03-03 21:37:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 1613.7 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18049
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 440
telemt_upstream_connect_success_total 435
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 435
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 27
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 7461
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 15
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 7
telemt_user_connections_total{user="hello"} 17294
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 124903168 (119.12 MB)
telemt_user_octets_to_client{user="hello"} 8169228052 (7.61 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 1610.3 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7121
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 999
telemt_upstream_connect_attempt_total 458
telemt_upstream_connect_success_total 390
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 390
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 2874
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 30
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 5990
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 26994304 (25.74 MB)
telemt_user_octets_to_client{user="hello"} 1593300524 (1.48 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 1608.9 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18085
telemt_connections_bad_total 4356
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 516
telemt_upstream_connect_success_total 502
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 502
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 25
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 3640
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 58
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 13065
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 109505628 (104.43 MB)
telemt_user_octets_to_client{user="hello"} 5558382844 (5.18 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 1608.1 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7638
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 575
telemt_upstream_connect_success_total 566
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 566
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 3920
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 7421
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 67540976 (64.41 MB)
telemt_user_octets_to_client{user="hello"} 1569988008 (1.46 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 1606.7 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19280
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 4434
telemt_upstream_connect_attempt_total 483
telemt_upstream_connect_success_total 462
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 462
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 36
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 19531
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 15
telemt_user_connections_total{user="hello"} 14502
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 44305424 (42.25 MB)
telemt_user_octets_to_client{user="hello"} 1600582920 (1.49 GB)
telemt_user_unique_ips_current{user="hello"} 43
```