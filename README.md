# Server Metrics 2026-03-13 23:40:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 150128.3 (41h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4577252
telemt_connections_bad_total 38388
telemt_handshake_timeouts_total 107764
telemt_upstream_connect_attempt_total 31530
telemt_upstream_connect_success_total 31315
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 31530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 6653
telemt_me_reconnect_attempts_total 31635
telemt_me_reconnect_success_total 21505
telemt_me_reader_eof_total 23064
telemt_me_idle_close_by_peer_total 23063
telemt_me_route_drop_no_conn_total 1730442
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4194613
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16601
telemt_desync_full_logged_total 4470
telemt_desync_suppressed_total 12131
telemt_desync_frames_bucket_total{bucket="1_2"} 4132
telemt_desync_frames_bucket_total{bucket="3_10"} 6351
telemt_desync_frames_bucket_total{bucket="gt_10"} 6118
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 22133
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21492
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 4196537
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 61801385424 (57.56 GB)
telemt_user_octets_to_client{user="hello"} 1326612160677 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 49792.0 (13h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616761
telemt_connections_bad_total 45770
telemt_handshake_timeouts_total 12606
telemt_upstream_connect_attempt_total 14080
telemt_upstream_connect_success_total 13840
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 14079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 1925
telemt_me_reconnect_attempts_total 12739
telemt_me_reconnect_success_total 9299
telemt_me_reader_eof_total 9865
telemt_me_idle_close_by_peer_total 9864
telemt_me_route_drop_no_conn_total 221784
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527525
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9543
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9291
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 529476
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 5813689185 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 173361012860 (161.46 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 179748.8 (49h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3319165
telemt_connections_bad_total 32311
telemt_handshake_timeouts_total 221934
telemt_upstream_connect_attempt_total 39992
telemt_upstream_connect_success_total 39971
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10341
telemt_me_reconnect_attempts_total 35663
telemt_me_reconnect_success_total 30708
telemt_me_reader_eof_total 32594
telemt_me_idle_close_by_peer_total 32593
telemt_me_route_drop_no_conn_total 1138885
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2757910
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9032
telemt_desync_full_logged_total 3038
telemt_desync_suppressed_total 5994
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 3272
telemt_desync_frames_bucket_total{bucket="gt_10"} 4241
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 31158
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30667
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 2757159
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 44767287440 (41.69 GB)
telemt_user_octets_to_client{user="hello"} 975465852585 (908.47 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 179751.3 (49h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2187638
telemt_connections_bad_total 22853
telemt_handshake_timeouts_total 231542
telemt_upstream_connect_attempt_total 55977
telemt_upstream_connect_success_total 53524
telemt_upstream_connect_fail_total 2316
telemt_upstream_connect_attempts_per_request{bucket="1"} 55703
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2315
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20351
telemt_me_reconnect_attempts_total 46578
telemt_me_reconnect_success_total 37556
telemt_me_reader_eof_total 40282
telemt_me_idle_close_by_peer_total 40275
telemt_me_route_drop_no_conn_total 761361
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1770595
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3796
telemt_desync_full_logged_total 1217
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1003
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 38161
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37532
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 1776487
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 27350898923 (25.47 GB)
telemt_user_octets_to_client{user="hello"} 661457337990 (616.03 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 49185.0 (13h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659630
telemt_connections_bad_total 7858
telemt_handshake_timeouts_total 7789
telemt_upstream_connect_attempt_total 11690
telemt_upstream_connect_success_total 11339
telemt_upstream_connect_fail_total 351
telemt_upstream_connect_attempts_per_request{bucket="1"} 11690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 351
telemt_me_keepalive_timeout_total 1448
telemt_me_reconnect_attempts_total 39645
telemt_me_reconnect_success_total 8867
telemt_me_reader_eof_total 9986
telemt_me_idle_close_by_peer_total 9985
telemt_me_route_drop_no_conn_total 249779
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614195
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1611
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 9912
telemt_me_refill_failed_total 958
telemt_me_writer_restored_same_endpoint_total 8862
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1045
telemt_user_connections_total{user="hello"} 614094
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 9785395224 (9.11 GB)
telemt_user_octets_to_client{user="hello"} 200452572552 (186.69 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 29
```