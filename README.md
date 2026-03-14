# Server Metrics 2026-03-14 14:05:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 2852.8 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115845
telemt_connections_bad_total 1527
telemt_handshake_timeouts_total 1593
telemt_upstream_connect_attempt_total 583
telemt_upstream_connect_success_total 579
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 381
telemt_me_reconnect_success_total 371
telemt_me_reader_eof_total 354
telemt_me_idle_close_by_peer_total 354
telemt_me_route_drop_no_conn_total 43467
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108275
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_me_writer_removed_unexpected_total 376
telemt_me_writer_restored_same_endpoint_total 362
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 108268
telemt_user_connections_current{user="hello"} 1757
telemt_user_octets_from_client{user="hello"} 1790922684 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 25261004012 (23.53 GB)
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 2858.4 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45022
telemt_connections_bad_total 2674
telemt_handshake_timeouts_total 1832
telemt_upstream_connect_attempt_total 652
telemt_upstream_connect_success_total 647
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 451
telemt_me_reconnect_success_total 442
telemt_me_reader_eof_total 424
telemt_me_idle_close_by_peer_total 424
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 14875
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37648
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 294
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 443
telemt_me_writer_restored_same_endpoint_total 431
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 37611
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 580650480 (553.75 MB)
telemt_user_octets_to_client{user="hello"} 18624892960 (17.35 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 2721.1 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76623
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 10413
telemt_upstream_connect_attempt_total 534
telemt_upstream_connect_success_total 531
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 376
telemt_me_reconnect_success_total 371
telemt_me_reader_eof_total 337
telemt_me_idle_close_by_peer_total 337
telemt_me_route_drop_no_conn_total 22062
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61162
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 132
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_restored_same_endpoint_total 338
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 61136
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 972093296 (927.06 MB)
telemt_user_octets_to_client{user="hello"} 17923638488 (16.69 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 2575.6 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38070
telemt_connections_bad_total 13383
telemt_handshake_timeouts_total 6005
telemt_upstream_connect_attempt_total 708
telemt_upstream_connect_success_total 708
telemt_upstream_connect_attempts_per_request{bucket="1"} 708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 323
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 551
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 8064
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18303
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 538
telemt_me_writer_restored_same_endpoint_total 546
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 18287
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 571776836 (545.29 MB)
telemt_user_octets_to_client{user="hello"} 4658019140 (4.34 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 2870.9 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45005
telemt_connections_bad_total 95
telemt_handshake_timeouts_total 288
telemt_upstream_connect_attempt_total 703
telemt_upstream_connect_success_total 687
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 482
telemt_me_reader_eof_total 468
telemt_me_idle_close_by_peer_total 468
telemt_me_route_drop_no_conn_total 15624
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41111
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 170
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_me_writer_removed_unexpected_total 491
telemt_me_writer_restored_same_endpoint_total 464
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 41115
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 529972388 (505.42 MB)
telemt_user_octets_to_client{user="hello"} 16110398836 (15.00 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 117
```