# Server Metrics 2026-03-13 04:11:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 79963.8 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2180862
telemt_connections_bad_total 29227
telemt_handshake_timeouts_total 23108
telemt_upstream_connect_attempt_total 15805
telemt_upstream_connect_success_total 15717
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 15805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1299
telemt_me_reconnect_attempts_total 20607
telemt_me_reconnect_success_total 11742
telemt_me_reader_eof_total 12676
telemt_me_idle_close_by_peer_total 12675
telemt_me_route_drop_no_conn_total 833911
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2005638
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8878
telemt_desync_full_logged_total 2305
telemt_desync_suppressed_total 6573
telemt_desync_frames_bucket_total{bucket="1_2"} 2337
telemt_desync_frames_bucket_total{bucket="3_10"} 3199
telemt_desync_frames_bucket_total{bucket="gt_10"} 3342
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12182
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11729
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 2005063
telemt_user_connections_current{user="hello"} 956
telemt_user_octets_from_client{user="hello"} 28970092712 (26.98 GB)
telemt_user_octets_to_client{user="hello"} 689385380780 (642.04 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 109584.1 (30h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 887073
telemt_connections_bad_total 11848
telemt_handshake_timeouts_total 39269
telemt_upstream_connect_attempt_total 27876
telemt_upstream_connect_success_total 27847
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3474
telemt_me_reconnect_attempts_total 20868
telemt_me_reconnect_success_total 20756
telemt_me_reader_eof_total 22119
telemt_me_idle_close_by_peer_total 22119
telemt_me_route_drop_no_conn_total 283495
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 799672
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3172
telemt_desync_full_logged_total 999
telemt_desync_suppressed_total 2173
telemt_desync_frames_bucket_total{bucket="1_2"} 1274
telemt_desync_frames_bucket_total{bucket="3_10"} 1031
telemt_desync_frames_bucket_total{bucket="gt_10"} 867
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20958
telemt_me_writer_restored_same_endpoint_total 20747
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 801571
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 12750799608 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 309830613731 (288.55 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 109584.1 (30h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1833267
telemt_connections_bad_total 14311
telemt_handshake_timeouts_total 120720
telemt_upstream_connect_attempt_total 25561
telemt_upstream_connect_success_total 25551
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1628
telemt_me_reconnect_attempts_total 21018
telemt_me_reconnect_success_total 19751
telemt_me_reader_eof_total 20915
telemt_me_idle_close_by_peer_total 20914
telemt_me_route_drop_no_conn_total 593843
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1447421
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5106
telemt_desync_full_logged_total 1558
telemt_desync_suppressed_total 3548
telemt_desync_frames_bucket_total{bucket="1_2"} 817
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 2444
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19937
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19710
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 1447031
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 25130035984 (23.40 GB)
telemt_user_octets_to_client{user="hello"} 516600323677 (481.12 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 109584.5 (30h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1137891
telemt_connections_bad_total 13185
telemt_handshake_timeouts_total 74614
telemt_upstream_connect_attempt_total 37900
telemt_upstream_connect_success_total 35618
telemt_upstream_connect_fail_total 2145
telemt_upstream_connect_attempts_per_request{bucket="1"} 37626
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2144
telemt_me_keepalive_timeout_total 11381
telemt_me_reconnect_attempts_total 33235
telemt_me_reconnect_success_total 24304
telemt_me_reader_eof_total 26232
telemt_me_idle_close_by_peer_total 26225
telemt_me_route_drop_no_conn_total 403905
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 977875
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1937
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1297
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 24743
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24280
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 983053
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 15086954953 (14.05 GB)
telemt_user_octets_to_client{user="hello"} 386865452322 (360.30 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 109584.3 (30h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1263005
telemt_connections_bad_total 12877
telemt_handshake_timeouts_total 10135
telemt_upstream_connect_attempt_total 34632
telemt_upstream_connect_success_total 34208
telemt_upstream_connect_fail_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 34631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 423
telemt_me_keepalive_timeout_total 1920
telemt_me_reconnect_attempts_total 42497
telemt_me_reconnect_success_total 28764
telemt_me_reader_eof_total 30235
telemt_me_idle_close_by_peer_total 30235
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 469354
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1167998
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4292
telemt_desync_full_logged_total 1537
telemt_desync_suppressed_total 2755
telemt_desync_frames_bucket_total{bucket="1_2"} 1299
telemt_desync_frames_bucket_total{bucket="3_10"} 1404
telemt_desync_frames_bucket_total{bucket="gt_10"} 1589
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 29524
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28714
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 760
telemt_user_connections_total{user="hello"} 1167852
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 14313055116 (13.33 GB)
telemt_user_octets_to_client{user="hello"} 400464224244 (372.96 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 54
```