# Server Metrics 2026-03-11 21:50:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 304.3 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4773
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 103
telemt_upstream_connect_success_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 38
telemt_me_reconnect_success_total 38
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 1094
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4128
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 38
telemt_me_writer_restored_same_endpoint_total 22
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_user_connections_total{user="hello"} 4128
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 14772532 (14.09 MB)
telemt_user_octets_to_client{user="hello"} 1267512716 (1.18 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 305.0 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1874
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 111
telemt_upstream_connect_success_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 41
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1628
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_me_writer_removed_unexpected_total 42
telemt_me_writer_restored_same_endpoint_total 32
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 316
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1628
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 6359724 (6.07 MB)
telemt_user_octets_to_client{user="hello"} 254930472 (243.12 MB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 304.7 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3537
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 664
telemt_upstream_connect_success_total 664
telemt_upstream_connect_attempts_per_request{bucket="1"} 664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 97
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 272
telemt_me_reconnect_success_total 238
telemt_me_reader_eof_total 122
telemt_me_idle_close_by_peer_total 122
telemt_me_route_drop_no_conn_total 405
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2952
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 139
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 197
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 3306
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 7236784 (6.90 MB)
telemt_user_octets_to_client{user="hello"} 226409705 (215.92 MB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 305.3 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2559
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 126
telemt_upstream_connect_success_total 124
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 57
telemt_me_reconnect_success_total 57
telemt_me_reader_eof_total 29
telemt_me_idle_close_by_peer_total 29
telemt_me_route_drop_no_conn_total 394
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2454
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 50
telemt_me_writer_restored_same_endpoint_total 36
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 2454
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 20506748 (19.56 MB)
telemt_user_octets_to_client{user="hello"} 474903464 (452.90 MB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 305.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2278
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 121
telemt_upstream_connect_success_total 119
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 53
telemt_me_reconnect_success_total 53
telemt_me_reader_eof_total 23
telemt_me_idle_close_by_peer_total 23
telemt_me_route_drop_no_conn_total 361
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2157
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_writer_removed_unexpected_total 42
telemt_me_writer_restored_same_endpoint_total 51
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 124
telemt_user_connections_total{user="hello"} 2153
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 10815952 (10.31 MB)
telemt_user_octets_to_client{user="hello"} 501196532 (477.98 MB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 70
```