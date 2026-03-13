# Server Metrics 2026-03-13 08:21:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 94968.0 (26h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2649223
telemt_connections_bad_total 36270
telemt_handshake_timeouts_total 29092
telemt_upstream_connect_attempt_total 18470
telemt_upstream_connect_success_total 18369
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 22524
telemt_me_reconnect_success_total 13651
telemt_me_reader_eof_total 14715
telemt_me_idle_close_by_peer_total 14714
telemt_me_route_drop_no_conn_total 987361
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2424067
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10938
telemt_desync_full_logged_total 2823
telemt_desync_suppressed_total 8115
telemt_desync_frames_bucket_total{bucket="1_2"} 2806
telemt_desync_frames_bucket_total{bucket="3_10"} 4094
telemt_desync_frames_bucket_total{bucket="gt_10"} 4038
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14119
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13638
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 2423638
telemt_user_connections_current{user="hello"} 1760
telemt_user_octets_from_client{user="hello"} 34323011044 (31.97 GB)
telemt_user_octets_to_client{user="hello"} 807280633972 (751.84 GB)
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 124588.5 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082758
telemt_connections_bad_total 13534
telemt_handshake_timeouts_total 88190
telemt_upstream_connect_attempt_total 31124
telemt_upstream_connect_success_total 31093
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3632
telemt_me_reconnect_attempts_total 23377
telemt_me_reconnect_success_total 23256
telemt_me_reader_eof_total 24788
telemt_me_idle_close_by_peer_total 24788
telemt_me_route_drop_no_conn_total 333196
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940269
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4166
telemt_desync_full_logged_total 1272
telemt_desync_suppressed_total 2894
telemt_desync_frames_bucket_total{bucket="1_2"} 1541
telemt_desync_frames_bucket_total{bucket="3_10"} 1360
telemt_desync_frames_bucket_total{bucket="gt_10"} 1265
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 23485
telemt_me_writer_restored_same_endpoint_total 23247
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 942194
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 14437363932 (13.45 GB)
telemt_user_octets_to_client{user="hello"} 350433310719 (326.37 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 124588.3 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2118634
telemt_connections_bad_total 23665
telemt_handshake_timeouts_total 142296
telemt_upstream_connect_attempt_total 28640
telemt_upstream_connect_success_total 28630
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1743
telemt_me_reconnect_attempts_total 23360
telemt_me_reconnect_success_total 22079
telemt_me_reader_eof_total 23389
telemt_me_idle_close_by_peer_total 23388
telemt_me_route_drop_no_conn_total 685366
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1685662
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5678
telemt_desync_full_logged_total 1798
telemt_desync_suppressed_total 3880
telemt_desync_frames_bucket_total{bucket="1_2"} 931
telemt_desync_frames_bucket_total{bucket="3_10"} 2075
telemt_desync_frames_bucket_total{bucket="gt_10"} 2672
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 22295
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22038
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 1685126
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 28027524212 (26.10 GB)
telemt_user_octets_to_client{user="hello"} 612415405921 (570.36 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 124588.8 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1343879
telemt_connections_bad_total 14217
telemt_handshake_timeouts_total 83366
telemt_upstream_connect_attempt_total 41685
telemt_upstream_connect_success_total 39384
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41411
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11448
telemt_me_reconnect_attempts_total 36262
telemt_me_reconnect_success_total 27322
telemt_me_reader_eof_total 29427
telemt_me_idle_close_by_peer_total 29420
telemt_me_route_drop_no_conn_total 471874
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1120355
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2175
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1467
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 27793
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27298
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 1125107
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 17004571477 (15.84 GB)
telemt_user_octets_to_client{user="hello"} 450419890406 (419.49 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 124588.6 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1482318
telemt_connections_bad_total 29322
telemt_handshake_timeouts_total 12338
telemt_upstream_connect_attempt_total 39262
telemt_upstream_connect_success_total 38785
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 39262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_keepalive_timeout_total 2135
telemt_me_reconnect_attempts_total 46327
telemt_me_reconnect_success_total 32586
telemt_me_reader_eof_total 34191
telemt_me_idle_close_by_peer_total 34191
telemt_me_seq_mismatch_total 45
telemt_me_route_drop_no_conn_total 543046
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1360171
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 49
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4793
telemt_desync_full_logged_total 1712
telemt_desync_suppressed_total 3081
telemt_desync_frames_bucket_total{bucket="1_2"} 1461
telemt_desync_frames_bucket_total{bucket="3_10"} 1551
telemt_desync_frames_bucket_total{bucket="gt_10"} 1781
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33372
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32529
telemt_me_writer_restored_fallback_total 57
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 786
telemt_user_connections_total{user="hello"} 1359978
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 17337955048 (16.15 GB)
telemt_user_octets_to_client{user="hello"} 470930319440 (438.59 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 109
```