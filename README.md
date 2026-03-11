# Server Metrics 2026-03-11 21:55:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 610.3 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9011
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 118
telemt_upstream_connect_success_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 53
telemt_me_reconnect_success_total 53
telemt_me_reader_eof_total 31
telemt_me_idle_close_by_peer_total 31
telemt_me_route_drop_no_conn_total 2246
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7862
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 53
telemt_me_writer_restored_same_endpoint_total 37
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_user_connections_total{user="hello"} 7862
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 32638016 (31.13 MB)
telemt_user_octets_to_client{user="hello"} 2216294380 (2.06 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 611.0 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3220
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 142
telemt_upstream_connect_success_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_me_reconnect_attempts_total 72
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 46
telemt_me_idle_close_by_peer_total 46
telemt_me_route_drop_no_conn_total 621
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2937
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_me_writer_removed_unexpected_total 67
telemt_me_writer_restored_same_endpoint_total 63
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_user_connections_total{user="hello"} 2937
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 23551676 (22.46 MB)
telemt_user_octets_to_client{user="hello"} 503443136 (480.12 MB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 611.0 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6352
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 356
telemt_upstream_connect_attempt_total 740
telemt_upstream_connect_success_total 740
telemt_upstream_connect_attempts_per_request{bucket="1"} 740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 348
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 197
telemt_me_idle_close_by_peer_total 197
telemt_me_route_drop_no_conn_total 912
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5373
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 216
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 5727
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 17921836 (17.09 MB)
telemt_user_octets_to_client{user="hello"} 969244961 (924.34 MB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 611.2 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4673
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 149
telemt_upstream_connect_success_total 147
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 80
telemt_me_reconnect_success_total 80
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4477
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 73
telemt_me_writer_restored_same_endpoint_total 59
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 4477
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 35070052 (33.45 MB)
telemt_user_octets_to_client{user="hello"} 933572264 (890.32 MB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 611.1 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4527
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 143
telemt_upstream_connect_success_total 141
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 75
telemt_me_reconnect_success_total 75
telemt_me_reader_eof_total 45
telemt_me_idle_close_by_peer_total 45
telemt_me_route_drop_no_conn_total 803
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4220
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_me_writer_removed_unexpected_total 64
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 124
telemt_user_connections_total{user="hello"} 4216
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 78273984 (74.65 MB)
telemt_user_octets_to_client{user="hello"} 1402503196 (1.31 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 36
```