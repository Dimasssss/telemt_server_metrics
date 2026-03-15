# Server Metrics 2026-03-15 07:06:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 31893.9 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544438
telemt_connections_bad_total 13885
telemt_handshake_timeouts_total 3776
telemt_upstream_connect_attempt_total 6715
telemt_upstream_connect_success_total 6689
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5113
telemt_me_reconnect_success_total 5087
telemt_me_reader_eof_total 5379
telemt_me_idle_close_by_peer_total 5379
telemt_me_route_drop_no_conn_total 167216
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459866
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1208
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 826
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 515
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5149
telemt_me_writer_restored_same_endpoint_total 5076
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 459875
telemt_user_connections_current{user="hello"} 1650
telemt_user_octets_from_client{user="hello"} 5471044140 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 162582178516 (151.42 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 31894.7 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196256
telemt_connections_bad_total 18330
telemt_handshake_timeouts_total 5964
telemt_upstream_connect_attempt_total 8973
telemt_upstream_connect_success_total 8927
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4024
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7045
telemt_me_reconnect_success_total 7004
telemt_me_reader_eof_total 7414
telemt_me_idle_close_by_peer_total 7414
telemt_me_route_drop_no_conn_total 50754
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165246
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 560
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7037
telemt_me_writer_restored_same_endpoint_total 6996
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 165538
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 2618217627 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 61890059212 (57.64 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 31894.9 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360677
telemt_connections_bad_total 10427
telemt_handshake_timeouts_total 32998
telemt_upstream_connect_attempt_total 7316
telemt_upstream_connect_success_total 7284
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5704
telemt_me_reconnect_success_total 5673
telemt_me_reader_eof_total 6008
telemt_me_idle_close_by_peer_total 6008
telemt_me_route_drop_no_conn_total 93306
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298478
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 581
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 342
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5737
telemt_me_writer_restored_same_endpoint_total 5654
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 298289
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 4663140736 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 125045035444 (116.46 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 31894.7 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243795
telemt_connections_bad_total 44009
telemt_handshake_timeouts_total 15659
telemt_upstream_connect_attempt_total 10619
telemt_upstream_connect_success_total 10373
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 10619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 20043
telemt_me_reconnect_success_total 8767
telemt_me_reader_eof_total 9394
telemt_me_idle_close_by_peer_total 9394
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 58680
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178590
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 277
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 9192
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 8741
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 178593
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 1511405048 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 61556512240 (57.33 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 31896.0 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182521
telemt_connections_bad_total 260
telemt_handshake_timeouts_total 1742
telemt_upstream_connect_attempt_total 7133
telemt_upstream_connect_success_total 7105
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 7133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5527
telemt_me_reconnect_success_total 5502
telemt_me_reader_eof_total 5874
telemt_me_idle_close_by_peer_total 5874
telemt_me_route_drop_no_conn_total 55320
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171511
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 267
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5555
telemt_me_writer_restored_same_endpoint_total 5494
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 171518
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 1673797548 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 64995218044 (60.53 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 105
```