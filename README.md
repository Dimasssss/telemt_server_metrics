# Server Metrics 2026-03-11 22:20:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 2140.6 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25168
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 419
telemt_upstream_connect_success_total 419
telemt_upstream_connect_attempts_per_request{bucket="1"} 419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 266
telemt_me_reconnect_success_total 265
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 255
telemt_me_route_drop_no_conn_total 7888
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22766
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 268
telemt_me_writer_restored_same_endpoint_total 249
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 22762
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 151911704 (144.87 MB)
telemt_user_octets_to_client{user="hello"} 6796515264 (6.33 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2141.2 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8601
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 75
telemt_upstream_connect_attempt_total 598
telemt_upstream_connect_success_total 598
telemt_upstream_connect_attempts_per_request{bucket="1"} 598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 302
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 439
telemt_me_reconnect_success_total 433
telemt_me_reader_eof_total 418
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 2042
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8162
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 430
telemt_me_writer_restored_same_endpoint_total 424
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_user_connections_total{user="hello"} 8160
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 67710108 (64.57 MB)
telemt_user_octets_to_client{user="hello"} 4395673092 (4.09 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 2141.1 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18731
telemt_connections_bad_total 270
telemt_handshake_timeouts_total 2127
telemt_upstream_connect_attempt_total 1182
telemt_upstream_connect_success_total 1182
telemt_upstream_connect_attempts_per_request{bucket="1"} 1182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 702
telemt_me_reconnect_success_total 665
telemt_me_reader_eof_total 573
telemt_me_idle_close_by_peer_total 573
telemt_me_route_drop_no_conn_total 3602
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15366
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 578
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 624
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 15720
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 98453812 (93.89 MB)
telemt_user_octets_to_client{user="hello"} 5086821373 (4.74 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 2141.5 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12299
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 290
telemt_upstream_connect_attempt_total 670
telemt_upstream_connect_success_total 664
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 506
telemt_me_reconnect_success_total 501
telemt_me_reader_eof_total 472
telemt_me_idle_close_by_peer_total 472
telemt_me_route_drop_no_conn_total 3321
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11796
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 495
telemt_me_writer_restored_same_endpoint_total 480
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 11799
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 84207228 (80.31 MB)
telemt_user_octets_to_client{user="hello"} 4127270516 (3.84 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2141.4 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14444
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 623
telemt_upstream_connect_success_total 614
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 458
telemt_me_reconnect_success_total 451
telemt_me_reader_eof_total 418
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 3318
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13568
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 20
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 440
telemt_me_writer_restored_same_endpoint_total 449
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 13564
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 111043432 (105.90 MB)
telemt_user_octets_to_client{user="hello"} 4755437844 (4.43 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 37
```