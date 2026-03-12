# Server Metrics 2026-03-12 17:54:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 42920.6 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1546034
telemt_connections_bad_total 20345
telemt_handshake_timeouts_total 14463
telemt_upstream_connect_attempt_total 8487
telemt_upstream_connect_success_total 8436
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 528
telemt_me_reconnect_attempts_total 15097
telemt_me_reconnect_success_total 6253
telemt_me_reader_eof_total 6778
telemt_me_idle_close_by_peer_total 6777
telemt_me_route_drop_no_conn_total 601695
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1448521
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7391
telemt_desync_full_logged_total 1876
telemt_desync_suppressed_total 5515
telemt_desync_frames_bucket_total{bucket="1_2"} 1903
telemt_desync_frames_bucket_total{bucket="3_10"} 2697
telemt_desync_frames_bucket_total{bucket="gt_10"} 2791
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6615
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6240
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 1448016
telemt_user_connections_current{user="hello"} 1661
telemt_user_octets_from_client{user="hello"} 22084695196 (20.57 GB)
telemt_user_octets_to_client{user="hello"} 471968022340 (439.55 GB)
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 72541.0 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670814
telemt_connections_bad_total 8711
telemt_handshake_timeouts_total 29171
telemt_upstream_connect_attempt_total 18653
telemt_upstream_connect_success_total 18624
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 18653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3303
telemt_me_reconnect_attempts_total 13420
telemt_me_reconnect_success_total 13336
telemt_me_reader_eof_total 14178
telemt_me_idle_close_by_peer_total 14178
telemt_me_route_drop_no_conn_total 211654
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602469
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2545
telemt_desync_full_logged_total 782
telemt_desync_suppressed_total 1763
telemt_desync_frames_bucket_total{bucket="1_2"} 1052
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 661
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13475
telemt_me_writer_restored_same_endpoint_total 13327
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 604496
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 9156764244 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 227871842647 (212.22 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 72540.9 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1395314
telemt_connections_bad_total 6882
telemt_handshake_timeouts_total 98755
telemt_upstream_connect_attempt_total 17237
telemt_upstream_connect_success_total 17232
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1139
telemt_me_reconnect_attempts_total 14474
telemt_me_reconnect_success_total 13235
telemt_me_reader_eof_total 13957
telemt_me_idle_close_by_peer_total 13956
telemt_me_route_drop_no_conn_total 453391
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1059641
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4490
telemt_desync_full_logged_total 1393
telemt_desync_suppressed_total 3097
telemt_desync_frames_bucket_total{bucket="1_2"} 691
telemt_desync_frames_bucket_total{bucket="3_10"} 1636
telemt_desync_frames_bucket_total{bucket="gt_10"} 2163
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13344
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13194
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 1059504
telemt_user_connections_current{user="hello"} 1014
telemt_user_octets_from_client{user="hello"} 15879240928 (14.79 GB)
telemt_user_octets_to_client{user="hello"} 375728384797 (349.92 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 72541.4 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842771
telemt_connections_bad_total 10383
telemt_handshake_timeouts_total 64044
telemt_upstream_connect_attempt_total 18944
telemt_upstream_connect_success_total 18871
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 18944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 1591
telemt_me_reconnect_attempts_total 21642
telemt_me_reconnect_success_total 15236
telemt_me_reader_eof_total 16235
telemt_me_idle_close_by_peer_total 16235
telemt_me_route_drop_no_conn_total 295408
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 730180
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1656
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1103
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 640
telemt_desync_frames_bucket_total{bucket="gt_10"} 560
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15555
telemt_me_refill_failed_total 198
telemt_me_writer_restored_same_endpoint_total 15215
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 729595
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 8980158064 (8.36 GB)
telemt_user_octets_to_client{user="hello"} 294699789544 (274.46 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 72541.2 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 949549
telemt_connections_bad_total 11403
telemt_handshake_timeouts_total 7733
telemt_upstream_connect_attempt_total 23080
telemt_upstream_connect_success_total 22806
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 23080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 1303
telemt_me_reconnect_attempts_total 30180
telemt_me_reconnect_success_total 19152
telemt_me_reader_eof_total 20118
telemt_me_idle_close_by_peer_total 20118
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 350162
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 872017
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3379
telemt_desync_full_logged_total 1160
telemt_desync_suppressed_total 2219
telemt_desync_frames_bucket_total{bucket="1_2"} 928
telemt_desync_frames_bucket_total{bucket="3_10"} 1152
telemt_desync_frames_bucket_total{bucket="gt_10"} 1299
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 19713
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19108
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 871898
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 10679187048 (9.95 GB)
telemt_user_octets_to_client{user="hello"} 273448533732 (254.67 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 97
```