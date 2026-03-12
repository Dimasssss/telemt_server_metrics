# Server Metrics 2026-03-12 00:48:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11014.9 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92994
telemt_connections_bad_total 1334
telemt_handshake_timeouts_total 256
telemt_upstream_connect_attempt_total 2614
telemt_upstream_connect_success_total 2614
telemt_upstream_connect_attempts_per_request{bucket="1"} 2614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 2027
telemt_me_reconnect_success_total 2020
telemt_me_reader_eof_total 2123
telemt_me_idle_close_by_peer_total 2123
telemt_me_route_drop_no_conn_total 33720
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88136
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2045
telemt_me_writer_restored_same_endpoint_total 2004
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 88044
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 623189332 (594.32 MB)
telemt_user_octets_to_client{user="hello"} 26676415664 (24.84 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11015.7 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32275
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 388
telemt_upstream_connect_attempt_total 3314
telemt_upstream_connect_success_total 3311
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2542
telemt_me_reconnect_success_total 2521
telemt_me_reader_eof_total 2664
telemt_me_idle_close_by_peer_total 2664
telemt_me_route_drop_no_conn_total 8774
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30499
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2538
telemt_me_writer_restored_same_endpoint_total 2512
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 30678
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 598408823 (570.69 MB)
telemt_user_octets_to_client{user="hello"} 11128118782 (10.36 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 11015.5 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97294
telemt_connections_bad_total 722
telemt_handshake_timeouts_total 8468
telemt_upstream_connect_attempt_total 3649
telemt_upstream_connect_success_total 3647
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 2735
telemt_me_reconnect_success_total 2688
telemt_me_reader_eof_total 2739
telemt_me_idle_close_by_peer_total 2739
telemt_me_route_drop_no_conn_total 16769
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53261
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
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2626
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2647
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 53605
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 564648164 (538.49 MB)
telemt_user_octets_to_client{user="hello"} 22162290117 (20.64 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 11015.9 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50151
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 723
telemt_upstream_connect_attempt_total 3331
telemt_upstream_connect_success_total 3315
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 2725
telemt_me_reconnect_success_total 2715
telemt_me_reader_eof_total 2855
telemt_me_idle_close_by_peer_total 2855
telemt_me_route_drop_no_conn_total 16954
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48605
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2731
telemt_me_writer_restored_same_endpoint_total 2694
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 48601
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 249904784 (238.33 MB)
telemt_user_octets_to_client{user="hello"} 12370820868 (11.52 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11015.7 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64203
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 539
telemt_upstream_connect_attempt_total 4671
telemt_upstream_connect_success_total 4633
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 4671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2297
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 5513
telemt_me_reconnect_success_total 4022
telemt_me_reader_eof_total 4153
telemt_me_idle_close_by_peer_total 4153
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 15473
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60343
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 148
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 4090
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4014
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 60325
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 290685580 (277.22 MB)
telemt_user_octets_to_client{user="hello"} 14460344104 (13.47 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 33
```