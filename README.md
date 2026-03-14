# Server Metrics 2026-03-14 22:52:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 2268.6 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38292
telemt_connections_bad_total 290
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 453
telemt_upstream_connect_success_total 451
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 302
telemt_me_reconnect_success_total 301
telemt_me_reader_eof_total 286
telemt_me_idle_close_by_peer_total 286
telemt_me_route_drop_no_conn_total 10630
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35381
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 155
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 308
telemt_me_writer_restored_same_endpoint_total 290
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 35380
telemt_user_connections_current{user="hello"} 858
telemt_user_octets_from_client{user="hello"} 524912812 (500.60 MB)
telemt_user_octets_to_client{user="hello"} 12346642340 (11.50 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 2269.1 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17230
telemt_connections_bad_total 2570
telemt_handshake_timeouts_total 1311
telemt_upstream_connect_attempt_total 1016
telemt_upstream_connect_success_total 1006
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 552
telemt_me_reconnect_success_total 544
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 3393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12519
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 502
telemt_me_writer_restored_same_endpoint_total 536
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 12815
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 1141978323 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 3517396328 (3.28 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 2269.3 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24766
telemt_connections_bad_total 503
telemt_handshake_timeouts_total 1303
telemt_upstream_connect_attempt_total 442
telemt_upstream_connect_success_total 437
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 284
telemt_me_reconnect_success_total 284
telemt_me_reader_eof_total 274
telemt_me_idle_close_by_peer_total 274
telemt_me_route_drop_no_conn_total 4648
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22513
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 285
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 22512
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 411562612 (392.50 MB)
telemt_user_octets_to_client{user="hello"} 5049097392 (4.70 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 2269.2 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16141
telemt_connections_bad_total 1909
telemt_handshake_timeouts_total 724
telemt_upstream_connect_attempt_total 654
telemt_upstream_connect_success_total 617
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 480
telemt_me_reconnect_success_total 461
telemt_me_reader_eof_total 442
telemt_me_idle_close_by_peer_total 442
telemt_me_route_drop_no_conn_total 3070
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13249
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 13249
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 89529764 (85.38 MB)
telemt_user_octets_to_client{user="hello"} 3653248556 (3.40 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 2270.1 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13354
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 481
telemt_upstream_connect_attempt_total 394
telemt_upstream_connect_success_total 390
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 240
telemt_me_reconnect_success_total 238
telemt_me_reader_eof_total 227
telemt_me_idle_close_by_peer_total 227
telemt_me_route_drop_no_conn_total 2905
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12506
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 79
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 12506
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 91969656 (87.71 MB)
telemt_user_octets_to_client{user="hello"} 6068876436 (5.65 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 38
```