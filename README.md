# Server Metrics 2026-03-14 17:30:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 15155.9 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612867
telemt_connections_bad_total 33603
telemt_handshake_timeouts_total 8290
telemt_upstream_connect_attempt_total 3025
telemt_upstream_connect_success_total 3012
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 3006
telemt_me_reconnect_success_total 2206
telemt_me_reader_eof_total 2309
telemt_me_idle_close_by_peer_total 2309
telemt_me_route_drop_no_conn_total 234326
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543199
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1892
telemt_desync_full_logged_total 546
telemt_desync_suppressed_total 1346
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 763
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2267
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2197
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 543142
telemt_user_connections_current{user="hello"} 1752
telemt_user_octets_from_client{user="hello"} 9817467580 (9.14 GB)
telemt_user_octets_to_client{user="hello"} 169955712392 (158.28 GB)
telemt_user_unique_ips_current{user="hello"} 497
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 15161.6 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245154
telemt_connections_bad_total 22528
telemt_handshake_timeouts_total 7819
telemt_upstream_connect_attempt_total 3156
telemt_upstream_connect_success_total 3121
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 288
telemt_me_reconnect_attempts_total 3103
telemt_me_reconnect_success_total 2317
telemt_me_reader_eof_total 2417
telemt_me_idle_close_by_peer_total 2417
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 76054
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199104
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 747
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 512
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2397
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2302
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 199048
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 2889170144 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 77473542456 (72.15 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 15024.4 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512880
telemt_connections_bad_total 1961
telemt_handshake_timeouts_total 106419
telemt_upstream_connect_attempt_total 3056
telemt_upstream_connect_success_total 3047
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 6158
telemt_me_reconnect_success_total 2257
telemt_me_reader_eof_total 2432
telemt_me_idle_close_by_peer_total 2432
telemt_me_route_drop_no_conn_total 125522
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343178
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1022
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 680
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 506
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2396
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2224
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 343077
telemt_user_connections_current{user="hello"} 1101
telemt_user_octets_from_client{user="hello"} 5184070188 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 123715137780 (115.22 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 14878.7 (4h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266970
telemt_connections_bad_total 56206
telemt_handshake_timeouts_total 38573
telemt_upstream_connect_attempt_total 3667
telemt_upstream_connect_success_total 3666
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 3796
telemt_me_reconnect_success_total 2882
telemt_me_reader_eof_total 3000
telemt_me_idle_close_by_peer_total 3000
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 60744
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168404
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 329
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2940
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2875
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 168360
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 2529475872 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 53568517756 (49.89 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 15174.2 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237020
telemt_connections_bad_total 912
telemt_handshake_timeouts_total 2964
telemt_upstream_connect_attempt_total 3282
telemt_upstream_connect_success_total 3217
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 3282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3097
telemt_me_reconnect_success_total 2432
telemt_me_reader_eof_total 2553
telemt_me_idle_close_by_peer_total 2553
telemt_me_route_drop_no_conn_total 77030
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218296
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 561
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2501
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2414
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 218312
telemt_user_connections_current{user="hello"} 740
telemt_user_octets_from_client{user="hello"} 3386243484 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 85451318260 (79.58 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 100
```