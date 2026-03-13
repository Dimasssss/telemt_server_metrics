# Server Metrics 2026-03-13 06:49:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 89455.1 (24h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2420521
telemt_connections_bad_total 36046
telemt_handshake_timeouts_total 25721
telemt_upstream_connect_attempt_total 17536
telemt_upstream_connect_success_total 17438
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 17536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 1327
telemt_me_reconnect_attempts_total 21852
telemt_me_reconnect_success_total 12981
telemt_me_reader_eof_total 14003
telemt_me_idle_close_by_peer_total 14002
telemt_me_route_drop_no_conn_total 915878
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2226719
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10012
telemt_desync_full_logged_total 2576
telemt_desync_suppressed_total 7436
telemt_desync_frames_bucket_total{bucket="1_2"} 2557
telemt_desync_frames_bucket_total{bucket="3_10"} 3685
telemt_desync_frames_bucket_total{bucket="gt_10"} 3770
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 13439
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12968
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 2226229
telemt_user_connections_current{user="hello"} 1438
telemt_user_octets_from_client{user="hello"} 32097537508 (29.89 GB)
telemt_user_octets_to_client{user="hello"} 755286827848 (703.42 GB)
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 119075.8 (33h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 971276
telemt_connections_bad_total 12552
telemt_handshake_timeouts_total 41613
telemt_upstream_connect_attempt_total 29945
telemt_upstream_connect_success_total 29914
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3577
telemt_me_reconnect_attempts_total 22462
telemt_me_reconnect_success_total 22343
telemt_me_reader_eof_total 23828
telemt_me_idle_close_by_peer_total 23828
telemt_me_route_drop_no_conn_total 309802
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 877978
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3683
telemt_desync_full_logged_total 1144
telemt_desync_suppressed_total 2539
telemt_desync_frames_bucket_total{bucket="1_2"} 1410
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 1079
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22564
telemt_me_writer_restored_same_endpoint_total 22334
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 879893
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 13712169416 (12.77 GB)
telemt_user_octets_to_client{user="hello"} 333168591203 (310.29 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 119075.6 (33h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2003375
telemt_connections_bad_total 22829
telemt_handshake_timeouts_total 134947
telemt_upstream_connect_attempt_total 27547
telemt_upstream_connect_success_total 27537
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1688
telemt_me_reconnect_attempts_total 22526
telemt_me_reconnect_success_total 21252
telemt_me_reader_eof_total 22513
telemt_me_idle_close_by_peer_total 22512
telemt_me_route_drop_no_conn_total 641271
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1580704
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5435
telemt_desync_full_logged_total 1654
telemt_desync_suppressed_total 3781
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 1974
telemt_desync_frames_bucket_total{bucket="gt_10"} 2566
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 21456
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21211
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 1580199
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 26829095644 (24.99 GB)
telemt_user_octets_to_client{user="hello"} 562995609557 (524.33 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 119075.8 (33h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221765
telemt_connections_bad_total 14042
telemt_handshake_timeouts_total 78704
telemt_upstream_connect_attempt_total 40359
telemt_upstream_connect_success_total 38067
telemt_upstream_connect_fail_total 2155
telemt_upstream_connect_attempts_per_request{bucket="1"} 40085
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2154
telemt_me_keepalive_timeout_total 11422
telemt_me_reconnect_attempts_total 35206
telemt_me_reconnect_success_total 26270
telemt_me_reader_eof_total 28319
telemt_me_idle_close_by_peer_total 28312
telemt_me_route_drop_no_conn_total 437326
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1051248
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2082
telemt_desync_full_logged_total 674
telemt_desync_suppressed_total 1408
telemt_desync_frames_bucket_total{bucket="1_2"} 572
telemt_desync_frames_bucket_total{bucket="3_10"} 804
telemt_desync_frames_bucket_total{bucket="gt_10"} 706
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 26731
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26246
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 1056167
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 16261191485 (15.14 GB)
telemt_user_octets_to_client{user="hello"} 420332433674 (391.47 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 119075.6 (33h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1380678
telemt_connections_bad_total 20811
telemt_handshake_timeouts_total 11337
telemt_upstream_connect_attempt_total 37718
telemt_upstream_connect_success_total 37257
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 37718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_timeout_total 2037
telemt_me_reconnect_attempts_total 45064
telemt_me_reconnect_success_total 31327
telemt_me_reader_eof_total 32880
telemt_me_idle_close_by_peer_total 32880
telemt_me_seq_mismatch_total 43
telemt_me_route_drop_no_conn_total 506828
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1272510
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 47
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4583
telemt_desync_full_logged_total 1637
telemt_desync_suppressed_total 2946
telemt_desync_frames_bucket_total{bucket="1_2"} 1390
telemt_desync_frames_bucket_total{bucket="3_10"} 1479
telemt_desync_frames_bucket_total{bucket="gt_10"} 1714
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 32098
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31272
telemt_me_writer_restored_fallback_total 55
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 771
telemt_user_connections_total{user="hello"} 1272350
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 16267683872 (15.15 GB)
telemt_user_octets_to_client{user="hello"} 437059400320 (407.04 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 95
```