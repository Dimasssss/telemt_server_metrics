# Server Metrics 2026-03-15 05:14:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 25173.6 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328705
telemt_connections_bad_total 4890
telemt_handshake_timeouts_total 1516
telemt_upstream_connect_attempt_total 5380
telemt_upstream_connect_success_total 5360
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 5380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 4133
telemt_me_reconnect_success_total 4112
telemt_me_reader_eof_total 4347
telemt_me_idle_close_by_peer_total 4347
telemt_me_route_drop_no_conn_total 104994
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292768
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 710
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 493
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4160
telemt_me_writer_restored_same_endpoint_total 4101
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 292786
telemt_user_connections_current{user="hello"} 1085
telemt_user_octets_from_client{user="hello"} 3249147096 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 106559841772 (99.24 GB)
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 25174.4 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127949
telemt_connections_bad_total 18273
telemt_handshake_timeouts_total 4452
telemt_upstream_connect_attempt_total 7494
telemt_upstream_connect_success_total 7460
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 5923
telemt_me_reconnect_success_total 5894
telemt_me_reader_eof_total 6226
telemt_me_idle_close_by_peer_total 6226
telemt_me_route_drop_no_conn_total 28617
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102011
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 268
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5903
telemt_me_writer_restored_same_endpoint_total 5886
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 102307
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 1902040663 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 32650678456 (30.41 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 25174.6 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237098
telemt_connections_bad_total 4195
telemt_handshake_timeouts_total 25916
telemt_upstream_connect_attempt_total 5829
telemt_upstream_connect_success_total 5804
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 4572
telemt_me_reconnect_success_total 4549
telemt_me_reader_eof_total 4814
telemt_me_idle_close_by_peer_total 4814
telemt_me_route_drop_no_conn_total 56157
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198167
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 328
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4596
telemt_me_writer_restored_same_endpoint_total 4530
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 197990
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 2486596808 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 71618049184 (66.70 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 25174.3 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175689
telemt_connections_bad_total 35418
telemt_handshake_timeouts_total 12675
telemt_upstream_connect_attempt_total 8675
telemt_upstream_connect_success_total 8495
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 8675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12014
telemt_me_reconnect_success_total 7242
telemt_me_reader_eof_total 7642
telemt_me_idle_close_by_peer_total 7642
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 38129
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124385
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 201
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 7451
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7219
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 124388
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 1026619640 (979.06 MB)
telemt_user_octets_to_client{user="hello"} 44142720560 (41.11 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 25175.1 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112539
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 1287
telemt_upstream_connect_attempt_total 5773
telemt_upstream_connect_success_total 5749
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4517
telemt_me_reconnect_success_total 4498
telemt_me_reader_eof_total 4795
telemt_me_idle_close_by_peer_total 4795
telemt_me_route_drop_no_conn_total 30761
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107478
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 441
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 306
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4541
telemt_me_writer_restored_same_endpoint_total 4490
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 107476
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 1037030380 (988.99 MB)
telemt_user_octets_to_client{user="hello"} 36544027572 (34.03 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 56
```