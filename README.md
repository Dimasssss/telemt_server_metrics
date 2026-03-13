# Server Metrics 2026-03-13 03:45:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 78433.2 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2154711
telemt_connections_bad_total 28006
telemt_handshake_timeouts_total 22946
telemt_upstream_connect_attempt_total 15544
telemt_upstream_connect_success_total 15457
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 15544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 1297
telemt_me_reconnect_attempts_total 20390
telemt_me_reconnect_success_total 11527
telemt_me_reader_eof_total 12450
telemt_me_idle_close_by_peer_total 12449
telemt_me_route_drop_no_conn_total 825706
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1981873
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8814
telemt_desync_full_logged_total 2292
telemt_desync_suppressed_total 6522
telemt_desync_frames_bucket_total{bucket="1_2"} 2316
telemt_desync_frames_bucket_total{bucket="3_10"} 3179
telemt_desync_frames_bucket_total{bucket="gt_10"} 3319
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11964
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11514
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 1981316
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 28767021280 (26.79 GB)
telemt_user_octets_to_client{user="hello"} 683001923072 (636.10 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 108053.7 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 877692
telemt_connections_bad_total 11846
telemt_handshake_timeouts_total 39061
telemt_upstream_connect_attempt_total 27517
telemt_upstream_connect_success_total 27488
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3465
telemt_me_reconnect_attempts_total 20573
telemt_me_reconnect_success_total 20461
telemt_me_reader_eof_total 21803
telemt_me_idle_close_by_peer_total 21803
telemt_me_route_drop_no_conn_total 280480
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791044
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3132
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 2147
telemt_desync_frames_bucket_total{bucket="1_2"} 1269
telemt_desync_frames_bucket_total{bucket="3_10"} 1016
telemt_desync_frames_bucket_total{bucket="gt_10"} 847
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 20660
telemt_me_writer_restored_same_endpoint_total 20452
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 792947
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 12645788000 (11.78 GB)
telemt_user_octets_to_client{user="hello"} 306435868391 (285.39 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 108053.5 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1813483
telemt_connections_bad_total 12626
telemt_handshake_timeouts_total 120030
telemt_upstream_connect_attempt_total 25165
telemt_upstream_connect_success_total 25155
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1622
telemt_me_reconnect_attempts_total 20688
telemt_me_reconnect_success_total 19422
telemt_me_reader_eof_total 20576
telemt_me_idle_close_by_peer_total 20575
telemt_me_route_drop_no_conn_total 588361
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1430421
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5086
telemt_desync_full_logged_total 1551
telemt_desync_suppressed_total 3535
telemt_desync_frames_bucket_total{bucket="1_2"} 812
telemt_desync_frames_bucket_total{bucket="3_10"} 1838
telemt_desync_frames_bucket_total{bucket="gt_10"} 2436
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 19605
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19381
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 1430015
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 24852358436 (23.15 GB)
telemt_user_octets_to_client{user="hello"} 511748241577 (476.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 108053.8 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1128313
telemt_connections_bad_total 13156
telemt_handshake_timeouts_total 74470
telemt_upstream_connect_attempt_total 37481
telemt_upstream_connect_success_total 35200
telemt_upstream_connect_fail_total 2144
telemt_upstream_connect_attempts_per_request{bucket="1"} 37207
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2143
telemt_me_keepalive_timeout_total 11377
telemt_me_reconnect_attempts_total 32889
telemt_me_reconnect_success_total 23959
telemt_me_reader_eof_total 25864
telemt_me_idle_close_by_peer_total 25857
telemt_me_route_drop_no_conn_total 400378
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 968720
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1908
telemt_desync_full_logged_total 634
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 530
telemt_desync_frames_bucket_total{bucket="3_10"} 747
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 24396
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23935
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 973891
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 14873841837 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 384698070542 (358.28 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 108053.7 (30h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1250814
telemt_connections_bad_total 12862
telemt_handshake_timeouts_total 9915
telemt_upstream_connect_attempt_total 33950
telemt_upstream_connect_success_total 33537
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 33950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_keepalive_timeout_total 1913
telemt_me_reconnect_attempts_total 41900
telemt_me_reconnect_success_total 28169
telemt_me_reader_eof_total 29634
telemt_me_idle_close_by_peer_total 29634
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 465495
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1156651
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4270
telemt_desync_full_logged_total 1526
telemt_desync_suppressed_total 2744
telemt_desync_frames_bucket_total{bucket="1_2"} 1292
telemt_desync_frames_bucket_total{bucket="3_10"} 1399
telemt_desync_frames_bucket_total{bucket="gt_10"} 1579
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 28923
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28119
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 754
telemt_user_connections_total{user="hello"} 1156505
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 14234391292 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 397846900064 (370.52 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 60
```