# Server Metrics 2026-03-15 05:03:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 24562.9 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316962
telemt_connections_bad_total 4773
telemt_handshake_timeouts_total 1491
telemt_upstream_connect_attempt_total 5321
telemt_upstream_connect_success_total 5301
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 5321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 4074
telemt_me_reconnect_success_total 4053
telemt_me_reader_eof_total 4287
telemt_me_idle_close_by_peer_total 4287
telemt_me_route_drop_no_conn_total 100399
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281940
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 699
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4100
telemt_me_writer_restored_same_endpoint_total 4042
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 281962
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 3114568132 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 101679967868 (94.70 GB)
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 24563.5 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123499
telemt_connections_bad_total 18263
telemt_handshake_timeouts_total 4413
telemt_upstream_connect_attempt_total 7421
telemt_upstream_connect_success_total 7387
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 5852
telemt_me_reconnect_success_total 5823
telemt_me_reader_eof_total 6153
telemt_me_idle_close_by_peer_total 6153
telemt_me_route_drop_no_conn_total 27068
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97772
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 241
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5830
telemt_me_writer_restored_same_endpoint_total 5815
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 98068
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 1858516131 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 30542810668 (28.45 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 24563.7 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228683
telemt_connections_bad_total 4114
telemt_handshake_timeouts_total 25234
telemt_upstream_connect_attempt_total 5747
telemt_upstream_connect_success_total 5722
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 4490
telemt_me_reconnect_success_total 4468
telemt_me_reader_eof_total 4733
telemt_me_idle_close_by_peer_total 4733
telemt_me_route_drop_no_conn_total 52900
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190808
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4515
telemt_me_writer_restored_same_endpoint_total 4449
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 190640
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 2129051908 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 65779395984 (61.26 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 24563.6 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170277
telemt_connections_bad_total 34948
telemt_handshake_timeouts_total 11695
telemt_upstream_connect_attempt_total 8560
telemt_upstream_connect_success_total 8380
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 8560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11899
telemt_me_reconnect_success_total 7128
telemt_me_reader_eof_total 7527
telemt_me_idle_close_by_peer_total 7527
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 36579
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120609
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 185
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 7336
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7105
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 120612
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 997403676 (951.20 MB)
telemt_user_octets_to_client{user="hello"} 42093604648 (39.20 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 24564.7 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107848
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 1252
telemt_upstream_connect_attempt_total 5690
telemt_upstream_connect_success_total 5666
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4434
telemt_me_reconnect_success_total 4415
telemt_me_reader_eof_total 4711
telemt_me_idle_close_by_peer_total 4711
telemt_me_route_drop_no_conn_total 29327
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102999
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 424
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4457
telemt_me_writer_restored_same_endpoint_total 4407
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 102996
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 967513908 (922.69 MB)
telemt_user_octets_to_client{user="hello"} 34548545912 (32.18 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 63
```