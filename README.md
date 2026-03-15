# Server Metrics 2026-03-15 02:05:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 13868.0 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170407
telemt_connections_bad_total 1921
telemt_handshake_timeouts_total 557
telemt_upstream_connect_attempt_total 2960
telemt_upstream_connect_success_total 2951
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2242
telemt_me_reconnect_success_total 2230
telemt_me_reader_eof_total 2348
telemt_me_idle_close_by_peer_total 2348
telemt_me_route_drop_no_conn_total 52691
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149998
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 393
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2257
telemt_me_writer_restored_same_endpoint_total 2219
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 149986
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 1669290208 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 50684744040 (47.20 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 13868.5 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71770
telemt_connections_bad_total 12632
telemt_handshake_timeouts_total 3500
telemt_upstream_connect_attempt_total 4127
telemt_upstream_connect_success_total 4109
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1830
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3095
telemt_me_reconnect_success_total 3076
telemt_me_reader_eof_total 3215
telemt_me_idle_close_by_peer_total 3215
telemt_me_route_drop_no_conn_total 13735
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53723
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3051
telemt_me_writer_restored_same_endpoint_total 3068
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 54019
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 1534768591 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 16139349400 (15.03 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 13868.7 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115849
telemt_connections_bad_total 2344
telemt_handshake_timeouts_total 10396
telemt_upstream_connect_attempt_total 3240
telemt_upstream_connect_success_total 3224
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2512
telemt_me_reconnect_success_total 2503
telemt_me_reader_eof_total 2638
telemt_me_idle_close_by_peer_total 2638
telemt_me_route_drop_no_conn_total 25574
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100679
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 229
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2530
telemt_me_writer_restored_same_endpoint_total 2484
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 100590
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 999068620 (952.79 MB)
telemt_user_octets_to_client{user="hello"} 33241972028 (30.96 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 13868.6 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100119
telemt_connections_bad_total 26656
telemt_handshake_timeouts_total 2620
telemt_upstream_connect_attempt_total 5268
telemt_upstream_connect_success_total 5153
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 5268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7976
telemt_me_reconnect_success_total 4429
telemt_me_reader_eof_total 4651
telemt_me_idle_close_by_peer_total 4651
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 18694
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69249
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 4578
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4411
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 69251
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 409009056 (390.06 MB)
telemt_user_octets_to_client{user="hello"} 12626348508 (11.76 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 13869.3 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58907
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 715
telemt_upstream_connect_attempt_total 3138
telemt_upstream_connect_success_total 3123
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 2411
telemt_me_reconnect_success_total 2402
telemt_me_reader_eof_total 2543
telemt_me_idle_close_by_peer_total 2543
telemt_me_route_drop_no_conn_total 14602
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56446
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 204
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2421
telemt_me_writer_restored_same_endpoint_total 2394
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 56445
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 508018944 (484.48 MB)
telemt_user_octets_to_client{user="hello"} 19406207536 (18.07 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 26
```