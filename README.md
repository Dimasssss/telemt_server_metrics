# Server Metrics 2026-03-14 02:55:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 161783.6 (44h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4686724
telemt_connections_bad_total 39844
telemt_handshake_timeouts_total 108554
telemt_upstream_connect_attempt_total 34180
telemt_upstream_connect_success_total 33953
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 34180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 6728
telemt_me_reconnect_attempts_total 33708
telemt_me_reconnect_success_total 23567
telemt_me_reader_eof_total 25275
telemt_me_idle_close_by_peer_total 25274
telemt_me_route_drop_no_conn_total 1780953
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4298675
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16769
telemt_desync_full_logged_total 4523
telemt_desync_suppressed_total 12246
telemt_desync_frames_bucket_total{bucket="1_2"} 4189
telemt_desync_frames_bucket_total{bucket="3_10"} 6396
telemt_desync_frames_bucket_total{bucket="gt_10"} 6184
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 24223
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23554
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 656
telemt_user_connections_total{user="hello"} 4300274
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 63056177624 (58.73 GB)
telemt_user_octets_to_client{user="hello"} 1358746026781 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 61447.2 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701928
telemt_connections_bad_total 50975
telemt_handshake_timeouts_total 13149
telemt_upstream_connect_attempt_total 17171
telemt_upstream_connect_success_total 16918
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 17171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 2084
telemt_me_reconnect_attempts_total 15253
telemt_me_reconnect_success_total 11807
telemt_me_reader_eof_total 12534
telemt_me_idle_close_by_peer_total 12533
telemt_me_route_drop_no_conn_total 235617
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562409
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1690
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 1222
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 738
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12074
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11799
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 564367
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 6004417197 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 180991179816 (168.56 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 191403.9 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3385812
telemt_connections_bad_total 35436
telemt_handshake_timeouts_total 223463
telemt_upstream_connect_attempt_total 43153
telemt_upstream_connect_success_total 43132
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10426
telemt_me_reconnect_attempts_total 38262
telemt_me_reconnect_success_total 33299
telemt_me_reader_eof_total 35364
telemt_me_idle_close_by_peer_total 35363
telemt_me_route_drop_no_conn_total 1159999
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2818341
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9358
telemt_desync_full_logged_total 3126
telemt_desync_suppressed_total 6232
telemt_desync_frames_bucket_total{bucket="1_2"} 1611
telemt_desync_frames_bucket_total{bucket="3_10"} 3384
telemt_desync_frames_bucket_total{bucket="gt_10"} 4363
telemt_pool_swap_total 180
telemt_me_writer_removed_unexpected_total 33765
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33258
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 2817565
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 45234009080 (42.13 GB)
telemt_user_octets_to_client{user="hello"} 1006191169785 (937.09 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 191406.6 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2263089
telemt_connections_bad_total 22981
telemt_handshake_timeouts_total 248260
telemt_upstream_connect_attempt_total 60022
telemt_upstream_connect_success_total 57557
telemt_upstream_connect_fail_total 2328
telemt_upstream_connect_attempts_per_request{bucket="1"} 59748
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2327
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20429
telemt_me_reconnect_attempts_total 50045
telemt_me_reconnect_success_total 41012
telemt_me_reader_eof_total 43984
telemt_me_idle_close_by_peer_total 43977
telemt_me_route_drop_no_conn_total 773319
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1804113
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3811
telemt_desync_full_logged_total 1227
telemt_desync_suppressed_total 2584
telemt_desync_frames_bucket_total{bucket="1_2"} 1016
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1207
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 41646
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40988
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 1810047
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 27621512583 (25.72 GB)
telemt_user_octets_to_client{user="hello"} 667345987994 (621.51 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60839.9 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702541
telemt_connections_bad_total 7939
telemt_handshake_timeouts_total 8670
telemt_upstream_connect_attempt_total 15694
telemt_upstream_connect_success_total 15269
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 15694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 1510
telemt_me_reconnect_attempts_total 45541
telemt_me_reconnect_success_total 12226
telemt_me_reader_eof_total 13576
telemt_me_idle_close_by_peer_total 13575
telemt_me_route_drop_no_conn_total 266707
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654494
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1700
telemt_desync_full_logged_total 533
telemt_desync_suppressed_total 1167
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13374
telemt_me_refill_failed_total 1037
telemt_me_writer_restored_same_endpoint_total 12221
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1148
telemt_user_connections_total{user="hello"} 654374
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 11975055552 (11.15 GB)
telemt_user_octets_to_client{user="hello"} 212855093988 (198.24 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 33
```