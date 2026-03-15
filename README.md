# Server Metrics 2026-03-15 13:39:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 55490.1 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1664337
telemt_connections_bad_total 96807
telemt_handshake_timeouts_total 16343
telemt_upstream_connect_attempt_total 11071
telemt_upstream_connect_success_total 11022
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13124
telemt_me_reconnect_success_total 8237
telemt_me_reader_eof_total 8825
telemt_me_idle_close_by_peer_total 8825
telemt_me_route_drop_no_conn_total 565195
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1401580
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5215
telemt_desync_full_logged_total 1459
telemt_desync_suppressed_total 3756
telemt_desync_frames_bucket_total{bucket="1_2"} 1339
telemt_desync_frames_bucket_total{bucket="3_10"} 2028
telemt_desync_frames_bucket_total{bucket="gt_10"} 1848
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8519
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8226
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 1401226
telemt_user_connections_current{user="hello"} 2341
telemt_user_octets_from_client{user="hello"} 19660735892 (18.31 GB)
telemt_user_octets_to_client{user="hello"} 559636172932 (521.20 GB)
telemt_user_unique_ips_current{user="hello"} 681
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 55491.0 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 669693
telemt_connections_bad_total 35451
telemt_handshake_timeouts_total 48874
telemt_upstream_connect_attempt_total 14289
telemt_upstream_connect_success_total 14219
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11185
telemt_me_reconnect_success_total 11102
telemt_me_reader_eof_total 11738
telemt_me_idle_close_by_peer_total 11738
telemt_me_route_drop_no_conn_total 167621
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506564
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1951
telemt_desync_full_logged_total 672
telemt_desync_suppressed_total 1279
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 514
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11236
telemt_me_writer_restored_same_endpoint_total 11090
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 506831
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 7146142455 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 192187213040 (178.99 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 55491.0 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1402771
telemt_connections_bad_total 43172
telemt_handshake_timeouts_total 145112
telemt_upstream_connect_attempt_total 12299
telemt_upstream_connect_success_total 12243
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 10693
telemt_me_reconnect_success_total 9442
telemt_me_reader_eof_total 10010
telemt_me_idle_close_by_peer_total 10010
telemt_me_route_drop_no_conn_total 393076
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 896117
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2275
telemt_desync_full_logged_total 836
telemt_desync_suppressed_total 1439
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 861
telemt_desync_frames_bucket_total{bucket="gt_10"} 896
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9604
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9423
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 892599
telemt_user_connections_current{user="hello"} 1237
telemt_user_octets_from_client{user="hello"} 12919545120 (12.03 GB)
telemt_user_octets_to_client{user="hello"} 325876454680 (303.50 GB)
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 55490.9 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 680601
telemt_connections_bad_total 69741
telemt_handshake_timeouts_total 36854
telemt_upstream_connect_attempt_total 85042
telemt_upstream_connect_success_total 84606
telemt_upstream_connect_fail_total 436
telemt_upstream_connect_attempts_per_request{bucket="1"} 85042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 436
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 46737
telemt_me_reconnect_success_total 11777
telemt_me_reader_eof_total 13201
telemt_me_idle_close_by_peer_total 13201
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 168670
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440777
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1158
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12980
telemt_me_refill_failed_total 1093
telemt_me_writer_restored_same_endpoint_total 11745
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1203
telemt_user_connections_total{user="hello"} 510700
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 9507188652 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 175956265818 (163.87 GB)
telemt_user_msgs_from_client{user="hello"} 1294558
telemt_user_msgs_to_client{user="hello"} 4889734
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 55491.7 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710363
telemt_connections_bad_total 9139
telemt_handshake_timeouts_total 14680
telemt_upstream_connect_attempt_total 12255
telemt_upstream_connect_success_total 12188
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 13078
telemt_me_reconnect_success_total 9408
telemt_me_reader_eof_total 10076
telemt_me_idle_close_by_peer_total 10076
telemt_me_route_drop_no_conn_total 176903
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576766
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2161
telemt_desync_full_logged_total 722
telemt_desync_suppressed_total 1439
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 851
telemt_desync_frames_bucket_total{bucket="gt_10"} 667
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9634
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9400
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 576808
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 7237423232 (6.74 GB)
telemt_user_octets_to_client{user="hello"} 217580768772 (202.64 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 126
```