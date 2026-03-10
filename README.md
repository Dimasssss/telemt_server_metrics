# Server Metrics 2026-03-10 15:00:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1989.0 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73019
telemt_connections_bad_total 248
telemt_handshake_timeouts_total 481
telemt_upstream_connect_attempt_total 468
telemt_upstream_connect_success_total 466
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 307
telemt_me_reconnect_success_total 302
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 29997
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69498
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_me_writer_removed_unexpected_total 283
telemt_me_writer_restored_same_endpoint_total 296
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_user_connections_total{user="hello"} 69494
telemt_user_connections_current{user="hello"} 1673
telemt_user_octets_from_client{user="hello"} 770359840 (734.67 MB)
telemt_user_octets_to_client{user="hello"} 21331339420 (19.87 GB)
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2045.7 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33864
telemt_connections_bad_total 769
telemt_handshake_timeouts_total 5705
telemt_upstream_connect_attempt_total 416
telemt_upstream_connect_success_total 415
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 256
telemt_me_reconnect_success_total 254
telemt_me_reader_eof_total 226
telemt_me_idle_close_by_peer_total 226
telemt_me_route_drop_no_conn_total 7149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25240
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_me_writer_removed_unexpected_total 249
telemt_me_writer_restored_same_endpoint_total 233
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 25239
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 296526452 (282.79 MB)
telemt_user_octets_to_client{user="hello"} 8122952760 (7.57 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 2045.9 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47719
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 1239
telemt_upstream_connect_attempt_total 1429
telemt_upstream_connect_success_total 1402
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 227
telemt_me_reconnect_success_total 208
telemt_me_reader_eof_total 196
telemt_me_idle_close_by_peer_total 196
telemt_me_route_drop_no_conn_total 16125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43998
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 218
telemt_me_writer_restored_same_endpoint_total 197
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 45001
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 532457441 (507.79 MB)
telemt_user_octets_to_client{user="hello"} 15084633053 (14.05 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 2046.2 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34109
telemt_connections_bad_total 1880
telemt_handshake_timeouts_total 2393
telemt_upstream_connect_attempt_total 384
telemt_upstream_connect_success_total 384
telemt_upstream_connect_attempts_per_request{bucket="1"} 384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 149
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 230
telemt_me_reconnect_success_total 229
telemt_me_reader_eof_total 212
telemt_me_idle_close_by_peer_total 212
telemt_me_route_drop_no_conn_total 10329
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27925
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 223
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 27898
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 328885572 (313.65 MB)
telemt_user_octets_to_client{user="hello"} 6343922348 (5.91 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2045.8 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38261
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 211
telemt_upstream_connect_attempt_total 566
telemt_upstream_connect_success_total 563
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 405
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 376
telemt_me_idle_close_by_peer_total 376
telemt_me_route_drop_no_conn_total 10970
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35466
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 220
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 397
telemt_me_writer_restored_same_endpoint_total 401
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 35444
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 818276876 (780.37 MB)
telemt_user_octets_to_client{user="hello"} 9754990128 (9.09 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 159
```