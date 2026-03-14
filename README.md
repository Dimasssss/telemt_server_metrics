# Server Metrics 2026-03-14 03:15:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 163010.6 (45h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4700536
telemt_connections_bad_total 39873
telemt_handshake_timeouts_total 108903
telemt_upstream_connect_attempt_total 34457
telemt_upstream_connect_success_total 34228
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 34457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 6731
telemt_me_reconnect_attempts_total 33897
telemt_me_reconnect_success_total 23755
telemt_me_reader_eof_total 25474
telemt_me_idle_close_by_peer_total 25473
telemt_me_route_drop_no_conn_total 1785460
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4311935
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
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 24413
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23742
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 658
telemt_user_connections_total{user="hello"} 4313530
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 63151441952 (58.81 GB)
telemt_user_octets_to_client{user="hello"} 1362268588913 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62674.2 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707431
telemt_connections_bad_total 51354
telemt_handshake_timeouts_total 13210
telemt_upstream_connect_attempt_total 17467
telemt_upstream_connect_success_total 17211
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 17467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 2090
telemt_me_reconnect_attempts_total 15504
telemt_me_reconnect_success_total 12056
telemt_me_reader_eof_total 12798
telemt_me_idle_close_by_peer_total 12797
telemt_me_route_drop_no_conn_total 237073
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567059
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1700
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 744
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12328
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12048
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 569017
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 6075260173 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 185961394128 (173.19 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 192630.9 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3394223
telemt_connections_bad_total 35677
telemt_handshake_timeouts_total 223707
telemt_upstream_connect_attempt_total 43447
telemt_upstream_connect_success_total 43426
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10427
telemt_me_reconnect_attempts_total 38508
telemt_me_reconnect_success_total 33542
telemt_me_reader_eof_total 35623
telemt_me_idle_close_by_peer_total 35622
telemt_me_route_drop_no_conn_total 1162377
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2826095
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
telemt_me_writer_removed_unexpected_total 34012
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33501
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 2825318
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 45277269708 (42.17 GB)
telemt_user_octets_to_client{user="hello"} 1008136303713 (938.90 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 192633.5 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2272072
telemt_connections_bad_total 22996
telemt_handshake_timeouts_total 249667
telemt_upstream_connect_attempt_total 60368
telemt_upstream_connect_success_total 57901
telemt_upstream_connect_fail_total 2330
telemt_upstream_connect_attempts_per_request{bucket="1"} 60094
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2329
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20440
telemt_me_reconnect_attempts_total 50343
telemt_me_reconnect_success_total 41308
telemt_me_reader_eof_total 44300
telemt_me_idle_close_by_peer_total 44293
telemt_me_route_drop_no_conn_total 774659
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1808179
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
telemt_me_writer_removed_unexpected_total 41943
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41284
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 635
telemt_user_connections_total{user="hello"} 1814117
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 27644152175 (25.75 GB)
telemt_user_octets_to_client{user="hello"} 669135746434 (623.18 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62067.0 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707519
telemt_connections_bad_total 7953
telemt_handshake_timeouts_total 8680
telemt_upstream_connect_attempt_total 16101
telemt_upstream_connect_success_total 15668
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 16101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_keepalive_timeout_total 1520
telemt_me_reconnect_attempts_total 47239
telemt_me_reconnect_success_total 12579
telemt_me_reader_eof_total 13973
telemt_me_idle_close_by_peer_total 13972
telemt_me_route_drop_no_conn_total 268953
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 659343
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
telemt_me_writer_removed_unexpected_total 13771
telemt_me_refill_failed_total 1079
telemt_me_writer_restored_same_endpoint_total 12574
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1192
telemt_user_connections_total{user="hello"} 659221
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 12019078452 (11.19 GB)
telemt_user_octets_to_client{user="hello"} 214282456564 (199.57 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 32
```