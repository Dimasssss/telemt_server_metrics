# Server Metrics 2026-03-06 09:04:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 1967.9 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55806
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 543
telemt_upstream_connect_success_total 540
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 13202
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 313
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 44385
telemt_user_connections_current{user="hello"} 960
telemt_user_octets_from_client{user="hello"} 752440088 (717.58 MB)
telemt_user_octets_to_client{user="hello"} 14100885412 (13.13 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 1965.2 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26625
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 6940
telemt_upstream_connect_attempt_total 563
telemt_upstream_connect_success_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 281
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 17
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 6916
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 93
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_me_writer_removed_unexpected_total 17
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 18244
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 278918124 (266.00 MB)
telemt_user_octets_to_client{user="hello"} 7031178292 (6.55 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 1948.6 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41357
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 7467
telemt_upstream_connect_attempt_total 660
telemt_upstream_connect_success_total 652
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 20
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 11235
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 75
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 32144
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 575068988 (548.43 MB)
telemt_user_octets_to_client{user="hello"} 10178323036 (9.48 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 1933.0 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34992
telemt_connections_bad_total 1741
telemt_handshake_timeouts_total 10104
telemt_upstream_connect_attempt_total 670
telemt_upstream_connect_success_total 661
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 16
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 12632
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 12
telemt_user_connections_total{user="hello"} 22361
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 500629640 (477.44 MB)
telemt_user_octets_to_client{user="hello"} 7005412400 (6.52 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 1874.8 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29343
telemt_connections_bad_total 255
telemt_handshake_timeouts_total 100
telemt_upstream_connect_attempt_total 626
telemt_upstream_connect_success_total 611
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 25
telemt_me_reconnect_success_total 28
telemt_me_reader_eof_total 23
telemt_me_idle_close_by_peer_total 23
telemt_me_route_drop_no_conn_total 11317
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 42
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 23
telemt_user_connections_total{user="hello"} 25761
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 556974248 (531.17 MB)
telemt_user_octets_to_client{user="hello"} 10018766648 (9.33 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 95
```