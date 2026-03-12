# Server Metrics 2026-03-12 00:38:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 10403.0 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88849
telemt_connections_bad_total 1334
telemt_handshake_timeouts_total 251
telemt_upstream_connect_attempt_total 2467
telemt_upstream_connect_success_total 2467
telemt_upstream_connect_attempts_per_request{bucket="1"} 2467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1923
telemt_me_reconnect_success_total 1916
telemt_me_reader_eof_total 2008
telemt_me_idle_close_by_peer_total 2008
telemt_me_route_drop_no_conn_total 32438
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84021
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 198
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1939
telemt_me_writer_restored_same_endpoint_total 1900
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 83954
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 604689564 (576.68 MB)
telemt_user_octets_to_client{user="hello"} 25654710872 (23.89 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10403.6 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31073
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 377
telemt_upstream_connect_attempt_total 3118
telemt_upstream_connect_success_total 3115
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2389
telemt_me_reconnect_success_total 2367
telemt_me_reader_eof_total 2495
telemt_me_idle_close_by_peer_total 2495
telemt_me_route_drop_no_conn_total 8473
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29342
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 35
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2385
telemt_me_writer_restored_same_endpoint_total 2358
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 29521
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 594764415 (567.21 MB)
telemt_user_octets_to_client{user="hello"} 10877211154 (10.13 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 10403.4 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89528
telemt_connections_bad_total 722
telemt_handshake_timeouts_total 7795
telemt_upstream_connect_attempt_total 3473
telemt_upstream_connect_success_total 3471
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1414
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2603
telemt_me_reconnect_success_total 2556
telemt_me_reader_eof_total 2594
telemt_me_idle_close_by_peer_total 2594
telemt_me_route_drop_no_conn_total 15363
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50875
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2493
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2515
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 51219
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 555306292 (529.58 MB)
telemt_user_octets_to_client{user="hello"} 21977202573 (20.47 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 10403.6 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47901
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 688
telemt_upstream_connect_attempt_total 3153
telemt_upstream_connect_success_total 3139
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 2592
telemt_me_reconnect_success_total 2582
telemt_me_reader_eof_total 2706
telemt_me_idle_close_by_peer_total 2706
telemt_me_route_drop_no_conn_total 16005
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46403
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2598
telemt_me_writer_restored_same_endpoint_total 2561
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 46399
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 238930344 (227.86 MB)
telemt_user_octets_to_client{user="hello"} 12107963736 (11.28 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10403.6 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61564
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 534
telemt_upstream_connect_attempt_total 4512
telemt_upstream_connect_success_total 4474
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 4512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 5397
telemt_me_reconnect_success_total 3906
telemt_me_reader_eof_total 4027
telemt_me_idle_close_by_peer_total 4027
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 14907
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57752
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 138
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3974
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3900
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 57734
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 281763368 (268.71 MB)
telemt_user_octets_to_client{user="hello"} 13857580244 (12.91 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 35
```