# Server Metrics 2026-03-11 22:10:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1528.9 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19248
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 91
telemt_upstream_connect_attempt_total 276
telemt_upstream_connect_success_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 167
telemt_me_reconnect_success_total 166
telemt_me_reader_eof_total 149
telemt_me_idle_close_by_peer_total 149
telemt_me_route_drop_no_conn_total 5581
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16979
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 169
telemt_me_writer_restored_same_endpoint_total 150
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 16976
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 115327528 (109.98 MB)
telemt_user_octets_to_client{user="hello"} 5414566660 (5.04 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 1529.6 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6580
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 357
telemt_upstream_connect_success_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 175
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 243
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 223
telemt_me_idle_close_by_peer_total 223
telemt_me_route_drop_no_conn_total 1611
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6179
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 235
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_user_connections_total{user="hello"} 6177
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 53740884 (51.25 MB)
telemt_user_octets_to_client{user="hello"} 2095672488 (1.95 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 1529.4 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14856
telemt_connections_bad_total 183
telemt_handshake_timeouts_total 1528
telemt_upstream_connect_attempt_total 957
telemt_upstream_connect_success_total 957
telemt_upstream_connect_attempts_per_request{bucket="1"} 957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 521
telemt_me_reconnect_success_total 485
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 2833
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12201
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 398
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 444
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 12555
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 83438432 (79.57 MB)
telemt_user_octets_to_client{user="hello"} 2951916449 (2.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 1529.7 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9332
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 213
telemt_upstream_connect_attempt_total 404
telemt_upstream_connect_success_total 400
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 288
telemt_me_reconnect_success_total 284
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 255
telemt_me_route_drop_no_conn_total 2173
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8973
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 278
telemt_me_writer_restored_same_endpoint_total 263
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 8976
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 62499136 (59.60 MB)
telemt_user_octets_to_client{user="hello"} 3330932036 (3.10 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1529.6 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10648
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 64
telemt_upstream_connect_attempt_total 388
telemt_upstream_connect_success_total 383
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 271
telemt_me_reconnect_success_total 264
telemt_me_reader_eof_total 230
telemt_me_idle_close_by_peer_total 230
telemt_me_route_drop_no_conn_total 2378
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9929
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 19
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_restored_same_endpoint_total 262
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 9925
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 98796640 (94.22 MB)
telemt_user_octets_to_client{user="hello"} 3324331076 (3.10 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 30
```