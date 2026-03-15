# Server Metrics 2026-03-15 13:18:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 54263.6 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1596365
telemt_connections_bad_total 92493
telemt_handshake_timeouts_total 14595
telemt_upstream_connect_attempt_total 10859
telemt_upstream_connect_success_total 10810
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12957
telemt_me_reconnect_success_total 8071
telemt_me_reader_eof_total 8659
telemt_me_idle_close_by_peer_total 8659
telemt_me_route_drop_no_conn_total 540274
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1345530
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4978
telemt_desync_full_logged_total 1408
telemt_desync_suppressed_total 3570
telemt_desync_frames_bucket_total{bucket="1_2"} 1268
telemt_desync_frames_bucket_total{bucket="3_10"} 1940
telemt_desync_frames_bucket_total{bucket="gt_10"} 1770
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8349
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8060
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 1345185
telemt_user_connections_current{user="hello"} 2527
telemt_user_octets_from_client{user="hello"} 18804292884 (17.51 GB)
telemt_user_octets_to_client{user="hello"} 535708299236 (498.92 GB)
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 320
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 54264.5 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 640363
telemt_connections_bad_total 33339
telemt_handshake_timeouts_total 43790
telemt_upstream_connect_attempt_total 14040
telemt_upstream_connect_success_total 13970
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10979
telemt_me_reconnect_success_total 10897
telemt_me_reader_eof_total 11511
telemt_me_idle_close_by_peer_total 11511
telemt_me_route_drop_no_conn_total 161849
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487893
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1917
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1255
telemt_desync_frames_bucket_total{bucket="1_2"} 720
telemt_desync_frames_bucket_total{bucket="3_10"} 697
telemt_desync_frames_bucket_total{bucket="gt_10"} 500
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11023
telemt_me_writer_restored_same_endpoint_total 10885
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 488164
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 6897230771 (6.42 GB)
telemt_user_octets_to_client{user="hello"} 183992151692 (171.36 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 54264.4 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1309162
telemt_connections_bad_total 42020
telemt_handshake_timeouts_total 137017
telemt_upstream_connect_attempt_total 12087
telemt_upstream_connect_success_total 12031
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10525
telemt_me_reconnect_success_total 9276
telemt_me_reader_eof_total 9833
telemt_me_idle_close_by_peer_total 9833
telemt_me_route_drop_no_conn_total 381391
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 861025
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2218
telemt_desync_full_logged_total 807
telemt_desync_suppressed_total 1411
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 836
telemt_desync_frames_bucket_total{bucket="gt_10"} 881
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9436
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9257
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 857515
telemt_user_connections_current{user="hello"} 1311
telemt_user_octets_from_client{user="hello"} 12508043536 (11.65 GB)
telemt_user_octets_to_client{user="hello"} 316389460040 (294.66 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 54264.3 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 648196
telemt_connections_bad_total 68341
telemt_handshake_timeouts_total 35362
telemt_upstream_connect_attempt_total 61186
telemt_upstream_connect_success_total 60763
telemt_upstream_connect_fail_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 61186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 423
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 45347
telemt_me_reconnect_success_total 11764
telemt_me_reader_eof_total 13146
telemt_me_idle_close_by_peer_total 13146
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 167501
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438251
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1157
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12924
telemt_me_refill_failed_total 1050
telemt_me_writer_restored_same_endpoint_total 11732
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1160
telemt_user_connections_total{user="hello"} 484382
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 9167970296 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 167553251165 (156.05 GB)
telemt_user_msgs_from_client{user="hello"} 852713
telemt_user_msgs_to_client{user="hello"} 2977379
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 54265.2 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681960
telemt_connections_bad_total 8921
telemt_handshake_timeouts_total 13737
telemt_upstream_connect_attempt_total 12062
telemt_upstream_connect_success_total 11998
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 12931
telemt_me_reconnect_success_total 9263
telemt_me_reader_eof_total 9923
telemt_me_idle_close_by_peer_total 9923
telemt_me_route_drop_no_conn_total 170297
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553430
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2066
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 1372
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9487
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9255
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 553472
telemt_user_connections_current{user="hello"} 969
telemt_user_octets_from_client{user="hello"} 7061844628 (6.58 GB)
telemt_user_octets_to_client{user="hello"} 205422511972 (191.31 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 128
```