# Server Metrics 2026-03-14 05:38:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 171599.7 (47h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4846753
telemt_connections_bad_total 40021
telemt_handshake_timeouts_total 111960
telemt_upstream_connect_attempt_total 36112
telemt_upstream_connect_success_total 35876
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 36112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 7306
telemt_me_reconnect_attempts_total 35155
telemt_me_reconnect_success_total 25009
telemt_me_reader_eof_total 26843
telemt_me_idle_close_by_peer_total 26842
telemt_me_route_drop_no_conn_total 1834804
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4446197
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17125
telemt_desync_full_logged_total 4620
telemt_desync_suppressed_total 12505
telemt_desync_frames_bucket_total{bucket="1_2"} 4273
telemt_desync_frames_bucket_total{bucket="3_10"} 6548
telemt_desync_frames_bucket_total{bucket="gt_10"} 6304
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 25683
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24996
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 674
telemt_user_connections_total{user="hello"} 4447743
telemt_user_connections_current{user="hello"} 996
telemt_user_octets_from_client{user="hello"} 65007899124 (60.54 GB)
telemt_user_octets_to_client{user="hello"} 1404315656145 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71263.4 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 778550
telemt_connections_bad_total 53075
telemt_handshake_timeouts_total 14322
telemt_upstream_connect_attempt_total 19547
telemt_upstream_connect_success_total 19279
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 19547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 2115
telemt_me_reconnect_attempts_total 17141
telemt_me_reconnect_success_total 13682
telemt_me_reader_eof_total 14539
telemt_me_idle_close_by_peer_total 14538
telemt_me_route_drop_no_conn_total 254054
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613786
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1832
telemt_desync_full_logged_total 546
telemt_desync_suppressed_total 1286
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 818
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13975
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13674
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 615738
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 6549575049 (6.10 GB)
telemt_user_octets_to_client{user="hello"} 208536914668 (194.22 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 201220.1 (55h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3482449
telemt_connections_bad_total 38106
telemt_handshake_timeouts_total 230309
telemt_upstream_connect_attempt_total 45518
telemt_upstream_connect_success_total 45497
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10631
telemt_me_reconnect_attempts_total 40151
telemt_me_reconnect_success_total 35180
telemt_me_reader_eof_total 37376
telemt_me_idle_close_by_peer_total 37375
telemt_me_route_drop_no_conn_total 1190736
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2901609
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9587
telemt_desync_full_logged_total 3224
telemt_desync_suppressed_total 6363
telemt_desync_frames_bucket_total{bucket="1_2"} 1666
telemt_desync_frames_bucket_total{bucket="3_10"} 3469
telemt_desync_frames_bucket_total{bucket="gt_10"} 4452
telemt_pool_swap_total 191
telemt_me_writer_removed_unexpected_total 35668
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35139
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 2900821
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 46528311432 (43.33 GB)
telemt_user_octets_to_client{user="hello"} 1038760888381 (967.42 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 201222.9 (55h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2331686
telemt_connections_bad_total 23141
telemt_handshake_timeouts_total 267859
telemt_upstream_connect_attempt_total 62880
telemt_upstream_connect_success_total 60398
telemt_upstream_connect_fail_total 2345
telemt_upstream_connect_attempts_per_request{bucket="1"} 62606
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2344
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20477
telemt_me_reconnect_attempts_total 52409
telemt_me_reconnect_success_total 43367
telemt_me_reader_eof_total 46504
telemt_me_idle_close_by_peer_total 46497
telemt_me_route_drop_no_conn_total 788987
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1845830
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3886
telemt_desync_full_logged_total 1253
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1615
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 178
telemt_me_writer_removed_unexpected_total 44027
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43343
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 1851824
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 28067527895 (26.14 GB)
telemt_user_octets_to_client{user="hello"} 680428261490 (633.70 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70656.1 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756290
telemt_connections_bad_total 8028
telemt_handshake_timeouts_total 8985
telemt_upstream_connect_attempt_total 18325
telemt_upstream_connect_success_total 17843
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 18325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_timeout_total 1558
telemt_me_reconnect_attempts_total 55489
telemt_me_reconnect_success_total 14313
telemt_me_reader_eof_total 15955
telemt_me_idle_close_by_peer_total 15954
telemt_me_route_drop_no_conn_total 289889
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706153
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1752
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1194
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15725
telemt_me_refill_failed_total 1282
telemt_me_writer_restored_same_endpoint_total 14308
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1412
telemt_user_connections_total{user="hello"} 706019
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 12652991412 (11.78 GB)
telemt_user_octets_to_client{user="hello"} 234612452324 (218.50 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 53
```