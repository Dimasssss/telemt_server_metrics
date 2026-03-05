# Server Metrics 2026-03-05 22:24:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 184.0 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1283
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 97
telemt_upstream_connect_success_total 89
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 89
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 82
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_user_connections_total{user="hello"} 1227
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 3926176 (3.74 MB)
telemt_user_octets_to_client{user="hello"} 191018816 (182.17 MB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 179.4 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 109
telemt_upstream_connect_success_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 84
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_user_connections_total{user="hello"} 605
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 1326644 (1.27 MB)
telemt_user_octets_to_client{user="hello"} 97287652 (92.78 MB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 177.0 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 97
telemt_upstream_connect_success_total 85
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 85
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 5
telemt_me_route_drop_no_conn_total 65
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_user_connections_total{user="hello"} 901
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 12343580 (11.77 MB)
telemt_user_octets_to_client{user="hello"} 459883372 (438.58 MB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 173.6 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 865
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 93
telemt_upstream_connect_success_total 86
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 86
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 99
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_user_connections_total{user="hello"} 823
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2607268 (2.49 MB)
telemt_user_octets_to_client{user="hello"} 512192640 (488.46 MB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 172.5 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 941
telemt_upstream_connect_attempt_total 100
telemt_upstream_connect_success_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 215
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 888
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 5233416 (4.99 MB)
telemt_user_octets_to_client{user="hello"} 1001745828 (955.34 MB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 25
```