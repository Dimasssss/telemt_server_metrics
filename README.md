# Server Metrics 2026-03-14 16:59:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 13315.5 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 534751
telemt_connections_bad_total 27960
telemt_handshake_timeouts_total 7301
telemt_upstream_connect_attempt_total 2749
telemt_upstream_connect_success_total 2736
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 2817
telemt_me_reconnect_success_total 2019
telemt_me_reader_eof_total 2107
telemt_me_idle_close_by_peer_total 2107
telemt_me_route_drop_no_conn_total 206032
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476076
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1644
telemt_desync_full_logged_total 479
telemt_desync_suppressed_total 1165
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 671
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2075
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2010
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 475997
telemt_user_connections_current{user="hello"} 1788
telemt_user_octets_from_client{user="hello"} 8556576592 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 147616040640 (137.48 GB)
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 13321.0 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216745
telemt_connections_bad_total 21434
telemt_handshake_timeouts_total 6572
telemt_upstream_connect_attempt_total 2844
telemt_upstream_connect_success_total 2812
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 2844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 2879
telemt_me_reconnect_success_total 2097
telemt_me_reader_eof_total 2182
telemt_me_idle_close_by_peer_total 2182
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 66814
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175015
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 621
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 432
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2173
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2082
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 174960
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 2593976364 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 69433718560 (64.67 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 13183.9 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443330
telemt_connections_bad_total 1632
telemt_handshake_timeouts_total 92013
telemt_upstream_connect_attempt_total 2748
telemt_upstream_connect_success_total 2740
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 5937
telemt_me_reconnect_success_total 2038
telemt_me_reader_eof_total 2197
telemt_me_idle_close_by_peer_total 2197
telemt_me_route_drop_no_conn_total 111830
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301711
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 787
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 531
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2171
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2005
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 301599
telemt_user_connections_current{user="hello"} 991
telemt_user_octets_from_client{user="hello"} 4345406292 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 109944759940 (102.39 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 13038.2 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234729
telemt_connections_bad_total 50076
telemt_handshake_timeouts_total 36618
telemt_upstream_connect_attempt_total 3312
telemt_upstream_connect_success_total 3311
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3527
telemt_me_reconnect_success_total 2614
telemt_me_reader_eof_total 2712
telemt_me_idle_close_by_peer_total 2712
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 52231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144838
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 297
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2668
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2607
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 144798
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 2350816820 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 47888145372 (44.60 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 13333.9 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207702
telemt_connections_bad_total 731
telemt_handshake_timeouts_total 2763
telemt_upstream_connect_attempt_total 2987
telemt_upstream_connect_success_total 2928
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 2987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 2895
telemt_me_reconnect_success_total 2230
telemt_me_reader_eof_total 2338
telemt_me_idle_close_by_peer_total 2338
telemt_me_route_drop_no_conn_total 68498
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191162
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 498
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2295
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2212
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 191178
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 3081897012 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 75373698600 (70.20 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 97
```