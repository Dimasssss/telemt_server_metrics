# Server Metrics 2026-03-14 22:37:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 1352.6 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24819
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 236
telemt_upstream_connect_success_total 235
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 129
telemt_me_reconnect_success_total 128
telemt_me_reader_eof_total 114
telemt_me_idle_close_by_peer_total 114
telemt_me_route_drop_no_conn_total 6835
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23045
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 135
telemt_me_writer_restored_same_endpoint_total 117
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 23045
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 366960096 (349.96 MB)
telemt_user_octets_to_client{user="hello"} 7380350776 (6.87 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 1353.2 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11796
telemt_connections_bad_total 1794
telemt_handshake_timeouts_total 813
telemt_upstream_connect_attempt_total 792
telemt_upstream_connect_success_total 783
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 373
telemt_me_reconnect_success_total 365
telemt_me_reader_eof_total 325
telemt_me_idle_close_by_peer_total 325
telemt_me_route_drop_no_conn_total 2368
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8606
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 322
telemt_me_writer_restored_same_endpoint_total 357
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 8902
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 1050402199 (1001.74 MB)
telemt_user_octets_to_client{user="hello"} 2536276280 (2.36 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 1353.3 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15660
telemt_connections_bad_total 502
telemt_handshake_timeouts_total 775
telemt_upstream_connect_attempt_total 240
telemt_upstream_connect_success_total 236
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 127
telemt_me_reconnect_success_total 127
telemt_me_reader_eof_total 107
telemt_me_idle_close_by_peer_total 107
telemt_me_route_drop_no_conn_total 2837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14263
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 128
telemt_me_writer_restored_same_endpoint_total 108
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 14263
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 332138772 (316.75 MB)
telemt_user_octets_to_client{user="hello"} 2743964588 (2.56 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 1353.2 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10447
telemt_connections_bad_total 1100
telemt_handshake_timeouts_total 511
telemt_upstream_connect_attempt_total 332
telemt_upstream_connect_success_total 301
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 207
telemt_me_reconnect_success_total 188
telemt_me_reader_eof_total 169
telemt_me_idle_close_by_peer_total 169
telemt_me_route_drop_no_conn_total 1922
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8674
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 193
telemt_me_writer_restored_same_endpoint_total 177
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 8674
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 47250444 (45.06 MB)
telemt_user_octets_to_client{user="hello"} 1728883340 (1.61 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 1354.0 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8635
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 339
telemt_upstream_connect_attempt_total 219
telemt_upstream_connect_success_total 217
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 111
telemt_me_reconnect_success_total 109
telemt_me_reader_eof_total 92
telemt_me_idle_close_by_peer_total 92
telemt_me_route_drop_no_conn_total 1601
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8061
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 114
telemt_me_writer_restored_same_endpoint_total 101
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 8061
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 60815808 (58.00 MB)
telemt_user_octets_to_client{user="hello"} 2118926448 (1.97 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 42
```