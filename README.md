# Server Metrics 2026-03-15 11:26:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 47521.8 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1245165
telemt_connections_bad_total 78068
telemt_handshake_timeouts_total 10442
telemt_upstream_connect_attempt_total 9509
telemt_upstream_connect_success_total 9467
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9601
telemt_me_reconnect_success_total 7095
telemt_me_reader_eof_total 7561
telemt_me_idle_close_by_peer_total 7561
telemt_me_route_drop_no_conn_total 414792
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1048449
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4001
telemt_desync_full_logged_total 1132
telemt_desync_suppressed_total 2869
telemt_desync_frames_bucket_total{bucket="1_2"} 962
telemt_desync_frames_bucket_total{bucket="3_10"} 1584
telemt_desync_frames_bucket_total{bucket="gt_10"} 1455
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7275
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 7084
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 1048428
telemt_user_connections_current{user="hello"} 2203
telemt_user_octets_from_client{user="hello"} 14739937424 (13.73 GB)
telemt_user_octets_to_client{user="hello"} 423338049456 (394.26 GB)
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 47522.6 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487476
telemt_connections_bad_total 26219
telemt_handshake_timeouts_total 21821
telemt_upstream_connect_attempt_total 12428
telemt_upstream_connect_success_total 12364
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9731
telemt_me_reconnect_success_total 9668
telemt_me_reader_eof_total 10229
telemt_me_idle_close_by_peer_total 10229
telemt_me_route_drop_no_conn_total 125127
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384679
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1380
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 496
telemt_desync_frames_bucket_total{bucket="gt_10"} 379
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9770
telemt_me_writer_restored_same_endpoint_total 9656
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 384950
telemt_user_connections_current{user="hello"} 677
telemt_user_octets_from_client{user="hello"} 5559728611 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 145662635024 (135.66 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 47522.7 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 952813
telemt_connections_bad_total 30954
telemt_handshake_timeouts_total 94231
telemt_upstream_connect_attempt_total 10456
telemt_upstream_connect_success_total 10407
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 8078
telemt_me_reconnect_success_total 8024
telemt_me_reader_eof_total 8492
telemt_me_idle_close_by_peer_total 8492
telemt_me_route_drop_no_conn_total 271928
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672326
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1653
telemt_desync_full_logged_total 583
telemt_desync_suppressed_total 1070
telemt_desync_frames_bucket_total{bucket="1_2"} 367
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 677
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8132
telemt_me_writer_restored_same_endpoint_total 8005
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 670946
telemt_user_connections_current{user="hello"} 1221
telemt_user_octets_from_client{user="hello"} 10018823640 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 261791597552 (243.81 GB)
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 47522.4 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498725
telemt_connections_bad_total 61875
telemt_handshake_timeouts_total 26879
telemt_upstream_connect_attempt_total 14104
telemt_upstream_connect_success_total 13742
telemt_upstream_connect_fail_total 362
telemt_upstream_connect_attempts_per_request{bucket="1"} 14104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 362
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 34097
telemt_me_reconnect_success_total 11363
telemt_me_reader_eof_total 12408
telemt_me_idle_close_by_peer_total 12408
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 140217
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373391
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 908
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 678
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12181
telemt_me_refill_failed_total 710
telemt_me_writer_restored_same_endpoint_total 11331
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 818
telemt_user_connections_total{user="hello"} 373291
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 4600747664 (4.28 GB)
telemt_user_octets_to_client{user="hello"} 116293206480 (108.31 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 47523.4 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520476
telemt_connections_bad_total 6401
telemt_handshake_timeouts_total 11045
telemt_upstream_connect_attempt_total 10607
telemt_upstream_connect_success_total 10556
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 8231
telemt_me_reconnect_success_total 8186
telemt_me_reader_eof_total 8694
telemt_me_idle_close_by_peer_total 8694
telemt_me_route_drop_no_conn_total 134279
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429531
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1689
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 1142
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8279
telemt_me_writer_restored_same_endpoint_total 8178
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 429557
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 5496923068 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 158830247524 (147.92 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 100
```