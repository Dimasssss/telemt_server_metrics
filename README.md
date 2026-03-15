# Server Metrics 2026-03-15 00:08:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 6847.9 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91592
telemt_connections_bad_total 1091
telemt_handshake_timeouts_total 404
telemt_upstream_connect_attempt_total 1457
telemt_upstream_connect_success_total 1451
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1087
telemt_me_reconnect_success_total 1081
telemt_me_reader_eof_total 1124
telemt_me_idle_close_by_peer_total 1124
telemt_me_route_drop_no_conn_total 29364
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83445
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 242
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1097
telemt_me_writer_restored_same_endpoint_total 1070
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 83437
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 965669440 (920.93 MB)
telemt_user_octets_to_client{user="hello"} 30893987632 (28.77 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 6848.3 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36120
telemt_connections_bad_total 5433
telemt_handshake_timeouts_total 1978
telemt_upstream_connect_attempt_total 2274
telemt_upstream_connect_success_total 2260
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1591
telemt_me_reconnect_success_total 1578
telemt_me_reader_eof_total 1614
telemt_me_idle_close_by_peer_total 1614
telemt_me_route_drop_no_conn_total 7335
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27356
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 84
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1544
telemt_me_writer_restored_same_endpoint_total 1570
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 27653
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 1295290767 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 6510233660 (6.06 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 6848.7 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60469
telemt_connections_bad_total 1030
telemt_handshake_timeouts_total 4096
telemt_upstream_connect_attempt_total 1547
telemt_upstream_connect_success_total 1538
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1170
telemt_me_reconnect_success_total 1167
telemt_me_reader_eof_total 1211
telemt_me_idle_close_by_peer_total 1211
telemt_me_route_drop_no_conn_total 14727
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54136
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1177
telemt_me_writer_restored_same_endpoint_total 1148
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 54056
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 684004404 (652.32 MB)
telemt_user_octets_to_client{user="hello"} 15710560128 (14.63 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 6848.5 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54113
telemt_connections_bad_total 14074
telemt_handshake_timeouts_total 900
telemt_upstream_connect_attempt_total 2353
telemt_upstream_connect_success_total 2287
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 2353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3214
telemt_me_reconnect_success_total 1911
telemt_me_reader_eof_total 1984
telemt_me_idle_close_by_peer_total 1984
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 9295
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38095
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1964
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 1898
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 38098
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 265351604 (253.06 MB)
telemt_user_octets_to_client{user="hello"} 9528197468 (8.87 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 6848.9 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33354
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 539
telemt_upstream_connect_attempt_total 1438
telemt_upstream_connect_success_total 1433
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1068
telemt_me_reconnect_success_total 1063
telemt_me_reader_eof_total 1106
telemt_me_idle_close_by_peer_total 1106
telemt_me_route_drop_no_conn_total 8239
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32023
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1074
telemt_me_writer_restored_same_endpoint_total 1055
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 32023
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 259843208 (247.81 MB)
telemt_user_octets_to_client{user="hello"} 14690524476 (13.68 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 29
```