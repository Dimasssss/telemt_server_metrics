# Server Metrics 2026-03-12 00:23:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9485.2 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82538
telemt_connections_bad_total 1334
telemt_handshake_timeouts_total 242
telemt_upstream_connect_attempt_total 2272
telemt_upstream_connect_success_total 2272
telemt_upstream_connect_attempts_per_request{bucket="1"} 2272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1771
telemt_me_reconnect_success_total 1764
telemt_me_reader_eof_total 1846
telemt_me_idle_close_by_peer_total 1846
telemt_me_route_drop_no_conn_total 30157
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77844
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1786
telemt_me_writer_restored_same_endpoint_total 1748
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 77785
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 575580796 (548.92 MB)
telemt_user_octets_to_client{user="hello"} 23630288272 (22.01 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9485.9 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29224
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 2858
telemt_upstream_connect_success_total 2855
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 2172
telemt_me_reconnect_success_total 2152
telemt_me_reader_eof_total 2264
telemt_me_idle_close_by_peer_total 2264
telemt_me_route_drop_no_conn_total 7631
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27618
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2167
telemt_me_writer_restored_same_endpoint_total 2143
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 27797
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 573259295 (546.70 MB)
telemt_user_octets_to_client{user="hello"} 10479479286 (9.76 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 9485.6 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84246
telemt_connections_bad_total 554
telemt_handshake_timeouts_total 6861
telemt_upstream_connect_attempt_total 3236
telemt_upstream_connect_success_total 3234
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 2409
telemt_me_reconnect_success_total 2363
telemt_me_reader_eof_total 2389
telemt_me_idle_close_by_peer_total 2389
telemt_me_route_drop_no_conn_total 14191
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46753
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2297
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2322
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 47098
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 540129396 (515.11 MB)
telemt_user_octets_to_client{user="hello"} 21483771841 (20.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 9485.9 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44329
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 637
telemt_upstream_connect_attempt_total 2862
telemt_upstream_connect_success_total 2848
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2344
telemt_me_reconnect_success_total 2335
telemt_me_reader_eof_total 2437
telemt_me_idle_close_by_peer_total 2437
telemt_me_route_drop_no_conn_total 14796
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42919
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2348
telemt_me_writer_restored_same_endpoint_total 2314
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 42915
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 209454004 (199.75 MB)
telemt_user_octets_to_client{user="hello"} 11856085696 (11.04 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9485.8 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57231
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 524
telemt_upstream_connect_attempt_total 4265
telemt_upstream_connect_success_total 4230
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 5196
telemt_me_reconnect_success_total 3706
telemt_me_reader_eof_total 3814
telemt_me_idle_close_by_peer_total 3814
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 13654
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53477
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 131
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3772
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3700
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 53459
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 269820880 (257.32 MB)
telemt_user_octets_to_client{user="hello"} 13141493236 (12.24 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 32
```