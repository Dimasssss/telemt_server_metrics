# Server Metrics 2026-03-15 08:02:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 35262.6 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 669325
telemt_connections_bad_total 26619
telemt_handshake_timeouts_total 4658
telemt_upstream_connect_attempt_total 7320
telemt_upstream_connect_success_total 7291
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 7319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5539
telemt_me_reconnect_success_total 5511
telemt_me_reader_eof_total 5829
telemt_me_idle_close_by_peer_total 5829
telemt_me_route_drop_no_conn_total 210570
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563856
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1600
telemt_desync_full_logged_total 499
telemt_desync_suppressed_total 1101
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 675
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5584
telemt_me_writer_restored_same_endpoint_total 5500
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 563852
telemt_user_connections_current{user="hello"} 2002
telemt_user_octets_from_client{user="hello"} 7108494332 (6.62 GB)
telemt_user_octets_to_client{user="hello"} 211561188688 (197.03 GB)
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 35263.4 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257470
telemt_connections_bad_total 18361
telemt_handshake_timeouts_total 10479
telemt_upstream_connect_attempt_total 9685
telemt_upstream_connect_success_total 9637
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7577
telemt_me_reconnect_success_total 7531
telemt_me_reader_eof_total 7974
telemt_me_idle_close_by_peer_total 7974
telemt_me_route_drop_no_conn_total 65616
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206509
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 763
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 509
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7578
telemt_me_writer_restored_same_endpoint_total 7523
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 206789
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 3131152051 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 76460609772 (71.21 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 35263.6 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451388
telemt_connections_bad_total 13147
telemt_handshake_timeouts_total 41416
telemt_upstream_connect_attempt_total 7887
telemt_upstream_connect_success_total 7852
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 7887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 6097
telemt_me_reconnect_success_total 6061
telemt_me_reader_eof_total 6419
telemt_me_idle_close_by_peer_total 6419
telemt_me_route_drop_no_conn_total 118836
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366499
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 699
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 288
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6133
telemt_me_writer_restored_same_endpoint_total 6042
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 366281
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 5598412124 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 154003964396 (143.43 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 35263.4 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290074
telemt_connections_bad_total 46596
telemt_handshake_timeouts_total 20467
telemt_upstream_connect_attempt_total 11380
telemt_upstream_connect_success_total 11118
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 11380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21973
telemt_me_reconnect_success_total 9335
telemt_me_reader_eof_total 10022
telemt_me_idle_close_by_peer_total 10022
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 73777
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215970
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 399
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 9805
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9309
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 215971
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 1884853668 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 72060899880 (67.11 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 35264.2 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234557
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 2268
telemt_upstream_connect_attempt_total 7823
telemt_upstream_connect_success_total 7791
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 6039
telemt_me_reconnect_success_total 6011
telemt_me_reader_eof_total 6416
telemt_me_idle_close_by_peer_total 6416
telemt_me_route_drop_no_conn_total 69904
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215751
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 617
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6072
telemt_me_writer_restored_same_endpoint_total 6003
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 215770
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 2293955472 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 87243971980 (81.25 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 112
```