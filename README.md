# Server Metrics 2026-03-12 02:56:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18663.7 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156043
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 3081
telemt_upstream_connect_attempt_total 4297
telemt_upstream_connect_success_total 4297
telemt_upstream_connect_attempts_per_request{bucket="1"} 4297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 3365
telemt_me_reconnect_success_total 3351
telemt_me_reader_eof_total 3541
telemt_me_idle_close_by_peer_total 3541
telemt_me_route_drop_no_conn_total 56420
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147031
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 233
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3390
telemt_me_writer_restored_same_endpoint_total 3335
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 146865
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 1055140924 (1006.26 MB)
telemt_user_octets_to_client{user="hello"} 46587253892 (43.39 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18664.4 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52752
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 891
telemt_upstream_connect_attempt_total 5350
telemt_upstream_connect_success_total 5347
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 4233
telemt_me_reconnect_success_total 4206
telemt_me_reader_eof_total 4457
telemt_me_idle_close_by_peer_total 4457
telemt_me_route_drop_no_conn_total 14271
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49238
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4237
telemt_me_writer_restored_same_endpoint_total 4197
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 49417
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 769101491 (733.47 MB)
telemt_user_octets_to_client{user="hello"} 18087007294 (16.84 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 18664.3 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270281
telemt_connections_bad_total 1327
telemt_handshake_timeouts_total 16423
telemt_upstream_connect_attempt_total 5689
telemt_upstream_connect_success_total 5687
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 4431
telemt_me_reconnect_success_total 4377
telemt_me_reader_eof_total 4536
telemt_me_idle_close_by_peer_total 4536
telemt_me_route_drop_no_conn_total 27916
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90210
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 198
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4333
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4336
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 90548
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 759537612 (724.35 MB)
telemt_user_octets_to_client{user="hello"} 28723105005 (26.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 18664.7 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82794
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 3511
telemt_upstream_connect_attempt_total 5574
telemt_upstream_connect_success_total 5546
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 4612
telemt_me_reconnect_success_total 4596
telemt_me_reader_eof_total 4865
telemt_me_idle_close_by_peer_total 4865
telemt_me_route_drop_no_conn_total 28094
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78005
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 126
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4625
telemt_me_writer_restored_same_endpoint_total 4575
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 77991
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 503387484 (480.07 MB)
telemt_user_octets_to_client{user="hello"} 17627642220 (16.42 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18664.4 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100242
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 653
telemt_upstream_connect_attempt_total 6949
telemt_upstream_connect_success_total 6877
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 6949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 7412
telemt_me_reconnect_success_total 5914
telemt_me_reader_eof_total 6136
telemt_me_idle_close_by_peer_total 6136
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 25610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95522
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 330
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6004
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5898
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 95499
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 561369440 (535.36 MB)
telemt_user_octets_to_client{user="hello"} 20959210464 (19.52 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 37
```