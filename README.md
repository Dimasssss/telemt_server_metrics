# Server Metrics 2026-03-06 08:23:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 248.9 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7075
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 83
telemt_upstream_connect_success_total 82
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 1490
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_user_connections_total{user="hello"} 6575
telemt_user_connections_current{user="hello"} 926
telemt_user_octets_from_client{user="hello"} 86179052 (82.19 MB)
telemt_user_octets_to_client{user="hello"} 2424689184 (2.26 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 245.7 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2426
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 24
telemt_upstream_connect_attempt_total 88
telemt_upstream_connect_success_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 88
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 367
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 2222
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 37745836 (36.00 MB)
telemt_user_octets_to_client{user="hello"} 616074524 (587.53 MB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 244.8 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4214
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 197
telemt_upstream_connect_attempt_total 91
telemt_upstream_connect_success_total 88
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 1161
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_user_connections_total{user="hello"} 3818
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 23758920 (22.66 MB)
telemt_user_octets_to_client{user="hello"} 681702112 (650.12 MB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 244.2 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4468
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 626
telemt_upstream_connect_attempt_total 107
telemt_upstream_connect_success_total 99
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 719
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 3040
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 33979840 (32.41 MB)
telemt_user_octets_to_client{user="hello"} 878792004 (838.08 MB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 243.2 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4410
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 92
telemt_upstream_connect_success_total 90
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 92
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 900
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_user_connections_total{user="hello"} 3927
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 27098672 (25.84 MB)
telemt_user_octets_to_client{user="hello"} 1033970860 (986.07 MB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 81
```