# Server Metrics 2026-03-06 10:26:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 289.5 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11612
telemt_handshake_timeouts_total 139
telemt_upstream_connect_attempt_total 81
telemt_upstream_connect_success_total 79
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 81
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 1768
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 23
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_user_connections_total{user="hello"} 8414
telemt_user_connections_current{user="hello"} 1058
telemt_user_octets_from_client{user="hello"} 215261508 (205.29 MB)
telemt_user_octets_to_client{user="hello"} 2746788448 (2.56 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 289.3 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4063
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 82
telemt_upstream_connect_success_total 81
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 82
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 663
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 3770
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 26092120 (24.88 MB)
telemt_user_octets_to_client{user="hello"} 1025659468 (978.15 MB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 289.2 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5938
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 80
telemt_upstream_connect_attempt_total 93
telemt_upstream_connect_success_total 90
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 93
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 1524
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 5585
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 56959576 (54.32 MB)
telemt_user_octets_to_client{user="hello"} 994994368 (948.90 MB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 289.4 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4354
telemt_connections_bad_total 266
telemt_handshake_timeouts_total 194
telemt_upstream_connect_attempt_total 94
telemt_upstream_connect_success_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 94
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_route_drop_no_conn_total 897
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_user_connections_total{user="hello"} 3701
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 50708868 (48.36 MB)
telemt_user_octets_to_client{user="hello"} 1710139684 (1.59 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 289.7 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4158
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 96
telemt_upstream_connect_success_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 96
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 1039
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_user_connections_total{user="hello"} 4032
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 3025927120 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 1770589056 (1.65 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 75
```