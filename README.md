# Server Metrics 2026-03-13 18:19:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 130841.9 (36h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4180092
telemt_connections_bad_total 37533
telemt_handshake_timeouts_total 102209
telemt_upstream_connect_attempt_total 27644
telemt_upstream_connect_success_total 27464
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 27644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 5761
telemt_me_reconnect_attempts_total 28691
telemt_me_reconnect_success_total 18584
telemt_me_reader_eof_total 19958
telemt_me_idle_close_by_peer_total 19957
telemt_me_route_drop_no_conn_total 1562655
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3819909
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14899
telemt_desync_full_logged_total 3968
telemt_desync_suppressed_total 10931
telemt_desync_frames_bucket_total{bucket="1_2"} 3688
telemt_desync_frames_bucket_total{bucket="3_10"} 5666
telemt_desync_frames_bucket_total{bucket="gt_10"} 5545
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19164
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18571
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 3822081
telemt_user_connections_current{user="hello"} 1485
telemt_user_octets_from_client{user="hello"} 53592447992 (49.91 GB)
telemt_user_octets_to_client{user="hello"} 1191772454509 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 30505.9 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453619
telemt_connections_bad_total 35293
telemt_handshake_timeouts_total 10668
telemt_upstream_connect_attempt_total 8623
telemt_upstream_connect_success_total 8445
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 8623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 1607
telemt_me_reconnect_attempts_total 8883
telemt_me_reconnect_success_total 5485
telemt_me_reader_eof_total 5799
telemt_me_idle_close_by_peer_total 5798
telemt_me_route_drop_no_conn_total 170787
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394633
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1385
telemt_desync_full_logged_total 362
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 640
telemt_desync_frames_bucket_total{bucket="gt_10"} 472
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5665
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5477
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 395967
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 4090798171 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 122021161580 (113.64 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 160462.5 (44h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3055567
telemt_connections_bad_total 28911
telemt_handshake_timeouts_total 204523
telemt_upstream_connect_attempt_total 35760
telemt_upstream_connect_success_total 35750
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17128
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3512
telemt_me_reconnect_attempts_total 29977
telemt_me_reconnect_success_total 27422
telemt_me_reader_eof_total 29078
telemt_me_idle_close_by_peer_total 29077
telemt_me_route_drop_no_conn_total 1044981
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2528516
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8541
telemt_desync_full_logged_total 2833
telemt_desync_suppressed_total 5708
telemt_desync_frames_bucket_total{bucket="1_2"} 1383
telemt_desync_frames_bucket_total{bucket="3_10"} 3124
telemt_desync_frames_bucket_total{bucket="gt_10"} 4034
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 27742
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27381
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 2527843
telemt_user_connections_current{user="hello"} 1102
telemt_user_octets_from_client{user="hello"} 41653166528 (38.79 GB)
telemt_user_octets_to_client{user="hello"} 887120455465 (826.20 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 160463.0 (44h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1968150
telemt_connections_bad_total 19818
telemt_handshake_timeouts_total 181144
telemt_upstream_connect_attempt_total 49660
telemt_upstream_connect_success_total 47316
telemt_upstream_connect_fail_total 2207
telemt_upstream_connect_attempts_per_request{bucket="1"} 49386
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2206
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11973
telemt_me_reconnect_attempts_total 42449
telemt_me_reconnect_success_total 33463
telemt_me_reader_eof_total 35936
telemt_me_idle_close_by_peer_total 35929
telemt_me_route_drop_no_conn_total 700026
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1624249
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3262
telemt_desync_full_logged_total 1062
telemt_desync_suppressed_total 2200
telemt_desync_frames_bucket_total{bucket="1_2"} 899
telemt_desync_frames_bucket_total{bucket="3_10"} 1333
telemt_desync_frames_bucket_total{bucket="gt_10"} 1030
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 34015
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33439
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 1628944
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 25091295373 (23.37 GB)
telemt_user_octets_to_client{user="hello"} 613681045558 (571.54 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29898.6 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489524
telemt_connections_bad_total 4696
telemt_handshake_timeouts_total 5062
telemt_upstream_connect_attempt_total 6705
telemt_upstream_connect_success_total 6486
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 6705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 876
telemt_me_reconnect_attempts_total 21658
telemt_me_reconnect_success_total 4954
telemt_me_reader_eof_total 5572
telemt_me_idle_close_by_peer_total 5572
telemt_me_route_drop_no_conn_total 187357
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458121
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1345
telemt_desync_full_logged_total 429
telemt_desync_suppressed_total 916
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5516
telemt_me_refill_failed_total 520
telemt_me_writer_restored_same_endpoint_total 4950
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 562
telemt_user_connections_total{user="hello"} 458094
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 5147563088 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 145558303180 (135.56 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 95
```