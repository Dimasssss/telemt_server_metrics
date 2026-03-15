# Server Metrics 2026-03-15 08:37:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 37406.3 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756959
telemt_connections_bad_total 30376
telemt_handshake_timeouts_total 5368
telemt_upstream_connect_attempt_total 7693
telemt_upstream_connect_success_total 7661
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5820
telemt_me_reconnect_success_total 5789
telemt_me_reader_eof_total 6123
telemt_me_idle_close_by_peer_total 6123
telemt_me_route_drop_no_conn_total 244465
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642922
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1953
telemt_desync_full_logged_total 611
telemt_desync_suppressed_total 1342
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 811
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5865
telemt_me_writer_restored_same_endpoint_total 5778
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 642912
telemt_user_connections_current{user="hello"} 1882
telemt_user_octets_from_client{user="hello"} 8605444996 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 239709177004 (223.25 GB)
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 37407.2 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298616
telemt_connections_bad_total 18442
telemt_handshake_timeouts_total 12323
telemt_upstream_connect_attempt_total 10086
telemt_upstream_connect_success_total 10036
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 10086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7888
telemt_me_reconnect_success_total 7840
telemt_me_reader_eof_total 8304
telemt_me_idle_close_by_peer_total 8304
telemt_me_route_drop_no_conn_total 75257
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235656
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 866
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7897
telemt_me_writer_restored_same_endpoint_total 7832
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 235933
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 3425673015 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 87620803820 (81.60 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 37407.2 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516019
telemt_connections_bad_total 15797
telemt_handshake_timeouts_total 45701
telemt_upstream_connect_attempt_total 8342
telemt_upstream_connect_success_total 8305
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 6464
telemt_me_reconnect_success_total 6423
telemt_me_reader_eof_total 6804
telemt_me_idle_close_by_peer_total 6804
telemt_me_route_drop_no_conn_total 140405
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414795
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 834
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 512
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6502
telemt_me_writer_restored_same_endpoint_total 6404
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 414327
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 6135428684 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 173876937956 (161.94 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 37407.1 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324038
telemt_connections_bad_total 48505
telemt_handshake_timeouts_total 22021
telemt_upstream_connect_attempt_total 11961
telemt_upstream_connect_success_total 11689
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 11961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 22457
telemt_me_reconnect_success_total 9814
telemt_me_reader_eof_total 10514
telemt_me_idle_close_by_peer_total 10514
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 85868
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241863
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 531
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 394
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10290
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9785
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 241866
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 2121723380 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 79788731904 (74.31 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 37408.1 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287007
telemt_connections_bad_total 3668
telemt_handshake_timeouts_total 3017
telemt_upstream_connect_attempt_total 8290
telemt_upstream_connect_success_total 8256
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 8290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 6417
telemt_me_reconnect_success_total 6388
telemt_me_reader_eof_total 6815
telemt_me_idle_close_by_peer_total 6815
telemt_me_route_drop_no_conn_total 80543
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248884
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 985
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 663
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 402
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6452
telemt_me_writer_restored_same_endpoint_total 6380
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 248894
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 2792505904 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 96917855736 (90.26 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 109
```