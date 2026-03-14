# Server Metrics 2026-03-14 17:40:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 15769.9 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 637962
telemt_connections_bad_total 35677
telemt_handshake_timeouts_total 8548
telemt_upstream_connect_attempt_total 3168
telemt_upstream_connect_success_total 3154
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 3104
telemt_me_reconnect_success_total 2304
telemt_me_reader_eof_total 2406
telemt_me_idle_close_by_peer_total 2406
telemt_me_route_drop_no_conn_total 242877
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564855
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1967
telemt_desync_full_logged_total 566
telemt_desync_suppressed_total 1401
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 741
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2364
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2295
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 564793
telemt_user_connections_current{user="hello"} 1866
telemt_user_octets_from_client{user="hello"} 10206430780 (9.51 GB)
telemt_user_octets_to_client{user="hello"} 177653498644 (165.45 GB)
telemt_user_unique_ips_current{user="hello"} 498
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 15775.0 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253528
telemt_connections_bad_total 22587
telemt_handshake_timeouts_total 8194
telemt_upstream_connect_attempt_total 3305
telemt_upstream_connect_success_total 3268
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 3305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 303
telemt_me_reconnect_attempts_total 3207
telemt_me_reconnect_success_total 2420
telemt_me_reader_eof_total 2527
telemt_me_idle_close_by_peer_total 2527
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 78716
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206060
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 542
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2500
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2405
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 206001
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 2987542008 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 79236250716 (73.79 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 15638.0 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 534902
telemt_connections_bad_total 1970
telemt_handshake_timeouts_total 108046
telemt_upstream_connect_attempt_total 3173
telemt_upstream_connect_success_total 3164
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 6232
telemt_me_reconnect_success_total 2330
telemt_me_reader_eof_total 2511
telemt_me_idle_close_by_peer_total 2511
telemt_me_route_drop_no_conn_total 129926
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357113
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1086
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 713
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2471
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2297
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 357010
telemt_user_connections_current{user="hello"} 1031
telemt_user_octets_from_client{user="hello"} 5418097600 (5.05 GB)
telemt_user_octets_to_client{user="hello"} 128243435412 (119.44 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 15492.5 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280991
telemt_connections_bad_total 59963
telemt_handshake_timeouts_total 39750
telemt_upstream_connect_attempt_total 3804
telemt_upstream_connect_success_total 3803
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 3889
telemt_me_reconnect_success_total 2975
telemt_me_reader_eof_total 3103
telemt_me_idle_close_by_peer_total 3103
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 63169
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177138
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3033
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2968
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 177094
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 2758007612 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 56661271744 (52.77 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 15788.3 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246165
telemt_connections_bad_total 934
telemt_handshake_timeouts_total 3020
telemt_upstream_connect_attempt_total 3404
telemt_upstream_connect_success_total 3338
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 3175
telemt_me_reconnect_success_total 2510
telemt_me_reader_eof_total 2637
telemt_me_idle_close_by_peer_total 2637
telemt_me_route_drop_no_conn_total 79488
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226966
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 586
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2579
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2492
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 226975
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 3473056572 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 88497851400 (82.42 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 99
```