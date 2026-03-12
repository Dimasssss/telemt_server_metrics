# Server Metrics 2026-03-12 04:22:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23867.3 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222764
telemt_connections_bad_total 1386
telemt_handshake_timeouts_total 3596
telemt_upstream_connect_attempt_total 5445
telemt_upstream_connect_success_total 5445
telemt_upstream_connect_attempts_per_request{bucket="1"} 5445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 4253
telemt_me_reconnect_success_total 4236
telemt_me_reader_eof_total 4477
telemt_me_idle_close_by_peer_total 4477
telemt_me_route_drop_no_conn_total 80221
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211724
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 444
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 324
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4280
telemt_me_writer_restored_same_endpoint_total 4220
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 211485
telemt_user_connections_current{user="hello"} 885
telemt_user_octets_from_client{user="hello"} 1940427476 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 65685946304 (61.17 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 23868.1 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75540
telemt_connections_bad_total 179
telemt_handshake_timeouts_total 1405
telemt_upstream_connect_attempt_total 6662
telemt_upstream_connect_success_total 6659
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 5285
telemt_me_reconnect_success_total 5252
telemt_me_reader_eof_total 5578
telemt_me_idle_close_by_peer_total 5578
telemt_me_route_drop_no_conn_total 21628
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68493
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5293
telemt_me_writer_restored_same_endpoint_total 5243
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 68680
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 1116058447 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 22984881934 (21.41 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 23868.0 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350808
telemt_connections_bad_total 1782
telemt_handshake_timeouts_total 22018
telemt_upstream_connect_attempt_total 6986
telemt_upstream_connect_success_total 6984
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 5466
telemt_me_reconnect_success_total 5408
telemt_me_reader_eof_total 5643
telemt_me_idle_close_by_peer_total 5643
telemt_me_route_drop_no_conn_total 40068
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127055
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 415
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5376
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5367
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 127374
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 1165502076 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 39862804761 (37.13 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 23868.4 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113099
telemt_connections_bad_total 1078
telemt_handshake_timeouts_total 6801
telemt_upstream_connect_attempt_total 7112
telemt_upstream_connect_success_total 7081
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 7112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 5886
telemt_me_reconnect_success_total 5865
telemt_me_reader_eof_total 6226
telemt_me_idle_close_by_peer_total 6226
telemt_me_route_drop_no_conn_total 37797
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103707
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5901
telemt_me_writer_restored_same_endpoint_total 5844
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 103691
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 819350220 (781.39 MB)
telemt_user_octets_to_client{user="hello"} 29289312544 (27.28 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 23868.0 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132116
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 774
telemt_upstream_connect_attempt_total 8960
telemt_upstream_connect_success_total 8869
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 8960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 9143
telemt_me_reconnect_success_total 7641
telemt_me_reader_eof_total 7941
telemt_me_idle_close_by_peer_total 7941
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 36139
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126345
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 476
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 311
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 7748
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7624
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 126322
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 851167352 (811.74 MB)
telemt_user_octets_to_client{user="hello"} 27775692344 (25.87 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 59
```