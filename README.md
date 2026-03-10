# Server Metrics 2026-03-10 14:55:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1682.8 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61187
telemt_connections_bad_total 248
telemt_handshake_timeouts_total 459
telemt_upstream_connect_attempt_total 359
telemt_upstream_connect_success_total 358
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 245
telemt_me_reconnect_success_total 240
telemt_me_reader_eof_total 198
telemt_me_idle_close_by_peer_total 198
telemt_me_route_drop_no_conn_total 25204
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57870
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_me_writer_removed_unexpected_total 221
telemt_me_writer_restored_same_endpoint_total 234
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_user_connections_total{user="hello"} 57866
telemt_user_connections_current{user="hello"} 1468
telemt_user_octets_from_client{user="hello"} 701461296 (668.97 MB)
telemt_user_octets_to_client{user="hello"} 17982983992 (16.75 GB)
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 1739.5 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29328
telemt_connections_bad_total 608
telemt_handshake_timeouts_total 5493
telemt_upstream_connect_attempt_total 292
telemt_upstream_connect_success_total 291
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 177
telemt_me_reconnect_success_total 176
telemt_me_reader_eof_total 146
telemt_me_idle_close_by_peer_total 146
telemt_me_route_drop_no_conn_total 5826
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21164
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 81
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_me_writer_removed_unexpected_total 169
telemt_me_writer_restored_same_endpoint_total 155
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 21163
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 264716336 (252.45 MB)
telemt_user_octets_to_client{user="hello"} 6804119288 (6.34 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 1739.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40547
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 927
telemt_upstream_connect_attempt_total 1296
telemt_upstream_connect_success_total 1276
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 144
telemt_me_reconnect_success_total 125
telemt_me_reader_eof_total 113
telemt_me_idle_close_by_peer_total 113
telemt_me_route_drop_no_conn_total 12933
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37299
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 135
telemt_me_writer_restored_same_endpoint_total 114
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 38305
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 484050441 (461.63 MB)
telemt_user_octets_to_client{user="hello"} 13213708461 (12.31 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 1739.8 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28284
telemt_connections_bad_total 1591
telemt_handshake_timeouts_total 1817
telemt_upstream_connect_attempt_total 277
telemt_upstream_connect_success_total 277
telemt_upstream_connect_attempts_per_request{bucket="1"} 277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 166
telemt_me_reconnect_success_total 166
telemt_me_reader_eof_total 140
telemt_me_idle_close_by_peer_total 140
telemt_me_route_drop_no_conn_total 8548
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23257
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 61
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 160
telemt_me_writer_restored_same_endpoint_total 155
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 23230
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 282952248 (269.84 MB)
telemt_user_octets_to_client{user="hello"} 5216342936 (4.86 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1739.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32320
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 167
telemt_upstream_connect_attempt_total 412
telemt_upstream_connect_success_total 411
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 297
telemt_me_reconnect_success_total 296
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 9015
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29952
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 178
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 287
telemt_me_writer_restored_same_endpoint_total 296
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 29930
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 200273840 (191.00 MB)
telemt_user_octets_to_client{user="hello"} 7394993944 (6.89 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 120
```