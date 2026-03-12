# Server Metrics 2026-03-12 06:09:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 677.4 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20606
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 161
telemt_upstream_connect_success_total 160
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 92
telemt_me_reconnect_success_total 92
telemt_me_reader_eof_total 62
telemt_me_idle_close_by_peer_total 62
telemt_me_route_drop_no_conn_total 6716
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19974
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 102
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_me_writer_removed_unexpected_total 83
telemt_me_writer_restored_same_endpoint_total 79
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 19968
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 990732804 (944.84 MB)
telemt_user_octets_to_client{user="hello"} 4963839732 (4.62 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 30297.8 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116699
telemt_connections_bad_total 1242
telemt_handshake_timeouts_total 3237
telemt_upstream_connect_attempt_total 8081
telemt_upstream_connect_success_total 8076
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 6402
telemt_me_reconnect_success_total 6365
telemt_me_reader_eof_total 6770
telemt_me_idle_close_by_peer_total 6770
telemt_me_route_drop_no_conn_total 35191
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105336
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6420
telemt_me_writer_restored_same_endpoint_total 6356
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 105524
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 1613166079 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 44695906798 (41.63 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 30297.6 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439895
telemt_connections_bad_total 2259
telemt_handshake_timeouts_total 31525
telemt_upstream_connect_attempt_total 8373
telemt_upstream_connect_success_total 8371
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6552
telemt_me_reconnect_success_total 6489
telemt_me_reader_eof_total 6795
telemt_me_idle_close_by_peer_total 6795
telemt_me_route_drop_no_conn_total 66190
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199632
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 300
telemt_desync_frames_bucket_total{bucket="gt_10"} 413
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6467
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6448
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 199939
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 2044619792 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 59903079729 (55.79 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 30298.1 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164944
telemt_connections_bad_total 1719
telemt_handshake_timeouts_total 11645
telemt_upstream_connect_attempt_total 8769
telemt_upstream_connect_success_total 8730
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 7232
telemt_me_reconnect_success_total 7206
telemt_me_reader_eof_total 7648
telemt_me_idle_close_by_peer_total 7648
telemt_me_route_drop_no_conn_total 56710
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148444
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 214
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7249
telemt_me_writer_restored_same_endpoint_total 7185
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 148301
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 1748250488 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 45302895632 (42.19 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 30297.9 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191141
telemt_connections_bad_total 305
telemt_handshake_timeouts_total 1190
telemt_upstream_connect_attempt_total 10605
telemt_upstream_connect_success_total 10487
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 10605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 202
telemt_me_reconnect_attempts_total 10461
telemt_me_reconnect_success_total 8952
telemt_me_reader_eof_total 9326
telemt_me_idle_close_by_peer_total 9326
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 58676
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182918
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 664
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 436
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 9078
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8933
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 182872
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 1607704236 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 42101127404 (39.21 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 75
```