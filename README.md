# Server Metrics 2026-03-15 01:19:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 11120.6 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140560
telemt_connections_bad_total 1605
telemt_handshake_timeouts_total 504
telemt_upstream_connect_attempt_total 2380
telemt_upstream_connect_success_total 2371
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1792
telemt_me_reconnect_success_total 1782
telemt_me_reader_eof_total 1873
telemt_me_idle_close_by_peer_total 1873
telemt_me_route_drop_no_conn_total 43860
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122860
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 308
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 224
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1806
telemt_me_writer_restored_same_endpoint_total 1771
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 122847
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 1421775972 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 42193632688 (39.30 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 11121.1 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57500
telemt_connections_bad_total 10371
telemt_handshake_timeouts_total 2256
telemt_upstream_connect_attempt_total 3380
telemt_upstream_connect_success_total 3362
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2477
telemt_me_reconnect_success_total 2461
telemt_me_reader_eof_total 2565
telemt_me_idle_close_by_peer_total 2565
telemt_me_route_drop_no_conn_total 11576
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43227
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 99
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2434
telemt_me_writer_restored_same_endpoint_total 2453
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 43523
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1476918707 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 12318188440 (11.47 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 11121.4 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92751
telemt_connections_bad_total 1788
telemt_handshake_timeouts_total 7807
telemt_upstream_connect_attempt_total 2553
telemt_upstream_connect_success_total 2542
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1959
telemt_me_reconnect_success_total 1952
telemt_me_reader_eof_total 2051
telemt_me_idle_close_by_peer_total 2051
telemt_me_route_drop_no_conn_total 21116
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 185
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1971
telemt_me_writer_restored_same_endpoint_total 1933
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 81396
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 850663836 (811.26 MB)
telemt_user_octets_to_client{user="hello"} 28644847716 (26.68 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 11121.3 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86162
telemt_connections_bad_total 24511
telemt_handshake_timeouts_total 1841
telemt_upstream_connect_attempt_total 4060
telemt_upstream_connect_success_total 3965
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 4060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4677
telemt_me_reconnect_success_total 3371
telemt_me_reader_eof_total 3490
telemt_me_idle_close_by_peer_total 3490
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 15603
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58401
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3441
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 3354
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 58403
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 342092012 (326.24 MB)
telemt_user_octets_to_client{user="hello"} 11550987892 (10.76 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 11121.7 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49921
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 677
telemt_upstream_connect_attempt_total 2437
telemt_upstream_connect_success_total 2425
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1844
telemt_me_reconnect_success_total 1836
telemt_me_reader_eof_total 1937
telemt_me_idle_close_by_peer_total 1937
telemt_me_route_drop_no_conn_total 12250
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47821
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 184
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1853
telemt_me_writer_restored_same_endpoint_total 1828
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 47821
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 350736036 (334.49 MB)
telemt_user_octets_to_client{user="hello"} 17755377452 (16.54 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 27
```