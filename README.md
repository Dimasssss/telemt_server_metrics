# Server Metrics 2026-03-13 04:21:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 80576.0 (22h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2191757
telemt_connections_bad_total 29802
telemt_handshake_timeouts_total 23164
telemt_upstream_connect_attempt_total 15948
telemt_upstream_connect_success_total 15860
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 15948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1302
telemt_me_reconnect_attempts_total 20707
telemt_me_reconnect_success_total 11842
telemt_me_reader_eof_total 12783
telemt_me_idle_close_by_peer_total 12782
telemt_me_route_drop_no_conn_total 837451
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2015544
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8894
telemt_desync_full_logged_total 2308
telemt_desync_suppressed_total 6586
telemt_desync_frames_bucket_total{bucket="1_2"} 2339
telemt_desync_frames_bucket_total{bucket="3_10"} 3209
telemt_desync_frames_bucket_total{bucket="gt_10"} 3346
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12283
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11829
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 2014977
telemt_user_connections_current{user="hello"} 979
telemt_user_octets_from_client{user="hello"} 29138506728 (27.14 GB)
telemt_user_octets_to_client{user="hello"} 693233866608 (645.62 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 110196.6 (30h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891271
telemt_connections_bad_total 11872
telemt_handshake_timeouts_total 39377
telemt_upstream_connect_attempt_total 28020
telemt_upstream_connect_success_total 27991
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 28020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3474
telemt_me_reconnect_attempts_total 20969
telemt_me_reconnect_success_total 20857
telemt_me_reader_eof_total 22231
telemt_me_idle_close_by_peer_total 22231
telemt_me_route_drop_no_conn_total 284652
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 803557
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3179
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 2176
telemt_desync_frames_bucket_total{bucket="1_2"} 1277
telemt_desync_frames_bucket_total{bucket="3_10"} 1033
telemt_desync_frames_bucket_total{bucket="gt_10"} 869
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 21061
telemt_me_writer_restored_same_endpoint_total 20848
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 805456
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 12791542304 (11.91 GB)
telemt_user_octets_to_client{user="hello"} 310729405583 (289.39 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 110196.4 (30h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1840938
telemt_connections_bad_total 14889
telemt_handshake_timeouts_total 120860
telemt_upstream_connect_attempt_total 25723
telemt_upstream_connect_success_total 25713
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1639
telemt_me_reconnect_attempts_total 21137
telemt_me_reconnect_success_total 19870
telemt_me_reader_eof_total 21045
telemt_me_idle_close_by_peer_total 21044
telemt_me_route_drop_no_conn_total 595868
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1453972
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5106
telemt_desync_full_logged_total 1558
telemt_desync_suppressed_total 3548
telemt_desync_frames_bucket_total{bucket="1_2"} 817
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 2444
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 20058
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19829
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 1453582
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 25206547564 (23.48 GB)
telemt_user_octets_to_client{user="hello"} 518426573581 (482.82 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 110197.0 (30h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1141564
telemt_connections_bad_total 13193
telemt_handshake_timeouts_total 74713
telemt_upstream_connect_attempt_total 38064
telemt_upstream_connect_success_total 35781
telemt_upstream_connect_fail_total 2146
telemt_upstream_connect_attempts_per_request{bucket="1"} 37790
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2145
telemt_me_keepalive_timeout_total 11382
telemt_me_reconnect_attempts_total 33355
telemt_me_reconnect_success_total 24424
telemt_me_reader_eof_total 26362
telemt_me_idle_close_by_peer_total 26355
telemt_me_route_drop_no_conn_total 405872
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 981393
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1951
telemt_desync_full_logged_total 643
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 24864
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24400
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 986571
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 15149223437 (14.11 GB)
telemt_user_octets_to_client{user="hello"} 388802640582 (362.10 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 110196.5 (30h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1267663
telemt_connections_bad_total 12881
telemt_handshake_timeouts_total 10164
telemt_upstream_connect_attempt_total 34845
telemt_upstream_connect_success_total 34422
telemt_upstream_connect_fail_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 34845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 423
telemt_me_keepalive_timeout_total 1925
telemt_me_reconnect_attempts_total 42666
telemt_me_reconnect_success_total 28934
telemt_me_reader_eof_total 30431
telemt_me_idle_close_by_peer_total 30431
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 470719
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1172555
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4298
telemt_desync_full_logged_total 1540
telemt_desync_suppressed_total 2758
telemt_desync_frames_bucket_total{bucket="1_2"} 1301
telemt_desync_frames_bucket_total{bucket="3_10"} 1405
telemt_desync_frames_bucket_total{bucket="gt_10"} 1592
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 29693
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28884
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 759
telemt_user_connections_total{user="hello"} 1172409
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 14333034752 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 401319980020 (373.76 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 69
```