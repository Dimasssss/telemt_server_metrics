# Server Metrics 2026-03-11 22:00:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 916.5 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12345
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 124
telemt_upstream_connect_success_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 39
telemt_me_idle_close_by_peer_total 39
telemt_me_route_drop_no_conn_total 3376
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10648
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 61
telemt_me_writer_restored_same_endpoint_total 43
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 10648
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 51119296 (48.75 MB)
telemt_user_octets_to_client{user="hello"} 2969625408 (2.77 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 917.2 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4233
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 179
telemt_upstream_connect_success_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 80
telemt_me_reconnect_attempts_total 108
telemt_me_reconnect_success_total 106
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 996
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3927
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_restored_same_endpoint_total 97
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_user_connections_total{user="hello"} 3927
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 29782064 (28.40 MB)
telemt_user_octets_to_client{user="hello"} 693361592 (661.24 MB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 917.0 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9137
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 661
telemt_upstream_connect_attempt_total 783
telemt_upstream_connect_success_total 783
telemt_upstream_connect_attempts_per_request{bucket="1"} 783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 391
telemt_me_reconnect_success_total 356
telemt_me_reader_eof_total 249
telemt_me_idle_close_by_peer_total 249
telemt_me_route_drop_no_conn_total 1473
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7775
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 268
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 8129
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 51001056 (48.64 MB)
telemt_user_octets_to_client{user="hello"} 1602862137 (1.49 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 917.5 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6325
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 175
telemt_upstream_connect_success_total 173
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 106
telemt_me_reconnect_success_total 105
telemt_me_reader_eof_total 76
telemt_me_idle_close_by_peer_total 76
telemt_me_route_drop_no_conn_total 1144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6074
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 98
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 6080
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 46923296 (44.75 MB)
telemt_user_octets_to_client{user="hello"} 1844456580 (1.72 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 917.4 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6567
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 180
telemt_upstream_connect_success_total 178
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 112
telemt_me_reconnect_success_total 109
telemt_me_reader_eof_total 71
telemt_me_idle_close_by_peer_total 71
telemt_me_route_drop_no_conn_total 1360
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6084
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_me_writer_removed_unexpected_total 93
telemt_me_writer_restored_same_endpoint_total 107
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 6080
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 84910388 (80.98 MB)
telemt_user_octets_to_client{user="hello"} 1911407020 (1.78 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 39
```