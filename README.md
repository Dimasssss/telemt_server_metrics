# Server Metrics 2026-03-14 15:37:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 8368.5 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326646
telemt_connections_bad_total 10359
telemt_handshake_timeouts_total 4068
telemt_upstream_connect_attempt_total 1812
telemt_upstream_connect_success_total 1804
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 2103
telemt_me_reconnect_success_total 1319
telemt_me_reader_eof_total 1369
telemt_me_idle_close_by_peer_total 1369
telemt_me_route_drop_no_conn_total 129708
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299128
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 805
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 561
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 337
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1359
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1310
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 299121
telemt_user_connections_current{user="hello"} 1533
telemt_user_octets_from_client{user="hello"} 5076601744 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 90737431776 (84.51 GB)
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 8373.9 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133778
telemt_connections_bad_total 11137
telemt_handshake_timeouts_total 4827
telemt_upstream_connect_attempt_total 1841
telemt_upstream_connect_success_total 1818
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 721
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 2102
telemt_me_reconnect_success_total 1330
telemt_me_reader_eof_total 1380
telemt_me_idle_close_by_peer_total 1380
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 41745
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108178
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 497
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 364
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1388
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1319
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 108139
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 1470046204 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 45527863488 (42.40 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 8236.9 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270605
telemt_connections_bad_total 881
telemt_handshake_timeouts_total 63277
telemt_upstream_connect_attempt_total 1850
telemt_upstream_connect_success_total 1842
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5258
telemt_me_reconnect_success_total 1365
telemt_me_reader_eof_total 1478
telemt_me_idle_close_by_peer_total 1478
telemt_me_route_drop_no_conn_total 69796
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189337
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 287
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1483
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1332
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 189258
telemt_user_connections_current{user="hello"} 1005
telemt_user_octets_from_client{user="hello"} 2728248672 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 70268857052 (65.44 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 8091.2 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136588
telemt_connections_bad_total 30669
telemt_handshake_timeouts_total 19453
telemt_upstream_connect_attempt_total 2085
telemt_upstream_connect_success_total 2084
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1667
telemt_me_reconnect_success_total 1657
telemt_me_reader_eof_total 1685
telemt_me_idle_close_by_peer_total 1685
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 31232
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84790
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1662
telemt_me_writer_restored_same_endpoint_total 1655
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 84763
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 1545512648 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 26999276392 (25.15 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 8386.4 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130959
telemt_connections_bad_total 325
telemt_handshake_timeouts_total 1902
telemt_upstream_connect_attempt_total 2053
telemt_upstream_connect_success_total 2006
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 2190
telemt_me_reconnect_success_total 1528
telemt_me_reader_eof_total 1596
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 44638
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121016
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 369
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1583
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1510
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 121021
telemt_user_connections_current{user="hello"} 724
telemt_user_octets_from_client{user="hello"} 1797431524 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 44866463236 (41.79 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 103
```