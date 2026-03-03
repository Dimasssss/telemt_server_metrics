# Server Metrics 2026-03-03 21:16:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 376.6 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4525
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 95
telemt_upstream_connect_success_total 91
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 855
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_user_connections_total{user="hello"} 4241
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 27838032 (26.55 MB)
telemt_user_octets_to_client{user="hello"} 1802541804 (1.68 GB)
telemt_user_unique_ips_current{user="hello"} 78
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 373.0 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1271
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 128
telemt_upstream_connect_success_total 115
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 115
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 407
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_user_connections_total{user="hello"} 1112
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 4172820 (3.98 MB)
telemt_user_octets_to_client{user="hello"} 309859520 (295.51 MB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 371.7 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3749
telemt_connections_bad_total 824
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 120
telemt_upstream_connect_success_total 113
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 113
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 21
telemt_me_route_drop_no_conn_total 470
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_user_connections_total{user="hello"} 2742
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 13292000 (12.68 MB)
telemt_user_octets_to_client{user="hello"} 725559784 (691.95 MB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 370.7 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1529
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 132
telemt_upstream_connect_success_total 129
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 129
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 19
telemt_me_route_drop_no_conn_total 319
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_user_connections_total{user="hello"} 1513
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 8714320 (8.31 MB)
telemt_user_octets_to_client{user="hello"} 258449176 (246.48 MB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 369.5 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4196
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 940
telemt_upstream_connect_attempt_total 106
telemt_upstream_connect_success_total 100
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 100
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 21
telemt_me_route_drop_no_conn_total 481
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_user_connections_total{user="hello"} 3099
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 10340168 (9.86 MB)
telemt_user_octets_to_client{user="hello"} 350121356 (333.90 MB)
telemt_user_unique_ips_current{user="hello"} 39
```