# Server Metrics 2026-03-14 19:48:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 23447.0 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 921275
telemt_connections_bad_total 40385
telemt_handshake_timeouts_total 13777
telemt_upstream_connect_attempt_total 4301
telemt_upstream_connect_success_total 4284
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 3879
telemt_me_reconnect_success_total 3075
telemt_me_reader_eof_total 3236
telemt_me_idle_close_by_peer_total 3236
telemt_me_route_drop_no_conn_total 353087
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 815319
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2786
telemt_desync_full_logged_total 798
telemt_desync_suppressed_total 1988
telemt_desync_frames_bucket_total{bucket="1_2"} 661
telemt_desync_frames_bucket_total{bucket="3_10"} 1025
telemt_desync_frames_bucket_total{bucket="gt_10"} 1100
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3153
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3066
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 815273
telemt_user_connections_current{user="hello"} 1534
telemt_user_octets_from_client{user="hello"} 14516184628 (13.52 GB)
telemt_user_octets_to_client{user="hello"} 268033872120 (249.63 GB)
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 23452.1 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356807
telemt_connections_bad_total 24841
telemt_handshake_timeouts_total 10659
telemt_upstream_connect_attempt_total 5000
telemt_upstream_connect_success_total 4946
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 5000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 441
telemt_me_reconnect_attempts_total 4523
telemt_me_reconnect_success_total 3730
telemt_me_reader_eof_total 3884
telemt_me_idle_close_by_peer_total 3884
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 109775
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301065
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1449
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 1059
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3837
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3708
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 300996
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 4038326448 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 105410797660 (98.17 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 23314.8 (6h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752942
telemt_connections_bad_total 2901
telemt_handshake_timeouts_total 156032
telemt_upstream_connect_attempt_total 4493
telemt_upstream_connect_success_total 4477
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 7199
telemt_me_reconnect_success_total 3290
telemt_me_reader_eof_total 3532
telemt_me_idle_close_by_peer_total 3532
telemt_me_route_drop_no_conn_total 180615
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507616
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1838
telemt_desync_full_logged_total 713
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 947
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3447
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3257
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 507447
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 7469589512 (6.96 GB)
telemt_user_octets_to_client{user="hello"} 182340443768 (169.82 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 23169.5 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415609
telemt_connections_bad_total 93001
telemt_handshake_timeouts_total 49882
telemt_upstream_connect_attempt_total 5429
telemt_upstream_connect_success_total 5428
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 5167
telemt_me_reconnect_success_total 4248
telemt_me_reader_eof_total 4444
telemt_me_idle_close_by_peer_total 4444
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 95617
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265852
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 589
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 383
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4324
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4237
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 265769
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 3763733012 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 84408413352 (78.61 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 23465.0 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351575
telemt_connections_bad_total 1315
telemt_handshake_timeouts_total 3775
telemt_upstream_connect_attempt_total 4914
telemt_upstream_connect_success_total 4814
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 4914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 4285
telemt_me_reconnect_success_total 3613
telemt_me_reader_eof_total 3803
telemt_me_idle_close_by_peer_total 3803
telemt_me_route_drop_no_conn_total 111407
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325601
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 812
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 517
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3702
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3595
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 325574
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 5070298628 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 139075888104 (129.52 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 70
```