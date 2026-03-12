# Server Metrics 2026-03-12 19:51:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 49970.9 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1747031
telemt_connections_bad_total 20545
telemt_handshake_timeouts_total 18145
telemt_upstream_connect_attempt_total 9794
telemt_upstream_connect_success_total 9739
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 575
telemt_me_reconnect_attempts_total 16052
telemt_me_reconnect_success_total 7206
telemt_me_reader_eof_total 7801
telemt_me_idle_close_by_peer_total 7800
telemt_me_route_drop_no_conn_total 688217
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1631606
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8125
telemt_desync_full_logged_total 2088
telemt_desync_suppressed_total 6037
telemt_desync_frames_bucket_total{bucket="1_2"} 2122
telemt_desync_frames_bucket_total{bucket="3_10"} 2929
telemt_desync_frames_bucket_total{bucket="gt_10"} 3074
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 7585
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7193
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 1631095
telemt_user_connections_current{user="hello"} 1148
telemt_user_octets_from_client{user="hello"} 25261192988 (23.53 GB)
telemt_user_octets_to_client{user="hello"} 560528125876 (522.03 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79591.4 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741561
telemt_connections_bad_total 10390
telemt_handshake_timeouts_total 30071
telemt_upstream_connect_attempt_total 20212
telemt_upstream_connect_success_total 20182
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3376
telemt_me_reconnect_attempts_total 14630
telemt_me_reconnect_success_total 14542
telemt_me_reader_eof_total 15462
telemt_me_idle_close_by_peer_total 15462
telemt_me_route_drop_no_conn_total 238029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668491
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2892
telemt_desync_full_logged_total 887
telemt_desync_suppressed_total 2005
telemt_desync_frames_bucket_total{bucket="1_2"} 1123
telemt_desync_frames_bucket_total{bucket="3_10"} 956
telemt_desync_frames_bucket_total{bucket="gt_10"} 813
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 14693
telemt_me_writer_restored_same_endpoint_total 14533
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 670368
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 11382656504 (10.60 GB)
telemt_user_octets_to_client{user="hello"} 251554072727 (234.28 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 79591.3 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1532583
telemt_connections_bad_total 7278
telemt_handshake_timeouts_total 104055
telemt_upstream_connect_attempt_total 18762
telemt_upstream_connect_success_total 18757
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8590
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1188
telemt_me_reconnect_attempts_total 15647
telemt_me_reconnect_success_total 14402
telemt_me_reader_eof_total 15196
telemt_me_idle_close_by_peer_total 15195
telemt_me_route_drop_no_conn_total 506019
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1178219
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4790
telemt_desync_full_logged_total 1477
telemt_desync_suppressed_total 3313
telemt_desync_frames_bucket_total{bucket="1_2"} 758
telemt_desync_frames_bucket_total{bucket="3_10"} 1736
telemt_desync_frames_bucket_total{bucket="gt_10"} 2296
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14535
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14361
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 1177830
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 18379950336 (17.12 GB)
telemt_user_octets_to_client{user="hello"} 437982240145 (407.90 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 79591.8 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 939229
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 70225
telemt_upstream_connect_attempt_total 20416
telemt_upstream_connect_success_total 20335
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1651
telemt_me_reconnect_attempts_total 24072
telemt_me_reconnect_success_total 16347
telemt_me_reader_eof_total 17466
telemt_me_idle_close_by_peer_total 17466
telemt_me_route_drop_no_conn_total 332995
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 812961
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1749
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 491
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16722
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16326
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 812316
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 12661224200 (11.79 GB)
telemt_user_octets_to_client{user="hello"} 333017111852 (310.15 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79591.6 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055752
telemt_connections_bad_total 12339
telemt_handshake_timeouts_total 8713
telemt_upstream_connect_attempt_total 24703
telemt_upstream_connect_success_total 24400
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 24703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_keepalive_timeout_total 1396
telemt_me_reconnect_attempts_total 31430
telemt_me_reconnect_success_total 20393
telemt_me_reader_eof_total 21424
telemt_me_idle_close_by_peer_total 21424
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 394872
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 968237
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3626
telemt_desync_full_logged_total 1266
telemt_desync_suppressed_total 2360
telemt_desync_frames_bucket_total{bucket="1_2"} 1027
telemt_desync_frames_bucket_total{bucket="3_10"} 1206
telemt_desync_frames_bucket_total{bucket="gt_10"} 1393
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 20970
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20349
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 968107
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 11991630132 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 333018971592 (310.15 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 75
```