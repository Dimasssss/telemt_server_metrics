# Server Metrics 2026-03-13 13:08:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 112163.8 (31h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3371369
telemt_connections_bad_total 37363
telemt_handshake_timeouts_total 58276
telemt_upstream_connect_attempt_total 22057
telemt_upstream_connect_success_total 21934
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 2109
telemt_me_reconnect_attempts_total 26435
telemt_me_reconnect_success_total 16351
telemt_me_reader_eof_total 17579
telemt_me_idle_close_by_peer_total 17578
telemt_me_route_drop_no_conn_total 1250240
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3091944
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12927
telemt_desync_full_logged_total 3368
telemt_desync_suppressed_total 9559
telemt_desync_frames_bucket_total{bucket="1_2"} 3283
telemt_desync_frames_bucket_total{bucket="3_10"} 4887
telemt_desync_frames_bucket_total{bucket="gt_10"} 4757
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 16896
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16338
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 3091840
telemt_user_connections_current{user="hello"} 1732
telemt_user_octets_from_client{user="hello"} 42765049636 (39.83 GB)
telemt_user_octets_to_client{user="hello"} 994177990972 (925.90 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11827.7 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162236
telemt_connections_bad_total 9202
telemt_handshake_timeouts_total 3834
telemt_upstream_connect_attempt_total 2877
telemt_upstream_connect_success_total 2802
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 2877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1353
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 3371
telemt_me_reconnect_success_total 2142
telemt_me_reader_eof_total 2251
telemt_me_idle_close_by_peer_total 2251
telemt_me_route_drop_no_conn_total 58706
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145327
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 535
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2197
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2135
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 145352
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 1450488616 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 39438281700 (36.73 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 141784.2 (39h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2543210
telemt_connections_bad_total 26593
telemt_handshake_timeouts_total 167608
telemt_upstream_connect_attempt_total 32201
telemt_upstream_connect_success_total 32191
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3191
telemt_me_reconnect_attempts_total 27333
telemt_me_reconnect_success_total 24787
telemt_me_reader_eof_total 26280
telemt_me_idle_close_by_peer_total 26279
telemt_me_route_drop_no_conn_total 852402
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2069879
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7071
telemt_desync_full_logged_total 2305
telemt_desync_suppressed_total 4766
telemt_desync_frames_bucket_total{bucket="1_2"} 1121
telemt_desync_frames_bucket_total{bucket="3_10"} 2584
telemt_desync_frames_bucket_total{bucket="gt_10"} 3366
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 25075
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24746
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 2069300
telemt_user_connections_current{user="hello"} 1086
telemt_user_octets_from_client{user="hello"} 34709926528 (32.33 GB)
telemt_user_octets_to_client{user="hello"} 745097352221 (693.93 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 141784.8 (39h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1621534
telemt_connections_bad_total 17880
telemt_handshake_timeouts_total 114009
telemt_upstream_connect_attempt_total 45555
telemt_upstream_connect_success_total 43235
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45281
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11830
telemt_me_reconnect_attempts_total 39284
telemt_me_reconnect_success_total 30318
telemt_me_reader_eof_total 32602
telemt_me_idle_close_by_peer_total 32595
telemt_me_route_drop_no_conn_total 577521
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1354203
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2700
telemt_desync_full_logged_total 880
telemt_desync_suppressed_total 1820
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 1109
telemt_desync_frames_bucket_total{bucket="gt_10"} 868
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 30822
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30294
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 1358924
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 20594222805 (19.18 GB)
telemt_user_octets_to_client{user="hello"} 530425643082 (494.00 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11220.6 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173427
telemt_connections_bad_total 3838
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 2285
telemt_upstream_connect_success_total 2209
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 2285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 9674
telemt_me_reconnect_success_total 1600
telemt_me_reader_eof_total 1853
telemt_me_idle_close_by_peer_total 1853
telemt_me_route_drop_no_conn_total 66912
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161940
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 567
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1848
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1596
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 161924
telemt_user_connections_current{user="hello"} 832
telemt_user_octets_from_client{user="hello"} 1800166296 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 51326958000 (47.80 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 112
```