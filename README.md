# Server Metrics 2026-03-13 03:40:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 78126.8 (21h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2150054
telemt_connections_bad_total 28005
telemt_handshake_timeouts_total 22918
telemt_upstream_connect_attempt_total 15464
telemt_upstream_connect_success_total 15377
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 15464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 1296
telemt_me_reconnect_attempts_total 20353
telemt_me_reconnect_success_total 11490
telemt_me_reader_eof_total 12407
telemt_me_idle_close_by_peer_total 12406
telemt_me_route_drop_no_conn_total 824210
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1977325
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8808
telemt_desync_full_logged_total 2290
telemt_desync_suppressed_total 6518
telemt_desync_frames_bucket_total{bucket="1_2"} 2316
telemt_desync_frames_bucket_total{bucket="3_10"} 3174
telemt_desync_frames_bucket_total{bucket="gt_10"} 3318
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11926
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11477
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 1976771
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 28730784164 (26.76 GB)
telemt_user_octets_to_client{user="hello"} 681817821188 (634.99 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 107747.3 (29h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875809
telemt_connections_bad_total 11846
telemt_handshake_timeouts_total 38706
telemt_upstream_connect_attempt_total 27454
telemt_upstream_connect_success_total 27425
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3463
telemt_me_reconnect_attempts_total 20533
telemt_me_reconnect_success_total 20421
telemt_me_reader_eof_total 21763
telemt_me_idle_close_by_peer_total 21763
telemt_me_route_drop_no_conn_total 280064
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 789505
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3128
telemt_desync_full_logged_total 983
telemt_desync_suppressed_total 2145
telemt_desync_frames_bucket_total{bucket="1_2"} 1266
telemt_desync_frames_bucket_total{bucket="3_10"} 1015
telemt_desync_frames_bucket_total{bucket="gt_10"} 847
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 20620
telemt_me_writer_restored_same_endpoint_total 20412
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 791408
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 12614322448 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 305218541483 (284.26 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 107747.2 (29h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1810209
telemt_connections_bad_total 12226
telemt_handshake_timeouts_total 120021
telemt_upstream_connect_attempt_total 25114
telemt_upstream_connect_success_total 25104
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1622
telemt_me_reconnect_attempts_total 20659
telemt_me_reconnect_success_total 19393
telemt_me_reader_eof_total 20545
telemt_me_idle_close_by_peer_total 20544
telemt_me_route_drop_no_conn_total 587415
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1427588
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5086
telemt_desync_full_logged_total 1551
telemt_desync_suppressed_total 3535
telemt_desync_frames_bucket_total{bucket="1_2"} 812
telemt_desync_frames_bucket_total{bucket="3_10"} 1838
telemt_desync_frames_bucket_total{bucket="gt_10"} 2436
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 19574
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19352
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 1427182
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 24836053212 (23.13 GB)
telemt_user_octets_to_client{user="hello"} 511350038041 (476.23 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 107747.6 (29h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1126805
telemt_connections_bad_total 13156
telemt_handshake_timeouts_total 74424
telemt_upstream_connect_attempt_total 37424
telemt_upstream_connect_success_total 35143
telemt_upstream_connect_fail_total 2144
telemt_upstream_connect_attempts_per_request{bucket="1"} 37150
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2143
telemt_me_keepalive_timeout_total 11376
telemt_me_reconnect_attempts_total 32846
telemt_me_reconnect_success_total 23916
telemt_me_reader_eof_total 25821
telemt_me_idle_close_by_peer_total 25814
telemt_me_route_drop_no_conn_total 399831
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 967270
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 24353
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23892
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 972441
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 14859990901 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 383997651622 (357.63 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 107747.4 (29h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1248435
telemt_connections_bad_total 12862
telemt_handshake_timeouts_total 9886
telemt_upstream_connect_attempt_total 33883
telemt_upstream_connect_success_total 33470
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 33883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_keepalive_timeout_total 1910
telemt_me_reconnect_attempts_total 41844
telemt_me_reconnect_success_total 28113
telemt_me_reader_eof_total 29577
telemt_me_idle_close_by_peer_total 29577
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 464830
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1154356
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4267
telemt_desync_full_logged_total 1524
telemt_desync_suppressed_total 2743
telemt_desync_frames_bucket_total{bucket="1_2"} 1290
telemt_desync_frames_bucket_total{bucket="3_10"} 1399
telemt_desync_frames_bucket_total{bucket="gt_10"} 1578
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 28866
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28063
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 753
telemt_user_connections_total{user="hello"} 1154210
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 14224136568 (13.25 GB)
telemt_user_octets_to_client{user="hello"} 397322846296 (370.04 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 45
```