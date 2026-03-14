# Server Metrics 2026-03-14 00:16:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 152275.6 (42h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4595967
telemt_connections_bad_total 38395
telemt_handshake_timeouts_total 107829
telemt_upstream_connect_attempt_total 32036
telemt_upstream_connect_success_total 31819
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 32036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 6660
telemt_me_reconnect_attempts_total 32006
telemt_me_reconnect_success_total 21874
telemt_me_reader_eof_total 23467
telemt_me_idle_close_by_peer_total 23466
telemt_me_route_drop_no_conn_total 1739022
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4212759
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16623
telemt_desync_full_logged_total 4479
telemt_desync_suppressed_total 12144
telemt_desync_frames_bucket_total{bucket="1_2"} 4138
telemt_desync_frames_bucket_total{bucket="3_10"} 6360
telemt_desync_frames_bucket_total{bucket="gt_10"} 6125
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 22506
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21861
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 4214638
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 62184845512 (57.91 GB)
telemt_user_octets_to_client{user="hello"} 1332600590405 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51939.1 (14h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 637592
telemt_connections_bad_total 47450
telemt_handshake_timeouts_total 12797
telemt_upstream_connect_attempt_total 14639
telemt_upstream_connect_success_total 14399
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 14639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 1937
telemt_me_reconnect_attempts_total 13210
telemt_me_reconnect_success_total 9770
telemt_me_reader_eof_total 10363
telemt_me_idle_close_by_peer_total 10362
telemt_me_route_drop_no_conn_total 224515
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533294
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
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 10016
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9762
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 535245
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 5838273961 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 174122887392 (162.16 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 181895.8 (50h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3330338
telemt_connections_bad_total 32558
telemt_handshake_timeouts_total 222216
telemt_upstream_connect_attempt_total 40627
telemt_upstream_connect_success_total 40606
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10349
telemt_me_reconnect_attempts_total 36168
telemt_me_reconnect_success_total 31212
telemt_me_reader_eof_total 33127
telemt_me_idle_close_by_peer_total 33126
telemt_me_route_drop_no_conn_total 1143042
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2768307
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9083
telemt_desync_full_logged_total 3053
telemt_desync_suppressed_total 6030
telemt_desync_frames_bucket_total{bucket="1_2"} 1529
telemt_desync_frames_bucket_total{bucket="3_10"} 3291
telemt_desync_frames_bucket_total{bucket="gt_10"} 4263
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 31664
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31171
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 2767550
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 44830963276 (41.75 GB)
telemt_user_octets_to_client{user="hello"} 981134475401 (913.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 181898.5 (50h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2203042
telemt_connections_bad_total 22862
telemt_handshake_timeouts_total 235533
telemt_upstream_connect_attempt_total 56604
telemt_upstream_connect_success_total 54149
telemt_upstream_connect_fail_total 2318
telemt_upstream_connect_attempts_per_request{bucket="1"} 56330
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2317
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20374
telemt_me_reconnect_attempts_total 47079
telemt_me_reconnect_success_total 38054
telemt_me_reader_eof_total 40815
telemt_me_idle_close_by_peer_total 40808
telemt_me_route_drop_no_conn_total 763792
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1777037
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3798
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 38665
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38030
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 1782935
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 27377766731 (25.50 GB)
telemt_user_octets_to_client{user="hello"} 662727637034 (617.21 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51332.0 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 669930
telemt_connections_bad_total 7868
telemt_handshake_timeouts_total 8560
telemt_upstream_connect_attempt_total 12351
telemt_upstream_connect_success_total 11989
telemt_upstream_connect_fail_total 361
telemt_upstream_connect_attempts_per_request{bucket="1"} 12350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 361
telemt_me_keepalive_timeout_total 1458
telemt_me_reconnect_attempts_total 41582
telemt_me_reconnect_success_total 9425
telemt_me_reader_eof_total 10612
telemt_me_idle_close_by_peer_total 10611
telemt_me_route_drop_no_conn_total 252868
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622883
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 10515
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9420
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1090
telemt_user_connections_total{user="hello"} 622782
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 10180848160 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 202778045596 (188.85 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 27
```