# Server Metrics 2026-03-13 06:29:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 88229.9 (24h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2380111
telemt_connections_bad_total 36041
telemt_handshake_timeouts_total 25372
telemt_upstream_connect_attempt_total 17273
telemt_upstream_connect_success_total 17177
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 1324
telemt_me_reconnect_attempts_total 21673
telemt_me_reconnect_success_total 12803
telemt_me_reader_eof_total 13812
telemt_me_idle_close_by_peer_total 13811
telemt_me_route_drop_no_conn_total 901783
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2190136
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9892
telemt_desync_full_logged_total 2540
telemt_desync_suppressed_total 7352
telemt_desync_frames_bucket_total{bucket="1_2"} 2541
telemt_desync_frames_bucket_total{bucket="3_10"} 3630
telemt_desync_frames_bucket_total{bucket="gt_10"} 3721
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 13259
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12790
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 2189533
telemt_user_connections_current{user="hello"} 1452
telemt_user_octets_from_client{user="hello"} 31662558140 (29.49 GB)
telemt_user_octets_to_client{user="hello"} 744162089840 (693.05 GB)
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 117850.5 (32h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959124
telemt_connections_bad_total 12491
telemt_handshake_timeouts_total 41302
telemt_upstream_connect_attempt_total 29659
telemt_upstream_connect_success_total 29628
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3576
telemt_me_reconnect_attempts_total 22263
telemt_me_reconnect_success_total 22144
telemt_me_reader_eof_total 23610
telemt_me_idle_close_by_peer_total 23610
telemt_me_route_drop_no_conn_total 305461
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 866460
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3572
telemt_desync_full_logged_total 1115
telemt_desync_suppressed_total 2457
telemt_desync_frames_bucket_total{bucket="1_2"} 1380
telemt_desync_frames_bucket_total{bucket="3_10"} 1160
telemt_desync_frames_bucket_total{bucket="gt_10"} 1032
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 22364
telemt_me_writer_restored_same_endpoint_total 22135
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 868371
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 13643988032 (12.71 GB)
telemt_user_octets_to_client{user="hello"} 329869820503 (307.22 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 117850.4 (32h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1980751
telemt_connections_bad_total 22785
telemt_handshake_timeouts_total 133232
telemt_upstream_connect_attempt_total 27252
telemt_upstream_connect_success_total 27242
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1684
telemt_me_reconnect_attempts_total 22319
telemt_me_reconnect_success_total 21046
telemt_me_reader_eof_total 22293
telemt_me_idle_close_by_peer_total 22292
telemt_me_route_drop_no_conn_total 633558
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1560346
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5386
telemt_desync_full_logged_total 1633
telemt_desync_suppressed_total 3753
telemt_desync_frames_bucket_total{bucket="1_2"} 891
telemt_desync_frames_bucket_total{bucket="3_10"} 1959
telemt_desync_frames_bucket_total{bucket="gt_10"} 2536
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 21249
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21005
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 1559841
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 26624575520 (24.80 GB)
telemt_user_octets_to_client{user="hello"} 553906801277 (515.87 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 117850.7 (32h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1208212
telemt_connections_bad_total 13996
telemt_handshake_timeouts_total 78185
telemt_upstream_connect_attempt_total 40040
telemt_upstream_connect_success_total 37752
telemt_upstream_connect_fail_total 2151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39766
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2150
telemt_me_keepalive_timeout_total 11418
telemt_me_reconnect_attempts_total 34978
telemt_me_reconnect_success_total 26043
telemt_me_reader_eof_total 28072
telemt_me_idle_close_by_peer_total 28065
telemt_me_route_drop_no_conn_total 432599
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1038598
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2062
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 794
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 26500
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26019
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 1043518
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 15914342597 (14.82 GB)
telemt_user_octets_to_client{user="hello"} 416251601218 (387.66 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 117850.5 (32h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1362808
telemt_connections_bad_total 18900
telemt_handshake_timeouts_total 11121
telemt_upstream_connect_attempt_total 37271
telemt_upstream_connect_success_total 36820
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 37271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17895
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2033
telemt_me_reconnect_attempts_total 44713
telemt_me_reconnect_success_total 30976
telemt_me_reader_eof_total 32528
telemt_me_idle_close_by_peer_total 32528
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 500851
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1257436
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 46
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4501
telemt_desync_full_logged_total 1616
telemt_desync_suppressed_total 2885
telemt_desync_frames_bucket_total{bucket="1_2"} 1367
telemt_desync_frames_bucket_total{bucket="3_10"} 1460
telemt_desync_frames_bucket_total{bucket="gt_10"} 1674
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 31745
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30922
telemt_me_writer_restored_fallback_total 54
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1257277
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 15152763356 (14.11 GB)
telemt_user_octets_to_client{user="hello"} 432545046540 (402.84 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 98
```