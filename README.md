# Server Metrics 2026-03-13 19:20:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 134511.1 (37h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4298416
telemt_connections_bad_total 37751
telemt_handshake_timeouts_total 104958
telemt_upstream_connect_attempt_total 28250
telemt_upstream_connect_success_total 28058
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 28250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 6524
telemt_me_reconnect_attempts_total 29118
telemt_me_reconnect_success_total 19002
telemt_me_reader_eof_total 20399
telemt_me_idle_close_by_peer_total 20398
telemt_me_route_drop_no_conn_total 1612934
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3929910
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15469
telemt_desync_full_logged_total 4120
telemt_desync_suppressed_total 11349
telemt_desync_frames_bucket_total{bucket="1_2"} 3853
telemt_desync_frames_bucket_total{bucket="3_10"} 5887
telemt_desync_frames_bucket_total{bucket="gt_10"} 5729
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 19590
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18989
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 3932081
telemt_user_connections_current{user="hello"} 1554
telemt_user_octets_from_client{user="hello"} 56937181524 (53.03 GB)
telemt_user_octets_to_client{user="hello"} 1235826487441 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 34175.0 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498120
telemt_connections_bad_total 38815
telemt_handshake_timeouts_total 10983
telemt_upstream_connect_attempt_total 10060
telemt_upstream_connect_success_total 9847
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 10060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 1865
telemt_me_reconnect_attempts_total 9523
telemt_me_reconnect_success_total 6110
telemt_me_reader_eof_total 6457
telemt_me_idle_close_by_peer_total 6456
telemt_me_route_drop_no_conn_total 187134
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433429
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1518
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 1112
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6300
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6102
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 435360
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 4622323757 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 137700383424 (128.24 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 164131.7 (45h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3141685
telemt_connections_bad_total 29280
telemt_handshake_timeouts_total 211171
telemt_upstream_connect_attempt_total 36511
telemt_upstream_connect_success_total 36496
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10176
telemt_me_reconnect_attempts_total 30556
telemt_me_reconnect_success_total 27993
telemt_me_reader_eof_total 29670
telemt_me_idle_close_by_peer_total 29669
telemt_me_route_drop_no_conn_total 1073589
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2596871
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8697
telemt_desync_full_logged_total 2878
telemt_desync_suppressed_total 5819
telemt_desync_frames_bucket_total{bucket="1_2"} 1426
telemt_desync_frames_bucket_total{bucket="3_10"} 3181
telemt_desync_frames_bucket_total{bucket="gt_10"} 4090
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 28325
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27952
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 2596161
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 42524118972 (39.60 GB)
telemt_user_octets_to_client{user="hello"} 910999387309 (848.43 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 164132.1 (45h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2025691
telemt_connections_bad_total 21700
telemt_handshake_timeouts_total 186190
telemt_upstream_connect_attempt_total 51638
telemt_upstream_connect_success_total 49204
telemt_upstream_connect_fail_total 2297
telemt_upstream_connect_attempts_per_request{bucket="1"} 51364
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2296
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20183
telemt_me_reconnect_attempts_total 43000
telemt_me_reconnect_success_total 33995
telemt_me_reader_eof_total 36502
telemt_me_idle_close_by_peer_total 36495
telemt_me_route_drop_no_conn_total 719238
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1672232
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3535
telemt_desync_full_logged_total 1132
telemt_desync_suppressed_total 2403
telemt_desync_frames_bucket_total{bucket="1_2"} 944
telemt_desync_frames_bucket_total{bucket="3_10"} 1463
telemt_desync_frames_bucket_total{bucket="gt_10"} 1128
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 34557
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33971
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 562
telemt_user_connections_total{user="hello"} 1678102
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 25678206315 (23.91 GB)
telemt_user_octets_to_client{user="hello"} 634539502890 (590.96 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33567.9 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539267
telemt_connections_bad_total 5619
telemt_handshake_timeouts_total 5327
telemt_upstream_connect_attempt_total 7241
telemt_upstream_connect_success_total 7003
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 7241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 956
telemt_me_reconnect_attempts_total 26227
telemt_me_reconnect_success_total 5292
telemt_me_reader_eof_total 6042
telemt_me_idle_close_by_peer_total 6041
telemt_me_route_drop_no_conn_total 204918
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504964
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1454
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5988
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5288
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 696
telemt_user_connections_total{user="hello"} 504938
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 5850476932 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 162832803120 (151.65 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 76
```