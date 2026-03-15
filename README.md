# Server Metrics 2026-03-15 08:12:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 35875.2 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694545
telemt_connections_bad_total 28242
telemt_handshake_timeouts_total 4869
telemt_upstream_connect_attempt_total 7438
telemt_upstream_connect_success_total 7410
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 7438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5655
telemt_me_reconnect_success_total 5626
telemt_me_reader_eof_total 5944
telemt_me_idle_close_by_peer_total 5944
telemt_me_route_drop_no_conn_total 221344
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586124
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1697
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1165
telemt_desync_frames_bucket_total{bucket="1_2"} 370
telemt_desync_frames_bucket_total{bucket="3_10"} 617
telemt_desync_frames_bucket_total{bucket="gt_10"} 710
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5700
telemt_me_writer_restored_same_endpoint_total 5615
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 586129
telemt_user_connections_current{user="hello"} 1794
telemt_user_octets_from_client{user="hello"} 7410139116 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 220070894940 (204.96 GB)
telemt_user_unique_ips_current{user="hello"} 543
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 35876.1 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270217
telemt_connections_bad_total 18434
telemt_handshake_timeouts_total 10982
telemt_upstream_connect_attempt_total 9781
telemt_upstream_connect_success_total 9733
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7673
telemt_me_reconnect_success_total 7627
telemt_me_reader_eof_total 8075
telemt_me_idle_close_by_peer_total 8075
telemt_me_route_drop_no_conn_total 68177
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214035
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 810
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7676
telemt_me_writer_restored_same_endpoint_total 7619
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 214315
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 3191570287 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 79213525272 (73.77 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 35876.2 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468353
telemt_connections_bad_total 13857
telemt_handshake_timeouts_total 42309
telemt_upstream_connect_attempt_total 8023
telemt_upstream_connect_success_total 7988
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 6233
telemt_me_reconnect_success_total 6196
telemt_me_reader_eof_total 6557
telemt_me_idle_close_by_peer_total 6557
telemt_me_route_drop_no_conn_total 126664
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380553
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 711
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 432
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6271
telemt_me_writer_restored_same_endpoint_total 6177
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 380093
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 5708044848 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 159534242376 (148.58 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 35876.0 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300200
telemt_connections_bad_total 47326
telemt_handshake_timeouts_total 20901
telemt_upstream_connect_attempt_total 11474
telemt_upstream_connect_success_total 11212
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 11474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 22067
telemt_me_reconnect_success_total 9426
telemt_me_reader_eof_total 10122
telemt_me_idle_close_by_peer_total 10122
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 77268
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223755
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 420
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 308
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 9897
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9399
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 223756
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 1951667220 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 75204130096 (70.04 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 35876.9 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251478
telemt_connections_bad_total 3625
telemt_handshake_timeouts_total 2414
telemt_upstream_connect_attempt_total 7900
telemt_upstream_connect_success_total 7868
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 6116
telemt_me_reconnect_success_total 6088
telemt_me_reader_eof_total 6497
telemt_me_idle_close_by_peer_total 6497
telemt_me_route_drop_no_conn_total 73453
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225730
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 921
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 627
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 388
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6149
telemt_me_writer_restored_same_endpoint_total 6080
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 225749
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 2440862580 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 90052146544 (83.87 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 101
```