# Server Metrics 2026-03-15 07:16:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 32505.1 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565572
telemt_connections_bad_total 15926
telemt_handshake_timeouts_total 3850
telemt_upstream_connect_attempt_total 6785
telemt_upstream_connect_success_total 6759
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5152
telemt_me_reconnect_success_total 5126
telemt_me_reader_eof_total 5420
telemt_me_idle_close_by_peer_total 5420
telemt_me_route_drop_no_conn_total 174413
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478165
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1262
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 857
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 461
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5190
telemt_me_writer_restored_same_endpoint_total 5115
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 478173
telemt_user_connections_current{user="hello"} 1514
telemt_user_octets_from_client{user="hello"} 5738960452 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 169751798936 (158.09 GB)
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 32505.8 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206049
telemt_connections_bad_total 18346
telemt_handshake_timeouts_total 6611
telemt_upstream_connect_attempt_total 9058
telemt_upstream_connect_success_total 9012
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 9058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7086
telemt_me_reconnect_success_total 7045
telemt_me_reader_eof_total 7455
telemt_me_idle_close_by_peer_total 7455
telemt_me_route_drop_no_conn_total 53216
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172787
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 398
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7078
telemt_me_writer_restored_same_endpoint_total 7037
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 173075
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 2717908659 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 64036208368 (59.64 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 32505.8 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381563
telemt_connections_bad_total 10889
telemt_handshake_timeouts_total 37053
telemt_upstream_connect_attempt_total 7392
telemt_upstream_connect_success_total 7359
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 5739
telemt_me_reconnect_success_total 5708
telemt_me_reader_eof_total 6044
telemt_me_idle_close_by_peer_total 6044
telemt_me_route_drop_no_conn_total 98183
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311327
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 590
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5773
telemt_me_writer_restored_same_endpoint_total 5689
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 311132
telemt_user_connections_current{user="hello"} 889
telemt_user_octets_from_client{user="hello"} 4809831340 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 129123058268 (120.26 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 32505.7 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253105
telemt_connections_bad_total 44477
telemt_handshake_timeouts_total 16738
telemt_upstream_connect_attempt_total 10723
telemt_upstream_connect_success_total 10472
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 10723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 20117
telemt_me_reconnect_success_total 8825
telemt_me_reader_eof_total 9452
telemt_me_idle_close_by_peer_total 9452
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 61070
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186015
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 296
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 9251
telemt_me_refill_failed_total 352
telemt_me_writer_restored_same_endpoint_total 8799
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 426
telemt_user_connections_total{user="hello"} 186018
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 1638246628 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 63608777608 (59.24 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 32507.1 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191235
telemt_connections_bad_total 378
telemt_handshake_timeouts_total 1841
telemt_upstream_connect_attempt_total 7240
telemt_upstream_connect_success_total 7210
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 5589
telemt_me_reconnect_success_total 5563
telemt_me_reader_eof_total 5937
telemt_me_idle_close_by_peer_total 5937
telemt_me_route_drop_no_conn_total 58129
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179720
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 734
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 499
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5618
telemt_me_writer_restored_same_endpoint_total 5555
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 179727
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 1883929628 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 68723756312 (64.00 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 111
```