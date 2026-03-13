# Server Metrics 2026-03-13 01:12:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 69256.0 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2023438
telemt_connections_bad_total 26124
telemt_handshake_timeouts_total 21618
telemt_upstream_connect_attempt_total 13723
telemt_upstream_connect_success_total 13644
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1249
telemt_me_reconnect_attempts_total 19052
telemt_me_reconnect_success_total 10193
telemt_me_reader_eof_total 11024
telemt_me_idle_close_by_peer_total 11023
telemt_me_route_drop_no_conn_total 789490
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1882508
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8674
telemt_desync_full_logged_total 2259
telemt_desync_suppressed_total 6415
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3126
telemt_desync_frames_bucket_total{bucket="gt_10"} 3260
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10614
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10180
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 1881965
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 27617379320 (25.72 GB)
telemt_user_octets_to_client{user="hello"} 658981475636 (613.72 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 98876.4 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 833553
telemt_connections_bad_total 11757
telemt_handshake_timeouts_total 31958
telemt_upstream_connect_attempt_total 25180
telemt_upstream_connect_success_total 25151
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3444
telemt_me_reconnect_attempts_total 18691
telemt_me_reconnect_success_total 18587
telemt_me_reader_eof_total 19789
telemt_me_idle_close_by_peer_total 19789
telemt_me_route_drop_no_conn_total 269157
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754987
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3056
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 2098
telemt_desync_frames_bucket_total{bucket="1_2"} 1236
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 18769
telemt_me_writer_restored_same_endpoint_total 18578
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 756890
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 12235549672 (11.40 GB)
telemt_user_octets_to_client{user="hello"} 286000730339 (266.36 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 98876.4 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1733304
telemt_connections_bad_total 8965
telemt_handshake_timeouts_total 114547
telemt_upstream_connect_attempt_total 23066
telemt_upstream_connect_success_total 23056
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1584
telemt_me_reconnect_attempts_total 19044
telemt_me_reconnect_success_total 17782
telemt_me_reader_eof_total 18818
telemt_me_idle_close_by_peer_total 18817
telemt_me_route_drop_no_conn_total 568230
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1360958
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17952
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17741
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 1360556
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 20046721500 (18.67 GB)
telemt_user_octets_to_client{user="hello"} 495360642481 (461.34 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 98876.6 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1086842
telemt_connections_bad_total 13093
telemt_handshake_timeouts_total 72409
telemt_upstream_connect_attempt_total 34418
telemt_upstream_connect_success_total 32153
telemt_upstream_connect_fail_total 2128
telemt_upstream_connect_attempts_per_request{bucket="1"} 34144
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2127
telemt_me_keepalive_timeout_total 11270
telemt_me_reconnect_attempts_total 29216
telemt_me_reconnect_success_total 21375
telemt_me_reader_eof_total 23128
telemt_me_idle_close_by_peer_total 23121
telemt_me_route_drop_no_conn_total 384202
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931190
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 21754
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21353
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 936378
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 14441527481 (13.45 GB)
telemt_user_octets_to_client{user="hello"} 368694008654 (343.37 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 98876.6 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1196767
telemt_connections_bad_total 12582
telemt_handshake_timeouts_total 9365
telemt_upstream_connect_attempt_total 29988
telemt_upstream_connect_success_total 29613
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 29988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_keepalive_timeout_total 1841
telemt_me_reconnect_attempts_total 35738
telemt_me_reconnect_success_total 24692
telemt_me_reader_eof_total 25981
telemt_me_idle_close_by_peer_total 25981
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 448290
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1105349
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4137
telemt_desync_full_logged_total 1465
telemt_desync_suppressed_total 2672
telemt_desync_frames_bucket_total{bucket="1_2"} 1229
telemt_desync_frames_bucket_total{bucket="3_10"} 1375
telemt_desync_frames_bucket_total{bucket="gt_10"} 1533
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 25326
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24646
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 1105205
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 13698223084 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 381931455760 (355.70 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 83
```