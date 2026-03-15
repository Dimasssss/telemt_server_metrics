# Server Metrics 2026-03-15 08:48:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 38018.2 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 782607
telemt_connections_bad_total 32390
telemt_handshake_timeouts_total 5672
telemt_upstream_connect_attempt_total 7791
telemt_upstream_connect_success_total 7758
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5874
telemt_me_reconnect_success_total 5843
telemt_me_reader_eof_total 6183
telemt_me_idle_close_by_peer_total 6183
telemt_me_route_drop_no_conn_total 253363
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664370
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2049
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1409
telemt_desync_frames_bucket_total{bucket="1_2"} 455
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 852
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5921
telemt_me_writer_restored_same_endpoint_total 5832
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 664364
telemt_user_connections_current{user="hello"} 1873
telemt_user_octets_from_client{user="hello"} 8915016872 (8.30 GB)
telemt_user_octets_to_client{user="hello"} 250222026912 (233.04 GB)
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 38019.2 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309282
telemt_connections_bad_total 18520
telemt_handshake_timeouts_total 12598
telemt_upstream_connect_attempt_total 10223
telemt_upstream_connect_success_total 10172
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4564
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7980
telemt_me_reconnect_success_total 7931
telemt_me_reader_eof_total 8402
telemt_me_idle_close_by_peer_total 8402
telemt_me_route_drop_no_conn_total 78028
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244520
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 916
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 613
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 346
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7996
telemt_me_writer_restored_same_endpoint_total 7923
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 244796
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 3573272543 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 92660929192 (86.30 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 38019.3 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535068
telemt_connections_bad_total 16813
telemt_handshake_timeouts_total 47916
telemt_upstream_connect_attempt_total 8478
telemt_upstream_connect_success_total 8441
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 6556
telemt_me_reconnect_success_total 6513
telemt_me_reader_eof_total 6906
telemt_me_idle_close_by_peer_total 6906
telemt_me_route_drop_no_conn_total 149329
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429665
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 894
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6594
telemt_me_writer_restored_same_endpoint_total 6494
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 429195
telemt_user_connections_current{user="hello"} 1121
telemt_user_octets_from_client{user="hello"} 6337282160 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 177237844868 (165.07 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 38019.0 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335401
telemt_connections_bad_total 50398
telemt_handshake_timeouts_total 22419
telemt_upstream_connect_attempt_total 12197
telemt_upstream_connect_success_total 11912
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 12197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 23627
telemt_me_reconnect_success_total 9992
telemt_me_reader_eof_total 10723
telemt_me_idle_close_by_peer_total 10723
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 88546
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249453
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 597
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 446
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10500
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 9962
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 249459
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 2210578188 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 81588876352 (75.99 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 38020.1 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300090
telemt_connections_bad_total 3739
telemt_handshake_timeouts_total 3345
telemt_upstream_connect_attempt_total 8431
telemt_upstream_connect_success_total 8395
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 8431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 6512
telemt_me_reconnect_success_total 6482
telemt_me_reader_eof_total 6909
telemt_me_idle_close_by_peer_total 6909
telemt_me_route_drop_no_conn_total 83653
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258669
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1019
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 684
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 417
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6546
telemt_me_writer_restored_same_endpoint_total 6474
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 258677
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 2918103208 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 100017331024 (93.15 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 113
```