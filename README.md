# Server Metrics 2026-03-12 23:41:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 63751.9 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1963081
telemt_connections_bad_total 26084
telemt_handshake_timeouts_total 21268
telemt_upstream_connect_attempt_total 12625
telemt_upstream_connect_success_total 12554
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 12625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 620
telemt_me_reconnect_attempts_total 18221
telemt_me_reconnect_success_total 9364
telemt_me_reader_eof_total 10108
telemt_me_idle_close_by_peer_total 10107
telemt_me_route_drop_no_conn_total 763808
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1825070
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8595
telemt_desync_full_logged_total 2243
telemt_desync_suppressed_total 6352
telemt_desync_frames_bucket_total{bucket="1_2"} 2266
telemt_desync_frames_bucket_total{bucket="3_10"} 3094
telemt_desync_frames_bucket_total{bucket="gt_10"} 3235
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9774
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9351
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 1824535
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 27290061008 (25.42 GB)
telemt_user_octets_to_client{user="hello"} 646124801580 (601.75 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93372.4 (25h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 811194
telemt_connections_bad_total 11738
telemt_handshake_timeouts_total 31570
telemt_upstream_connect_attempt_total 23660
telemt_upstream_connect_success_total 23631
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3427
telemt_me_reconnect_attempts_total 17429
telemt_me_reconnect_success_total 17332
telemt_me_reader_eof_total 18445
telemt_me_idle_close_by_peer_total 18445
telemt_me_route_drop_no_conn_total 262138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733681
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3018
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 1201
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17504
telemt_me_writer_restored_same_endpoint_total 17323
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 735561
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 12140461456 (11.31 GB)
telemt_user_octets_to_client{user="hello"} 283693505535 (264.21 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 93372.2 (25h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1688555
telemt_connections_bad_total 8104
telemt_handshake_timeouts_total 113413
telemt_upstream_connect_attempt_total 21689
telemt_upstream_connect_success_total 21683
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1232
telemt_me_reconnect_attempts_total 17928
telemt_me_reconnect_success_total 16674
telemt_me_reader_eof_total 17633
telemt_me_idle_close_by_peer_total 17632
telemt_me_route_drop_no_conn_total 553767
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1321015
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4974
telemt_desync_full_logged_total 1526
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2383
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16835
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16633
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 1320620
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 19817740244 (18.46 GB)
telemt_user_octets_to_client{user="hello"} 485790616909 (452.43 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 93372.3 (25h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046297
telemt_connections_bad_total 13014
telemt_handshake_timeouts_total 71583
telemt_upstream_connect_attempt_total 32931
telemt_upstream_connect_success_total 30672
telemt_upstream_connect_fail_total 2122
telemt_upstream_connect_attempts_per_request{bucket="1"} 32657
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2121
telemt_me_keepalive_timeout_total 11251
telemt_me_reconnect_attempts_total 27993
telemt_me_reconnect_success_total 20154
telemt_me_reader_eof_total 21824
telemt_me_idle_close_by_peer_total 21817
telemt_me_route_drop_no_conn_total 370180
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904117
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 20519
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20132
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 909337
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 14312238797 (13.33 GB)
telemt_user_octets_to_client{user="hello"} 362193770702 (337.32 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93372.4 (25h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1162930
telemt_connections_bad_total 12544
telemt_handshake_timeouts_total 9275
telemt_upstream_connect_attempt_total 28337
telemt_upstream_connect_success_total 27986
telemt_upstream_connect_fail_total 351
telemt_upstream_connect_attempts_per_request{bucket="1"} 28337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 351
telemt_me_keepalive_timeout_total 1462
telemt_me_reconnect_attempts_total 34370
telemt_me_reconnect_success_total 23330
telemt_me_reader_eof_total 24548
telemt_me_idle_close_by_peer_total 24548
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 434209
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1072168
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4041
telemt_desync_full_logged_total 1414
telemt_desync_suppressed_total 2627
telemt_desync_frames_bucket_total{bucket="1_2"} 1178
telemt_desync_frames_bucket_total{bucket="3_10"} 1346
telemt_desync_frames_bucket_total{bucket="gt_10"} 1517
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 23949
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23285
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 619
telemt_user_connections_total{user="hello"} 1072026
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 13533733592 (12.60 GB)
telemt_user_octets_to_client{user="hello"} 377901236064 (351.95 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 38
```