# Server Metrics 2026-03-15 00:23:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 7763.6 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102636
telemt_connections_bad_total 1211
telemt_handshake_timeouts_total 433
telemt_upstream_connect_attempt_total 1639
telemt_upstream_connect_success_total 1632
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1225
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1269
telemt_me_idle_close_by_peer_total 1269
telemt_me_route_drop_no_conn_total 32814
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91956
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1235
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 91948
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 1012721252 (965.81 MB)
telemt_user_octets_to_client{user="hello"} 32901306840 (30.64 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 7764.2 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40450
telemt_connections_bad_total 6172
telemt_handshake_timeouts_total 2001
telemt_upstream_connect_attempt_total 2530
telemt_upstream_connect_success_total 2516
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1803
telemt_me_reconnect_success_total 1789
telemt_me_reader_eof_total 1841
telemt_me_idle_close_by_peer_total 1841
telemt_me_route_drop_no_conn_total 8358
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30858
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1755
telemt_me_writer_restored_same_endpoint_total 1781
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 31154
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 1327196455 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 7261297124 (6.76 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 7764.3 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66927
telemt_connections_bad_total 1432
telemt_handshake_timeouts_total 4586
telemt_upstream_connect_attempt_total 1762
telemt_upstream_connect_success_total 1753
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1342
telemt_me_reconnect_success_total 1338
telemt_me_reader_eof_total 1394
telemt_me_idle_close_by_peer_total 1394
telemt_me_route_drop_no_conn_total 15989
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59642
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 118
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1350
telemt_me_writer_restored_same_endpoint_total 1319
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 59561
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 717029700 (683.81 MB)
telemt_user_octets_to_client{user="hello"} 16402452896 (15.28 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 7764.2 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64603
telemt_connections_bad_total 19326
telemt_handshake_timeouts_total 919
telemt_upstream_connect_attempt_total 2687
telemt_upstream_connect_success_total 2612
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 2687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3496
telemt_me_reconnect_success_total 2193
telemt_me_reader_eof_total 2266
telemt_me_idle_close_by_peer_total 2266
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 10506
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43209
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 74
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2247
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2179
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 43212
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 281639852 (268.59 MB)
telemt_user_octets_to_client{user="hello"} 9906959640 (9.23 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 7765.0 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36559
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 618
telemt_upstream_connect_attempt_total 1656
telemt_upstream_connect_success_total 1651
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1243
telemt_me_reconnect_success_total 1236
telemt_me_reader_eof_total 1292
telemt_me_idle_close_by_peer_total 1292
telemt_me_route_drop_no_conn_total 9075
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35066
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1248
telemt_me_writer_restored_same_endpoint_total 1228
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 35066
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 288677792 (275.30 MB)
telemt_user_octets_to_client{user="hello"} 15365702480 (14.31 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 28
```