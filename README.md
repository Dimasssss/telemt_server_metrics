# Server Metrics 2026-03-15 00:39:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 8679.1 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115311
telemt_connections_bad_total 1324
telemt_handshake_timeouts_total 454
telemt_upstream_connect_attempt_total 1832
telemt_upstream_connect_success_total 1824
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1374
telemt_me_reconnect_success_total 1366
telemt_me_reader_eof_total 1426
telemt_me_idle_close_by_peer_total 1426
telemt_me_route_drop_no_conn_total 36389
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100664
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 268
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1385
telemt_me_writer_restored_same_endpoint_total 1355
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 100656
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 1055466012 (1006.57 MB)
telemt_user_octets_to_client{user="hello"} 35243893052 (32.82 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 8679.6 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45362
telemt_connections_bad_total 7427
telemt_handshake_timeouts_total 2048
telemt_upstream_connect_attempt_total 2753
telemt_upstream_connect_success_total 2737
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1186
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 1981
telemt_me_reconnect_success_total 1965
telemt_me_reader_eof_total 2029
telemt_me_idle_close_by_peer_total 2029
telemt_me_route_drop_no_conn_total 9314
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34396
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
telemt_me_writer_removed_unexpected_total 1933
telemt_me_writer_restored_same_endpoint_total 1957
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 34692
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 1356362299 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 7852515536 (7.31 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 8679.8 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73090
telemt_connections_bad_total 1454
telemt_handshake_timeouts_total 5060
telemt_upstream_connect_attempt_total 1961
telemt_upstream_connect_success_total 1951
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1497
telemt_me_reconnect_success_total 1493
telemt_me_reader_eof_total 1559
telemt_me_idle_close_by_peer_total 1559
telemt_me_route_drop_no_conn_total 17411
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65222
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1508
telemt_me_writer_restored_same_endpoint_total 1474
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 65141
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 739145908 (704.90 MB)
telemt_user_octets_to_client{user="hello"} 17423858596 (16.23 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 8679.7 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70396
telemt_connections_bad_total 20764
telemt_handshake_timeouts_total 942
telemt_upstream_connect_attempt_total 3089
telemt_upstream_connect_success_total 3007
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 3089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3848
telemt_me_reconnect_success_total 2544
telemt_me_reader_eof_total 2624
telemt_me_idle_close_by_peer_total 2624
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 11721
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47481
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
telemt_me_writer_removed_unexpected_total 2605
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2530
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 47484
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 291557220 (278.05 MB)
telemt_user_octets_to_client{user="hello"} 10417308060 (9.70 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 8680.4 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39625
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 645
telemt_upstream_connect_attempt_total 1859
telemt_upstream_connect_success_total 1853
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1401
telemt_me_reconnect_success_total 1394
telemt_me_reader_eof_total 1461
telemt_me_idle_close_by_peer_total 1461
telemt_me_route_drop_no_conn_total 10122
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38025
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
telemt_me_writer_removed_unexpected_total 1406
telemt_me_writer_restored_same_endpoint_total 1386
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 38025
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 301367080 (287.41 MB)
telemt_user_octets_to_client{user="hello"} 15880016872 (14.79 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 22
```