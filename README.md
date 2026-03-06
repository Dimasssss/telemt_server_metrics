# Server Metrics 2026-03-06 18:09:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 83.9 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4210
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 93
telemt_upstream_connect_success_total 86
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 626
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 18
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 3828
telemt_user_connections_current{user="hello"} 1081
telemt_user_octets_from_client{user="hello"} 15427160 (14.71 MB)
telemt_user_octets_to_client{user="hello"} 446230904 (425.56 MB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 83.7 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1300
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 89
telemt_upstream_connect_success_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 89
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 260
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 1260
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 12511292 (11.93 MB)
telemt_user_octets_to_client{user="hello"} 126048492 (120.21 MB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 83.7 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1739
telemt_upstream_connect_attempt_total 109
telemt_upstream_connect_success_total 104
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 7
telemt_me_route_drop_no_conn_total 207
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1632
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 2760384 (2.63 MB)
telemt_user_octets_to_client{user="hello"} 127648820 (121.74 MB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 84.2 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2093
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 97
telemt_upstream_connect_success_total 86
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 93
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 349
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1782
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 3943784 (3.76 MB)
telemt_user_octets_to_client{user="hello"} 156372512 (149.13 MB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 82.6 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2569
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 92
telemt_upstream_connect_success_total 80
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 88
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 355
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_user_connections_total{user="hello"} 2189
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 4567164 (4.36 MB)
telemt_user_octets_to_client{user="hello"} 248037376 (236.55 MB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 132
```