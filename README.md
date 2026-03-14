# Server Metrics 2026-03-14 13:24:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 404.0 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18224
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 221
telemt_upstream_connect_attempt_total 100
telemt_upstream_connect_success_total 99
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 33
telemt_me_reconnect_success_total 33
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 5834
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17220
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 24
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_user_connections_total{user="hello"} 17223
telemt_user_connections_current{user="hello"} 1669
telemt_user_octets_from_client{user="hello"} 178958196 (170.67 MB)
telemt_user_octets_to_client{user="hello"} 2900560084 (2.70 GB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 409.4 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9533
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 324
telemt_upstream_connect_attempt_total 148
telemt_upstream_connect_success_total 147
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 82
telemt_me_reconnect_success_total 81
telemt_me_reader_eof_total 46
telemt_me_idle_close_by_peer_total 46
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 2079
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6970
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 67
telemt_me_writer_restored_same_endpoint_total 70
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_user_connections_total{user="hello"} 6932
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 58477080 (55.77 MB)
telemt_user_octets_to_client{user="hello"} 2059849252 (1.92 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 272.1 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8323
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 530
telemt_upstream_connect_attempt_total 112
telemt_upstream_connect_success_total 111
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 46
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 1443
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7272
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 11
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 29
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 7261
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 81818276 (78.03 MB)
telemt_user_octets_to_client{user="hello"} 1534028508 (1.43 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 229166.6 (63h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2690664
telemt_connections_bad_total 23536
telemt_handshake_timeouts_total 358074
telemt_upstream_connect_attempt_total 70412
telemt_upstream_connect_success_total 67902
telemt_upstream_connect_fail_total 2373
telemt_upstream_connect_attempts_per_request{bucket="1"} 70138
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2372
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21025
telemt_me_reconnect_attempts_total 62255
telemt_me_reconnect_success_total 49463
telemt_me_reader_eof_total 52981
telemt_me_idle_close_by_peer_total 52973
telemt_me_route_drop_no_conn_total 887529
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2094649
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4124
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 2768
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 1688
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 196
telemt_me_writer_removed_unexpected_total 50294
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49438
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 831
telemt_user_connections_total{user="hello"} 2101363
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 30932581803 (28.81 GB)
telemt_user_octets_to_client{user="hello"} 745626153350 (694.42 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 422.2 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7294
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 120
telemt_upstream_connect_success_total 117
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 54
telemt_me_reader_eof_total 29
telemt_me_idle_close_by_peer_total 29
telemt_me_route_drop_no_conn_total 1807
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6564
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_restored_same_endpoint_total 36
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_user_connections_total{user="hello"} 6564
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 119743172 (114.20 MB)
telemt_user_octets_to_client{user="hello"} 2882324964 (2.68 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 96
```