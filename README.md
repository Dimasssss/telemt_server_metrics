# Server Metrics 2026-03-15 03:27:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 18759.1 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228694
telemt_connections_bad_total 3050
telemt_handshake_timeouts_total 993
telemt_upstream_connect_attempt_total 3961
telemt_upstream_connect_success_total 3946
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 3022
telemt_me_reconnect_success_total 3008
telemt_me_reader_eof_total 3175
telemt_me_idle_close_by_peer_total 3175
telemt_me_route_drop_no_conn_total 70756
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202434
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 535
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 375
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3042
telemt_me_writer_restored_same_endpoint_total 2997
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 202410
telemt_user_connections_current{user="hello"} 734
telemt_user_octets_from_client{user="hello"} 2162027480 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 72524698748 (67.54 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 18759.8 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91627
telemt_connections_bad_total 15304
telemt_handshake_timeouts_total 3768
telemt_upstream_connect_attempt_total 5559
telemt_upstream_connect_success_total 5535
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4305
telemt_me_reconnect_success_total 4284
telemt_me_reader_eof_total 4504
telemt_me_idle_close_by_peer_total 4504
telemt_me_route_drop_no_conn_total 18412
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70279
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4274
telemt_me_writer_restored_same_endpoint_total 4276
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 70575
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 1620805719 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 21392234548 (19.92 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 18760.0 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158256
telemt_connections_bad_total 3101
telemt_handshake_timeouts_total 14789
telemt_upstream_connect_attempt_total 4334
telemt_upstream_connect_success_total 4316
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3388
telemt_me_reconnect_success_total 3373
telemt_me_reader_eof_total 3559
telemt_me_idle_close_by_peer_total 3559
telemt_me_route_drop_no_conn_total 34287
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137439
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 273
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3407
telemt_me_writer_restored_same_endpoint_total 3354
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 137340
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 1197194016 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 41628621656 (38.77 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 18759.9 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127578
telemt_connections_bad_total 30441
telemt_handshake_timeouts_total 4109
telemt_upstream_connect_attempt_total 6546
telemt_upstream_connect_success_total 6413
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 6546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9019
telemt_me_reconnect_success_total 5468
telemt_me_reader_eof_total 5764
telemt_me_idle_close_by_peer_total 5764
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 25653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91158
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5629
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5449
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 91167
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 659527184 (628.97 MB)
telemt_user_octets_to_client{user="hello"} 24740581376 (23.04 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 18760.8 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77951
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 980
telemt_upstream_connect_attempt_total 4310
telemt_upstream_connect_success_total 4292
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3363
telemt_me_reconnect_success_total 3350
telemt_me_reader_eof_total 3567
telemt_me_idle_close_by_peer_total 3567
telemt_me_route_drop_no_conn_total 20502
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74556
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 259
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3381
telemt_me_writer_restored_same_endpoint_total 3342
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 74554
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 628066424 (598.97 MB)
telemt_user_octets_to_client{user="hello"} 23805921068 (22.17 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 36
```