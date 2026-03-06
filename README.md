# Server Metrics 2026-03-06 08:33:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 113.1 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3776
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 72
telemt_upstream_connect_success_total 71
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 355
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 17
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_user_connections_total{user="hello"} 3575
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 9698680 (9.25 MB)
telemt_user_octets_to_client{user="hello"} 871051620 (830.70 MB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 110.8 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1610
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 69
telemt_upstream_connect_success_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27
telemt_me_route_drop_no_conn_total 238
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_user_connections_total{user="hello"} 1517
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 17291816 (16.49 MB)
telemt_user_octets_to_client{user="hello"} 224617540 (214.21 MB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 93.7 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2855
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 71
telemt_upstream_connect_success_total 70
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 71
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 378
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2665
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 18863396 (17.99 MB)
telemt_user_octets_to_client{user="hello"} 302862796 (288.83 MB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 78.6 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1470
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 75
telemt_upstream_connect_success_total 70
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 189
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 1281
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 28707584 (27.38 MB)
telemt_user_octets_to_client{user="hello"} 181010996 (172.63 MB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

Не удалось получить метрики для этого сервера.