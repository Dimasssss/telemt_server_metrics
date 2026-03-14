# Server Metrics 2026-03-14 22:42:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 1657.8 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29282
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 262
telemt_upstream_connect_success_total 261
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 155
telemt_me_reconnect_success_total 154
telemt_me_reader_eof_total 140
telemt_me_idle_close_by_peer_total 140
telemt_me_route_drop_no_conn_total 8031
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27177
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 161
telemt_me_writer_restored_same_endpoint_total 143
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 27177
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 402037748 (383.41 MB)
telemt_user_octets_to_client{user="hello"} 8930723296 (8.32 GB)
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 1658.4 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13816
telemt_connections_bad_total 2053
telemt_handshake_timeouts_total 1027
telemt_upstream_connect_attempt_total 834
telemt_upstream_connect_success_total 825
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 415
telemt_me_reconnect_success_total 407
telemt_me_reader_eof_total 367
telemt_me_idle_close_by_peer_total 367
telemt_me_route_drop_no_conn_total 2696
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9972
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 364
telemt_me_writer_restored_same_endpoint_total 399
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 10268
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 1088617747 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 2742978592 (2.55 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 1658.7 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18952
telemt_connections_bad_total 502
telemt_handshake_timeouts_total 937
telemt_upstream_connect_attempt_total 280
telemt_upstream_connect_success_total 276
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 167
telemt_me_reconnect_success_total 167
telemt_me_reader_eof_total 147
telemt_me_idle_close_by_peer_total 147
telemt_me_route_drop_no_conn_total 3414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17366
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 168
telemt_me_writer_restored_same_endpoint_total 148
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 17366
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 355996028 (339.50 MB)
telemt_user_octets_to_client{user="hello"} 3248220048 (3.03 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 1658.5 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12276
telemt_connections_bad_total 1371
telemt_handshake_timeouts_total 609
telemt_upstream_connect_attempt_total 399
telemt_upstream_connect_success_total 368
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 2253
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10078
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 260
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 10078
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 53821348 (51.33 MB)
telemt_user_octets_to_client{user="hello"} 2654911080 (2.47 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 1659.2 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10558
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 460
telemt_upstream_connect_attempt_total 243
telemt_upstream_connect_success_total 241
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 135
telemt_me_reconnect_success_total 133
telemt_me_reader_eof_total 116
telemt_me_idle_close_by_peer_total 116
telemt_me_route_drop_no_conn_total 2141
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9830
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 72
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 138
telemt_me_writer_restored_same_endpoint_total 125
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 9830
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 70217160 (66.96 MB)
telemt_user_octets_to_client{user="hello"} 3031765940 (2.82 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 38
```