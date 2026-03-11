# Server Metrics 2026-03-11 23:37:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 6731.2 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61497
telemt_connections_bad_total 1041
telemt_handshake_timeouts_total 202
telemt_upstream_connect_attempt_total 1655
telemt_upstream_connect_success_total 1655
telemt_upstream_connect_attempts_per_request{bucket="1"} 1655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1284
telemt_me_reconnect_success_total 1280
telemt_me_reader_eof_total 1332
telemt_me_idle_close_by_peer_total 1332
telemt_me_route_drop_no_conn_total 23063
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57409
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 145
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1299
telemt_me_writer_restored_same_endpoint_total 1264
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 57376
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 394977460 (376.68 MB)
telemt_user_octets_to_client{user="hello"} 14431587828 (13.44 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 6732.0 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21756
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 189
telemt_upstream_connect_attempt_total 1935
telemt_upstream_connect_success_total 1934
telemt_upstream_connect_attempts_per_request{bucket="1"} 1934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1001
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1559
telemt_me_reconnect_success_total 1547
telemt_me_reader_eof_total 1618
telemt_me_idle_close_by_peer_total 1618
telemt_me_route_drop_no_conn_total 5697
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20721
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
telemt_me_writer_removed_unexpected_total 1553
telemt_me_writer_restored_same_endpoint_total 1538
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 20719
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 533256332 (508.55 MB)
telemt_user_octets_to_client{user="hello"} 9619802128 (8.96 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 6731.8 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55543
telemt_connections_bad_total 540
telemt_handshake_timeouts_total 4049
telemt_upstream_connect_attempt_total 2488
telemt_upstream_connect_success_total 2486
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1790
telemt_me_reconnect_success_total 1747
telemt_me_reader_eof_total 1725
telemt_me_idle_close_by_peer_total 1725
telemt_me_route_drop_no_conn_total 10000
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33895
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
telemt_me_writer_removed_unexpected_total 1674
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1706
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 34243
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 442786108 (422.27 MB)
telemt_user_octets_to_client{user="hello"} 18599097885 (17.32 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 6732.2 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32605
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 512
telemt_upstream_connect_attempt_total 2065
telemt_upstream_connect_success_total 2053
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1678
telemt_me_reconnect_success_total 1669
telemt_me_reader_eof_total 1724
telemt_me_idle_close_by_peer_total 1724
telemt_me_route_drop_no_conn_total 10223
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31556
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1677
telemt_me_writer_restored_same_endpoint_total 1648
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 31555
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 170729816 (162.82 MB)
telemt_user_octets_to_client{user="hello"} 10904975076 (10.16 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6731.9 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42128
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 474
telemt_upstream_connect_attempt_total 3117
telemt_upstream_connect_success_total 3088
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 4185
telemt_me_reconnect_success_total 2699
telemt_me_reader_eof_total 2768
telemt_me_idle_close_by_peer_total 2768
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 9573
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39246
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 62
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2757
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 2694
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 39243
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 230142260 (219.48 MB)
telemt_user_octets_to_client{user="hello"} 11417219524 (10.63 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 44
```