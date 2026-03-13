# Server Metrics 2026-03-13 17:43:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 128698.5 (35h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4105655
telemt_connections_bad_total 37527
telemt_handshake_timeouts_total 101287
telemt_upstream_connect_attempt_total 27250
telemt_upstream_connect_success_total 27072
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 27250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 5684
telemt_me_reconnect_attempts_total 28431
telemt_me_reconnect_success_total 18325
telemt_me_reader_eof_total 19687
telemt_me_idle_close_by_peer_total 19686
telemt_me_route_drop_no_conn_total 1527249
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3749841
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14675
telemt_desync_full_logged_total 3901
telemt_desync_suppressed_total 10774
telemt_desync_frames_bucket_total{bucket="1_2"} 3642
telemt_desync_frames_bucket_total{bucket="3_10"} 5575
telemt_desync_frames_bucket_total{bucket="gt_10"} 5458
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 18897
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18312
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 3752006
telemt_user_connections_current{user="hello"} 1514
telemt_user_octets_from_client{user="hello"} 52840981144 (49.21 GB)
telemt_user_octets_to_client{user="hello"} 1166086752745 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28362.4 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423448
telemt_connections_bad_total 31986
telemt_handshake_timeouts_total 10441
telemt_upstream_connect_attempt_total 8131
telemt_upstream_connect_success_total 7957
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 8131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 1601
telemt_me_reconnect_attempts_total 8483
telemt_me_reconnect_success_total 5086
telemt_me_reader_eof_total 5383
telemt_me_idle_close_by_peer_total 5382
telemt_me_route_drop_no_conn_total 159702
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368940
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1267
telemt_desync_full_logged_total 324
telemt_desync_suppressed_total 943
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5258
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5078
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 370278
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 3802499475 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 112554759412 (104.82 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 158318.9 (43h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3003087
telemt_connections_bad_total 28476
telemt_handshake_timeouts_total 201050
telemt_upstream_connect_attempt_total 35328
telemt_upstream_connect_success_total 35318
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3423
telemt_me_reconnect_attempts_total 29675
telemt_me_reconnect_success_total 27121
telemt_me_reader_eof_total 28753
telemt_me_idle_close_by_peer_total 28752
telemt_me_route_drop_no_conn_total 1023649
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2481203
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8513
telemt_desync_full_logged_total 2821
telemt_desync_suppressed_total 5692
telemt_desync_frames_bucket_total{bucket="1_2"} 1370
telemt_desync_frames_bucket_total{bucket="3_10"} 3116
telemt_desync_frames_bucket_total{bucket="gt_10"} 4027
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 27437
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27080
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 2480542
telemt_user_connections_current{user="hello"} 1100
telemt_user_octets_from_client{user="hello"} 40793283188 (37.99 GB)
telemt_user_octets_to_client{user="hello"} 864899410497 (805.50 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 158319.4 (43h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1934732
telemt_connections_bad_total 18257
telemt_handshake_timeouts_total 178619
telemt_upstream_connect_attempt_total 49189
telemt_upstream_connect_success_total 46850
telemt_upstream_connect_fail_total 2202
telemt_upstream_connect_attempts_per_request{bucket="1"} 48915
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2201
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11970
telemt_me_reconnect_attempts_total 42113
telemt_me_reconnect_success_total 33130
telemt_me_reader_eof_total 35576
telemt_me_idle_close_by_peer_total 35569
telemt_me_route_drop_no_conn_total 686738
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1595609
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3131
telemt_desync_full_logged_total 1018
telemt_desync_suppressed_total 2113
telemt_desync_frames_bucket_total{bucket="1_2"} 871
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 975
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 33675
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33106
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 1600305
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 24625551265 (22.93 GB)
telemt_user_octets_to_client{user="hello"} 605451131826 (563.87 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 27754.9 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454146
telemt_connections_bad_total 4583
telemt_handshake_timeouts_total 4791
telemt_upstream_connect_attempt_total 6356
telemt_upstream_connect_success_total 6152
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 6356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 869
telemt_me_reconnect_attempts_total 17613
telemt_me_reconnect_success_total 4749
telemt_me_reader_eof_total 5245
telemt_me_idle_close_by_peer_total 5245
telemt_me_route_drop_no_conn_total 174183
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424419
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1286
telemt_desync_full_logged_total 412
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5188
telemt_me_refill_failed_total 400
telemt_me_writer_restored_same_endpoint_total 4745
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 424392
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 4821159096 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 133228922316 (124.08 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 98
```