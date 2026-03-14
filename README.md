# Server Metrics 2026-03-14 22:31:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 1047.6 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19635
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 169
telemt_upstream_connect_success_total 168
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 77
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 62
telemt_me_reconnect_success_total 61
telemt_me_reader_eof_total 45
telemt_me_idle_close_by_peer_total 45
telemt_me_route_drop_no_conn_total 5385
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18273
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_restored_same_endpoint_total 50
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 18273
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 265658168 (253.35 MB)
telemt_user_octets_to_client{user="hello"} 5826060384 (5.43 GB)
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 1048.5 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9684
telemt_connections_bad_total 1546
telemt_handshake_timeouts_total 630
telemt_upstream_connect_attempt_total 711
telemt_upstream_connect_success_total 702
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 292
telemt_me_reconnect_success_total 285
telemt_me_reader_eof_total 232
telemt_me_idle_close_by_peer_total 232
telemt_me_route_drop_no_conn_total 1969
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6972
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 242
telemt_me_writer_restored_same_endpoint_total 277
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 7268
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 615955595 (587.42 MB)
telemt_user_octets_to_client{user="hello"} 1853513536 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 1048.5 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12367
telemt_connections_bad_total 392
telemt_handshake_timeouts_total 617
telemt_upstream_connect_attempt_total 175
telemt_upstream_connect_success_total 171
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 62
telemt_me_reconnect_success_total 62
telemt_me_reader_eof_total 40
telemt_me_idle_close_by_peer_total 40
telemt_me_route_drop_no_conn_total 2411
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11269
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 61
telemt_me_writer_restored_same_endpoint_total 43
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_user_connections_total{user="hello"} 11268
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 289192932 (275.80 MB)
telemt_user_octets_to_client{user="hello"} 2251173156 (2.10 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 1048.3 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8480
telemt_connections_bad_total 835
telemt_handshake_timeouts_total 350
telemt_upstream_connect_attempt_total 234
telemt_upstream_connect_success_total 203
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 109
telemt_me_reconnect_success_total 90
telemt_me_reader_eof_total 71
telemt_me_idle_close_by_peer_total 71
telemt_me_route_drop_no_conn_total 1578
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7140
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 95
telemt_me_writer_restored_same_endpoint_total 79
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 7140
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 38966604 (37.16 MB)
telemt_user_octets_to_client{user="hello"} 1081748340 (1.01 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 1048.8 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6789
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 253
telemt_upstream_connect_attempt_total 158
telemt_upstream_connect_success_total 156
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 50
telemt_me_reconnect_success_total 48
telemt_me_reader_eof_total 29
telemt_me_idle_close_by_peer_total 29
telemt_me_route_drop_no_conn_total 1296
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6372
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_restored_same_endpoint_total 40
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 6372
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 46270280 (44.13 MB)
telemt_user_octets_to_client{user="hello"} 1797855288 (1.67 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 48
```