# Server Metrics 2026-03-03 21:22:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 684.0 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7561
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 139
telemt_upstream_connect_success_total 135
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 135
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 63
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 2399
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 7218
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 47922080 (45.70 MB)
telemt_user_octets_to_client{user="hello"} 3364281652 (3.13 GB)
telemt_user_unique_ips_current{user="hello"} 95
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 680.5 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2838
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 328
telemt_upstream_connect_attempt_total 182
telemt_upstream_connect_success_total 169
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 169
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 1022
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 24
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 2430
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 9168820 (8.74 MB)
telemt_user_octets_to_client{user="hello"} 522187280 (498.00 MB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 679.2 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7188
telemt_connections_bad_total 1751
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 175
telemt_upstream_connect_success_total 167
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 167
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 1014
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 19
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 5110
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 20354232 (19.41 MB)
telemt_user_octets_to_client{user="hello"} 1075857220 (1.00 GB)
telemt_user_unique_ips_current{user="hello"} 64
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 678.3 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3268
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 202
telemt_upstream_connect_success_total 199
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 199
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 20
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 1836
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 3227
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 25531868 (24.35 MB)
telemt_user_octets_to_client{user="hello"} 703422484 (670.84 MB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 676.8 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8053
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 1884
telemt_upstream_connect_attempt_total 147
telemt_upstream_connect_success_total 141
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 141
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 2393
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 5965
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 17321364 (16.52 MB)
telemt_user_octets_to_client{user="hello"} 703398820 (670.81 MB)
telemt_user_unique_ips_current{user="hello"} 70
```