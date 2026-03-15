# Server Metrics 2026-03-15 15:41:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 62848.9 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2047447
telemt_connections_bad_total 111616
telemt_handshake_timeouts_total 24109
telemt_upstream_connect_attempt_total 12557
telemt_upstream_connect_success_total 12502
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 12557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14250
telemt_me_reconnect_success_total 9356
telemt_me_reader_eof_total 9995
telemt_me_idle_close_by_peer_total 9995
telemt_me_route_drop_no_conn_total 704185
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1729571
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6609
telemt_desync_full_logged_total 1822
telemt_desync_suppressed_total 4787
telemt_desync_frames_bucket_total{bucket="1_2"} 1633
telemt_desync_frames_bucket_total{bucket="3_10"} 2539
telemt_desync_frames_bucket_total{bucket="gt_10"} 2437
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9660
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9345
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 1729083
telemt_user_connections_current{user="hello"} 2273
telemt_user_octets_from_client{user="hello"} 25411495088 (23.67 GB)
telemt_user_octets_to_client{user="hello"} 666221994004 (620.47 GB)
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 62849.6 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 815730
telemt_connections_bad_total 43495
telemt_handshake_timeouts_total 59375
telemt_upstream_connect_attempt_total 15810
telemt_upstream_connect_success_total 15734
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 15810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12347
telemt_me_reconnect_success_total 12249
telemt_me_reader_eof_total 12943
telemt_me_idle_close_by_peer_total 12943
telemt_me_route_drop_no_conn_total 204730
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 620504
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2076
telemt_desync_full_logged_total 698
telemt_desync_suppressed_total 1378
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 763
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12407
telemt_me_writer_restored_same_endpoint_total 12237
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 620750
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 8665461991 (8.07 GB)
telemt_user_octets_to_client{user="hello"} 233852985396 (217.79 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 62849.7 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1827265
telemt_connections_bad_total 47729
telemt_handshake_timeouts_total 181339
telemt_upstream_connect_attempt_total 13714
telemt_upstream_connect_success_total 13649
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11742
telemt_me_reconnect_success_total 10481
telemt_me_reader_eof_total 11108
telemt_me_idle_close_by_peer_total 11108
telemt_me_route_drop_no_conn_total 477032
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1100137
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2687
telemt_desync_full_logged_total 988
telemt_desync_suppressed_total 1699
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 1046
telemt_desync_frames_bucket_total{bucket="gt_10"} 1020
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10667
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10462
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 1096109
telemt_user_connections_current{user="hello"} 1273
telemt_user_octets_from_client{user="hello"} 15798743452 (14.71 GB)
telemt_user_octets_to_client{user="hello"} 391176494372 (364.31 GB)
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 62849.5 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 862786
telemt_connections_bad_total 76392
telemt_handshake_timeouts_total 42435
telemt_upstream_connect_attempt_total 168096
telemt_upstream_connect_success_total 167587
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 168096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52817
telemt_me_reconnect_success_total 12377
telemt_me_reader_eof_total 13990
telemt_me_idle_close_by_peer_total 13990
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 191563
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510083
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1393
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 1030
telemt_desync_frames_bucket_total{bucket="1_2"} 368
telemt_desync_frames_bucket_total{bucket="3_10"} 560
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 13763
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12343
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1386
telemt_user_connections_total{user="hello"} 661734
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 13046362246 (12.15 GB)
telemt_user_octets_to_client{user="hello"} 234478376649 (218.38 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 62850.5 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 870375
telemt_connections_bad_total 9434
telemt_handshake_timeouts_total 19063
telemt_upstream_connect_attempt_total 13958
telemt_upstream_connect_success_total 13881
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14418
telemt_me_reconnect_success_total 10736
telemt_me_reader_eof_total 11461
telemt_me_idle_close_by_peer_total 11461
telemt_me_route_drop_no_conn_total 216935
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716279
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2481
telemt_desync_full_logged_total 842
telemt_desync_suppressed_total 1639
telemt_desync_frames_bucket_total{bucket="1_2"} 753
telemt_desync_frames_bucket_total{bucket="3_10"} 956
telemt_desync_frames_bucket_total{bucket="gt_10"} 772
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10978
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10728
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 716319
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 8815752372 (8.21 GB)
telemt_user_octets_to_client{user="hello"} 257746968292 (240.05 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 109
```