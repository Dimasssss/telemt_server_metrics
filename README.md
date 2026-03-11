# Server Metrics 2026-03-11 05:05:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 52697.0 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021300
telemt_connections_bad_total 11212
telemt_handshake_timeouts_total 32946
telemt_upstream_connect_attempt_total 11305
telemt_upstream_connect_success_total 11296
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5563
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 20288
telemt_me_reconnect_success_total 8612
telemt_me_reader_eof_total 9378
telemt_me_idle_close_by_peer_total 9378
telemt_me_route_drop_no_conn_total 380596
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 918840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4203
telemt_desync_full_logged_total 1185
telemt_desync_suppressed_total 3018
telemt_desync_frames_bucket_total{bucket="1_2"} 1176
telemt_desync_frames_bucket_total{bucket="3_10"} 1586
telemt_desync_frames_bucket_total{bucket="gt_10"} 1441
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 9053
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8606
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 918547
telemt_user_connections_current{user="hello"} 876
telemt_user_octets_from_client{user="hello"} 12310207268 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 269312642960 (250.82 GB)
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52753.7 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399016
telemt_connections_bad_total 2755
telemt_handshake_timeouts_total 19288
telemt_upstream_connect_attempt_total 19708
telemt_upstream_connect_success_total 16804
telemt_upstream_connect_fail_total 2904
telemt_upstream_connect_attempts_per_request{bucket="1"} 19708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2904
telemt_me_keepalive_timeout_total 1782
telemt_me_reconnect_attempts_total 12024
telemt_me_reconnect_success_total 11204
telemt_me_reader_eof_total 11832
telemt_me_idle_close_by_peer_total 11830
telemt_me_route_drop_no_conn_total 189000
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342840
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11336
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11183
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 345112
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 3306867018 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 82459502528 (76.80 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 52753.6 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679250
telemt_connections_bad_total 5766
telemt_handshake_timeouts_total 37137
telemt_upstream_connect_attempt_total 14270
telemt_upstream_connect_success_total 14084
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 14270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 567
telemt_me_reconnect_attempts_total 21429
telemt_me_reconnect_success_total 10357
telemt_me_reader_eof_total 11200
telemt_me_idle_close_by_peer_total 11200
telemt_me_route_drop_no_conn_total 228777
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605934
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1660
telemt_desync_full_logged_total 494
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 368
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10839
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10346
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 606794
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 7469656381 (6.96 GB)
telemt_user_octets_to_client{user="hello"} 181573548769 (169.10 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 52754.0 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518322
telemt_connections_bad_total 49615
telemt_handshake_timeouts_total 54247
telemt_upstream_connect_attempt_total 15205
telemt_upstream_connect_success_total 15205
telemt_upstream_connect_attempts_per_request{bucket="1"} 15205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 491
telemt_me_reconnect_attempts_total 13597
telemt_me_reconnect_success_total 12555
telemt_me_reader_eof_total 13331
telemt_me_idle_close_by_peer_total 13331
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 153396
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400144
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 848
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 501
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 308
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12700
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12534
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 399783
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 4874420440 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 109541579072 (102.02 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52753.6 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540590
telemt_connections_bad_total 5831
telemt_handshake_timeouts_total 3527
telemt_upstream_connect_attempt_total 15181
telemt_upstream_connect_success_total 15119
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 558
telemt_me_reconnect_attempts_total 16210
telemt_me_reconnect_success_total 12428
telemt_me_reader_eof_total 13122
telemt_me_idle_close_by_peer_total 13122
telemt_me_route_drop_no_conn_total 175524
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 493075
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2422
telemt_desync_full_logged_total 949
telemt_desync_suppressed_total 1473
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1026
telemt_desync_frames_bucket_total{bucket="gt_10"} 504
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 12705
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12428
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 492692
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 8940427892 (8.33 GB)
telemt_user_octets_to_client{user="hello"} 174251449024 (162.28 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 79
```