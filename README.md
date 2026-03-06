# Server Metrics 2026-03-06 10:31:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 596.5 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23068
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 354
telemt_upstream_connect_attempt_total 99
telemt_upstream_connect_success_total 96
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 4133
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 42
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_user_connections_total{user="hello"} 16365
telemt_user_connections_current{user="hello"} 1108
telemt_user_octets_from_client{user="hello"} 326952792 (311.81 MB)
telemt_user_octets_to_client{user="hello"} 5344960212 (4.98 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 596.4 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6964
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 170
telemt_upstream_connect_attempt_total 104
telemt_upstream_connect_success_total 103
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 1503
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_user_connections_total{user="hello"} 6526
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 52176788 (49.76 MB)
telemt_user_octets_to_client{user="hello"} 1554109176 (1.45 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 596.3 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11892
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 124
telemt_upstream_connect_success_total 121
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 3097
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 9
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_user_connections_total{user="hello"} 11347
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 106014984 (101.10 MB)
telemt_user_octets_to_client{user="hello"} 2530151124 (2.36 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 596.4 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8136
telemt_connections_bad_total 530
telemt_handshake_timeouts_total 262
telemt_upstream_connect_attempt_total 145
telemt_upstream_connect_success_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 67
telemt_me_keepalive_timeout_total 1
telemt_me_route_drop_no_conn_total 2256
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 27
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_user_connections_total{user="hello"} 7068
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 73401020 (70.00 MB)
telemt_user_octets_to_client{user="hello"} 3649874340 (3.40 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 596.4 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8177
telemt_handshake_timeouts_total 124
telemt_upstream_connect_attempt_total 148
telemt_upstream_connect_success_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_route_drop_no_conn_total 2544
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_user_connections_total{user="hello"} 7787
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 6399940236 (5.96 GB)
telemt_user_octets_to_client{user="hello"} 3470047944 (3.23 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 86
```