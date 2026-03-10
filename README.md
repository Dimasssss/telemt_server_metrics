# Server Metrics 2026-03-10 16:52:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8730.2 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300523
telemt_connections_bad_total 1355
telemt_handshake_timeouts_total 1484
telemt_upstream_connect_attempt_total 1517
telemt_upstream_connect_success_total 1509
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 9167
telemt_me_reconnect_success_total 1030
telemt_me_reader_eof_total 1246
telemt_me_idle_close_by_peer_total 1246
telemt_me_route_drop_no_conn_total 132410
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288098
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1243
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 901
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 450
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1276
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 1024
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 288033
telemt_user_connections_current{user="hello"} 1329
telemt_user_octets_from_client{user="hello"} 3802100884 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 83982957552 (78.22 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 8786.9 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121131
telemt_connections_bad_total 1673
telemt_handshake_timeouts_total 8763
telemt_upstream_connect_attempt_total 1955
telemt_upstream_connect_success_total 1945
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 1482
telemt_me_reconnect_success_total 1471
telemt_me_reader_eof_total 1517
telemt_me_idle_close_by_peer_total 1517
telemt_me_route_drop_no_conn_total 33928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104418
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 537
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 387
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1477
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 104400
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 1243699304 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 27952982864 (26.03 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 8786.8 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232158
telemt_connections_bad_total 695
telemt_handshake_timeouts_total 28154
telemt_upstream_connect_attempt_total 3054
telemt_upstream_connect_success_total 3000
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 3054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1518
telemt_me_reconnect_success_total 1485
telemt_me_reader_eof_total 1543
telemt_me_idle_close_by_peer_total 1543
telemt_me_route_drop_no_conn_total 72293
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183180
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 528
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1510
telemt_me_writer_restored_same_endpoint_total 1474
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 184156
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 2532457293 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 53623328841 (49.94 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 8787.2 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142331
telemt_connections_bad_total 8778
telemt_handshake_timeouts_total 13507
telemt_upstream_connect_attempt_total 2203
telemt_upstream_connect_success_total 2203
telemt_upstream_connect_attempts_per_request{bucket="1"} 2203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1013
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1739
telemt_me_reconnect_success_total 1731
telemt_me_reader_eof_total 1777
telemt_me_idle_close_by_peer_total 1777
telemt_me_route_drop_no_conn_total 47466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113794
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1739
telemt_me_writer_restored_same_endpoint_total 1720
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 113654
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 1792298584 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 29407421560 (27.39 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8787.1 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155504
telemt_connections_bad_total 523
telemt_handshake_timeouts_total 1279
telemt_upstream_connect_attempt_total 2781
telemt_upstream_connect_success_total 2775
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 2299
telemt_me_reconnect_success_total 2284
telemt_me_reader_eof_total 2315
telemt_me_idle_close_by_peer_total 2315
telemt_me_route_drop_no_conn_total 58568
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145275
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 725
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 475
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 319
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2304
telemt_me_writer_restored_same_endpoint_total 2284
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 145217
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 2607265188 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 44392866824 (41.34 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 106
```