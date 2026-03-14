# Server Metrics 2026-03-14 15:32:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 8062.0 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314957
telemt_connections_bad_total 9477
telemt_handshake_timeouts_total 3813
telemt_upstream_connect_attempt_total 1701
telemt_upstream_connect_success_total 1693
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 2035
telemt_me_reconnect_success_total 1251
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1286
telemt_me_route_drop_no_conn_total 125457
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288949
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 719
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1290
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1242
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 288939
telemt_user_connections_current{user="hello"} 1648
telemt_user_octets_from_client{user="hello"} 4945733972 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 87504601144 (81.50 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 8067.5 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129261
telemt_connections_bad_total 10659
telemt_handshake_timeouts_total 4761
telemt_upstream_connect_attempt_total 1741
telemt_upstream_connect_success_total 1718
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 678
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 2046
telemt_me_reconnect_success_total 1274
telemt_me_reader_eof_total 1315
telemt_me_idle_close_by_peer_total 1315
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 40216
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104339
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 493
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 363
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1332
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1263
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 104301
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 1397336564 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 43517409420 (40.53 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 7930.4 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257834
telemt_connections_bad_total 881
telemt_handshake_timeouts_total 58040
telemt_upstream_connect_attempt_total 1758
telemt_upstream_connect_success_total 1751
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5210
telemt_me_reconnect_success_total 1318
telemt_me_reader_eof_total 1426
telemt_me_idle_close_by_peer_total 1426
telemt_me_route_drop_no_conn_total 67394
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182981
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 276
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1436
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1285
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 182905
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 2664432672 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 66386064412 (61.83 GB)
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 7784.8 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130366
telemt_connections_bad_total 29897
telemt_handshake_timeouts_total 17701
telemt_upstream_connect_attempt_total 2054
telemt_upstream_connect_success_total 2053
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1636
telemt_me_reconnect_success_total 1626
telemt_me_reader_eof_total 1654
telemt_me_idle_close_by_peer_total 1654
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 29945
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81193
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 158
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1631
telemt_me_writer_restored_same_endpoint_total 1624
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 81166
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 1484597100 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 25404195156 (23.66 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 8080.2 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126183
telemt_connections_bad_total 323
telemt_handshake_timeouts_total 1876
telemt_upstream_connect_attempt_total 1934
telemt_upstream_connect_success_total 1891
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 1934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 2118
telemt_me_reconnect_success_total 1456
telemt_me_reader_eof_total 1508
telemt_me_idle_close_by_peer_total 1508
telemt_me_route_drop_no_conn_total 43110
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116510
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1511
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1438
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 116515
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 1731381052 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 43710935548 (40.71 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 114
```