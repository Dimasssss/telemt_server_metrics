# Server Metrics 2026-03-10 21:02:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23730.5 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 674817
telemt_connections_bad_total 8151
telemt_handshake_timeouts_total 7974
telemt_upstream_connect_attempt_total 5122
telemt_upstream_connect_success_total 5113
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 345
telemt_me_reconnect_attempts_total 15488
telemt_me_reconnect_success_total 3833
telemt_me_reader_eof_total 4246
telemt_me_idle_close_by_peer_total 4246
telemt_me_route_drop_no_conn_total 282620
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636973
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3257
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 2365
telemt_desync_frames_bucket_total{bucket="1_2"} 915
telemt_desync_frames_bucket_total{bucket="3_10"} 1227
telemt_desync_frames_bucket_total{bucket="gt_10"} 1115
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 4222
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3827
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 636781
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 9105152172 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 193507636864 (180.22 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 23787.3 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296600
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 17169
telemt_upstream_connect_attempt_total 11432
telemt_upstream_connect_success_total 8571
telemt_upstream_connect_fail_total 2861
telemt_upstream_connect_attempts_per_request{bucket="1"} 11432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2861
telemt_me_keepalive_timeout_total 1340
telemt_me_reconnect_attempts_total 5182
telemt_me_reconnect_success_total 4380
telemt_me_reader_eof_total 4580
telemt_me_idle_close_by_peer_total 4578
telemt_me_route_drop_no_conn_total 159650
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248602
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1428
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 1040
telemt_desync_frames_bucket_total{bucket="1_2"} 451
telemt_desync_frames_bucket_total{bucket="3_10"} 506
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4460
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4359
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 250866
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 2556883118 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 58984445340 (54.93 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 23787.1 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481113
telemt_connections_bad_total 2570
telemt_handshake_timeouts_total 33127
telemt_upstream_connect_attempt_total 6862
telemt_upstream_connect_success_total 6756
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 6862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 15485
telemt_me_reconnect_success_total 4443
telemt_me_reader_eof_total 4912
telemt_me_idle_close_by_peer_total 4912
telemt_me_route_drop_no_conn_total 167004
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419123
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1376
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 994
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4864
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4432
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 420061
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 6061810481 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 133317005365 (124.16 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 23787.5 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328134
telemt_connections_bad_total 23197
telemt_handshake_timeouts_total 28200
telemt_upstream_connect_attempt_total 6408
telemt_upstream_connect_success_total 6408
telemt_upstream_connect_attempts_per_request{bucket="1"} 6408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 6187
telemt_me_reconnect_success_total 5167
telemt_me_reader_eof_total 5425
telemt_me_idle_close_by_peer_total 5425
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 106601
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264441
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 675
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 5253
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5154
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 264120
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 3892548908 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 81833269120 (76.21 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 23787.1 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347779
telemt_connections_bad_total 1041
telemt_handshake_timeouts_total 2198
telemt_upstream_connect_attempt_total 7416
telemt_upstream_connect_success_total 7387
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 155
telemt_me_reconnect_attempts_total 9871
telemt_me_reconnect_success_total 6118
telemt_me_reader_eof_total 6410
telemt_me_idle_close_by_peer_total 6410
telemt_me_route_drop_no_conn_total 125239
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326662
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1898
telemt_desync_full_logged_total 713
telemt_desync_suppressed_total 1185
telemt_desync_frames_bucket_total{bucket="1_2"} 730
telemt_desync_frames_bucket_total{bucket="3_10"} 797
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6323
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6118
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 326552
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 6220825592 (5.79 GB)
telemt_user_octets_to_client{user="hello"} 113904054972 (106.08 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 57
```