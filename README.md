# Server Metrics 2026-03-13 16:32:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 124416.7 (34h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3930912
telemt_connections_bad_total 37507
telemt_handshake_timeouts_total 92894
telemt_upstream_connect_attempt_total 24133
telemt_upstream_connect_success_total 23995
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 24133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 2240
telemt_me_reconnect_attempts_total 27892
telemt_me_reconnect_success_total 17798
telemt_me_reader_eof_total 19123
telemt_me_idle_close_by_peer_total 19122
telemt_me_route_drop_no_conn_total 1459236
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3594683
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14246
telemt_desync_full_logged_total 3763
telemt_desync_suppressed_total 10483
telemt_desync_frames_bucket_total{bucket="1_2"} 3566
telemt_desync_frames_bucket_total{bucket="3_10"} 5394
telemt_desync_frames_bucket_total{bucket="gt_10"} 5286
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18357
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17785
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 559
telemt_user_connections_total{user="hello"} 3594489
telemt_user_connections_current{user="hello"} 1682
telemt_user_octets_from_client{user="hello"} 50626119972 (47.15 GB)
telemt_user_octets_to_client{user="hello"} 1122585985856 (1.02 TB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24080.7 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353472
telemt_connections_bad_total 23567
telemt_handshake_timeouts_total 9865
telemt_upstream_connect_attempt_total 5692
telemt_upstream_connect_success_total 5604
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 5692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 6659
telemt_me_reconnect_success_total 4363
telemt_me_reader_eof_total 4609
telemt_me_idle_close_by_peer_total 4608
telemt_me_route_drop_no_conn_total 127515
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311239
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1125
telemt_desync_full_logged_total 291
telemt_desync_suppressed_total 834
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4491
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 4356
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 311269
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 3099910908 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 88863580580 (82.76 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 154037.2 (42h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2893608
telemt_connections_bad_total 28046
telemt_handshake_timeouts_total 194934
telemt_upstream_connect_attempt_total 34407
telemt_upstream_connect_success_total 34397
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3315
telemt_me_reconnect_attempts_total 28943
telemt_me_reconnect_success_total 26391
telemt_me_reader_eof_total 27987
telemt_me_idle_close_by_peer_total 27986
telemt_me_route_drop_no_conn_total 981179
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2381583
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8382
telemt_desync_full_logged_total 2771
telemt_desync_suppressed_total 5611
telemt_desync_frames_bucket_total{bucket="1_2"} 1352
telemt_desync_frames_bucket_total{bucket="3_10"} 3062
telemt_desync_frames_bucket_total{bucket="gt_10"} 3968
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 26702
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26350
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 2380955
telemt_user_connections_current{user="hello"} 1176
telemt_user_octets_from_client{user="hello"} 38950242868 (36.28 GB)
telemt_user_octets_to_client{user="hello"} 827380845165 (770.56 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 154037.7 (42h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1858338
telemt_connections_bad_total 18166
telemt_handshake_timeouts_total 164972
telemt_upstream_connect_attempt_total 48296
telemt_upstream_connect_success_total 45960
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 48022
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11906
telemt_me_reconnect_attempts_total 41399
telemt_me_reconnect_success_total 32425
telemt_me_reader_eof_total 34827
telemt_me_idle_close_by_peer_total 34820
telemt_me_route_drop_no_conn_total 661321
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1534519
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3074
telemt_desync_full_logged_total 996
telemt_desync_suppressed_total 2078
telemt_desync_frames_bucket_total{bucket="1_2"} 834
telemt_desync_frames_bucket_total{bucket="3_10"} 1274
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 32960
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32401
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 1539220
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 23719721557 (22.09 GB)
telemt_user_octets_to_client{user="hello"} 584493778110 (544.35 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 23473.2 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381843
telemt_connections_bad_total 4162
telemt_handshake_timeouts_total 3428
telemt_upstream_connect_attempt_total 5245
telemt_upstream_connect_success_total 5097
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 5245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 14466
telemt_me_reconnect_success_total 3888
telemt_me_reader_eof_total 4294
telemt_me_idle_close_by_peer_total 4294
telemt_me_route_drop_no_conn_total 149199
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356780
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1183
telemt_desync_full_logged_total 369
telemt_desync_suppressed_total 814
telemt_desync_frames_bucket_total{bucket="1_2"} 397
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4245
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3884
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 357
telemt_user_connections_total{user="hello"} 356755
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 4113559204 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 114826712508 (106.94 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 114
```