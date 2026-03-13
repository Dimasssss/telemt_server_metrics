# Server Metrics 2026-03-13 18:44:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 132371.4 (36h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4231633
telemt_connections_bad_total 37746
telemt_handshake_timeouts_total 102674
telemt_upstream_connect_attempt_total 27890
telemt_upstream_connect_success_total 27707
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 27890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 5787
telemt_me_reconnect_attempts_total 28865
telemt_me_reconnect_success_total 18757
telemt_me_reader_eof_total 20143
telemt_me_idle_close_by_peer_total 20142
telemt_me_route_drop_no_conn_total 1584758
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3867578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15178
telemt_desync_full_logged_total 4037
telemt_desync_suppressed_total 11141
telemt_desync_frames_bucket_total{bucket="1_2"} 3771
telemt_desync_frames_bucket_total{bucket="3_10"} 5772
telemt_desync_frames_bucket_total{bucket="gt_10"} 5635
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19340
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18744
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 3869747
telemt_user_connections_current{user="hello"} 1512
telemt_user_octets_from_client{user="hello"} 54502945404 (50.76 GB)
telemt_user_octets_to_client{user="hello"} 1212669548805 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32035.5 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471036
telemt_connections_bad_total 36856
telemt_handshake_timeouts_total 10810
telemt_upstream_connect_attempt_total 9045
telemt_upstream_connect_success_total 8862
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 9045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3637
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 1635
telemt_me_reconnect_attempts_total 9216
telemt_me_reconnect_success_total 5815
telemt_me_reader_eof_total 6147
telemt_me_idle_close_by_peer_total 6146
telemt_me_route_drop_no_conn_total 177492
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409887
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1436
telemt_desync_full_logged_total 380
telemt_desync_suppressed_total 1056
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 493
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5999
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5807
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 411223
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 4327309395 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 127995378172 (119.20 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 161992.2 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3091513
telemt_connections_bad_total 28928
telemt_handshake_timeouts_total 207151
telemt_upstream_connect_attempt_total 35983
telemt_upstream_connect_success_total 35973
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3530
telemt_me_reconnect_attempts_total 30157
telemt_me_reconnect_success_total 27602
telemt_me_reader_eof_total 29268
telemt_me_idle_close_by_peer_total 29267
telemt_me_route_drop_no_conn_total 1057107
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2556578
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8612
telemt_desync_full_logged_total 2853
telemt_desync_suppressed_total 5759
telemt_desync_frames_bucket_total{bucket="1_2"} 1405
telemt_desync_frames_bucket_total{bucket="3_10"} 3153
telemt_desync_frames_bucket_total{bucket="gt_10"} 4054
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 27926
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27561
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 2555881
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 42098491100 (39.21 GB)
telemt_user_octets_to_client{user="hello"} 898452163013 (836.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 161992.7 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1987960
telemt_connections_bad_total 20333
telemt_handshake_timeouts_total 182479
telemt_upstream_connect_attempt_total 49909
telemt_upstream_connect_success_total 47563
telemt_upstream_connect_fail_total 2209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49635
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2208
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11991
telemt_me_reconnect_attempts_total 42653
telemt_me_reconnect_success_total 33666
telemt_me_reader_eof_total 36145
telemt_me_idle_close_by_peer_total 36138
telemt_me_route_drop_no_conn_total 707706
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1641721
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3366
telemt_desync_full_logged_total 1090
telemt_desync_suppressed_total 2276
telemt_desync_frames_bucket_total{bucket="1_2"} 915
telemt_desync_frames_bucket_total{bucket="3_10"} 1373
telemt_desync_frames_bucket_total{bucket="gt_10"} 1078
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 34220
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33642
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 1646416
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 25289446757 (23.55 GB)
telemt_user_octets_to_client{user="hello"} 624142982474 (581.28 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 31427.9 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511142
telemt_connections_bad_total 4736
telemt_handshake_timeouts_total 5167
telemt_upstream_connect_attempt_total 6882
telemt_upstream_connect_success_total 6661
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 6882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 880
telemt_me_reconnect_attempts_total 23293
telemt_me_reconnect_success_total 5083
telemt_me_reader_eof_total 5749
telemt_me_idle_close_by_peer_total 5749
telemt_me_route_drop_no_conn_total 194444
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478991
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1384
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 942
telemt_desync_frames_bucket_total{bucket="1_2"} 431
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 408
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5693
telemt_me_refill_failed_total 567
telemt_me_writer_restored_same_endpoint_total 5079
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 478957
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 5507199448 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 154369236116 (143.77 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 81
```