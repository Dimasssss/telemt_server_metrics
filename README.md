# Server Metrics 2026-03-14 18:00:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 16994.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688048
telemt_connections_bad_total 37955
telemt_handshake_timeouts_total 9182
telemt_upstream_connect_attempt_total 3356
telemt_upstream_connect_success_total 3342
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 3249
telemt_me_reconnect_success_total 2448
telemt_me_reader_eof_total 2562
telemt_me_idle_close_by_peer_total 2562
telemt_me_route_drop_no_conn_total 262147
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609996
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 605
telemt_desync_suppressed_total 1501
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 792
telemt_desync_frames_bucket_total{bucket="gt_10"} 815
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2512
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2439
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 609929
telemt_user_connections_current{user="hello"} 1854
telemt_user_octets_from_client{user="hello"} 10710336716 (9.97 GB)
telemt_user_octets_to_client{user="hello"} 195161034068 (181.76 GB)
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 17000.2 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271057
telemt_connections_bad_total 22636
telemt_handshake_timeouts_total 8689
telemt_upstream_connect_attempt_total 3512
telemt_upstream_connect_success_total 3471
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 3512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 308
telemt_me_reconnect_attempts_total 3369
telemt_me_reconnect_success_total 2579
telemt_me_reader_eof_total 2697
telemt_me_idle_close_by_peer_total 2697
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 83924
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222394
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 872
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 601
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2661
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2564
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 222335
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 3143583376 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 84036802920 (78.27 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 16863.1 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 570321
telemt_connections_bad_total 1979
telemt_handshake_timeouts_total 114320
telemt_upstream_connect_attempt_total 3364
telemt_upstream_connect_success_total 3355
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 6380
telemt_me_reconnect_success_total 2477
telemt_me_reader_eof_total 2666
telemt_me_idle_close_by_peer_total 2666
telemt_me_route_drop_no_conn_total 138880
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383993
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1190
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 600
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2622
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2444
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 383885
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 5704366248 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 137640563376 (128.19 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 16717.6 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306554
telemt_connections_bad_total 69889
telemt_handshake_timeouts_total 40910
telemt_upstream_connect_attempt_total 4054
telemt_upstream_connect_success_total 4053
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 4096
telemt_me_reconnect_success_total 3181
telemt_me_reader_eof_total 3321
telemt_me_idle_close_by_peer_total 3321
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 68284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 378
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3239
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3174
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 191312
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 2892703612 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 60286976080 (56.15 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 17013.1 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263596
telemt_connections_bad_total 1104
telemt_handshake_timeouts_total 3160
telemt_upstream_connect_attempt_total 3566
telemt_upstream_connect_success_total 3496
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 3566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 3290
telemt_me_reconnect_success_total 2624
telemt_me_reader_eof_total 2759
telemt_me_idle_close_by_peer_total 2759
telemt_me_route_drop_no_conn_total 83998
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243279
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 607
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2697
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2606
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 243289
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 3824641296 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 99258400472 (92.44 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 104
```