# Server Metrics 2026-03-03 21:47:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 2228.4 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23642
telemt_connections_bad_total 259
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 788
telemt_upstream_connect_success_total 781
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 781
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 42
telemt_me_reconnect_success_total 57
telemt_me_reader_eof_total 38
telemt_me_idle_close_by_peer_total 38
telemt_me_route_drop_no_conn_total 9754
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 42
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_me_writer_removed_unexpected_total 38
telemt_me_writer_restored_same_endpoint_total 37
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 22657
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 237425464 (226.43 MB)
telemt_user_octets_to_client{user="hello"} 10944949036 (10.19 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 2224.8 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9650
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 1446
telemt_upstream_connect_attempt_total 925
telemt_upstream_connect_success_total 846
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 846
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 87
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 84
telemt_me_idle_close_by_peer_total 84
telemt_me_route_drop_no_conn_total 3729
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 84
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 8037
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 37081372 (35.36 MB)
telemt_user_octets_to_client{user="hello"} 2226057096 (2.07 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 2223.7 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23649
telemt_connections_bad_total 6123
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 909
telemt_upstream_connect_success_total 894
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 894
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 34
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 32
telemt_me_idle_close_by_peer_total 32
telemt_me_route_drop_no_conn_total 4869
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 68
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 16672
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 137476352 (131.11 MB)
telemt_user_octets_to_client{user="hello"} 8498848600 (7.92 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 2222.6 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10518
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 209
telemt_upstream_connect_attempt_total 952
telemt_upstream_connect_success_total 943
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 943
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 30
telemt_me_reconnect_success_total 47
telemt_me_reader_eof_total 29
telemt_me_idle_close_by_peer_total 29
telemt_me_route_drop_no_conn_total 4888
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 29
telemt_me_writer_restored_same_endpoint_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 10132
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 85822116 (81.85 MB)
telemt_user_octets_to_client{user="hello"} 3222353140 (3.00 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 2221.6 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23865
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 5915
telemt_upstream_connect_attempt_total 879
telemt_upstream_connect_success_total 856
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 856
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 90
telemt_me_reconnect_success_total 107
telemt_me_reader_eof_total 86
telemt_me_idle_close_by_peer_total 86
telemt_me_route_drop_no_conn_total 21737
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 86
telemt_me_writer_restored_same_endpoint_total 86
telemt_user_connections_total{user="hello"} 17542
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 68909944 (65.72 MB)
telemt_user_octets_to_client{user="hello"} 2617271352 (2.44 GB)
telemt_user_unique_ips_current{user="hello"} 39
```