# Server Metrics 2026-03-13 04:01:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 79351.2 (22h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2168612
telemt_connections_bad_total 28476
telemt_handshake_timeouts_total 23023
telemt_upstream_connect_attempt_total 15711
telemt_upstream_connect_success_total 15623
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 15711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1299
telemt_me_reconnect_attempts_total 20513
telemt_me_reconnect_success_total 11649
telemt_me_reader_eof_total 12579
telemt_me_idle_close_by_peer_total 12578
telemt_me_route_drop_no_conn_total 830297
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1995034
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8868
telemt_desync_full_logged_total 2301
telemt_desync_suppressed_total 6567
telemt_desync_frames_bucket_total{bucket="1_2"} 2337
telemt_desync_frames_bucket_total{bucket="3_10"} 3192
telemt_desync_frames_bucket_total{bucket="gt_10"} 3339
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12088
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11636
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 1994464
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 28884154076 (26.90 GB)
telemt_user_octets_to_client{user="hello"} 686926873944 (639.75 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 108971.6 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 882945
telemt_connections_bad_total 11846
telemt_handshake_timeouts_total 39232
telemt_upstream_connect_attempt_total 27743
telemt_upstream_connect_success_total 27714
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3466
telemt_me_reconnect_attempts_total 20752
telemt_me_reconnect_success_total 20640
telemt_me_reader_eof_total 21991
telemt_me_idle_close_by_peer_total 21991
telemt_me_route_drop_no_conn_total 282151
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 795729
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3136
telemt_desync_full_logged_total 987
telemt_desync_suppressed_total 2149
telemt_desync_frames_bucket_total{bucket="1_2"} 1269
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 847
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 20840
telemt_me_writer_restored_same_endpoint_total 20631
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 797632
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 12719702580 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 308739177475 (287.54 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 108971.6 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1824636
telemt_connections_bad_total 13890
telemt_handshake_timeouts_total 120311
telemt_upstream_connect_attempt_total 25368
telemt_upstream_connect_success_total 25358
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1625
telemt_me_reconnect_attempts_total 20847
telemt_me_reconnect_success_total 19580
telemt_me_reader_eof_total 20741
telemt_me_idle_close_by_peer_total 20740
telemt_me_route_drop_no_conn_total 591543
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1439831
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5106
telemt_desync_full_logged_total 1558
telemt_desync_suppressed_total 3548
telemt_desync_frames_bucket_total{bucket="1_2"} 817
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 2444
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19763
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19539
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 1439446
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 24914406404 (23.20 GB)
telemt_user_octets_to_client{user="hello"} 514881510113 (479.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 108971.9 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1133562
telemt_connections_bad_total 13169
telemt_handshake_timeouts_total 74571
telemt_upstream_connect_attempt_total 37735
telemt_upstream_connect_success_total 35454
telemt_upstream_connect_fail_total 2144
telemt_upstream_connect_attempts_per_request{bucket="1"} 37461
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2143
telemt_me_keepalive_timeout_total 11381
telemt_me_reconnect_attempts_total 33089
telemt_me_reconnect_success_total 24158
telemt_me_reader_eof_total 26075
telemt_me_idle_close_by_peer_total 26068
telemt_me_route_drop_no_conn_total 402353
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 973682
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1925
telemt_desync_full_logged_total 637
telemt_desync_suppressed_total 1288
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 751
telemt_desync_frames_bucket_total{bucket="gt_10"} 636
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 24595
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24134
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 978864
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 14947181309 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 385884843558 (359.38 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 108971.6 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1257611
telemt_connections_bad_total 12869
telemt_handshake_timeouts_total 10092
telemt_upstream_connect_attempt_total 34344
telemt_upstream_connect_success_total 33926
telemt_upstream_connect_fail_total 418
telemt_upstream_connect_attempts_per_request{bucket="1"} 34344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 418
telemt_me_keepalive_timeout_total 1918
telemt_me_reconnect_attempts_total 42236
telemt_me_reconnect_success_total 28504
telemt_me_reader_eof_total 29970
telemt_me_idle_close_by_peer_total 29970
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 467613
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1162991
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4288
telemt_desync_full_logged_total 1534
telemt_desync_suppressed_total 2754
telemt_desync_frames_bucket_total{bucket="1_2"} 1297
telemt_desync_frames_bucket_total{bucket="3_10"} 1403
telemt_desync_frames_bucket_total{bucket="gt_10"} 1588
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 29259
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28454
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 755
telemt_user_connections_total{user="hello"} 1162845
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 14278685012 (13.30 GB)
telemt_user_octets_to_client{user="hello"} 399324260124 (371.90 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 71
```