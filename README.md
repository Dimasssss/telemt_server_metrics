# Server Metrics 2026-03-14 22:26:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 741.7 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14921
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 107
telemt_upstream_connect_success_total 106
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 43
telemt_me_reconnect_success_total 42
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 3911
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13978
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 35
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 47
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 13978
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 118238184 (112.76 MB)
telemt_user_octets_to_client{user="hello"} 4967719608 (4.63 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 742.3 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7567
telemt_connections_bad_total 1195
telemt_handshake_timeouts_total 391
telemt_upstream_connect_attempt_total 562
telemt_upstream_connect_success_total 556
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 189
telemt_me_reconnect_success_total 182
telemt_me_reader_eof_total 113
telemt_me_idle_close_by_peer_total 113
telemt_me_route_drop_no_conn_total 1542
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5487
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
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
telemt_me_writer_removed_unexpected_total 139
telemt_me_writer_restored_same_endpoint_total 174
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 5783
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 48095343 (45.87 MB)
telemt_user_octets_to_client{user="hello"} 1699898236 (1.58 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 742.3 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9053
telemt_connections_bad_total 392
telemt_handshake_timeouts_total 447
telemt_upstream_connect_attempt_total 112
telemt_upstream_connect_success_total 111
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 1683
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8127
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
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 26
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_user_connections_total{user="hello"} 8129
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 149804272 (142.86 MB)
telemt_user_octets_to_client{user="hello"} 1574123248 (1.47 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 742.3 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6474
telemt_connections_bad_total 579
telemt_handshake_timeouts_total 271
telemt_upstream_connect_attempt_total 147
telemt_upstream_connect_success_total 127
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 76
telemt_me_reconnect_success_total 58
telemt_me_reader_eof_total 38
telemt_me_idle_close_by_peer_total 38
telemt_me_route_drop_no_conn_total 976
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5510
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 62
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 5510
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 32105500 (30.62 MB)
telemt_user_octets_to_client{user="hello"} 745331364 (710.80 MB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 742.9 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4839
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 96
telemt_upstream_connect_success_total 94
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 96
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 31
telemt_me_reconnect_success_total 29
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 879
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4581
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 4581
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 23196604 (22.12 MB)
telemt_user_octets_to_client{user="hello"} 1346922872 (1.25 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 46
```