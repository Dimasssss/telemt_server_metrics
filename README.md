# Server Metrics 2026-03-12 19:31:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 48745.6 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1718537
telemt_connections_bad_total 20543
telemt_handshake_timeouts_total 17198
telemt_upstream_connect_attempt_total 9597
telemt_upstream_connect_success_total 9542
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 573
telemt_me_reconnect_attempts_total 15898
telemt_me_reconnect_success_total 7052
telemt_me_reader_eof_total 7638
telemt_me_idle_close_by_peer_total 7637
telemt_me_route_drop_no_conn_total 674422
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1605530
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8091
telemt_desync_full_logged_total 2076
telemt_desync_suppressed_total 6015
telemt_desync_frames_bucket_total{bucket="1_2"} 2109
telemt_desync_frames_bucket_total{bucket="3_10"} 2918
telemt_desync_frames_bucket_total{bucket="gt_10"} 3064
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7430
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7039
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 378
telemt_user_connections_total{user="hello"} 1605022
telemt_user_connections_current{user="hello"} 1337
telemt_user_octets_from_client{user="hello"} 24933221332 (23.22 GB)
telemt_user_octets_to_client{user="hello"} 548090700708 (510.45 GB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78366.1 (21h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731885
telemt_connections_bad_total 9997
telemt_handshake_timeouts_total 29939
telemt_upstream_connect_attempt_total 19903
telemt_upstream_connect_success_total 19874
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3373
telemt_me_reconnect_attempts_total 14378
telemt_me_reconnect_success_total 14292
telemt_me_reader_eof_total 15191
telemt_me_idle_close_by_peer_total 15191
telemt_me_route_drop_no_conn_total 234595
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 659602
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2861
telemt_desync_full_logged_total 876
telemt_desync_suppressed_total 1985
telemt_desync_frames_bucket_total{bucket="1_2"} 1120
telemt_desync_frames_bucket_total{bucket="3_10"} 938
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 14442
telemt_me_writer_restored_same_endpoint_total 14283
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 661478
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 11218647720 (10.45 GB)
telemt_user_octets_to_client{user="hello"} 249638337323 (232.49 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 78366.0 (21h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1513125
telemt_connections_bad_total 7267
telemt_handshake_timeouts_total 103582
telemt_upstream_connect_attempt_total 18507
telemt_upstream_connect_success_total 18502
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1186
telemt_me_reconnect_attempts_total 15452
telemt_me_reconnect_success_total 14208
telemt_me_reader_eof_total 14983
telemt_me_idle_close_by_peer_total 14982
telemt_me_route_drop_no_conn_total 498175
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1159336
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4758
telemt_desync_full_logged_total 1467
telemt_desync_suppressed_total 3291
telemt_desync_frames_bucket_total{bucket="1_2"} 750
telemt_desync_frames_bucket_total{bucket="3_10"} 1723
telemt_desync_frames_bucket_total{bucket="gt_10"} 2285
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14337
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14167
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 1159188
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 18118474112 (16.87 GB)
telemt_user_octets_to_client{user="hello"} 429705497661 (400.19 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 78366.9 (21h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924001
telemt_connections_bad_total 12961
telemt_handshake_timeouts_total 67748
telemt_upstream_connect_attempt_total 20104
telemt_upstream_connect_success_total 20023
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1641
telemt_me_reconnect_attempts_total 23826
telemt_me_reconnect_success_total 16101
telemt_me_reader_eof_total 17199
telemt_me_idle_close_by_peer_total 17199
telemt_me_route_drop_no_conn_total 327528
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800504
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1745
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 16474
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16080
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 799861
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 12408847508 (11.56 GB)
telemt_user_octets_to_client{user="hello"} 327509777964 (305.02 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78366.5 (21h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1038272
telemt_connections_bad_total 12100
telemt_handshake_timeouts_total 8529
telemt_upstream_connect_attempt_total 24293
telemt_upstream_connect_success_total 24002
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 24293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 1394
telemt_me_reconnect_attempts_total 31099
telemt_me_reconnect_success_total 20064
telemt_me_reader_eof_total 21089
telemt_me_idle_close_by_peer_total 21089
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 388318
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 952197
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3561
telemt_desync_full_logged_total 1247
telemt_desync_suppressed_total 2314
telemt_desync_frames_bucket_total{bucket="1_2"} 1014
telemt_desync_frames_bucket_total{bucket="3_10"} 1186
telemt_desync_frames_bucket_total{bucket="gt_10"} 1361
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 20635
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20020
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 571
telemt_user_connections_total{user="hello"} 952067
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 11802608524 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 322697030228 (300.54 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 84
```