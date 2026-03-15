# Server Metrics 2026-03-15 02:20:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 14783.9 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180469
telemt_connections_bad_total 2222
telemt_handshake_timeouts_total 565
telemt_upstream_connect_attempt_total 3170
telemt_upstream_connect_success_total 3160
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 2408
telemt_me_reconnect_success_total 2395
telemt_me_reader_eof_total 2525
telemt_me_idle_close_by_peer_total 2525
telemt_me_route_drop_no_conn_total 55924
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159025
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 437
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2422
telemt_me_writer_restored_same_endpoint_total 2384
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 159012
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 1764764492 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 53581556004 (49.90 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 14784.3 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75493
telemt_connections_bad_total 13351
telemt_handshake_timeouts_total 3566
telemt_upstream_connect_attempt_total 4371
telemt_upstream_connect_success_total 4351
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 3294
telemt_me_reconnect_success_total 3274
telemt_me_reader_eof_total 3426
telemt_me_idle_close_by_peer_total 3426
telemt_me_route_drop_no_conn_total 14445
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56609
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3252
telemt_me_writer_restored_same_endpoint_total 3266
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 56905
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 1543068511 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 16370123112 (15.25 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 14784.6 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123724
telemt_connections_bad_total 2361
telemt_handshake_timeouts_total 11428
telemt_upstream_connect_attempt_total 3470
telemt_upstream_connect_success_total 3453
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 2698
telemt_me_reconnect_success_total 2687
telemt_me_reader_eof_total 2836
telemt_me_idle_close_by_peer_total 2836
telemt_me_route_drop_no_conn_total 26808
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107404
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 248
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2716
telemt_me_writer_restored_same_endpoint_total 2668
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 107315
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 1036188284 (988.19 MB)
telemt_user_octets_to_client{user="hello"} 35294354672 (32.87 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 14784.5 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104773
telemt_connections_bad_total 27357
telemt_handshake_timeouts_total 2631
telemt_upstream_connect_attempt_total 5558
telemt_upstream_connect_success_total 5438
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 5558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8218
telemt_me_reconnect_success_total 4670
telemt_me_reader_eof_total 4911
telemt_me_idle_close_by_peer_total 4911
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 19693
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73147
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4821
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4651
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 73149
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 430391064 (410.45 MB)
telemt_user_octets_to_client{user="hello"} 14235375392 (13.26 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 14784.9 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62383
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 722
telemt_upstream_connect_attempt_total 3372
telemt_upstream_connect_success_total 3356
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2601
telemt_me_reconnect_success_total 2592
telemt_me_reader_eof_total 2746
telemt_me_idle_close_by_peer_total 2746
telemt_me_route_drop_no_conn_total 15628
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59823
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 213
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2611
telemt_me_writer_restored_same_endpoint_total 2584
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 59822
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 530954416 (506.36 MB)
telemt_user_octets_to_client{user="hello"} 20421941816 (19.02 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 35
```