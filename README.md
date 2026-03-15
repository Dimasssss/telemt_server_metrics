# Server Metrics 2026-03-15 08:17:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 36181.2 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706181
telemt_connections_bad_total 28283
telemt_handshake_timeouts_total 4936
telemt_upstream_connect_attempt_total 7530
telemt_upstream_connect_success_total 7501
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5703
telemt_me_reconnect_success_total 5673
telemt_me_reader_eof_total 6002
telemt_me_idle_close_by_peer_total 6002
telemt_me_route_drop_no_conn_total 226109
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597243
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1753
telemt_desync_full_logged_total 546
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 733
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5748
telemt_me_writer_restored_same_endpoint_total 5662
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 597245
telemt_user_connections_current{user="hello"} 1730
telemt_user_octets_from_client{user="hello"} 7524718900 (7.01 GB)
telemt_user_octets_to_client{user="hello"} 224780502844 (209.34 GB)
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 36182.2 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275478
telemt_connections_bad_total 18437
telemt_handshake_timeouts_total 11302
telemt_upstream_connect_attempt_total 9873
telemt_upstream_connect_success_total 9824
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 9873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7721
telemt_me_reconnect_success_total 7673
telemt_me_reader_eof_total 8133
telemt_me_idle_close_by_peer_total 8133
telemt_me_route_drop_no_conn_total 69605
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218171
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 822
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7726
telemt_me_writer_restored_same_endpoint_total 7665
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 218449
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 3259140571 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 80726556652 (75.18 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 36182.3 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476633
telemt_connections_bad_total 14096
telemt_handshake_timeouts_total 42791
telemt_upstream_connect_attempt_total 8121
telemt_upstream_connect_success_total 8084
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 6286
telemt_me_reconnect_success_total 6247
telemt_me_reader_eof_total 6617
telemt_me_idle_close_by_peer_total 6617
telemt_me_route_drop_no_conn_total 128961
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386942
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 730
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 442
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6324
telemt_me_writer_restored_same_endpoint_total 6228
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 386483
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 5753981144 (5.36 GB)
telemt_user_octets_to_client{user="hello"} 163087472924 (151.89 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 36182.0 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304885
telemt_connections_bad_total 47561
telemt_handshake_timeouts_total 21006
telemt_upstream_connect_attempt_total 11574
telemt_upstream_connect_success_total 11304
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 11574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 22116
telemt_me_reconnect_success_total 9475
telemt_me_reader_eof_total 10171
telemt_me_idle_close_by_peer_total 10171
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 78992
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227362
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 9946
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9448
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 227362
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 1981135828 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 76439148176 (71.19 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 36183.2 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257523
telemt_connections_bad_total 3626
telemt_handshake_timeouts_total 2469
telemt_upstream_connect_attempt_total 8001
telemt_upstream_connect_success_total 7968
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 6172
telemt_me_reconnect_success_total 6144
telemt_me_reader_eof_total 6553
telemt_me_idle_close_by_peer_total 6553
telemt_me_route_drop_no_conn_total 74861
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230331
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 945
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 642
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 388
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6205
telemt_me_writer_restored_same_endpoint_total 6136
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 230342
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 2488156620 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 91443432112 (85.16 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 108
```