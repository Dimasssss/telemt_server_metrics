# Server Metrics 2026-03-12 01:39:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14073.5 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114969
telemt_connections_bad_total 1345
telemt_handshake_timeouts_total 673
telemt_upstream_connect_attempt_total 3286
telemt_upstream_connect_success_total 3286
telemt_upstream_connect_attempts_per_request{bucket="1"} 3286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 2569
telemt_me_reconnect_success_total 2560
telemt_me_reader_eof_total 2697
telemt_me_idle_close_by_peer_total 2697
telemt_me_route_drop_no_conn_total 42397
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109305
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2590
telemt_me_writer_restored_same_endpoint_total 2544
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 109181
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 756982312 (721.91 MB)
telemt_user_octets_to_client{user="hello"} 29792824196 (27.75 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14074.3 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40002
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 432
telemt_upstream_connect_attempt_total 4123
telemt_upstream_connect_success_total 4120
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 3222
telemt_me_reconnect_success_total 3199
telemt_me_reader_eof_total 3384
telemt_me_idle_close_by_peer_total 3384
telemt_me_route_drop_no_conn_total 10933
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37289
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3221
telemt_me_writer_restored_same_endpoint_total 3190
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 37468
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 667566291 (636.64 MB)
telemt_user_octets_to_client{user="hello"} 13010710530 (12.12 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 14074.1 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145010
telemt_connections_bad_total 1108
telemt_handshake_timeouts_total 11930
telemt_upstream_connect_attempt_total 4450
telemt_upstream_connect_success_total 4448
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 3407
telemt_me_reconnect_success_total 3357
telemt_me_reader_eof_total 3450
telemt_me_idle_close_by_peer_total 3450
telemt_me_route_drop_no_conn_total 21537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66322
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3302
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3316
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 66667
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 625853892 (596.86 MB)
telemt_user_octets_to_client{user="hello"} 24463000953 (22.78 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 14074.4 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60685
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 1266
telemt_upstream_connect_attempt_total 4264
telemt_upstream_connect_success_total 4242
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 3523
telemt_me_reconnect_success_total 3512
telemt_me_reader_eof_total 3709
telemt_me_idle_close_by_peer_total 3709
telemt_me_route_drop_no_conn_total 21242
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58482
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3533
telemt_me_writer_restored_same_endpoint_total 3491
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 58474
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 328331176 (313.12 MB)
telemt_user_octets_to_client{user="hello"} 13528624024 (12.60 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14074.2 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78264
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 590
telemt_upstream_connect_attempt_total 5527
telemt_upstream_connect_success_total 5477
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 5527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 6228
telemt_me_reconnect_success_total 4734
telemt_me_reader_eof_total 4904
telemt_me_idle_close_by_peer_total 4904
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 19363
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74072
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 206
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 4816
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4725
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 74052
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 341000344 (325.20 MB)
telemt_user_octets_to_client{user="hello"} 15854054136 (14.77 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 38
```