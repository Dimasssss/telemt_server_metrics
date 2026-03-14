# Server Metrics 2026-03-14 15:57:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 9618.1 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 374703
telemt_connections_bad_total 13993
telemt_handshake_timeouts_total 4466
telemt_upstream_connect_attempt_total 2050
telemt_upstream_connect_success_total 2042
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 2297
telemt_me_reconnect_success_total 1511
telemt_me_reader_eof_total 1564
telemt_me_idle_close_by_peer_total 1564
telemt_me_route_drop_no_conn_total 147871
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341342
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1059
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 740
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1554
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1502
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 341342
telemt_user_connections_current{user="hello"} 1694
telemt_user_octets_from_client{user="hello"} 5882405956 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 103960893360 (96.82 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 9623.4 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155235
telemt_connections_bad_total 14723
telemt_handshake_timeouts_total 5277
telemt_upstream_connect_attempt_total 2079
telemt_upstream_connect_success_total 2054
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 2079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 814
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 264
telemt_me_reconnect_attempts_total 2295
telemt_me_reconnect_success_total 1520
telemt_me_reader_eof_total 1574
telemt_me_idle_close_by_peer_total 1574
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 47787
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123937
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 527
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1584
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1506
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 123877
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 1623579028 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 51498128024 (47.96 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 9486.2 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314738
telemt_connections_bad_total 1047
telemt_handshake_timeouts_total 76888
telemt_upstream_connect_attempt_total 2053
telemt_upstream_connect_success_total 2045
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 5417
telemt_me_reconnect_success_total 1521
telemt_me_reader_eof_total 1651
telemt_me_idle_close_by_peer_total 1651
telemt_me_route_drop_no_conn_total 80087
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216143
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 387
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 281
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1644
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1488
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 216045
telemt_user_connections_current{user="hello"} 1032
telemt_user_octets_from_client{user="hello"} 3013400436 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 83127925716 (77.42 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 9340.8 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163476
telemt_connections_bad_total 33855
telemt_handshake_timeouts_total 27080
telemt_upstream_connect_attempt_total 2367
telemt_upstream_connect_success_total 2366
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1092
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1863
telemt_me_reconnect_success_total 1850
telemt_me_reader_eof_total 1897
telemt_me_idle_close_by_peer_total 1897
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 36273
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100517
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 204
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1859
telemt_me_writer_restored_same_endpoint_total 1848
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 100484
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 1772599652 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 33199058196 (30.92 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 9636.4 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148508
telemt_connections_bad_total 341
telemt_handshake_timeouts_total 2037
telemt_upstream_connect_attempt_total 2236
telemt_upstream_connect_success_total 2186
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 2236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2327
telemt_me_reconnect_success_total 1664
telemt_me_reader_eof_total 1742
telemt_me_idle_close_by_peer_total 1742
telemt_me_route_drop_no_conn_total 50055
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137493
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 434
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1724
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1646
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 137496
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 2033125088 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 50967925768 (47.47 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 124
```