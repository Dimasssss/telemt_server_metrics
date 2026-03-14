# Server Metrics 2026-03-14 07:00:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 176517.4 (49h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4972996
telemt_connections_bad_total 40205
telemt_handshake_timeouts_total 113169
telemt_upstream_connect_attempt_total 37023
telemt_upstream_connect_success_total 36780
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 37023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_timeout_total 7330
telemt_me_reconnect_attempts_total 35801
telemt_me_reconnect_success_total 25650
telemt_me_reader_eof_total 27524
telemt_me_idle_close_by_peer_total 27523
telemt_me_route_drop_no_conn_total 1882339
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4562616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17426
telemt_desync_full_logged_total 4731
telemt_desync_suppressed_total 12695
telemt_desync_frames_bucket_total{bucket="1_2"} 4347
telemt_desync_frames_bucket_total{bucket="3_10"} 6637
telemt_desync_frames_bucket_total{bucket="gt_10"} 6442
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26335
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25637
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 685
telemt_user_connections_total{user="hello"} 4564099
telemt_user_connections_current{user="hello"} 1615
telemt_user_octets_from_client{user="hello"} 66912077276 (62.32 GB)
telemt_user_octets_to_client{user="hello"} 1438187886865 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 76180.7 (21h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829821
telemt_connections_bad_total 53811
telemt_handshake_timeouts_total 15189
telemt_upstream_connect_attempt_total 20621
telemt_upstream_connect_success_total 20350
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 20621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 2144
telemt_me_reconnect_attempts_total 17996
telemt_me_reconnect_success_total 14531
telemt_me_reader_eof_total 15445
telemt_me_idle_close_by_peer_total 15444
telemt_me_route_drop_no_conn_total 272278
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661335
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1921
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1335
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 859
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14846
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14523
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 663249
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 6968475645 (6.49 GB)
telemt_user_octets_to_client{user="hello"} 224950955644 (209.50 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 206137.5 (57h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3568891
telemt_connections_bad_total 41699
telemt_handshake_timeouts_total 234577
telemt_upstream_connect_attempt_total 46528
telemt_upstream_connect_success_total 46507
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10679
telemt_me_reconnect_attempts_total 40930
telemt_me_reconnect_success_total 35955
telemt_me_reader_eof_total 38192
telemt_me_idle_close_by_peer_total 38191
telemt_me_route_drop_no_conn_total 1219684
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2975571
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9806
telemt_desync_full_logged_total 3292
telemt_desync_suppressed_total 6514
telemt_desync_frames_bucket_total{bucket="1_2"} 1704
telemt_desync_frames_bucket_total{bucket="3_10"} 3546
telemt_desync_frames_bucket_total{bucket="gt_10"} 4556
telemt_pool_swap_total 195
telemt_me_writer_removed_unexpected_total 36454
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35914
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 2974721
telemt_user_connections_current{user="hello"} 913
telemt_user_octets_from_client{user="hello"} 49803651908 (46.38 GB)
telemt_user_octets_to_client{user="hello"} 1061855724969 (988.93 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 206140.0 (57h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2378384
telemt_connections_bad_total 23300
telemt_handshake_timeouts_total 282721
telemt_upstream_connect_attempt_total 64132
telemt_upstream_connect_success_total 61643
telemt_upstream_connect_fail_total 2352
telemt_upstream_connect_attempts_per_request{bucket="1"} 63858
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2351
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20516
telemt_me_reconnect_attempts_total 53433
telemt_me_reconnect_success_total 44387
telemt_me_reader_eof_total 47584
telemt_me_idle_close_by_peer_total 47577
telemt_me_route_drop_no_conn_total 800918
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1875151
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3913
telemt_desync_full_logged_total 1270
telemt_desync_suppressed_total 2643
telemt_desync_frames_bucket_total{bucket="1_2"} 1070
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 45053
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 44363
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 1881222
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 28339733871 (26.39 GB)
telemt_user_octets_to_client{user="hello"} 691148366642 (643.68 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75573.5 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802270
telemt_connections_bad_total 8232
telemt_handshake_timeouts_total 9399
telemt_upstream_connect_attempt_total 19204
telemt_upstream_connect_success_total 18688
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 19204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_keepalive_timeout_total 1584
telemt_me_reconnect_attempts_total 60245
telemt_me_reconnect_success_total 14939
telemt_me_reader_eof_total 16720
telemt_me_idle_close_by_peer_total 16719
telemt_me_route_drop_no_conn_total 308946
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 749533
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1826
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1242
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16482
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 14934
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1543
telemt_user_connections_total{user="hello"} 749394
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 13331188524 (12.42 GB)
telemt_user_octets_to_client{user="hello"} 253381928308 (235.98 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 85
```