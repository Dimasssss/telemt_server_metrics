# Server Metrics 2026-03-10 21:07:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24036.3 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679167
telemt_connections_bad_total 8151
telemt_handshake_timeouts_total 8007
telemt_upstream_connect_attempt_total 5217
telemt_upstream_connect_success_total 5208
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 348
telemt_me_reconnect_attempts_total 15583
telemt_me_reconnect_success_total 3926
telemt_me_reader_eof_total 4340
telemt_me_idle_close_by_peer_total 4340
telemt_me_route_drop_no_conn_total 284083
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641199
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3265
telemt_desync_full_logged_total 898
telemt_desync_suppressed_total 2367
telemt_desync_frames_bucket_total{bucket="1_2"} 918
telemt_desync_frames_bucket_total{bucket="3_10"} 1232
telemt_desync_frames_bucket_total{bucket="gt_10"} 1115
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 4317
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3920
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 641007
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 9130358220 (8.50 GB)
telemt_user_octets_to_client{user="hello"} 194632408920 (181.27 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24092.9 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298195
telemt_connections_bad_total 1853
telemt_handshake_timeouts_total 17179
telemt_upstream_connect_attempt_total 11505
telemt_upstream_connect_success_total 8644
telemt_upstream_connect_fail_total 2861
telemt_upstream_connect_attempts_per_request{bucket="1"} 11505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2861
telemt_me_keepalive_timeout_total 1341
telemt_me_reconnect_attempts_total 5255
telemt_me_reconnect_success_total 4452
telemt_me_reader_eof_total 4653
telemt_me_idle_close_by_peer_total 4651
telemt_me_route_drop_no_conn_total 160099
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250085
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1448
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 1054
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 477
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4533
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4431
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 252349
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 2572837390 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 59445459672 (55.36 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 24092.8 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483888
telemt_connections_bad_total 2576
telemt_handshake_timeouts_total 33252
telemt_upstream_connect_attempt_total 6888
telemt_upstream_connect_success_total 6782
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 6888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 15511
telemt_me_reconnect_success_total 4469
telemt_me_reader_eof_total 4938
telemt_me_idle_close_by_peer_total 4938
telemt_me_route_drop_no_conn_total 167917
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421753
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1377
telemt_desync_full_logged_total 383
telemt_desync_suppressed_total 994
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4890
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4458
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 422691
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 6156707989 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 134757705677 (125.50 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 24093.2 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330908
telemt_connections_bad_total 23473
telemt_handshake_timeouts_total 28440
telemt_upstream_connect_attempt_total 6463
telemt_upstream_connect_success_total 6463
telemt_upstream_connect_attempts_per_request{bucket="1"} 6463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 6242
telemt_me_reconnect_success_total 5222
telemt_me_reader_eof_total 5480
telemt_me_idle_close_by_peer_total 5480
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 107480
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266641
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 675
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 5308
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5209
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 266320
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 3901840944 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 82242429420 (76.59 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 24093.0 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350892
telemt_connections_bad_total 1041
telemt_handshake_timeouts_total 2226
telemt_upstream_connect_attempt_total 7457
telemt_upstream_connect_success_total 7428
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 9912
telemt_me_reconnect_success_total 6158
telemt_me_reader_eof_total 6452
telemt_me_idle_close_by_peer_total 6452
telemt_me_route_drop_no_conn_total 126094
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329512
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1926
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 738
telemt_desync_frames_bucket_total{bucket="3_10"} 809
telemt_desync_frames_bucket_total{bucket="gt_10"} 379
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6365
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6158
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 329400
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 6234178612 (5.81 GB)
telemt_user_octets_to_client{user="hello"} 114735402908 (106.86 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 59
```