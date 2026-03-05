# Server Metrics 2026-03-05 23:00:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 2333.4 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18628
telemt_connections_bad_total 4806
telemt_handshake_timeouts_total 150
telemt_upstream_connect_attempt_total 1022
telemt_upstream_connect_success_total 1002
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1002
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 88
telemt_me_reconnect_success_total 89
telemt_me_reader_eof_total 85
telemt_me_idle_close_by_peer_total 85
telemt_me_route_drop_no_conn_total 3133
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 58
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 85
telemt_me_writer_restored_same_endpoint_total 85
telemt_user_connections_total{user="hello"} 13246
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 338137168 (322.47 MB)
telemt_user_octets_to_client{user="hello"} 5847281508 (5.45 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 2328.8 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6288
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 124
telemt_upstream_connect_attempt_total 950
telemt_upstream_connect_success_total 948
telemt_upstream_connect_attempts_per_request{bucket="1"} 948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 1593
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 22
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 1
telemt_pool_force_close_total 7
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 5955
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 66995668 (63.89 MB)
telemt_user_octets_to_client{user="hello"} 834851740 (796.18 MB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 2326.2 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9700
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 1033
telemt_upstream_connect_success_total 1003
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1003
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 87
telemt_me_reconnect_success_total 88
telemt_me_reader_eof_total 84
telemt_me_idle_close_by_peer_total 84
telemt_me_route_drop_no_conn_total 2760
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 26
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 84
telemt_me_writer_restored_same_endpoint_total 83
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 9585
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 277742432 (264.88 MB)
telemt_user_octets_to_client{user="hello"} 3265905144 (3.04 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 2322.8 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8740
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 198
telemt_upstream_connect_attempt_total 1171
telemt_upstream_connect_success_total 1164
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1164
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 442
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 142
telemt_me_reconnect_success_total 141
telemt_me_reader_eof_total 137
telemt_me_idle_close_by_peer_total 137
telemt_me_route_drop_no_conn_total 4030
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 137
telemt_me_writer_restored_same_endpoint_total 137
telemt_user_connections_total{user="hello"} 8059
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 116718636 (111.31 MB)
telemt_user_octets_to_client{user="hello"} 9256762900 (8.62 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 2321.8 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10192
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 1131
telemt_upstream_connect_success_total 1130
telemt_upstream_connect_attempts_per_request{bucket="1"} 1130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 357
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 71
telemt_me_reconnect_success_total 73
telemt_me_reader_eof_total 71
telemt_me_idle_close_by_peer_total 71
telemt_me_route_drop_no_conn_total 4611
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 71
telemt_me_writer_restored_same_endpoint_total 70
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 9975
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 1514328780 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 13206587740 (12.30 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```