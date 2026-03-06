# Server Metrics 2026-03-06 08:39:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 424.3 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10881
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 100
telemt_upstream_connect_success_total 98
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_route_drop_no_conn_total 2316
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 85
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_user_connections_total{user="hello"} 10460
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 162402748 (154.88 MB)
telemt_user_octets_to_client{user="hello"} 4026998308 (3.75 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 421.7 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4557
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 89
telemt_upstream_connect_success_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 89
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_me_route_drop_no_conn_total 1070
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 30
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_user_connections_total{user="hello"} 4253
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 56436708 (53.82 MB)
telemt_user_octets_to_client{user="hello"} 1432323220 (1.33 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 404.7 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8455
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 483
telemt_upstream_connect_attempt_total 118
telemt_upstream_connect_success_total 117
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 2036
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 25
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_user_connections_total{user="hello"} 7460
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 57830068 (55.15 MB)
telemt_user_octets_to_client{user="hello"} 1653489264 (1.54 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 389.4 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6873
telemt_connections_bad_total 348
telemt_handshake_timeouts_total 1492
telemt_upstream_connect_attempt_total 128
telemt_upstream_connect_success_total 123
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 1229
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_user_connections_total{user="hello"} 4797
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 102155720 (97.42 MB)
telemt_user_octets_to_client{user="hello"} 1501726508 (1.40 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 331.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5566
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 110
telemt_upstream_connect_success_total 104
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_success_total 5
telemt_me_route_drop_no_conn_total 1486
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_user_connections_total{user="hello"} 5311
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 57551644 (54.89 MB)
telemt_user_octets_to_client{user="hello"} 1531597168 (1.43 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 80
```