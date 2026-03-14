# Server Metrics 2026-03-14 01:02:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 155035.6 (43h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4619720
telemt_connections_bad_total 39185
telemt_handshake_timeouts_total 107945
telemt_upstream_connect_attempt_total 32781
telemt_upstream_connect_success_total 32563
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 32781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 6671
telemt_me_reconnect_attempts_total 32620
telemt_me_reconnect_success_total 22487
telemt_me_reader_eof_total 24114
telemt_me_idle_close_by_peer_total 24113
telemt_me_route_drop_no_conn_total 1750103
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4234925
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16662
telemt_desync_full_logged_total 4493
telemt_desync_suppressed_total 12169
telemt_desync_frames_bucket_total{bucket="1_2"} 4152
telemt_desync_frames_bucket_total{bucket="3_10"} 6368
telemt_desync_frames_bucket_total{bucket="gt_10"} 6142
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 23125
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22474
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 4236790
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 62480031560 (58.19 GB)
telemt_user_octets_to_client{user="hello"} 1339116985957 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 54699.1 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664636
telemt_connections_bad_total 49685
telemt_handshake_timeouts_total 12910
telemt_upstream_connect_attempt_total 15310
telemt_upstream_connect_success_total 15064
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 15310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 2020
telemt_me_reconnect_attempts_total 13746
telemt_me_reconnect_success_total 10304
telemt_me_reader_eof_total 10928
telemt_me_idle_close_by_peer_total 10927
telemt_me_route_drop_no_conn_total 228335
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541445
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10557
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10296
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 543396
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 5873970765 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 176240138040 (164.14 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 184655.8 (51h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3346078
telemt_connections_bad_total 34283
telemt_handshake_timeouts_total 222573
telemt_upstream_connect_attempt_total 41386
telemt_upstream_connect_success_total 41365
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10358
telemt_me_reconnect_attempts_total 36797
telemt_me_reconnect_success_total 31840
telemt_me_reader_eof_total 33807
telemt_me_idle_close_by_peer_total 33806
telemt_me_route_drop_no_conn_total 1148315
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2781579
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9165
telemt_desync_full_logged_total 3077
telemt_desync_suppressed_total 6088
telemt_desync_frames_bucket_total{bucket="1_2"} 1543
telemt_desync_frames_bucket_total{bucket="3_10"} 3318
telemt_desync_frames_bucket_total{bucket="gt_10"} 4304
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 32295
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31799
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2780824
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 44939860204 (41.85 GB)
telemt_user_octets_to_client{user="hello"} 989374641649 (921.43 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 184658.6 (51h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2224175
telemt_connections_bad_total 22922
telemt_handshake_timeouts_total 239813
telemt_upstream_connect_attempt_total 57512
telemt_upstream_connect_success_total 55053
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 57238
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20388
telemt_me_reconnect_attempts_total 47848
telemt_me_reconnect_success_total 38821
telemt_me_reader_eof_total 41639
telemt_me_idle_close_by_peer_total 41632
telemt_me_route_drop_no_conn_total 766303
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1785599
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3801
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 39437
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38797
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 1791516
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 27401678575 (25.52 GB)
telemt_user_octets_to_client{user="hello"} 663725892946 (618.14 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 54091.9 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679920
telemt_connections_bad_total 7884
telemt_handshake_timeouts_total 8615
telemt_upstream_connect_attempt_total 13270
telemt_upstream_connect_success_total 12889
telemt_upstream_connect_fail_total 380
telemt_upstream_connect_attempts_per_request{bucket="1"} 13269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 380
telemt_me_keepalive_timeout_total 1469
telemt_me_reconnect_attempts_total 42327
telemt_me_reconnect_success_total 10170
telemt_me_reader_eof_total 11400
telemt_me_idle_close_by_peer_total 11399
telemt_me_route_drop_no_conn_total 257086
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632488
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1126
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 11263
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10165
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1093
telemt_user_connections_total{user="hello"} 632387
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 10553721680 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 207437951288 (193.19 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 14
```