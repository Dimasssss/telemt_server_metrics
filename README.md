# Server Metrics 2026-03-14 16:39:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 12088.2 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482316
telemt_connections_bad_total 23447
telemt_handshake_timeouts_total 6456
telemt_upstream_connect_attempt_total 2574
telemt_upstream_connect_success_total 2562
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 2686
telemt_me_reconnect_success_total 1891
telemt_me_reader_eof_total 1970
telemt_me_idle_close_by_peer_total 1970
telemt_me_route_drop_no_conn_total 187196
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431245
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1484
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 1058
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 556
telemt_desync_frames_bucket_total{bucket="gt_10"} 604
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1945
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1882
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 431166
telemt_user_connections_current{user="hello"} 1832
telemt_user_octets_from_client{user="hello"} 7894868000 (7.35 GB)
telemt_user_octets_to_client{user="hello"} 130651614544 (121.68 GB)
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 12093.8 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197769
telemt_connections_bad_total 20386
telemt_handshake_timeouts_total 6199
telemt_upstream_connect_attempt_total 2653
telemt_upstream_connect_success_total 2624
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 280
telemt_me_reconnect_attempts_total 2734
telemt_me_reconnect_success_total 1953
telemt_me_reader_eof_total 2029
telemt_me_idle_close_by_peer_total 2029
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 60489
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158066
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 597
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2026
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1938
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 158019
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 2378572592 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 63722943856 (59.35 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 11956.5 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399768
telemt_connections_bad_total 1461
telemt_handshake_timeouts_total 86983
telemt_upstream_connect_attempt_total 2511
telemt_upstream_connect_success_total 2503
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 5743
telemt_me_reconnect_success_total 1845
telemt_me_reader_eof_total 1988
telemt_me_idle_close_by_peer_total 1988
telemt_me_route_drop_no_conn_total 102078
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273231
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 628
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 431
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1971
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1812
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 273116
telemt_user_connections_current{user="hello"} 1161
telemt_user_octets_from_client{user="hello"} 4041258908 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 102017688940 (95.01 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 11811.1 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212974
telemt_connections_bad_total 45003
telemt_handshake_timeouts_total 34415
telemt_upstream_connect_attempt_total 3029
telemt_upstream_connect_success_total 3028
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 2391
telemt_me_reconnect_success_total 2375
telemt_me_reader_eof_total 2432
telemt_me_idle_close_by_peer_total 2432
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 47789
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130754
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 267
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2399
telemt_me_writer_restored_same_endpoint_total 2368
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 130717
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 2184969200 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 42728538348 (39.79 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 12106.4 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189696
telemt_connections_bad_total 371
telemt_handshake_timeouts_total 2624
telemt_upstream_connect_attempt_total 2738
telemt_upstream_connect_success_total 2681
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 2738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2691
telemt_me_reconnect_success_total 2026
telemt_me_reader_eof_total 2118
telemt_me_idle_close_by_peer_total 2118
telemt_me_route_drop_no_conn_total 63100
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174720
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 485
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2089
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2008
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 174735
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 2693149356 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 68534486768 (63.83 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 97
```