# Server Metrics 2026-03-15 03:32:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 19064.7 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232389
telemt_connections_bad_total 3162
telemt_handshake_timeouts_total 1075
telemt_upstream_connect_attempt_total 4051
telemt_upstream_connect_success_total 4036
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 3069
telemt_me_reconnect_success_total 3055
telemt_me_reader_eof_total 3231
telemt_me_idle_close_by_peer_total 3231
telemt_me_route_drop_no_conn_total 71781
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205606
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 541
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3090
telemt_me_writer_restored_same_endpoint_total 3044
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 205582
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 2208602360 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 73387009016 (68.35 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 19065.2 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92934
telemt_connections_bad_total 15483
telemt_handshake_timeouts_total 3779
telemt_upstream_connect_attempt_total 5692
telemt_upstream_connect_success_total 5668
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4395
telemt_me_reconnect_success_total 4373
telemt_me_reader_eof_total 4613
telemt_me_idle_close_by_peer_total 4613
telemt_me_route_drop_no_conn_total 18654
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71366
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 128
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4363
telemt_me_writer_restored_same_endpoint_total 4365
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 71662
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1634111623 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 21537478556 (20.06 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 19065.6 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160988
telemt_connections_bad_total 3101
telemt_handshake_timeouts_total 15341
telemt_upstream_connect_attempt_total 4419
telemt_upstream_connect_success_total 4400
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 3428
telemt_me_reconnect_success_total 3412
telemt_me_reader_eof_total 3604
telemt_me_idle_close_by_peer_total 3604
telemt_me_route_drop_no_conn_total 34847
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139642
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 273
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3448
telemt_me_writer_restored_same_endpoint_total 3393
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 139542
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 1203618540 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 42185351384 (39.29 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 19065.4 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129596
telemt_connections_bad_total 30675
telemt_handshake_timeouts_total 4432
telemt_upstream_connect_attempt_total 6653
telemt_upstream_connect_success_total 6516
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 6653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9079
telemt_me_reconnect_success_total 5527
telemt_me_reader_eof_total 5827
telemt_me_idle_close_by_peer_total 5827
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 26064
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92596
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5689
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5508
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 92605
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 684597948 (652.88 MB)
telemt_user_octets_to_client{user="hello"} 25102038916 (23.38 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 19066.1 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79101
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 1009
telemt_upstream_connect_attempt_total 4409
telemt_upstream_connect_success_total 4390
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 3418
telemt_me_reconnect_success_total 3405
telemt_me_reader_eof_total 3628
telemt_me_idle_close_by_peer_total 3628
telemt_me_route_drop_no_conn_total 20872
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75624
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 269
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 192
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 105
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3436
telemt_me_writer_restored_same_endpoint_total 3397
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 75622
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 635869280 (606.41 MB)
telemt_user_octets_to_client{user="hello"} 24186421432 (22.53 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 40
```