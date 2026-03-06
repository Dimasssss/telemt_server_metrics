# Server Metrics 2026-03-06 18:19:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 701.6 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21511
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 248
telemt_upstream_connect_success_total 216
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 19
telemt_me_reconnect_success_total 15
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 6808
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 146
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_me_writer_removed_unexpected_total 27
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 19311
telemt_user_connections_current{user="hello"} 922
telemt_user_octets_from_client{user="hello"} 673174776 (641.99 MB)
telemt_user_octets_to_client{user="hello"} 5007656584 (4.66 GB)
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 701.4 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6774
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 548
telemt_upstream_connect_success_total 548
telemt_upstream_connect_attempts_per_request{bucket="1"} 548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 479
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 141
telemt_me_reconnect_success_total 142
telemt_me_reader_eof_total 177
telemt_me_idle_close_by_peer_total 177
telemt_me_route_drop_no_conn_total 2116
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 22
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 177
telemt_me_writer_restored_same_endpoint_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 6500
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 137921100 (131.53 MB)
telemt_user_octets_to_client{user="hello"} 1355097572 (1.26 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 701.4 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12773
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 319
telemt_upstream_connect_attempt_total 584
telemt_upstream_connect_success_total 578
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 26
telemt_me_reconnect_success_total 30
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 3078
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 72
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_writer_removed_unexpected_total 27
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 11835
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 222190308 (211.90 MB)
telemt_user_octets_to_client{user="hello"} 2103128060 (1.96 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 701.6 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12303
telemt_connections_bad_total 2615
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 420
telemt_upstream_connect_success_total 409
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 12
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 2292
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 9007
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 47918608 (45.70 MB)
telemt_user_octets_to_client{user="hello"} 3246532880 (3.02 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 700.4 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13433
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 296
telemt_upstream_connect_success_total 284
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 3012
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 38
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 12235
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 138130444 (131.73 MB)
telemt_user_octets_to_client{user="hello"} 4722686220 (4.40 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 64
```