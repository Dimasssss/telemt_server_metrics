# Server Metrics 2026-03-12 17:13:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 40468.4 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1460884
telemt_connections_bad_total 20276
telemt_handshake_timeouts_total 13825
telemt_upstream_connect_attempt_total 8045
telemt_upstream_connect_success_total 7999
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 497
telemt_me_reconnect_attempts_total 13615
telemt_me_reconnect_success_total 5956
telemt_me_reader_eof_total 6433
telemt_me_idle_close_by_peer_total 6432
telemt_me_route_drop_no_conn_total 542679
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1369222
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6934
telemt_desync_full_logged_total 1750
telemt_desync_suppressed_total 5184
telemt_desync_frames_bucket_total{bucket="1_2"} 1801
telemt_desync_frames_bucket_total{bucket="3_10"} 2512
telemt_desync_frames_bucket_total{bucket="gt_10"} 2621
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6275
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 5943
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 1368875
telemt_user_connections_current{user="hello"} 1837
telemt_user_octets_from_client{user="hello"} 21030294628 (19.59 GB)
telemt_user_octets_to_client{user="hello"} 414850592056 (386.36 GB)
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70088.3 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 637724
telemt_connections_bad_total 8536
telemt_handshake_timeouts_total 28879
telemt_upstream_connect_attempt_total 16690
telemt_upstream_connect_success_total 16683
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 13085
telemt_me_reconnect_success_total 13008
telemt_me_reader_eof_total 13828
telemt_me_idle_close_by_peer_total 13828
telemt_me_route_drop_no_conn_total 197056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 572393
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2399
telemt_desync_full_logged_total 739
telemt_desync_suppressed_total 1660
telemt_desync_frames_bucket_total{bucket="1_2"} 1020
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 13140
telemt_me_writer_restored_same_endpoint_total 12999
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 572930
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 8797315363 (8.19 GB)
telemt_user_octets_to_client{user="hello"} 210484558030 (196.03 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 70088.3 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1333203
telemt_connections_bad_total 6583
telemt_handshake_timeouts_total 95643
telemt_upstream_connect_attempt_total 16732
telemt_upstream_connect_success_total 16727
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1123
telemt_me_reconnect_attempts_total 14106
telemt_me_reconnect_success_total 12871
telemt_me_reader_eof_total 13560
telemt_me_idle_close_by_peer_total 13559
telemt_me_route_drop_no_conn_total 429714
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1002734
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4293
telemt_desync_full_logged_total 1324
telemt_desync_suppressed_total 2969
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 1558
telemt_desync_frames_bucket_total{bucket="gt_10"} 2066
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12971
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12830
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 1002583
telemt_user_connections_current{user="hello"} 1227
telemt_user_octets_from_client{user="hello"} 14991012420 (13.96 GB)
telemt_user_octets_to_client{user="hello"} 340920101065 (317.51 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 70089.0 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803480
telemt_connections_bad_total 8560
telemt_handshake_timeouts_total 62194
telemt_upstream_connect_attempt_total 18278
telemt_upstream_connect_success_total 18207
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 18278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1569
telemt_me_reconnect_attempts_total 19961
telemt_me_reconnect_success_total 14708
telemt_me_reader_eof_total 15668
telemt_me_idle_close_by_peer_total 15668
telemt_me_route_drop_no_conn_total 279277
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 695996
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1509
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 414
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 500
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 14986
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14687
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 695419
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 8520473684 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 277211957888 (258.17 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70088.6 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 906519
telemt_connections_bad_total 11396
telemt_handshake_timeouts_total 7451
telemt_upstream_connect_attempt_total 22316
telemt_upstream_connect_success_total 22050
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 22316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 1277
telemt_me_reconnect_attempts_total 26008
telemt_me_reconnect_success_total 18534
telemt_me_reader_eof_total 19372
telemt_me_idle_close_by_peer_total 19372
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 329194
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 832471
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3283
telemt_desync_full_logged_total 1120
telemt_desync_suppressed_total 2163
telemt_desync_frames_bucket_total{bucket="1_2"} 884
telemt_desync_frames_bucket_total{bucket="3_10"} 1119
telemt_desync_frames_bucket_total{bucket="gt_10"} 1280
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 18967
telemt_me_refill_failed_total 231
telemt_me_writer_restored_same_endpoint_total 18490
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 832354
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 10217934124 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 250303681736 (233.11 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 114
```