# Server Metrics 2026-03-06 08:28:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 556.0 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13779
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 81
telemt_upstream_connect_attempt_total 107
telemt_upstream_connect_success_total 106
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 3838
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 101
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_user_connections_total{user="hello"} 13052
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 142929744 (136.31 MB)
telemt_user_octets_to_client{user="hello"} 5750554052 (5.36 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 552.6 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5144
telemt_connections_bad_total 260
telemt_handshake_timeouts_total 77
telemt_upstream_connect_attempt_total 116
telemt_upstream_connect_success_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 1303
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_user_connections_total{user="hello"} 4702
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 71534260 (68.22 MB)
telemt_user_octets_to_client{user="hello"} 1419769748 (1.32 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 551.9 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9780
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 667
telemt_upstream_connect_attempt_total 127
telemt_upstream_connect_success_total 124
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 2953
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_user_connections_total{user="hello"} 8761
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 106491728 (101.56 MB)
telemt_user_octets_to_client{user="hello"} 2525450476 (2.35 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 551.3 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9805
telemt_connections_bad_total 475
telemt_handshake_timeouts_total 2672
telemt_upstream_connect_attempt_total 186
telemt_upstream_connect_success_total 178
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 1813
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 6363
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 101820340 (97.10 MB)
telemt_user_octets_to_client{user="hello"} 1619008416 (1.51 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 550.2 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8145
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 100
telemt_upstream_connect_attempt_total 132
telemt_upstream_connect_success_total 130
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 2245
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 10
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_user_connections_total{user="hello"} 7576
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 79946840 (76.24 MB)
telemt_user_octets_to_client{user="hello"} 2697033108 (2.51 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 74
```