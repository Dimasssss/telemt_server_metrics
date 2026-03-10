# Server Metrics 2026-03-10 14:34:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 457.3 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18901
telemt_connections_bad_total 234
telemt_handshake_timeouts_total 340
telemt_upstream_connect_attempt_total 137
telemt_upstream_connect_success_total 136
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 67
telemt_me_reconnect_success_total 65
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 5919
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17355
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 59
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 918
telemt_user_connections_total{user="hello"} 17355
telemt_user_connections_current{user="hello"} 1378
telemt_user_octets_from_client{user="hello"} 135598080 (129.32 MB)
telemt_user_octets_to_client{user="hello"} 4577795072 (4.26 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 514.1 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8745
telemt_connections_bad_total 394
telemt_handshake_timeouts_total 1218
telemt_upstream_connect_attempt_total 117
telemt_upstream_connect_success_total 116
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 47
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 1346
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6416
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 37
telemt_me_writer_restored_same_endpoint_total 25
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 6416
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 62521408 (59.63 MB)
telemt_user_octets_to_client{user="hello"} 1423764884 (1.33 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 514.0 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14636
telemt_handshake_timeouts_total 389
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
telemt_me_route_drop_no_conn_total 3537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12631
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 5
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 13635
telemt_user_connections_current{user="hello"} 838
telemt_user_octets_from_client{user="hello"} 133804761 (127.61 MB)
telemt_user_octets_to_client{user="hello"} 4469263521 (4.16 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 514.4 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8657
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 436
telemt_upstream_connect_attempt_total 112
telemt_upstream_connect_success_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 2423
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7137
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 38
telemt_me_writer_restored_same_endpoint_total 33
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 7111
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 86252448 (82.26 MB)
telemt_user_octets_to_client{user="hello"} 1587655912 (1.48 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 514.4 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11045
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 144
telemt_upstream_connect_success_total 143
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 75
telemt_me_reconnect_success_total 75
telemt_me_reader_eof_total 46
telemt_me_idle_close_by_peer_total 46
telemt_me_route_drop_no_conn_total 2181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10164
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 60
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 64
telemt_me_writer_restored_same_endpoint_total 75
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 10143
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 78720476 (75.07 MB)
telemt_user_octets_to_client{user="hello"} 1998583704 (1.86 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 108
```