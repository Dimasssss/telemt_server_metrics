# Server Metrics 2026-03-14 14:00:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 2546.6 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102577
telemt_connections_bad_total 693
telemt_handshake_timeouts_total 1410
telemt_upstream_connect_attempt_total 490
telemt_upstream_connect_success_total 488
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 331
telemt_me_reconnect_success_total 321
telemt_me_reader_eof_total 304
telemt_me_idle_close_by_peer_total 304
telemt_me_route_drop_no_conn_total 37771
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96507
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 168
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_restored_same_endpoint_total 312
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 96501
telemt_user_connections_current{user="hello"} 1831
telemt_user_octets_from_client{user="hello"} 1642735452 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 21818678084 (20.32 GB)
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 2552.0 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40342
telemt_connections_bad_total 2273
telemt_handshake_timeouts_total 1531
telemt_upstream_connect_attempt_total 558
telemt_upstream_connect_success_total 554
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 402
telemt_me_reconnect_success_total 394
telemt_me_reader_eof_total 368
telemt_me_idle_close_by_peer_total 368
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 13016
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33739
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 240
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 195
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_me_writer_removed_unexpected_total 393
telemt_me_writer_restored_same_endpoint_total 383
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_user_connections_total{user="hello"} 33702
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 537197792 (512.31 MB)
telemt_user_octets_to_client{user="hello"} 15934127580 (14.84 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 2415.0 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68336
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 9777
telemt_upstream_connect_attempt_total 486
telemt_upstream_connect_success_total 483
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 328
telemt_me_reconnect_success_total 323
telemt_me_reader_eof_total 288
telemt_me_idle_close_by_peer_total 288
telemt_me_route_drop_no_conn_total 18395
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53829
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 309
telemt_me_writer_restored_same_endpoint_total 290
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 53807
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 880294680 (839.51 MB)
telemt_user_octets_to_client{user="hello"} 16134338340 (15.03 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 2269.2 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31030
telemt_connections_bad_total 12131
telemt_handshake_timeouts_total 4374
telemt_upstream_connect_attempt_total 640
telemt_upstream_connect_success_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 286
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 483
telemt_me_reconnect_success_total 479
telemt_me_reader_eof_total 461
telemt_me_idle_close_by_peer_total 461
telemt_me_route_drop_no_conn_total 6097
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14204
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 469
telemt_me_writer_restored_same_endpoint_total 479
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 14189
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 495733320 (472.77 MB)
telemt_user_octets_to_client{user="hello"} 3511524656 (3.27 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 2564.6 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39999
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 231
telemt_upstream_connect_attempt_total 574
telemt_upstream_connect_success_total 563
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 408
telemt_me_reconnect_success_total 404
telemt_me_reader_eof_total 388
telemt_me_idle_close_by_peer_total 388
telemt_me_route_drop_no_conn_total 13445
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36593
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 157
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_me_writer_removed_unexpected_total 411
telemt_me_writer_restored_same_endpoint_total 386
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 36597
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 478793336 (456.61 MB)
telemt_user_octets_to_client{user="hello"} 15009990740 (13.98 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 104
```