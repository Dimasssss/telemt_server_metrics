# Server Metrics 2026-03-12 00:28:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9790.6 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84494
telemt_connections_bad_total 1334
telemt_handshake_timeouts_total 248
telemt_upstream_connect_attempt_total 2311
telemt_upstream_connect_success_total 2311
telemt_upstream_connect_attempts_per_request{bucket="1"} 2311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1810
telemt_me_reconnect_success_total 1803
telemt_me_reader_eof_total 1885
telemt_me_idle_close_by_peer_total 1885
telemt_me_route_drop_no_conn_total 31122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79772
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1825
telemt_me_writer_restored_same_endpoint_total 1787
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 79710
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 583468840 (556.44 MB)
telemt_user_octets_to_client{user="hello"} 23939675336 (22.30 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9791.4 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29809
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 360
telemt_upstream_connect_attempt_total 2918
telemt_upstream_connect_success_total 2915
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2232
telemt_me_reconnect_success_total 2212
telemt_me_reader_eof_total 2324
telemt_me_idle_close_by_peer_total 2324
telemt_me_route_drop_no_conn_total 7775
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28187
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
telemt_me_writer_removed_unexpected_total 2227
telemt_me_writer_restored_same_endpoint_total 2203
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 28366
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 579331975 (552.49 MB)
telemt_user_octets_to_client{user="hello"} 10563879078 (9.84 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 9791.1 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86098
telemt_connections_bad_total 722
telemt_handshake_timeouts_total 7173
telemt_upstream_connect_attempt_total 3279
telemt_upstream_connect_success_total 3277
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2452
telemt_me_reconnect_success_total 2406
telemt_me_reader_eof_total 2434
telemt_me_idle_close_by_peer_total 2434
telemt_me_route_drop_no_conn_total 14559
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48111
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2342
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2365
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 48455
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 543486272 (518.31 MB)
telemt_user_octets_to_client{user="hello"} 21698700277 (20.21 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 9791.4 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45562
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 649
telemt_upstream_connect_attempt_total 2940
telemt_upstream_connect_success_total 2926
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2422
telemt_me_reconnect_success_total 2412
telemt_me_reader_eof_total 2515
telemt_me_idle_close_by_peer_total 2515
telemt_me_route_drop_no_conn_total 15290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44134
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2426
telemt_me_writer_restored_same_endpoint_total 2391
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 44130
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 216809148 (206.77 MB)
telemt_user_octets_to_client{user="hello"} 12023517708 (11.20 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9791.3 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58712
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 528
telemt_upstream_connect_attempt_total 4318
telemt_upstream_connect_success_total 4282
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 5249
telemt_me_reconnect_success_total 3757
telemt_me_reader_eof_total 3867
telemt_me_idle_close_by_peer_total 3867
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 14007
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54950
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
telemt_me_writer_removed_unexpected_total 3825
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3751
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 54932
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 272769864 (260.13 MB)
telemt_user_octets_to_client{user="hello"} 13220184824 (12.31 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 33
```