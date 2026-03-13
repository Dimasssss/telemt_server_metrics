# Server Metrics 2026-03-13 00:21:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 66198.0 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1990185
telemt_connections_bad_total 26106
telemt_handshake_timeouts_total 21390
telemt_upstream_connect_attempt_total 13160
telemt_upstream_connect_success_total 13084
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1242
telemt_me_reconnect_attempts_total 18623
telemt_me_reconnect_success_total 9764
telemt_me_reader_eof_total 10561
telemt_me_idle_close_by_peer_total 10560
telemt_me_route_drop_no_conn_total 775995
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1851290
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8658
telemt_desync_full_logged_total 2256
telemt_desync_suppressed_total 6402
telemt_desync_frames_bucket_total{bucket="1_2"} 2286
telemt_desync_frames_bucket_total{bucket="3_10"} 3119
telemt_desync_frames_bucket_total{bucket="gt_10"} 3253
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10178
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9751
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 1850751
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 27444512504 (25.56 GB)
telemt_user_octets_to_client{user="hello"} 653310146316 (608.44 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 95818.7 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820985
telemt_connections_bad_total 11751
telemt_handshake_timeouts_total 31758
telemt_upstream_connect_attempt_total 24377
telemt_upstream_connect_success_total 24348
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3435
telemt_me_reconnect_attempts_total 18017
telemt_me_reconnect_success_total 17918
telemt_me_reader_eof_total 19076
telemt_me_idle_close_by_peer_total 19076
telemt_me_route_drop_no_conn_total 265442
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743121
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3039
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 2088
telemt_desync_frames_bucket_total{bucket="1_2"} 1220
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18092
telemt_me_writer_restored_same_endpoint_total 17909
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 745001
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 12178749256 (11.34 GB)
telemt_user_octets_to_client{user="hello"} 285081245747 (265.50 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 95818.5 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1709417
telemt_connections_bad_total 8387
telemt_handshake_timeouts_total 113475
telemt_upstream_connect_attempt_total 22283
telemt_upstream_connect_success_total 22273
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1574
telemt_me_reconnect_attempts_total 18391
telemt_me_reconnect_success_total 17131
telemt_me_reader_eof_total 18141
telemt_me_idle_close_by_peer_total 18140
telemt_me_route_drop_no_conn_total 560899
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1341155
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4975
telemt_desync_full_logged_total 1527
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 17295
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17090
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 1340758
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 19931880388 (18.56 GB)
telemt_user_octets_to_client{user="hello"} 489232681025 (455.63 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 95818.7 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1065335
telemt_connections_bad_total 13034
telemt_handshake_timeouts_total 71745
telemt_upstream_connect_attempt_total 33556
telemt_upstream_connect_success_total 31294
telemt_upstream_connect_fail_total 2125
telemt_upstream_connect_attempts_per_request{bucket="1"} 33282
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2124
telemt_me_keepalive_timeout_total 11260
telemt_me_reconnect_attempts_total 28486
telemt_me_reconnect_success_total 20648
telemt_me_reader_eof_total 22354
telemt_me_idle_close_by_peer_total 22347
telemt_me_route_drop_no_conn_total 376481
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916627
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1892
telemt_desync_full_logged_total 627
telemt_desync_suppressed_total 1265
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 21018
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20626
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 921819
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 14375015697 (13.39 GB)
telemt_user_octets_to_client{user="hello"} 365706498806 (340.59 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 95818.7 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1178130
telemt_connections_bad_total 12575
telemt_handshake_timeouts_total 9303
telemt_upstream_connect_attempt_total 28989
telemt_upstream_connect_success_total 28626
telemt_upstream_connect_fail_total 363
telemt_upstream_connect_attempts_per_request{bucket="1"} 28989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 363
telemt_me_keepalive_timeout_total 1826
telemt_me_reconnect_attempts_total 34880
telemt_me_reconnect_success_total 23838
telemt_me_reader_eof_total 25094
telemt_me_idle_close_by_peer_total 25094
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 440824
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1087115
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4086
telemt_desync_full_logged_total 1438
telemt_desync_suppressed_total 2648
telemt_desync_frames_bucket_total{bucket="1_2"} 1200
telemt_desync_frames_bucket_total{bucket="3_10"} 1364
telemt_desync_frames_bucket_total{bucket="gt_10"} 1522
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 24458
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23792
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 1086972
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 13613400760 (12.68 GB)
telemt_user_octets_to_client{user="hello"} 380232830472 (354.12 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 47
```