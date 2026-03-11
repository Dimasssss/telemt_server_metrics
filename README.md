# Server Metrics 2026-03-11 23:42:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7037.3 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63808
telemt_connections_bad_total 1041
telemt_handshake_timeouts_total 204
telemt_upstream_connect_attempt_total 1702
telemt_upstream_connect_success_total 1702
telemt_upstream_connect_attempts_per_request{bucket="1"} 1702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1331
telemt_me_reconnect_success_total 1327
telemt_me_reader_eof_total 1379
telemt_me_idle_close_by_peer_total 1379
telemt_me_route_drop_no_conn_total 23809
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59683
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 149
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1346
telemt_me_writer_restored_same_endpoint_total 1311
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 59646
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 409583644 (390.61 MB)
telemt_user_octets_to_client{user="hello"} 16323521308 (15.20 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 7038.2 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22559
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 197
telemt_upstream_connect_attempt_total 1984
telemt_upstream_connect_success_total 1984
telemt_upstream_connect_attempts_per_request{bucket="1"} 1984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1032
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 1608
telemt_me_reconnect_success_total 1597
telemt_me_reader_eof_total 1669
telemt_me_idle_close_by_peer_total 1669
telemt_me_route_drop_no_conn_total 5969
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21486
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1604
telemt_me_writer_restored_same_endpoint_total 1588
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 21484
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 547144628 (521.80 MB)
telemt_user_octets_to_client{user="hello"} 9696683208 (9.03 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 7038.0 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59417
telemt_connections_bad_total 540
telemt_handshake_timeouts_total 4239
telemt_upstream_connect_attempt_total 2557
telemt_upstream_connect_success_total 2555
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1859
telemt_me_reconnect_success_total 1816
telemt_me_reader_eof_total 1794
telemt_me_idle_close_by_peer_total 1794
telemt_me_route_drop_no_conn_total 10336
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35284
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 50
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1743
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1775
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 35632
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 466308616 (444.71 MB)
telemt_user_octets_to_client{user="hello"} 18893670485 (17.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 7038.4 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33658
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 512
telemt_upstream_connect_attempt_total 2125
telemt_upstream_connect_success_total 2113
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1738
telemt_me_reconnect_success_total 1729
telemt_me_reader_eof_total 1784
telemt_me_idle_close_by_peer_total 1784
telemt_me_route_drop_no_conn_total 10542
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32606
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1737
telemt_me_writer_restored_same_endpoint_total 1708
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 32602
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 173871576 (165.82 MB)
telemt_user_octets_to_client{user="hello"} 10988427072 (10.23 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7038.1 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43850
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 476
telemt_upstream_connect_attempt_total 3170
telemt_upstream_connect_success_total 3141
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 4238
telemt_me_reconnect_success_total 2752
telemt_me_reader_eof_total 2821
telemt_me_idle_close_by_peer_total 2821
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 9999
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40817
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 68
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2810
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 2747
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 40813
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 233817308 (222.99 MB)
telemt_user_octets_to_client{user="hello"} 11673216052 (10.87 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 24
```