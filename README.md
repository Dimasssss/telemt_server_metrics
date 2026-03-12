# Server Metrics 2026-03-12 23:56:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 64668.8 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1972003
telemt_connections_bad_total 26098
telemt_handshake_timeouts_total 21318
telemt_upstream_connect_attempt_total 12814
telemt_upstream_connect_success_total 12742
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 12814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 621
telemt_me_reconnect_attempts_total 18366
telemt_me_reconnect_success_total 9508
telemt_me_reader_eof_total 10261
telemt_me_idle_close_by_peer_total 10260
telemt_me_route_drop_no_conn_total 767075
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1833491
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8606
telemt_desync_full_logged_total 2246
telemt_desync_suppressed_total 6360
telemt_desync_frames_bucket_total{bucket="1_2"} 2268
telemt_desync_frames_bucket_total{bucket="3_10"} 3100
telemt_desync_frames_bucket_total{bucket="gt_10"} 3238
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9919
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9495
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 411
telemt_user_connections_total{user="hello"} 1832955
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 27347840400 (25.47 GB)
telemt_user_octets_to_client{user="hello"} 648283723924 (603.76 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94289.4 (26h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814534
telemt_connections_bad_total 11746
telemt_handshake_timeouts_total 31641
telemt_upstream_connect_attempt_total 23918
telemt_upstream_connect_success_total 23889
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3431
telemt_me_reconnect_attempts_total 17644
telemt_me_reconnect_success_total 17546
telemt_me_reader_eof_total 18674
telemt_me_idle_close_by_peer_total 18674
telemt_me_route_drop_no_conn_total 263057
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 736890
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3020
telemt_desync_full_logged_total 943
telemt_desync_suppressed_total 2077
telemt_desync_frames_bucket_total{bucket="1_2"} 1202
telemt_desync_frames_bucket_total{bucket="3_10"} 990
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17719
telemt_me_writer_restored_same_endpoint_total 17537
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 738770
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 12149810988 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 283953532979 (264.45 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 94289.1 (26h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1695880
telemt_connections_bad_total 8350
telemt_handshake_timeouts_total 113429
telemt_upstream_connect_attempt_total 21921
telemt_upstream_connect_success_total 21915
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1242
telemt_me_reconnect_attempts_total 18117
telemt_me_reconnect_success_total 16863
telemt_me_reader_eof_total 17836
telemt_me_idle_close_by_peer_total 17835
telemt_me_route_drop_no_conn_total 555982
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1327863
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4975
telemt_desync_full_logged_total 1527
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 17024
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16822
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 1327467
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 19847702584 (18.48 GB)
telemt_user_octets_to_client{user="hello"} 486919046565 (453.48 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 94289.3 (26h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1051743
telemt_connections_bad_total 13022
telemt_handshake_timeouts_total 71675
telemt_upstream_connect_attempt_total 33173
telemt_upstream_connect_success_total 30913
telemt_upstream_connect_fail_total 2123
telemt_upstream_connect_attempts_per_request{bucket="1"} 32899
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2122
telemt_me_keepalive_timeout_total 11255
telemt_me_reconnect_attempts_total 28191
telemt_me_reconnect_success_total 20353
telemt_me_reader_eof_total 22036
telemt_me_idle_close_by_peer_total 22029
telemt_me_route_drop_no_conn_total 371521
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908401
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1889
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1265
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 626
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20720
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20331
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 913621
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 14341189225 (13.36 GB)
telemt_user_octets_to_client{user="hello"} 363065472478 (338.13 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94289.5 (26h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1167537
telemt_connections_bad_total 12557
telemt_handshake_timeouts_total 9287
telemt_upstream_connect_attempt_total 28565
telemt_upstream_connect_success_total 28210
telemt_upstream_connect_fail_total 355
telemt_upstream_connect_attempts_per_request{bucket="1"} 28565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 355
telemt_me_keepalive_timeout_total 1473
telemt_me_reconnect_attempts_total 34549
telemt_me_reconnect_success_total 23508
telemt_me_reader_eof_total 24736
telemt_me_idle_close_by_peer_total 24736
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 435911
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1076689
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4047
telemt_desync_full_logged_total 1420
telemt_desync_suppressed_total 2627
telemt_desync_frames_bucket_total{bucket="1_2"} 1179
telemt_desync_frames_bucket_total{bucket="3_10"} 1349
telemt_desync_frames_bucket_total{bucket="gt_10"} 1519
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 24128
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23463
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 1076546
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 13551712768 (12.62 GB)
telemt_user_octets_to_client{user="hello"} 378657889072 (352.65 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 50
```