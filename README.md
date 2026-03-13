# Server Metrics 2026-03-13 18:14:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 130533.6 (36h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4170337
telemt_connections_bad_total 37533
telemt_handshake_timeouts_total 102123
telemt_upstream_connect_attempt_total 27521
telemt_upstream_connect_success_total 27342
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 27521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 5758
telemt_me_reconnect_attempts_total 28607
telemt_me_reconnect_success_total 18500
telemt_me_reader_eof_total 19874
telemt_me_idle_close_by_peer_total 19873
telemt_me_route_drop_no_conn_total 1558290
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3810709
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14856
telemt_desync_full_logged_total 3958
telemt_desync_suppressed_total 10898
telemt_desync_frames_bucket_total{bucket="1_2"} 3678
telemt_desync_frames_bucket_total{bucket="3_10"} 5646
telemt_desync_frames_bucket_total{bucket="gt_10"} 5532
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19079
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18487
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 3812883
telemt_user_connections_current{user="hello"} 1446
telemt_user_octets_from_client{user="hello"} 53488905572 (49.82 GB)
telemt_user_octets_to_client{user="hello"} 1186141940613 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 411
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 30197.3 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449787
telemt_connections_bad_total 34831
telemt_handshake_timeouts_total 10622
telemt_upstream_connect_attempt_total 8580
telemt_upstream_connect_success_total 8402
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 8580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 1604
telemt_me_reconnect_attempts_total 8840
telemt_me_reconnect_success_total 5442
telemt_me_reader_eof_total 5757
telemt_me_idle_close_by_peer_total 5756
telemt_me_route_drop_no_conn_total 169397
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391384
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1366
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 1010
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 463
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5622
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5434
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 392718
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 4071009395 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 121125991956 (112.81 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 160154.1 (44h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3048574
telemt_connections_bad_total 28779
telemt_handshake_timeouts_total 204032
telemt_upstream_connect_attempt_total 35668
telemt_upstream_connect_success_total 35658
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3512
telemt_me_reconnect_attempts_total 29928
telemt_me_reconnect_success_total 27373
telemt_me_reader_eof_total 29025
telemt_me_idle_close_by_peer_total 29024
telemt_me_route_drop_no_conn_total 1042089
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2522396
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8533
telemt_desync_full_logged_total 2830
telemt_desync_suppressed_total 5703
telemt_desync_frames_bucket_total{bucket="1_2"} 1380
telemt_desync_frames_bucket_total{bucket="3_10"} 3122
telemt_desync_frames_bucket_total{bucket="gt_10"} 4031
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 27693
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27332
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 2521723
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 41437277768 (38.59 GB)
telemt_user_octets_to_client{user="hello"} 883946305961 (823.24 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 160154.7 (44h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1963791
telemt_connections_bad_total 19504
telemt_handshake_timeouts_total 181080
telemt_upstream_connect_attempt_total 49557
telemt_upstream_connect_success_total 47215
telemt_upstream_connect_fail_total 2205
telemt_upstream_connect_attempts_per_request{bucket="1"} 49283
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2204
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11973
telemt_me_reconnect_attempts_total 42391
telemt_me_reconnect_success_total 33407
telemt_me_reader_eof_total 35870
telemt_me_idle_close_by_peer_total 35863
telemt_me_route_drop_no_conn_total 698529
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1620392
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3241
telemt_desync_full_logged_total 1053
telemt_desync_suppressed_total 2188
telemt_desync_frames_bucket_total{bucket="1_2"} 897
telemt_desync_frames_bucket_total{bucket="3_10"} 1323
telemt_desync_frames_bucket_total{bucket="gt_10"} 1021
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 33956
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33383
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 1625087
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 25054031469 (23.33 GB)
telemt_user_octets_to_client{user="hello"} 612717915882 (570.64 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29590.1 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484774
telemt_connections_bad_total 4692
telemt_handshake_timeouts_total 4970
telemt_upstream_connect_attempt_total 6632
telemt_upstream_connect_success_total 6417
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 6632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 874
telemt_me_reconnect_attempts_total 20416
telemt_me_reconnect_success_total 4928
telemt_me_reader_eof_total 5508
telemt_me_idle_close_by_peer_total 5508
telemt_me_route_drop_no_conn_total 185652
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453617
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1338
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 911
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 528
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5452
telemt_me_refill_failed_total 482
telemt_me_writer_restored_same_endpoint_total 4924
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 453595
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 5099095720 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 143127329824 (133.30 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 99
```