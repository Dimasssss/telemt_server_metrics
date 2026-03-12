# Server Metrics 2026-03-12 01:19:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 12849.9 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105520
telemt_connections_bad_total 1343
telemt_handshake_timeouts_total 367
telemt_upstream_connect_attempt_total 3034
telemt_upstream_connect_success_total 3034
telemt_upstream_connect_attempts_per_request{bucket="1"} 3034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2361
telemt_me_reconnect_success_total 2353
telemt_me_reader_eof_total 2480
telemt_me_idle_close_by_peer_total 2480
telemt_me_route_drop_no_conn_total 39187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100316
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2382
telemt_me_writer_restored_same_endpoint_total 2337
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 100206
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 704470464 (671.84 MB)
telemt_user_octets_to_client{user="hello"} 28271344384 (26.33 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 12850.7 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36284
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 403
telemt_upstream_connect_attempt_total 3798
telemt_upstream_connect_success_total 3795
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 2940
telemt_me_reconnect_success_total 2918
telemt_me_reader_eof_total 3088
telemt_me_idle_close_by_peer_total 3088
telemt_me_route_drop_no_conn_total 10149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34362
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2938
telemt_me_writer_restored_same_endpoint_total 2909
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 34541
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 616429835 (587.87 MB)
telemt_user_octets_to_client{user="hello"} 12409576858 (11.56 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 12850.5 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122220
telemt_connections_bad_total 903
telemt_handshake_timeouts_total 10336
telemt_upstream_connect_attempt_total 4168
telemt_upstream_connect_success_total 4166
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1744
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 3168
telemt_me_reconnect_success_total 3119
telemt_me_reader_eof_total 3199
telemt_me_idle_close_by_peer_total 3199
telemt_me_route_drop_no_conn_total 19738
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61078
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3060
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3078
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 61423
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 604203072 (576.21 MB)
telemt_user_octets_to_client{user="hello"} 23380485125 (21.77 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 12850.9 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56874
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 1170
telemt_upstream_connect_attempt_total 3950
telemt_upstream_connect_success_total 3930
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 3950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 3254
telemt_me_reconnect_success_total 3243
telemt_me_reader_eof_total 3427
telemt_me_idle_close_by_peer_total 3427
telemt_me_route_drop_no_conn_total 19604
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54819
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3263
telemt_me_writer_restored_same_endpoint_total 3222
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 54813
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 311974140 (297.52 MB)
telemt_user_octets_to_client{user="hello"} 13044825704 (12.15 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12850.6 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72459
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 572
telemt_upstream_connect_attempt_total 5166
telemt_upstream_connect_success_total 5119
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 5166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 5913
telemt_me_reconnect_success_total 4420
telemt_me_reader_eof_total 4571
telemt_me_idle_close_by_peer_total 4571
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 17748
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68407
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 173
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4496
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4412
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 68389
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 316332272 (301.68 MB)
telemt_user_octets_to_client{user="hello"} 15289976908 (14.24 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 26
```