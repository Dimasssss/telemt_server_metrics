# Server Metrics 2026-03-13 06:54:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 89761.2 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2432778
telemt_connections_bad_total 36048
telemt_handshake_timeouts_total 25799
telemt_upstream_connect_attempt_total 17573
telemt_upstream_connect_success_total 17475
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 17573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 1327
telemt_me_reconnect_attempts_total 21889
telemt_me_reconnect_success_total 13018
telemt_me_reader_eof_total 14039
telemt_me_idle_close_by_peer_total 14038
telemt_me_route_drop_no_conn_total 919347
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2236276
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10038
telemt_desync_full_logged_total 2585
telemt_desync_suppressed_total 7453
telemt_desync_frames_bucket_total{bucket="1_2"} 2561
telemt_desync_frames_bucket_total{bucket="3_10"} 3697
telemt_desync_frames_bucket_total{bucket="gt_10"} 3780
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 13476
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13005
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 2235808
telemt_user_connections_current{user="hello"} 1441
telemt_user_octets_from_client{user="hello"} 32278827736 (30.06 GB)
telemt_user_octets_to_client{user="hello"} 759210364408 (707.07 GB)
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 119381.7 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 974783
telemt_connections_bad_total 12565
telemt_handshake_timeouts_total 41921
telemt_upstream_connect_attempt_total 29995
telemt_upstream_connect_success_total 29964
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3578
telemt_me_reconnect_attempts_total 22512
telemt_me_reconnect_success_total 22393
telemt_me_reader_eof_total 23878
telemt_me_idle_close_by_peer_total 23878
telemt_me_route_drop_no_conn_total 310793
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 881001
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3706
telemt_desync_full_logged_total 1150
telemt_desync_suppressed_total 2556
telemt_desync_frames_bucket_total{bucket="1_2"} 1418
telemt_desync_frames_bucket_total{bucket="3_10"} 1199
telemt_desync_frames_bucket_total{bucket="gt_10"} 1089
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22614
telemt_me_writer_restored_same_endpoint_total 22384
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 882921
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 13730107984 (12.79 GB)
telemt_user_octets_to_client{user="hello"} 334393943779 (311.43 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 119381.5 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2009745
telemt_connections_bad_total 22997
telemt_handshake_timeouts_total 135590
telemt_upstream_connect_attempt_total 27596
telemt_upstream_connect_success_total 27586
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1694
telemt_me_reconnect_attempts_total 22575
telemt_me_reconnect_success_total 21301
telemt_me_reader_eof_total 22562
telemt_me_idle_close_by_peer_total 22561
telemt_me_route_drop_no_conn_total 643131
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1586140
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5441
telemt_desync_full_logged_total 1660
telemt_desync_suppressed_total 3781
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 1976
telemt_desync_frames_bucket_total{bucket="gt_10"} 2570
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 21505
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21260
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 1585632
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 26868312632 (25.02 GB)
telemt_user_octets_to_client{user="hello"} 566937599053 (528.00 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 119381.9 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1225485
telemt_connections_bad_total 14047
telemt_handshake_timeouts_total 78754
telemt_upstream_connect_attempt_total 40432
telemt_upstream_connect_success_total 38140
telemt_upstream_connect_fail_total 2155
telemt_upstream_connect_attempts_per_request{bucket="1"} 40158
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2154
telemt_me_keepalive_timeout_total 11426
telemt_me_reconnect_attempts_total 35279
telemt_me_reconnect_success_total 26341
telemt_me_reader_eof_total 28391
telemt_me_idle_close_by_peer_total 28384
telemt_me_route_drop_no_conn_total 438492
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1054738
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2088
telemt_desync_full_logged_total 675
telemt_desync_suppressed_total 1413
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 805
telemt_desync_frames_bucket_total{bucket="gt_10"} 707
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 26803
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26317
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 1059660
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 16317202817 (15.20 GB)
telemt_user_octets_to_client{user="hello"} 421336767718 (392.40 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 119381.6 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1384975
telemt_connections_bad_total 21284
telemt_handshake_timeouts_total 11374
telemt_upstream_connect_attempt_total 37820
telemt_upstream_connect_success_total 37359
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 37820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_timeout_total 2043
telemt_me_reconnect_attempts_total 45166
telemt_me_reconnect_success_total 31429
telemt_me_reader_eof_total 32983
telemt_me_idle_close_by_peer_total 32983
telemt_me_seq_mismatch_total 43
telemt_me_route_drop_no_conn_total 508226
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1276159
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 47
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4586
telemt_desync_full_logged_total 1639
telemt_desync_suppressed_total 2947
telemt_desync_frames_bucket_total{bucket="1_2"} 1393
telemt_desync_frames_bucket_total{bucket="3_10"} 1479
telemt_desync_frames_bucket_total{bucket="gt_10"} 1714
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 32201
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31374
telemt_me_writer_restored_fallback_total 55
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 772
telemt_user_connections_total{user="hello"} 1275999
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 16303538856 (15.18 GB)
telemt_user_octets_to_client{user="hello"} 437769023588 (407.70 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 97
```