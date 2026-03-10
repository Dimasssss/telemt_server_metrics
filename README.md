# Server Metrics 2026-03-10 15:10:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 2602.7 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97050
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 529
telemt_upstream_connect_attempt_total 615
telemt_upstream_connect_success_total 613
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 614
telemt_me_reconnect_success_total 449
telemt_me_reader_eof_total 413
telemt_me_idle_close_by_peer_total 413
telemt_me_route_drop_no_conn_total 41437
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93006
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_me_writer_removed_unexpected_total 437
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_user_connections_total{user="hello"} 93002
telemt_user_connections_current{user="hello"} 1346
telemt_user_octets_from_client{user="hello"} 1377423064 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 27160719928 (25.30 GB)
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2659.3 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43145
telemt_connections_bad_total 1102
telemt_handshake_timeouts_total 6052
telemt_upstream_connect_attempt_total 526
telemt_upstream_connect_success_total 525
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 366
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 338
telemt_me_idle_close_by_peer_total 338
telemt_me_route_drop_no_conn_total 10056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33382
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 214
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_me_writer_removed_unexpected_total 361
telemt_me_writer_restored_same_endpoint_total 343
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 33370
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 379410360 (361.83 MB)
telemt_user_octets_to_client{user="hello"} 10402722420 (9.69 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 2659.2 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68408
telemt_connections_bad_total 93
telemt_handshake_timeouts_total 1953
telemt_upstream_connect_attempt_total 1569
telemt_upstream_connect_success_total 1542
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 367
telemt_me_reconnect_success_total 347
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 22506
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57434
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 118
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_restored_same_endpoint_total 336
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 58436
telemt_user_connections_current{user="hello"} 926
telemt_user_octets_from_client{user="hello"} 656584769 (626.17 MB)
telemt_user_octets_to_client{user="hello"} 18779251873 (17.49 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 2659.8 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45418
telemt_connections_bad_total 2528
telemt_handshake_timeouts_total 3796
telemt_upstream_connect_attempt_total 460
telemt_upstream_connect_success_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 306
telemt_me_reconnect_success_total 305
telemt_me_reader_eof_total 290
telemt_me_idle_close_by_peer_total 290
telemt_me_route_drop_no_conn_total 15058
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36767
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 301
telemt_me_writer_restored_same_endpoint_total 294
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 36733
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 521457460 (497.30 MB)
telemt_user_octets_to_client{user="hello"} 8606044356 (8.02 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2659.3 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51311
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 301
telemt_upstream_connect_attempt_total 735
telemt_upstream_connect_success_total 732
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 574
telemt_me_reconnect_success_total 570
telemt_me_reader_eof_total 545
telemt_me_idle_close_by_peer_total 545
telemt_me_route_drop_no_conn_total 16867
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47497
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 295
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 209
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_me_writer_removed_unexpected_total 566
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 47473
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 1070386204 (1020.80 MB)
telemt_user_octets_to_client{user="hello"} 12870506036 (11.99 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 108
```