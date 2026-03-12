# Server Metrics 2026-03-12 02:05:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15603.3 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128300
telemt_connections_bad_total 1350
telemt_handshake_timeouts_total 2027
telemt_upstream_connect_attempt_total 3630
telemt_upstream_connect_success_total 3630
telemt_upstream_connect_attempts_per_request{bucket="1"} 3630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 2827
telemt_me_reconnect_success_total 2815
telemt_me_reader_eof_total 2972
telemt_me_idle_close_by_peer_total 2972
telemt_me_route_drop_no_conn_total 46188
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120910
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 205
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2848
telemt_me_writer_restored_same_endpoint_total 2799
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 120770
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 863627760 (823.62 MB)
telemt_user_octets_to_client{user="hello"} 36063938068 (33.59 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 15603.8 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43788
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 4562
telemt_upstream_connect_success_total 4559
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3575
telemt_me_reconnect_success_total 3549
telemt_me_reader_eof_total 3762
telemt_me_idle_close_by_peer_total 3762
telemt_me_route_drop_no_conn_total 11983
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40904
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3576
telemt_me_writer_restored_same_endpoint_total 3540
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 41083
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 688338091 (656.45 MB)
telemt_user_octets_to_client{user="hello"} 13934750230 (12.98 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 15603.7 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185245
telemt_connections_bad_total 1119
telemt_handshake_timeouts_total 13521
telemt_upstream_connect_attempt_total 4879
telemt_upstream_connect_success_total 4877
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 3750
telemt_me_reconnect_success_total 3700
telemt_me_reader_eof_total 3819
telemt_me_idle_close_by_peer_total 3819
telemt_me_route_drop_no_conn_total 23626
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74420
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3649
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3659
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 74763
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 662131064 (631.46 MB)
telemt_user_octets_to_client{user="hello"} 25522988385 (23.77 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 15603.9 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66204
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 1533
telemt_upstream_connect_attempt_total 4695
telemt_upstream_connect_success_total 4672
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 3867
telemt_me_reconnect_success_total 3852
telemt_me_reader_eof_total 4075
telemt_me_idle_close_by_peer_total 4075
telemt_me_route_drop_no_conn_total 23457
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63648
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3877
telemt_me_writer_restored_same_endpoint_total 3831
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 63637
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 361043988 (344.32 MB)
telemt_user_octets_to_client{user="hello"} 14396147192 (13.41 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15603.9 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85464
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 612
telemt_upstream_connect_attempt_total 5979
telemt_upstream_connect_success_total 5920
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 5979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2936
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6585
telemt_me_reconnect_success_total 5090
telemt_me_reader_eof_total 5282
telemt_me_idle_close_by_peer_total 5282
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 21199
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81101
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 255
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5173
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5076
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 81080
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 384748628 (366.92 MB)
telemt_user_octets_to_client{user="hello"} 17067551140 (15.90 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 31
```