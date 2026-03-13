# Server Metrics 2026-03-13 00:16:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 65892.2 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1986509
telemt_connections_bad_total 26106
telemt_handshake_timeouts_total 21378
telemt_upstream_connect_attempt_total 13112
telemt_upstream_connect_success_total 13036
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1242
telemt_me_reconnect_attempts_total 18575
telemt_me_reconnect_success_total 9716
telemt_me_reader_eof_total 10513
telemt_me_idle_close_by_peer_total 10512
telemt_me_route_drop_no_conn_total 774306
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1847696
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8648
telemt_desync_full_logged_total 2255
telemt_desync_suppressed_total 6393
telemt_desync_frames_bucket_total{bucket="1_2"} 2278
telemt_desync_frames_bucket_total{bucket="3_10"} 3118
telemt_desync_frames_bucket_total{bucket="gt_10"} 3252
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10130
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9703
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 1847157
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 27425340368 (25.54 GB)
telemt_user_octets_to_client{user="hello"} 652318035536 (607.52 GB)
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 95512.8 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 819776
telemt_connections_bad_total 11751
telemt_handshake_timeouts_total 31726
telemt_upstream_connect_attempt_total 24287
telemt_upstream_connect_success_total 24258
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3434
telemt_me_reconnect_attempts_total 17927
telemt_me_reconnect_success_total 17827
telemt_me_reader_eof_total 18975
telemt_me_idle_close_by_peer_total 18975
telemt_me_route_drop_no_conn_total 264927
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 741953
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3038
telemt_desync_full_logged_total 950
telemt_desync_suppressed_total 2088
telemt_desync_frames_bucket_total{bucket="1_2"} 1219
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18002
telemt_me_writer_restored_same_endpoint_total 17818
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 743833
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 12175069668 (11.34 GB)
telemt_user_octets_to_client{user="hello"} 284898769115 (265.33 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 95512.6 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1706852
telemt_connections_bad_total 8369
telemt_handshake_timeouts_total 113458
telemt_upstream_connect_attempt_total 22218
telemt_upstream_connect_success_total 22208
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1572
telemt_me_reconnect_attempts_total 18326
telemt_me_reconnect_success_total 17066
telemt_me_reader_eof_total 18063
telemt_me_idle_close_by_peer_total 18062
telemt_me_route_drop_no_conn_total 559868
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1338655
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
telemt_me_writer_removed_unexpected_total 17228
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17025
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 1338258
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 19922407596 (18.55 GB)
telemt_user_octets_to_client{user="hello"} 488845036237 (455.27 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 95512.8 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1061747
telemt_connections_bad_total 13033
telemt_handshake_timeouts_total 71720
telemt_upstream_connect_attempt_total 33457
telemt_upstream_connect_success_total 31195
telemt_upstream_connect_fail_total 2125
telemt_upstream_connect_attempts_per_request{bucket="1"} 33183
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2124
telemt_me_keepalive_timeout_total 11257
telemt_me_reconnect_attempts_total 28387
telemt_me_reconnect_success_total 20549
telemt_me_reader_eof_total 22246
telemt_me_idle_close_by_peer_total 22239
telemt_me_route_drop_no_conn_total 375377
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 914982
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
telemt_me_writer_removed_unexpected_total 20919
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20527
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 920174
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 14370384129 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 365326297894 (340.24 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 95512.7 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1175891
telemt_connections_bad_total 12574
telemt_handshake_timeouts_total 9298
telemt_upstream_connect_attempt_total 28853
telemt_upstream_connect_success_total 28490
telemt_upstream_connect_fail_total 363
telemt_upstream_connect_attempts_per_request{bucket="1"} 28853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 363
telemt_me_keepalive_timeout_total 1825
telemt_me_reconnect_attempts_total 34751
telemt_me_reconnect_success_total 23709
telemt_me_reader_eof_total 24966
telemt_me_idle_close_by_peer_total 24966
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 439763
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1084904
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4078
telemt_desync_full_logged_total 1435
telemt_desync_suppressed_total 2643
telemt_desync_frames_bucket_total{bucket="1_2"} 1193
telemt_desync_frames_bucket_total{bucket="3_10"} 1363
telemt_desync_frames_bucket_total{bucket="gt_10"} 1522
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 24329
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23664
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 1084761
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 13602900620 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 380049402656 (353.95 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 104
```