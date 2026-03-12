# Server Metrics 2026-03-12 01:44:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14379.9 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117608
telemt_connections_bad_total 1348
telemt_handshake_timeouts_total 943
telemt_upstream_connect_attempt_total 3320
telemt_upstream_connect_success_total 3320
telemt_upstream_connect_attempts_per_request{bucket="1"} 3320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 2603
telemt_me_reconnect_success_total 2593
telemt_me_reader_eof_total 2732
telemt_me_idle_close_by_peer_total 2732
telemt_me_route_drop_no_conn_total 43038
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111626
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 203
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2625
telemt_me_writer_restored_same_endpoint_total 2577
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 111496
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 777104632 (741.10 MB)
telemt_user_octets_to_client{user="hello"} 30883970492 (28.76 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14380.5 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40786
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 444
telemt_upstream_connect_attempt_total 4168
telemt_upstream_connect_success_total 4165
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 3267
telemt_me_reconnect_success_total 3244
telemt_me_reader_eof_total 3431
telemt_me_idle_close_by_peer_total 3431
telemt_me_route_drop_no_conn_total 11195
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38035
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
telemt_me_writer_removed_unexpected_total 3268
telemt_me_writer_restored_same_endpoint_total 3235
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 38214
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 671567843 (640.46 MB)
telemt_user_octets_to_client{user="hello"} 13435398726 (12.51 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 14380.4 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153208
telemt_connections_bad_total 1112
telemt_handshake_timeouts_total 12241
telemt_upstream_connect_attempt_total 4496
telemt_upstream_connect_success_total 4494
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 3453
telemt_me_reconnect_success_total 3403
telemt_me_reader_eof_total 3496
telemt_me_idle_close_by_peer_total 3496
telemt_me_route_drop_no_conn_total 22138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68123
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3348
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3362
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 68468
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 632242668 (602.95 MB)
telemt_user_octets_to_client{user="hello"} 24633468909 (22.94 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 14380.7 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61621
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 1291
telemt_upstream_connect_attempt_total 4324
telemt_upstream_connect_success_total 4302
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 3583
telemt_me_reconnect_success_total 3572
telemt_me_reader_eof_total 3769
telemt_me_idle_close_by_peer_total 3769
telemt_me_route_drop_no_conn_total 21823
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59380
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
telemt_me_writer_removed_unexpected_total 3593
telemt_me_writer_restored_same_endpoint_total 3551
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 59372
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 332338404 (316.94 MB)
telemt_user_octets_to_client{user="hello"} 13670570596 (12.73 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14380.5 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79643
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 590
telemt_upstream_connect_attempt_total 5584
telemt_upstream_connect_success_total 5534
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 5584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2743
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 6285
telemt_me_reconnect_success_total 4791
telemt_me_reader_eof_total 4960
telemt_me_idle_close_by_peer_total 4960
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 19779
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75419
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 214
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 4873
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4782
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 75399
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 353775532 (337.39 MB)
telemt_user_octets_to_client{user="hello"} 15957359556 (14.86 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 37
```