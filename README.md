# Server Metrics 2026-03-15 00:34:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 8373.9 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111079
telemt_connections_bad_total 1282
telemt_handshake_timeouts_total 443
telemt_upstream_connect_attempt_total 1781
telemt_upstream_connect_success_total 1773
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1323
telemt_me_reconnect_success_total 1315
telemt_me_reader_eof_total 1374
telemt_me_idle_close_by_peer_total 1374
telemt_me_route_drop_no_conn_total 35318
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97799
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 257
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1333
telemt_me_writer_restored_same_endpoint_total 1304
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 97791
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 1042173044 (993.89 MB)
telemt_user_octets_to_client{user="hello"} 34502482540 (32.13 GB)
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 8374.4 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43686
telemt_connections_bad_total 6915
telemt_handshake_timeouts_total 2025
telemt_upstream_connect_attempt_total 2697
telemt_upstream_connect_success_total 2681
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 1925
telemt_me_reconnect_success_total 1910
telemt_me_reader_eof_total 1973
telemt_me_idle_close_by_peer_total 1973
telemt_me_route_drop_no_conn_total 9041
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33276
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1877
telemt_me_writer_restored_same_endpoint_total 1902
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 33572
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 1348272287 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 7659389256 (7.13 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 8374.7 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70929
telemt_connections_bad_total 1434
telemt_handshake_timeouts_total 4902
telemt_upstream_connect_attempt_total 1908
telemt_upstream_connect_success_total 1898
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1444
telemt_me_reconnect_success_total 1440
telemt_me_reader_eof_total 1505
telemt_me_idle_close_by_peer_total 1505
telemt_me_route_drop_no_conn_total 16817
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63275
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 126
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1454
telemt_me_writer_restored_same_endpoint_total 1421
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 63194
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 727132832 (693.45 MB)
telemt_user_octets_to_client{user="hello"} 16806196920 (15.65 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 8374.6 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68620
telemt_connections_bad_total 20291
telemt_handshake_timeouts_total 939
telemt_upstream_connect_attempt_total 2947
telemt_upstream_connect_success_total 2865
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 2947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3706
telemt_me_reconnect_success_total 2402
telemt_me_reader_eof_total 2481
telemt_me_idle_close_by_peer_total 2481
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 11426
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46200
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 82
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2462
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2388
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 46203
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 289096776 (275.70 MB)
telemt_user_octets_to_client{user="hello"} 10325419480 (9.62 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 8375.2 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38612
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 638
telemt_upstream_connect_attempt_total 1806
telemt_upstream_connect_success_total 1800
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1348
telemt_me_reconnect_success_total 1341
telemt_me_reader_eof_total 1408
telemt_me_idle_close_by_peer_total 1408
telemt_me_route_drop_no_conn_total 9879
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37045
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1353
telemt_me_writer_restored_same_endpoint_total 1333
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 37045
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 296257024 (282.53 MB)
telemt_user_octets_to_client{user="hello"} 15669924336 (14.59 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 25
```