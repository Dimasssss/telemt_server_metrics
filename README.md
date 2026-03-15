# Server Metrics 2026-03-15 00:13:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 7153.0 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94771
telemt_connections_bad_total 1138
telemt_handshake_timeouts_total 408
telemt_upstream_connect_attempt_total 1486
telemt_upstream_connect_success_total 1480
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1116
telemt_me_reconnect_success_total 1110
telemt_me_reader_eof_total 1153
telemt_me_idle_close_by_peer_total 1153
telemt_me_route_drop_no_conn_total 30466
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86327
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 250
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1126
telemt_me_writer_restored_same_endpoint_total 1099
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 86319
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 984664804 (939.05 MB)
telemt_user_octets_to_client{user="hello"} 31839159100 (29.65 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 7153.5 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37465
telemt_connections_bad_total 5675
telemt_handshake_timeouts_total 1987
telemt_upstream_connect_attempt_total 2341
telemt_upstream_connect_success_total 2327
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1658
telemt_me_reconnect_success_total 1645
telemt_me_reader_eof_total 1681
telemt_me_idle_close_by_peer_total 1681
telemt_me_route_drop_no_conn_total 7719
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28429
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1611
telemt_me_writer_restored_same_endpoint_total 1637
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 28725
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 1299458335 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 6646780888 (6.19 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 7153.8 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62350
telemt_connections_bad_total 1032
telemt_handshake_timeouts_total 4272
telemt_upstream_connect_attempt_total 1584
telemt_upstream_connect_success_total 1575
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1207
telemt_me_reconnect_success_total 1204
telemt_me_reader_eof_total 1249
telemt_me_idle_close_by_peer_total 1249
telemt_me_route_drop_no_conn_total 15123
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55826
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
telemt_me_writer_removed_unexpected_total 1215
telemt_me_writer_restored_same_endpoint_total 1185
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 55746
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 703216032 (670.64 MB)
telemt_user_octets_to_client{user="hello"} 15915671624 (14.82 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 7153.7 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60564
telemt_connections_bad_total 18669
telemt_handshake_timeouts_total 909
telemt_upstream_connect_attempt_total 2403
telemt_upstream_connect_success_total 2337
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 2403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3264
telemt_me_reconnect_success_total 1961
telemt_me_reader_eof_total 2033
telemt_me_idle_close_by_peer_total 2033
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 9607
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39901
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 66
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2014
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 1947
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 39904
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 270539680 (258.01 MB)
telemt_user_octets_to_client{user="hello"} 9645863628 (8.98 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 7154.3 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34498
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 599
telemt_upstream_connect_attempt_total 1488
telemt_upstream_connect_success_total 1483
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1118
telemt_me_reconnect_success_total 1112
telemt_me_reader_eof_total 1156
telemt_me_idle_close_by_peer_total 1156
telemt_me_route_drop_no_conn_total 8566
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33086
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
telemt_me_writer_removed_unexpected_total 1124
telemt_me_writer_restored_same_endpoint_total 1104
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 33086
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 280599672 (267.60 MB)
telemt_user_octets_to_client{user="hello"} 15058132444 (14.02 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 28
```