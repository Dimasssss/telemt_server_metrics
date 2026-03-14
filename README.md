# Server Metrics 2026-03-14 03:30:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 163930.7 (45h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4711696
telemt_connections_bad_total 39881
telemt_handshake_timeouts_total 109055
telemt_upstream_connect_attempt_total 34659
telemt_upstream_connect_success_total 34429
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 34659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 6734
telemt_me_reconnect_attempts_total 34054
telemt_me_reconnect_success_total 23912
telemt_me_reader_eof_total 25642
telemt_me_idle_close_by_peer_total 25641
telemt_me_route_drop_no_conn_total 1789231
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4322197
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16777
telemt_desync_full_logged_total 4525
telemt_desync_suppressed_total 12252
telemt_desync_frames_bucket_total{bucket="1_2"} 4193
telemt_desync_frames_bucket_total{bucket="3_10"} 6397
telemt_desync_frames_bucket_total{bucket="gt_10"} 6187
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 24571
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23899
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 659
telemt_user_connections_total{user="hello"} 4323782
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 63268331852 (58.92 GB)
telemt_user_octets_to_client{user="hello"} 1364558079993 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63594.3 (17h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712222
telemt_connections_bad_total 51691
telemt_handshake_timeouts_total 13254
telemt_upstream_connect_attempt_total 17687
telemt_upstream_connect_success_total 17430
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 17687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 2092
telemt_me_reconnect_attempts_total 15680
telemt_me_reconnect_success_total 12231
telemt_me_reader_eof_total 12985
telemt_me_idle_close_by_peer_total 12984
telemt_me_route_drop_no_conn_total 238502
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570696
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1704
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 748
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 12504
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12223
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 572651
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 6107298945 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 189467465664 (176.46 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 193551.1 (53h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3400426
telemt_connections_bad_total 35688
telemt_handshake_timeouts_total 223803
telemt_upstream_connect_attempt_total 43672
telemt_upstream_connect_success_total 43651
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10429
telemt_me_reconnect_attempts_total 38676
telemt_me_reconnect_success_total 33710
telemt_me_reader_eof_total 35805
telemt_me_idle_close_by_peer_total 35804
telemt_me_route_drop_no_conn_total 1163933
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2832070
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9369
telemt_desync_full_logged_total 3133
telemt_desync_suppressed_total 6236
telemt_desync_frames_bucket_total{bucket="1_2"} 1614
telemt_desync_frames_bucket_total{bucket="3_10"} 3386
telemt_desync_frames_bucket_total{bucket="gt_10"} 4369
telemt_pool_swap_total 182
telemt_me_writer_removed_unexpected_total 34181
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33669
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 2831291
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 45360514608 (42.25 GB)
telemt_user_octets_to_client{user="hello"} 1010758118937 (941.34 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 193553.6 (53h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2276912
telemt_connections_bad_total 22997
telemt_handshake_timeouts_total 250957
telemt_upstream_connect_attempt_total 60655
telemt_upstream_connect_success_total 58188
telemt_upstream_connect_fail_total 2330
telemt_upstream_connect_attempts_per_request{bucket="1"} 60381
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2329
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20443
telemt_me_reconnect_attempts_total 50576
telemt_me_reconnect_success_total 41541
telemt_me_reader_eof_total 44549
telemt_me_idle_close_by_peer_total 44542
telemt_me_route_drop_no_conn_total 775563
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1811287
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3822
telemt_desync_full_logged_total 1230
telemt_desync_suppressed_total 2592
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 1592
telemt_desync_frames_bucket_total{bucket="gt_10"} 1212
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 42178
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41517
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 1817224
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 27660899055 (25.76 GB)
telemt_user_octets_to_client{user="hello"} 669769979346 (623.77 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62987.4 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711381
telemt_connections_bad_total 7953
telemt_handshake_timeouts_total 8689
telemt_upstream_connect_attempt_total 16373
telemt_upstream_connect_success_total 15935
telemt_upstream_connect_fail_total 438
telemt_upstream_connect_attempts_per_request{bucket="1"} 16373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 438
telemt_me_keepalive_timeout_total 1521
telemt_me_reconnect_attempts_total 48806
telemt_me_reconnect_success_total 12802
telemt_me_reader_eof_total 14238
telemt_me_idle_close_by_peer_total 14237
telemt_me_route_drop_no_conn_total 270855
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 663136
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1701
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 1167
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14036
telemt_me_refill_failed_total 1121
telemt_me_writer_restored_same_endpoint_total 12797
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1234
telemt_user_connections_total{user="hello"} 663014
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 12086686032 (11.26 GB)
telemt_user_octets_to_client{user="hello"} 215376181660 (200.58 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 31
```