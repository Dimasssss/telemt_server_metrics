# Server Metrics 2026-03-13 06:34:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 88536.0 (24h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2390382
telemt_connections_bad_total 36041
telemt_handshake_timeouts_total 25553
telemt_upstream_connect_attempt_total 17378
telemt_upstream_connect_success_total 17281
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1325
telemt_me_reconnect_attempts_total 21738
telemt_me_reconnect_success_total 12868
telemt_me_reader_eof_total 13881
telemt_me_idle_close_by_peer_total 13880
telemt_me_route_drop_no_conn_total 906584
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2199802
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9919
telemt_desync_full_logged_total 2550
telemt_desync_suppressed_total 7369
telemt_desync_frames_bucket_total{bucket="1_2"} 2544
telemt_desync_frames_bucket_total{bucket="3_10"} 3642
telemt_desync_frames_bucket_total{bucket="gt_10"} 3733
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 13324
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12855
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 2199233
telemt_user_connections_current{user="hello"} 1472
telemt_user_octets_from_client{user="hello"} 31782226420 (29.60 GB)
telemt_user_octets_to_client{user="hello"} 746498261824 (695.23 GB)
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 118156.6 (32h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 961972
telemt_connections_bad_total 12512
telemt_handshake_timeouts_total 41418
telemt_upstream_connect_attempt_total 29765
telemt_upstream_connect_success_total 29734
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3576
telemt_me_reconnect_attempts_total 22325
telemt_me_reconnect_success_total 22206
telemt_me_reader_eof_total 23682
telemt_me_idle_close_by_peer_total 23682
telemt_me_route_drop_no_conn_total 306432
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 869117
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3605
telemt_desync_full_logged_total 1121
telemt_desync_suppressed_total 2484
telemt_desync_frames_bucket_total{bucket="1_2"} 1387
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 1051
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 22426
telemt_me_writer_restored_same_endpoint_total 22197
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 871029
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 13663416320 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 330331501531 (307.65 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 118156.4 (32h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1986626
telemt_connections_bad_total 22786
telemt_handshake_timeouts_total 133542
telemt_upstream_connect_attempt_total 27356
telemt_upstream_connect_success_total 27346
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1684
telemt_me_reconnect_attempts_total 22379
telemt_me_reconnect_success_total 21105
telemt_me_reader_eof_total 22360
telemt_me_idle_close_by_peer_total 22359
telemt_me_route_drop_no_conn_total 635432
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1565738
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5405
telemt_desync_full_logged_total 1638
telemt_desync_suppressed_total 3767
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1966
telemt_desync_frames_bucket_total{bucket="gt_10"} 2547
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 21309
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21064
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 1565233
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 26667191368 (24.84 GB)
telemt_user_octets_to_client{user="hello"} 555176825797 (517.05 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 118156.9 (32h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1211411
telemt_connections_bad_total 13996
telemt_handshake_timeouts_total 78400
telemt_upstream_connect_attempt_total 40149
telemt_upstream_connect_success_total 37859
telemt_upstream_connect_fail_total 2153
telemt_upstream_connect_attempts_per_request{bucket="1"} 39875
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2152
telemt_me_keepalive_timeout_total 11419
telemt_me_reconnect_attempts_total 35041
telemt_me_reconnect_success_total 26106
telemt_me_reader_eof_total 28145
telemt_me_idle_close_by_peer_total 28138
telemt_me_route_drop_no_conn_total 433797
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041458
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2064
telemt_desync_full_logged_total 668
telemt_desync_suppressed_total 1396
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 795
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 26566
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26082
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 1046378
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 15987870297 (14.89 GB)
telemt_user_octets_to_client{user="hello"} 417161551098 (388.51 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 118156.6 (32h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1367325
telemt_connections_bad_total 19378
telemt_handshake_timeouts_total 11149
telemt_upstream_connect_attempt_total 37405
telemt_upstream_connect_success_total 36949
telemt_upstream_connect_fail_total 456
telemt_upstream_connect_attempts_per_request{bucket="1"} 37405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 456
telemt_me_keepalive_timeout_total 2033
telemt_me_reconnect_attempts_total 44799
telemt_me_reconnect_success_total 31062
telemt_me_reader_eof_total 32614
telemt_me_idle_close_by_peer_total 32614
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 502396
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1261288
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 46
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4514
telemt_desync_full_logged_total 1620
telemt_desync_suppressed_total 2894
telemt_desync_frames_bucket_total{bucket="1_2"} 1370
telemt_desync_frames_bucket_total{bucket="3_10"} 1467
telemt_desync_frames_bucket_total{bucket="gt_10"} 1677
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 31831
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31008
telemt_me_writer_restored_fallback_total 54
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1261129
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 15212552660 (14.17 GB)
telemt_user_octets_to_client{user="hello"} 433743562572 (403.96 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 107
```