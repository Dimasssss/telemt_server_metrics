# Server Metrics 2026-03-13 05:22:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 84249.5 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2268560
telemt_connections_bad_total 33203
telemt_handshake_timeouts_total 23856
telemt_upstream_connect_attempt_total 16589
telemt_upstream_connect_success_total 16497
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 1309
telemt_me_reconnect_attempts_total 21172
telemt_me_reconnect_success_total 12305
telemt_me_reader_eof_total 13276
telemt_me_idle_close_by_peer_total 13275
telemt_me_route_drop_no_conn_total 863683
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2086348
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9234
telemt_desync_full_logged_total 2378
telemt_desync_suppressed_total 6856
telemt_desync_frames_bucket_total{bucket="1_2"} 2413
telemt_desync_frames_bucket_total{bucket="3_10"} 3356
telemt_desync_frames_bucket_total{bucket="gt_10"} 3465
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 12752
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12292
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 2085741
telemt_user_connections_current{user="hello"} 1131
telemt_user_octets_from_client{user="hello"} 30192657688 (28.12 GB)
telemt_user_octets_to_client{user="hello"} 717894017876 (668.59 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 113869.9 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920281
telemt_connections_bad_total 12375
telemt_handshake_timeouts_total 40156
telemt_upstream_connect_attempt_total 28828
telemt_upstream_connect_success_total 28797
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3539
telemt_me_reconnect_attempts_total 21605
telemt_me_reconnect_success_total 21488
telemt_me_reader_eof_total 22909
telemt_me_idle_close_by_peer_total 22909
telemt_me_route_drop_no_conn_total 293229
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 829629
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3281
telemt_desync_full_logged_total 1036
telemt_desync_suppressed_total 2245
telemt_desync_frames_bucket_total{bucket="1_2"} 1307
telemt_desync_frames_bucket_total{bucket="3_10"} 1073
telemt_desync_frames_bucket_total{bucket="gt_10"} 901
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 21699
telemt_me_writer_restored_same_endpoint_total 21479
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 831523
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 13285241676 (12.37 GB)
telemt_user_octets_to_client{user="hello"} 317914738519 (296.08 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 113870.0 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1901073
telemt_connections_bad_total 19749
telemt_handshake_timeouts_total 124841
telemt_upstream_connect_attempt_total 26515
telemt_upstream_connect_success_total 26505
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1645
telemt_me_reconnect_attempts_total 21757
telemt_me_reconnect_success_total 20487
telemt_me_reader_eof_total 21700
telemt_me_idle_close_by_peer_total 21699
telemt_me_route_drop_no_conn_total 610935
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1498116
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5190
telemt_desync_full_logged_total 1588
telemt_desync_suppressed_total 3602
telemt_desync_frames_bucket_total{bucket="1_2"} 844
telemt_desync_frames_bucket_total{bucket="3_10"} 1874
telemt_desync_frames_bucket_total{bucket="gt_10"} 2472
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 20683
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20446
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 1497615
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 25709831600 (23.94 GB)
telemt_user_octets_to_client{user="hello"} 532844178241 (496.25 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 113870.4 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1167573
telemt_connections_bad_total 13965
telemt_handshake_timeouts_total 75663
telemt_upstream_connect_attempt_total 38941
telemt_upstream_connect_success_total 36656
telemt_upstream_connect_fail_total 2148
telemt_upstream_connect_attempts_per_request{bucket="1"} 38667
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2147
telemt_me_keepalive_timeout_total 11397
telemt_me_reconnect_attempts_total 34057
telemt_me_reconnect_success_total 25123
telemt_me_reader_eof_total 27110
telemt_me_idle_close_by_peer_total 27103
telemt_me_route_drop_no_conn_total 415653
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005185
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1975
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1325
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 25573
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25099
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 1010367
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 15385826441 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 399408800450 (371.98 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 113870.0 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1305254
telemt_connections_bad_total 12925
telemt_handshake_timeouts_total 10436
telemt_upstream_connect_attempt_total 36016
telemt_upstream_connect_success_total 35582
telemt_upstream_connect_fail_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 36016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 434
telemt_me_keepalive_timeout_total 1962
telemt_me_reconnect_attempts_total 43649
telemt_me_reconnect_success_total 29916
telemt_me_reader_eof_total 31444
telemt_me_idle_close_by_peer_total 31444
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 482896
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1208669
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4379
telemt_desync_full_logged_total 1575
telemt_desync_suppressed_total 2804
telemt_desync_frames_bucket_total{bucket="1_2"} 1329
telemt_desync_frames_bucket_total{bucket="3_10"} 1422
telemt_desync_frames_bucket_total{bucket="gt_10"} 1628
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 30679
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29865
telemt_me_writer_restored_fallback_total 51
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1208526
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 14648539104 (13.64 GB)
telemt_user_octets_to_client{user="hello"} 410058572612 (381.90 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 103
```