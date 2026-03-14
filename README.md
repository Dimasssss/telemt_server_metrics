# Server Metrics 2026-03-14 15:47:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 8981.6 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350942
telemt_connections_bad_total 12167
telemt_handshake_timeouts_total 4337
telemt_upstream_connect_attempt_total 1871
telemt_upstream_connect_success_total 1863
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2162
telemt_me_reconnect_success_total 1378
telemt_me_reader_eof_total 1429
telemt_me_idle_close_by_peer_total 1429
telemt_me_route_drop_no_conn_total 139102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320114
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 951
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 352
telemt_desync_frames_bucket_total{bucket="gt_10"} 402
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1419
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1369
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 320111
telemt_user_connections_current{user="hello"} 1720
telemt_user_octets_from_client{user="hello"} 5347626780 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 96463113068 (89.84 GB)
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 8987.0 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144707
telemt_connections_bad_total 13226
telemt_handshake_timeouts_total 4941
telemt_upstream_connect_attempt_total 1906
telemt_upstream_connect_success_total 1883
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 2167
telemt_me_reconnect_success_total 1394
telemt_me_reader_eof_total 1446
telemt_me_idle_close_by_peer_total 1446
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 45131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116528
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 501
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 364
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1454
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1383
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 116470
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 1544454680 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 49265054024 (45.88 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 8849.9 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298657
telemt_connections_bad_total 1036
telemt_handshake_timeouts_total 74372
telemt_upstream_connect_attempt_total 1930
telemt_upstream_connect_success_total 1922
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 5338
telemt_me_reconnect_success_total 1445
telemt_me_reader_eof_total 1567
telemt_me_idle_close_by_peer_total 1567
telemt_me_route_drop_no_conn_total 74745
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202950
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1565
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1412
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 202869
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 2847683428 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 75817424632 (70.61 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 8704.3 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149366
telemt_connections_bad_total 32245
telemt_handshake_timeouts_total 21980
telemt_upstream_connect_attempt_total 2232
telemt_upstream_connect_success_total 2231
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1771
telemt_me_reconnect_success_total 1759
telemt_me_reader_eof_total 1798
telemt_me_idle_close_by_peer_total 1798
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 34045
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92931
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 128
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1767
telemt_me_writer_restored_same_endpoint_total 1757
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 92904
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 1703720716 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 30265943492 (28.19 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 8999.7 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139639
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 1950
telemt_upstream_connect_attempt_total 2105
telemt_upstream_connect_success_total 2058
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 2242
telemt_me_reconnect_success_total 1580
telemt_me_reader_eof_total 1650
telemt_me_idle_close_by_peer_total 1650
telemt_me_route_drop_no_conn_total 47326
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129251
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 394
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1637
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1562
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 129256
telemt_user_connections_current{user="hello"} 775
telemt_user_octets_from_client{user="hello"} 1932631764 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 48162978976 (44.86 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 100
```