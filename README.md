# Server Metrics 2026-03-14 22:21:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 435.3 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9411
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 98
telemt_upstream_connect_success_total 97
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 34
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 2146
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8880
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 12
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 38
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 8880
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 62236028 (59.35 MB)
telemt_user_octets_to_client{user="hello"} 3254394992 (3.03 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 435.8 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4593
telemt_connections_bad_total 728
telemt_handshake_timeouts_total 224
telemt_upstream_connect_attempt_total 151
telemt_upstream_connect_success_total 149
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 67
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 83
telemt_me_reconnect_success_total 83
telemt_me_reader_eof_total 56
telemt_me_idle_close_by_peer_total 56
telemt_me_route_drop_no_conn_total 1089
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3530
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 75
telemt_me_writer_restored_same_endpoint_total 75
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 3522
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 30721064 (29.30 MB)
telemt_user_octets_to_client{user="hello"} 1439515876 (1.34 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 436.0 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5448
telemt_connections_bad_total 391
telemt_handshake_timeouts_total 257
telemt_upstream_connect_attempt_total 108
telemt_upstream_connect_success_total 107
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 41
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 877
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4763
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_restored_same_endpoint_total 22
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_user_connections_total{user="hello"} 4762
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 104039600 (99.22 MB)
telemt_user_octets_to_client{user="hello"} 887400152 (846.29 MB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 435.8 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3996
telemt_connections_bad_total 337
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 130
telemt_upstream_connect_success_total 111
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 43
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 438
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3412
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 46
telemt_me_writer_restored_same_endpoint_total 32
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 3412
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 17194344 (16.40 MB)
telemt_user_octets_to_client{user="hello"} 426008168 (406.27 MB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 436.5 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2977
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 91
telemt_upstream_connect_success_total 90
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 26
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 501
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2782
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 29
telemt_me_writer_restored_same_endpoint_total 18
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 2782
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 14446432 (13.78 MB)
telemt_user_octets_to_client{user="hello"} 736727220 (702.60 MB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 38
```