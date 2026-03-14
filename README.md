# Server Metrics 2026-03-14 03:10:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 162703.9 (45h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4697338
telemt_connections_bad_total 39873
telemt_handshake_timeouts_total 108880
telemt_upstream_connect_attempt_total 34385
telemt_upstream_connect_success_total 34157
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 34385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 6729
telemt_me_reconnect_attempts_total 33869
telemt_me_reconnect_success_total 23727
telemt_me_reader_eof_total 25445
telemt_me_idle_close_by_peer_total 25444
telemt_me_route_drop_no_conn_total 1784226
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4308789
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16776
telemt_desync_full_logged_total 4524
telemt_desync_suppressed_total 12252
telemt_desync_frames_bucket_total{bucket="1_2"} 4192
telemt_desync_frames_bucket_total{bucket="3_10"} 6397
telemt_desync_frames_bucket_total{bucket="gt_10"} 6187
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 24385
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23714
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 658
telemt_user_connections_total{user="hello"} 4310385
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 63127635312 (58.79 GB)
telemt_user_octets_to_client{user="hello"} 1361622592713 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62367.5 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705959
telemt_connections_bad_total 51235
telemt_handshake_timeouts_total 13182
telemt_upstream_connect_attempt_total 17394
telemt_upstream_connect_success_total 17138
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 17394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 2087
telemt_me_reconnect_attempts_total 15431
telemt_me_reconnect_success_total 11983
telemt_me_reader_eof_total 12724
telemt_me_idle_close_by_peer_total 12723
telemt_me_route_drop_no_conn_total 236762
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 565923
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1699
telemt_desync_full_logged_total 475
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12254
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11975
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 567881
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 6057580065 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 184489186820 (171.82 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 192324.2 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3392227
telemt_connections_bad_total 35676
telemt_handshake_timeouts_total 223631
telemt_upstream_connect_attempt_total 43392
telemt_upstream_connect_success_total 43371
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10427
telemt_me_reconnect_attempts_total 38458
telemt_me_reconnect_success_total 33493
telemt_me_reader_eof_total 35573
telemt_me_idle_close_by_peer_total 35572
telemt_me_route_drop_no_conn_total 1161743
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2824206
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9363
telemt_desync_full_logged_total 3130
telemt_desync_suppressed_total 6233
telemt_desync_frames_bucket_total{bucket="1_2"} 1613
telemt_desync_frames_bucket_total{bucket="3_10"} 3385
telemt_desync_frames_bucket_total{bucket="gt_10"} 4365
telemt_pool_swap_total 181
telemt_me_writer_removed_unexpected_total 33962
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33452
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 2823430
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 45267513656 (42.16 GB)
telemt_user_octets_to_client{user="hello"} 1007395406101 (938.21 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 192326.8 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2269440
telemt_connections_bad_total 22989
telemt_handshake_timeouts_total 249355
telemt_upstream_connect_attempt_total 60306
telemt_upstream_connect_success_total 57839
telemt_upstream_connect_fail_total 2330
telemt_upstream_connect_attempts_per_request{bucket="1"} 60032
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2329
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20439
telemt_me_reconnect_attempts_total 50284
telemt_me_reconnect_success_total 41249
telemt_me_reader_eof_total 44241
telemt_me_idle_close_by_peer_total 44234
telemt_me_route_drop_no_conn_total 774256
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1807348
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3817
telemt_desync_full_logged_total 1229
telemt_desync_suppressed_total 2588
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 1591
telemt_desync_frames_bucket_total{bucket="gt_10"} 1208
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 41884
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41225
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 635
telemt_user_connections_total{user="hello"} 1813285
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 27638324823 (25.74 GB)
telemt_user_octets_to_client{user="hello"} 668420996826 (622.52 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 61760.2 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706416
telemt_connections_bad_total 7953
telemt_handshake_timeouts_total 8678
telemt_upstream_connect_attempt_total 16026
telemt_upstream_connect_success_total 15593
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 16026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8097
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_keepalive_timeout_total 1520
telemt_me_reconnect_attempts_total 47164
telemt_me_reconnect_success_total 12504
telemt_me_reader_eof_total 13898
telemt_me_idle_close_by_peer_total 13897
telemt_me_route_drop_no_conn_total 268169
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658248
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
telemt_me_writer_removed_unexpected_total 13696
telemt_me_refill_failed_total 1079
telemt_me_writer_restored_same_endpoint_total 12499
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1192
telemt_user_connections_total{user="hello"} 658127
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 12011385136 (11.19 GB)
telemt_user_octets_to_client{user="hello"} 213871367664 (199.18 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 39
```