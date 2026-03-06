# Server Metrics 2026-03-06 08:59:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 1659.1 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44545
telemt_connections_bad_total 180
telemt_handshake_timeouts_total 93
telemt_upstream_connect_attempt_total 410
telemt_upstream_connect_success_total 407
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 10045
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 276
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 36518
telemt_user_connections_current{user="hello"} 952
telemt_user_octets_from_client{user="hello"} 648983124 (618.92 MB)
telemt_user_octets_to_client{user="hello"} 11488121784 (10.70 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 1656.6 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19827
telemt_connections_bad_total 294
telemt_handshake_timeouts_total 4296
telemt_upstream_connect_attempt_total 402
telemt_upstream_connect_success_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 206
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 5557
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 77
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 14939
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 209653744 (199.94 MB)
telemt_user_octets_to_client{user="hello"} 5227065752 (4.87 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 1639.8 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34676
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 6186
telemt_upstream_connect_attempt_total 495
telemt_upstream_connect_success_total 490
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 10
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 8750
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 69
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 26675
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 535704104 (510.89 MB)
telemt_user_octets_to_client{user="hello"} 8167150480 (7.61 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 1624.3 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30020
telemt_connections_bad_total 1461
telemt_handshake_timeouts_total 9254
telemt_upstream_connect_attempt_total 517
telemt_upstream_connect_success_total 511
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 16
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 11087
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 66
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 12
telemt_user_connections_total{user="hello"} 18421
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 470841620 (449.03 MB)
telemt_user_octets_to_client{user="hello"} 6013583220 (5.60 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 1565.9 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24147
telemt_connections_bad_total 255
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 480
telemt_upstream_connect_success_total 468
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 8847
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 27
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_restored_same_endpoint_total 16
telemt_user_connections_total{user="hello"} 21239
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 247458320 (235.99 MB)
telemt_user_octets_to_client{user="hello"} 8012243704 (7.46 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 82
```