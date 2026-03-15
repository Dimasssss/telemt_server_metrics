# Server Metrics 2026-03-15 00:44:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 8984.4 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118812
telemt_connections_bad_total 1348
telemt_handshake_timeouts_total 455
telemt_upstream_connect_attempt_total 1863
telemt_upstream_connect_success_total 1855
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1405
telemt_me_reconnect_success_total 1397
telemt_me_reader_eof_total 1457
telemt_me_idle_close_by_peer_total 1457
telemt_me_route_drop_no_conn_total 37458
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103482
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 277
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1416
telemt_me_writer_restored_same_endpoint_total 1386
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 103474
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 1069421712 (1019.88 MB)
telemt_user_octets_to_client{user="hello"} 36099374592 (33.62 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 8984.9 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46960
telemt_connections_bad_total 7905
telemt_handshake_timeouts_total 2137
telemt_upstream_connect_attempt_total 2794
telemt_upstream_connect_success_total 2778
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2022
telemt_me_reconnect_success_total 2007
telemt_me_reader_eof_total 2070
telemt_me_idle_close_by_peer_total 2070
telemt_me_route_drop_no_conn_total 9650
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35394
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
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1974
telemt_me_writer_restored_same_endpoint_total 1999
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 35690
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1366275351 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 8125885212 (7.57 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 8985.1 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75120
telemt_connections_bad_total 1454
telemt_handshake_timeouts_total 5220
telemt_upstream_connect_attempt_total 2001
telemt_upstream_connect_success_total 1991
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1537
telemt_me_reconnect_success_total 1533
telemt_me_reader_eof_total 1599
telemt_me_idle_close_by_peer_total 1599
telemt_me_route_drop_no_conn_total 18032
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67055
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
telemt_me_writer_removed_unexpected_total 1548
telemt_me_writer_restored_same_endpoint_total 1514
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 66974
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 745497628 (710.96 MB)
telemt_user_octets_to_client{user="hello"} 17537005868 (16.33 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 8984.9 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72149
telemt_connections_bad_total 21239
telemt_handshake_timeouts_total 950
telemt_upstream_connect_attempt_total 3215
telemt_upstream_connect_success_total 3133
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 3215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3974
telemt_me_reconnect_success_total 2670
telemt_me_reader_eof_total 2750
telemt_me_idle_close_by_peer_total 2750
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 12202
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48733
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
telemt_me_writer_removed_unexpected_total 2731
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2656
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 48736
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 293697908 (280.09 MB)
telemt_user_octets_to_client{user="hello"} 10447775096 (9.73 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 8985.8 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40616
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 649
telemt_upstream_connect_attempt_total 1891
telemt_upstream_connect_success_total 1885
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1433
telemt_me_reconnect_success_total 1426
telemt_me_reader_eof_total 1495
telemt_me_idle_close_by_peer_total 1495
telemt_me_route_drop_no_conn_total 10249
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38955
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
telemt_me_writer_removed_unexpected_total 1440
telemt_me_writer_restored_same_endpoint_total 1418
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 38955
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 304994912 (290.87 MB)
telemt_user_octets_to_client{user="hello"} 15946940936 (14.85 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 24
```