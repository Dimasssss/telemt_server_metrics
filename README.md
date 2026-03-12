# Server Metrics 2026-03-12 01:49:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14685.7 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120132
telemt_connections_bad_total 1350
telemt_handshake_timeouts_total 1229
telemt_upstream_connect_attempt_total 3436
telemt_upstream_connect_success_total 3436
telemt_upstream_connect_attempts_per_request{bucket="1"} 3436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1637
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 2676
telemt_me_reconnect_success_total 2666
telemt_me_reader_eof_total 2813
telemt_me_idle_close_by_peer_total 2813
telemt_me_route_drop_no_conn_total 43758
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113790
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2698
telemt_me_writer_restored_same_endpoint_total 2650
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 113658
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 789169024 (752.61 MB)
telemt_user_octets_to_client{user="hello"} 31669048824 (29.49 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14686.3 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41409
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 452
telemt_upstream_connect_attempt_total 4302
telemt_upstream_connect_success_total 4299
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 3358
telemt_me_reconnect_success_total 3334
telemt_me_reader_eof_total 3534
telemt_me_idle_close_by_peer_total 3534
telemt_me_route_drop_no_conn_total 11300
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38628
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3358
telemt_me_writer_restored_same_endpoint_total 3325
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 38807
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 676079331 (644.76 MB)
telemt_user_octets_to_client{user="hello"} 13619606550 (12.68 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 14686.0 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159486
telemt_connections_bad_total 1112
telemt_handshake_timeouts_total 12559
telemt_upstream_connect_attempt_total 4619
telemt_upstream_connect_success_total 4617
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 3533
telemt_me_reconnect_success_total 3483
telemt_me_reader_eof_total 3590
telemt_me_idle_close_by_peer_total 3590
telemt_me_route_drop_no_conn_total 22381
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69512
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3430
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3442
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 69857
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 642625584 (612.86 MB)
telemt_user_octets_to_client{user="hello"} 24756899697 (23.06 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 14686.5 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62763
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 1349
telemt_upstream_connect_attempt_total 4452
telemt_upstream_connect_success_total 4429
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 3667
telemt_me_reconnect_success_total 3656
telemt_me_reader_eof_total 3868
telemt_me_idle_close_by_peer_total 3868
telemt_me_route_drop_no_conn_total 22166
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60446
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3679
telemt_me_writer_restored_same_endpoint_total 3635
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 60438
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 339807828 (324.07 MB)
telemt_user_octets_to_client{user="hello"} 13841427936 (12.89 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14686.4 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80925
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 592
telemt_upstream_connect_attempt_total 5709
telemt_upstream_connect_success_total 5654
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 5709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 6362
telemt_me_reconnect_success_total 4868
telemt_me_reader_eof_total 5051
telemt_me_idle_close_by_peer_total 5051
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 20138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76673
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 220
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4951
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4859
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 76653
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 356082732 (339.59 MB)
telemt_user_octets_to_client{user="hello"} 16068314428 (14.96 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 28
```