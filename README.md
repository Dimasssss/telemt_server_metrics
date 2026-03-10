# Server Metrics 2026-03-10 15:05:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 2296.3 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85491
telemt_connections_bad_total 258
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 558
telemt_upstream_connect_success_total 556
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 557
telemt_me_reconnect_success_total 392
telemt_me_reader_eof_total 354
telemt_me_idle_close_by_peer_total 354
telemt_me_route_drop_no_conn_total 35934
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81706
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_me_writer_removed_unexpected_total 378
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 386
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_user_connections_total{user="hello"} 81703
telemt_user_connections_current{user="hello"} 1557
telemt_user_octets_from_client{user="hello"} 968604848 (923.73 MB)
telemt_user_octets_to_client{user="hello"} 24066017564 (22.41 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2352.9 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38645
telemt_connections_bad_total 932
telemt_handshake_timeouts_total 5813
telemt_upstream_connect_attempt_total 475
telemt_upstream_connect_success_total 474
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 315
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 8761
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29537
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 176
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 308
telemt_me_writer_restored_same_endpoint_total 292
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 29527
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 334565648 (319.07 MB)
telemt_user_octets_to_client{user="hello"} 9354838024 (8.71 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 2352.9 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57878
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 1631
telemt_upstream_connect_attempt_total 1503
telemt_upstream_connect_success_total 1476
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 301
telemt_me_reconnect_success_total 281
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 270
telemt_me_route_drop_no_conn_total 19453
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51002
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 292
telemt_me_writer_restored_same_endpoint_total 270
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 52002
telemt_user_connections_current{user="hello"} 958
telemt_user_octets_from_client{user="hello"} 597360017 (569.69 MB)
telemt_user_octets_to_client{user="hello"} 16989028533 (15.82 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 2353.2 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40201
telemt_connections_bad_total 2202
telemt_handshake_timeouts_total 3340
telemt_upstream_connect_attempt_total 432
telemt_upstream_connect_success_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 176
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 278
telemt_me_reconnect_success_total 277
telemt_me_reader_eof_total 262
telemt_me_idle_close_by_peer_total 262
telemt_me_route_drop_no_conn_total 12904
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32530
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 273
telemt_me_writer_restored_same_endpoint_total 266
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 32499
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 392179320 (374.01 MB)
telemt_user_octets_to_client{user="hello"} 7629071648 (7.11 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2353.0 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45201
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 649
telemt_upstream_connect_success_total 646
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 484
telemt_me_reader_eof_total 459
telemt_me_idle_close_by_peer_total 459
telemt_me_route_drop_no_conn_total 14136
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41884
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 262
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_me_writer_removed_unexpected_total 480
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 41861
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 1022862524 (975.48 MB)
telemt_user_octets_to_client{user="hello"} 11510335652 (10.72 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 119
```