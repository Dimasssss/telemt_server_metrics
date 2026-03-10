# Server Metrics 2026-03-10 16:47:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8424.1 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290958
telemt_connections_bad_total 1355
telemt_handshake_timeouts_total 1413
telemt_upstream_connect_attempt_total 1489
telemt_upstream_connect_success_total 1481
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 9139
telemt_me_reconnect_success_total 1003
telemt_me_reader_eof_total 1217
telemt_me_idle_close_by_peer_total 1217
telemt_me_route_drop_no_conn_total 128894
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278664
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1166
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1247
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 997
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 278607
telemt_user_connections_current{user="hello"} 1332
telemt_user_octets_from_client{user="hello"} 3703365260 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 81515360872 (75.92 GB)
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 8480.8 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117576
telemt_connections_bad_total 1672
telemt_handshake_timeouts_total 8686
telemt_upstream_connect_attempt_total 1913
telemt_upstream_connect_success_total 1903
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1440
telemt_me_reconnect_success_total 1429
telemt_me_reader_eof_total 1474
telemt_me_idle_close_by_peer_total 1474
telemt_me_route_drop_no_conn_total 32974
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101033
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 529
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 383
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1434
telemt_me_writer_restored_same_endpoint_total 1408
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 101015
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 1204375300 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 27319006976 (25.44 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 8480.7 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224548
telemt_connections_bad_total 695
telemt_handshake_timeouts_total 26992
telemt_upstream_connect_attempt_total 3019
telemt_upstream_connect_success_total 2965
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 3019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 1483
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1508
telemt_me_idle_close_by_peer_total 1508
telemt_me_route_drop_no_conn_total 69998
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176802
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 474
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1475
telemt_me_writer_restored_same_endpoint_total 1439
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 177780
telemt_user_connections_current{user="hello"} 796
telemt_user_octets_from_client{user="hello"} 2379131657 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 51045859281 (47.54 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 8481.2 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137535
telemt_connections_bad_total 8503
telemt_handshake_timeouts_total 13272
telemt_upstream_connect_attempt_total 2118
telemt_upstream_connect_success_total 2118
telemt_upstream_connect_attempts_per_request{bucket="1"} 2118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 977
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1654
telemt_me_reconnect_success_total 1646
telemt_me_reader_eof_total 1692
telemt_me_idle_close_by_peer_total 1692
telemt_me_route_drop_no_conn_total 45920
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109749
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 344
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1654
telemt_me_writer_restored_same_endpoint_total 1635
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 109609
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 1752270928 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 28559933296 (26.60 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8480.9 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150716
telemt_connections_bad_total 521
telemt_handshake_timeouts_total 1212
telemt_upstream_connect_attempt_total 2657
telemt_upstream_connect_success_total 2651
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 2175
telemt_me_reconnect_success_total 2161
telemt_me_reader_eof_total 2191
telemt_me_idle_close_by_peer_total 2191
telemt_me_route_drop_no_conn_total 56792
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140753
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 704
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2180
telemt_me_writer_restored_same_endpoint_total 2161
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 140698
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 2469428000 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 42675124728 (39.74 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 94
```