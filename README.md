# Server Metrics 2026-03-10 14:29:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 151.0 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7271
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 122
telemt_upstream_connect_success_total 121
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 52
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 1606
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6577
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 29
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 918
telemt_user_connections_total{user="hello"} 6577
telemt_user_connections_current{user="hello"} 1213
telemt_user_octets_from_client{user="hello"} 56278528 (53.67 MB)
telemt_user_octets_to_client{user="hello"} 981076284 (935.63 MB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 207.7 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3582
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 110
telemt_upstream_connect_success_total 109
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 40
telemt_me_reconnect_success_total 39
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 345
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2748
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 30
telemt_me_writer_restored_same_endpoint_total 18
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 2750
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 18657632 (17.79 MB)
telemt_user_octets_to_client{user="hello"} 434110784 (414.00 MB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 207.6 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7925
telemt_handshake_timeouts_total 302
telemt_upstream_connect_attempt_total 1140
telemt_upstream_connect_success_total 1121
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 33
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 1328
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6227
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 18
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 5
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 7231
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 80603897 (76.87 MB)
telemt_user_octets_to_client{user="hello"} 1554764253 (1.45 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 208.1 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3905
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 102
telemt_upstream_connect_success_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_me_reconnect_attempts_total 34
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 685
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3217
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 28
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 3196
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 30774176 (29.35 MB)
telemt_user_octets_to_client{user="hello"} 663376416 (632.65 MB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 207.8 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5344
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 114
telemt_upstream_connect_success_total 113
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 712
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5065
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 14
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 45
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 5045
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 28340252 (27.03 MB)
telemt_user_octets_to_client{user="hello"} 600137476 (572.34 MB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 95
```