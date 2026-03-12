# Server Metrics 2026-03-12 03:01:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18969.7 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159203
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 3238
telemt_upstream_connect_attempt_total 4351
telemt_upstream_connect_success_total 4351
telemt_upstream_connect_attempts_per_request{bucket="1"} 4351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 3390
telemt_me_reconnect_success_total 3376
telemt_me_reader_eof_total 3566
telemt_me_idle_close_by_peer_total 3566
telemt_me_route_drop_no_conn_total 57844
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149965
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 195
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3415
telemt_me_writer_restored_same_endpoint_total 3360
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 149795
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 1080057652 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 47531250116 (44.27 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18970.5 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53512
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 910
telemt_upstream_connect_attempt_total 5436
telemt_upstream_connect_success_total 5432
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 4287
telemt_me_reconnect_success_total 4259
telemt_me_reader_eof_total 4511
telemt_me_idle_close_by_peer_total 4511
telemt_me_route_drop_no_conn_total 14532
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49953
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 75
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4291
telemt_me_writer_restored_same_endpoint_total 4250
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 50132
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 772084255 (736.32 MB)
telemt_user_octets_to_client{user="hello"} 18140844990 (16.89 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 18970.4 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279154
telemt_connections_bad_total 1333
telemt_handshake_timeouts_total 16677
telemt_upstream_connect_attempt_total 5763
telemt_upstream_connect_success_total 5761
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 4479
telemt_me_reconnect_success_total 4425
telemt_me_reader_eof_total 4587
telemt_me_idle_close_by_peer_total 4587
telemt_me_route_drop_no_conn_total 28364
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91975
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 212
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4384
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4384
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 92313
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 783844696 (747.53 MB)
telemt_user_octets_to_client{user="hello"} 28920270801 (26.93 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 18970.8 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84506
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 3794
telemt_upstream_connect_attempt_total 5657
telemt_upstream_connect_success_total 5629
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 4671
telemt_me_reconnect_success_total 4653
telemt_me_reader_eof_total 4925
telemt_me_idle_close_by_peer_total 4925
telemt_me_route_drop_no_conn_total 28508
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79469
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
telemt_me_writer_removed_unexpected_total 4685
telemt_me_writer_restored_same_endpoint_total 4632
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 79455
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 510361936 (486.72 MB)
telemt_user_octets_to_client{user="hello"} 18323574272 (17.07 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18970.5 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101881
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 661
telemt_upstream_connect_attempt_total 7045
telemt_upstream_connect_success_total 6972
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 7044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 7489
telemt_me_reconnect_success_total 5990
telemt_me_reader_eof_total 6215
telemt_me_idle_close_by_peer_total 6215
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 26103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97121
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 334
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6083
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5974
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 97098
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 577518064 (550.76 MB)
telemt_user_octets_to_client{user="hello"} 21303999800 (19.84 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 36
```