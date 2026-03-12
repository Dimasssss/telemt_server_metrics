# Server Metrics 2026-03-12 17:43:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 42307.5 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1527400
telemt_connections_bad_total 20345
telemt_handshake_timeouts_total 14275
telemt_upstream_connect_attempt_total 8309
telemt_upstream_connect_success_total 8261
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 8309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 14968
telemt_me_reconnect_success_total 6124
telemt_me_reader_eof_total 6646
telemt_me_idle_close_by_peer_total 6645
telemt_me_route_drop_no_conn_total 593442
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1431481
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7260
telemt_desync_full_logged_total 1847
telemt_desync_suppressed_total 5413
telemt_desync_frames_bucket_total{bucket="1_2"} 1880
telemt_desync_frames_bucket_total{bucket="3_10"} 2630
telemt_desync_frames_bucket_total{bucket="gt_10"} 2750
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6483
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6111
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 1430977
telemt_user_connections_current{user="hello"} 1651
telemt_user_octets_from_client{user="hello"} 21839279420 (20.34 GB)
telemt_user_octets_to_client{user="hello"} 457067505056 (425.68 GB)
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71927.8 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664336
telemt_connections_bad_total 8607
telemt_handshake_timeouts_total 29103
telemt_upstream_connect_attempt_total 18514
telemt_upstream_connect_success_total 18485
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 18514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 2608
telemt_me_reconnect_attempts_total 13325
telemt_me_reconnect_success_total 13242
telemt_me_reader_eof_total 14080
telemt_me_idle_close_by_peer_total 14080
telemt_me_route_drop_no_conn_total 208671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 596353
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2499
telemt_desync_full_logged_total 765
telemt_desync_suppressed_total 1734
telemt_desync_frames_bucket_total{bucket="1_2"} 1037
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 646
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 13381
telemt_me_writer_restored_same_endpoint_total 13233
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 598375
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 9089498952 (8.47 GB)
telemt_user_octets_to_client{user="hello"} 225374525119 (209.90 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 71927.7 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1380986
telemt_connections_bad_total 6716
telemt_handshake_timeouts_total 97790
telemt_upstream_connect_attempt_total 17101
telemt_upstream_connect_success_total 17096
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1138
telemt_me_reconnect_attempts_total 14382
telemt_me_reconnect_success_total 13144
telemt_me_reader_eof_total 13855
telemt_me_idle_close_by_peer_total 13854
telemt_me_route_drop_no_conn_total 447691
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1046762
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4420
telemt_desync_full_logged_total 1374
telemt_desync_suppressed_total 3046
telemt_desync_frames_bucket_total{bucket="1_2"} 680
telemt_desync_frames_bucket_total{bucket="3_10"} 1613
telemt_desync_frames_bucket_total{bucket="gt_10"} 2127
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13252
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13103
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 1046632
telemt_user_connections_current{user="hello"} 925
telemt_user_octets_from_client{user="hello"} 15686061740 (14.61 GB)
telemt_user_octets_to_client{user="hello"} 365658435701 (340.55 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 71928.3 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 833765
telemt_connections_bad_total 9913
telemt_handshake_timeouts_total 63731
telemt_upstream_connect_attempt_total 18776
telemt_upstream_connect_success_total 18704
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 18776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 1584
telemt_me_reconnect_attempts_total 20367
telemt_me_reconnect_success_total 15113
telemt_me_reader_eof_total 16075
telemt_me_idle_close_by_peer_total 16075
telemt_me_route_drop_no_conn_total 291982
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 722248
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1617
telemt_desync_full_logged_total 541
telemt_desync_suppressed_total 1076
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15394
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 15092
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 721664
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 8867149048 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 292877321728 (272.76 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71928.0 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940047
telemt_connections_bad_total 11403
telemt_handshake_timeouts_total 7661
telemt_upstream_connect_attempt_total 22896
telemt_upstream_connect_success_total 22624
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 22896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 1300
telemt_me_reconnect_attempts_total 28922
telemt_me_reconnect_success_total 19016
telemt_me_reader_eof_total 19942
telemt_me_idle_close_by_peer_total 19942
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 345936
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 863156
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3348
telemt_desync_full_logged_total 1151
telemt_desync_suppressed_total 2197
telemt_desync_frames_bucket_total{bucket="1_2"} 911
telemt_desync_frames_bucket_total{bucket="3_10"} 1144
telemt_desync_frames_bucket_total{bucket="gt_10"} 1293
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 19536
telemt_me_refill_failed_total 307
telemt_me_writer_restored_same_endpoint_total 18972
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 863038
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 10597810184 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 268771046496 (250.31 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 100
```