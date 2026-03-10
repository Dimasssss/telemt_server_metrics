# Server Metrics 2026-03-10 16:37:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7811.5 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273099
telemt_connections_bad_total 1355
telemt_handshake_timeouts_total 1348
telemt_upstream_connect_attempt_total 1382
telemt_upstream_connect_success_total 1374
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 9076
telemt_me_reconnect_success_total 940
telemt_me_reader_eof_total 1148
telemt_me_idle_close_by_peer_total 1148
telemt_me_route_drop_no_conn_total 121263
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261250
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1036
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 753
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_me_writer_removed_unexpected_total 1184
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 934
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 261196
telemt_user_connections_current{user="hello"} 1273
telemt_user_octets_from_client{user="hello"} 3389604804 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 76353568968 (71.11 GB)
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 7868.3 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110320
telemt_connections_bad_total 1670
telemt_handshake_timeouts_total 8405
telemt_upstream_connect_attempt_total 1762
telemt_upstream_connect_success_total 1752
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1333
telemt_me_reconnect_success_total 1323
telemt_me_reader_eof_total 1358
telemt_me_idle_close_by_peer_total 1358
telemt_me_route_drop_no_conn_total 30453
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94296
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1327
telemt_me_writer_restored_same_endpoint_total 1302
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 94278
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 1094261424 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 25771259276 (24.00 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 7868.2 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205277
telemt_connections_bad_total 682
telemt_handshake_timeouts_total 20975
telemt_upstream_connect_attempt_total 2875
telemt_upstream_connect_success_total 2825
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 2875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1386
telemt_me_reconnect_success_total 1354
telemt_me_reader_eof_total 1404
telemt_me_idle_close_by_peer_total 1404
telemt_me_route_drop_no_conn_total 65299
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165039
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 440
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 179
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1379
telemt_me_writer_restored_same_endpoint_total 1343
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 166017
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 2099066649 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 47982769209 (44.69 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 7868.7 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128569
telemt_connections_bad_total 7896
telemt_handshake_timeouts_total 12850
telemt_upstream_connect_attempt_total 1929
telemt_upstream_connect_success_total 1929
telemt_upstream_connect_attempts_per_request{bucket="1"} 1929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 891
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1511
telemt_me_reconnect_success_total 1504
telemt_me_reader_eof_total 1548
telemt_me_idle_close_by_peer_total 1548
telemt_me_route_drop_no_conn_total 42540
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102215
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 318
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1510
telemt_me_writer_restored_same_endpoint_total 1493
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 102078
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 1630152172 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 26405325760 (24.59 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7868.3 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140786
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 1065
telemt_upstream_connect_attempt_total 2378
telemt_upstream_connect_success_total 2372
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1942
telemt_me_reconnect_success_total 1931
telemt_me_reader_eof_total 1954
telemt_me_idle_close_by_peer_total 1954
telemt_me_route_drop_no_conn_total 53248
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131378
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 679
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1942
telemt_me_writer_restored_same_endpoint_total 1931
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 131324
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 2255502360 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 40231245952 (37.47 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 96
```