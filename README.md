# Server Metrics 2026-03-13 02:54:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 75372.8 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2109006
telemt_connections_bad_total 27893
telemt_handshake_timeouts_total 22510
telemt_upstream_connect_attempt_total 14923
telemt_upstream_connect_success_total 14839
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1268
telemt_me_reconnect_attempts_total 19944
telemt_me_reconnect_success_total 11082
telemt_me_reader_eof_total 11971
telemt_me_idle_close_by_peer_total 11970
telemt_me_route_drop_no_conn_total 811444
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1943068
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8735
telemt_desync_full_logged_total 2272
telemt_desync_suppressed_total 6463
telemt_desync_frames_bucket_total{bucket="1_2"} 2298
telemt_desync_frames_bucket_total{bucket="3_10"} 3152
telemt_desync_frames_bucket_total{bucket="gt_10"} 3285
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11514
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11069
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 1942524
telemt_user_connections_current{user="hello"} 724
telemt_user_octets_from_client{user="hello"} 28328180880 (26.38 GB)
telemt_user_octets_to_client{user="hello"} 674483404400 (628.16 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 104993.1 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 859541
telemt_connections_bad_total 11826
telemt_handshake_timeouts_total 33881
telemt_upstream_connect_attempt_total 26755
telemt_upstream_connect_success_total 26726
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3458
telemt_me_reconnect_attempts_total 19965
telemt_me_reconnect_success_total 19855
telemt_me_reader_eof_total 21155
telemt_me_idle_close_by_peer_total 21155
telemt_me_route_drop_no_conn_total 276374
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 778483
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3100
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2126
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 20049
telemt_me_writer_restored_same_endpoint_total 19846
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 780385
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 12396699124 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 295093924819 (274.83 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 104993.0 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1783315
telemt_connections_bad_total 9228
telemt_handshake_timeouts_total 119825
telemt_upstream_connect_attempt_total 24492
telemt_upstream_connect_success_total 24482
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1612
telemt_me_reconnect_attempts_total 20166
telemt_me_reconnect_success_total 18902
telemt_me_reader_eof_total 20020
telemt_me_idle_close_by_peer_total 20019
telemt_me_route_drop_no_conn_total 580678
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1404362
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5028
telemt_desync_full_logged_total 1539
telemt_desync_suppressed_total 3489
telemt_desync_frames_bucket_total{bucket="1_2"} 804
telemt_desync_frames_bucket_total{bucket="3_10"} 1823
telemt_desync_frames_bucket_total{bucket="gt_10"} 2401
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 19079
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18861
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 1403956
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 20287446144 (18.89 GB)
telemt_user_octets_to_client{user="hello"} 504936289073 (470.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 104993.4 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1112264
telemt_connections_bad_total 13139
telemt_handshake_timeouts_total 73424
telemt_upstream_connect_attempt_total 36670
telemt_upstream_connect_success_total 34394
telemt_upstream_connect_fail_total 2139
telemt_upstream_connect_attempts_per_request{bucket="1"} 36396
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2138
telemt_me_keepalive_timeout_total 11364
telemt_me_reconnect_attempts_total 32226
telemt_me_reconnect_success_total 23301
telemt_me_reader_eof_total 25161
telemt_me_idle_close_by_peer_total 25154
telemt_me_route_drop_no_conn_total 394488
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954078
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1899
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1269
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 23732
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23277
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 959248
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 14620566189 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 376480642974 (350.62 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 104993.1 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1230926
telemt_connections_bad_total 12632
telemt_handshake_timeouts_total 9559
telemt_upstream_connect_attempt_total 33160
telemt_upstream_connect_success_total 32754
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 33160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15793
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_keepalive_timeout_total 1900
telemt_me_reconnect_attempts_total 41257
telemt_me_reconnect_success_total 27527
telemt_me_reader_eof_total 28967
telemt_me_idle_close_by_peer_total 28967
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 459669
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1138632
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4230
telemt_desync_full_logged_total 1502
telemt_desync_suppressed_total 2728
telemt_desync_frames_bucket_total{bucket="1_2"} 1273
telemt_desync_frames_bucket_total{bucket="3_10"} 1393
telemt_desync_frames_bucket_total{bucket="gt_10"} 1564
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 28271
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27478
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 1138487
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 14066078896 (13.10 GB)
telemt_user_octets_to_client{user="hello"} 394190281660 (367.12 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 55
```