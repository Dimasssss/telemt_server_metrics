# Server Metrics 2026-03-14 16:13:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 10554.3 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416086
telemt_connections_bad_total 18362
telemt_handshake_timeouts_total 4809
telemt_upstream_connect_attempt_total 2289
telemt_upstream_connect_success_total 2279
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 2489
telemt_me_reconnect_success_total 1699
telemt_me_reader_eof_total 1759
telemt_me_idle_close_by_peer_total 1759
telemt_me_route_drop_no_conn_total 163357
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374958
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1199
telemt_desync_full_logged_total 355
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1750
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1690
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 374962
telemt_user_connections_current{user="hello"} 1760
telemt_user_octets_from_client{user="hello"} 6476041396 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 114557849092 (106.69 GB)
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 10559.8 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171259
telemt_connections_bad_total 16490
telemt_handshake_timeouts_total 5679
telemt_upstream_connect_attempt_total 2265
telemt_upstream_connect_success_total 2240
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 2265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 2437
telemt_me_reconnect_success_total 1661
telemt_me_reader_eof_total 1725
telemt_me_idle_close_by_peer_total 1725
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 52706
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137146
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 549
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 389
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1727
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1647
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 137085
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 1786361464 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 56405676156 (52.53 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 10422.6 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347578
telemt_connections_bad_total 1438
telemt_handshake_timeouts_total 80416
telemt_upstream_connect_attempt_total 2188
telemt_upstream_connect_success_total 2180
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 5509
telemt_me_reconnect_success_total 1613
telemt_me_reader_eof_total 1747
telemt_me_idle_close_by_peer_total 1747
telemt_me_route_drop_no_conn_total 88345
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237372
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 466
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 334
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1736
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1580
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 237273
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 3536520860 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 90801879940 (84.57 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 10277.0 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182029
telemt_connections_bad_total 36221
telemt_handshake_timeouts_total 30666
telemt_upstream_connect_attempt_total 2595
telemt_upstream_connect_success_total 2594
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 2047
telemt_me_reconnect_success_total 2032
telemt_me_reader_eof_total 2079
telemt_me_idle_close_by_peer_total 2079
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 40604
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112867
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 237
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2044
telemt_me_writer_restored_same_endpoint_total 2027
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 112832
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 1945886512 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 37991084308 (35.38 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 10572.5 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164500
telemt_connections_bad_total 345
telemt_handshake_timeouts_total 2284
telemt_upstream_connect_attempt_total 2398
telemt_upstream_connect_success_total 2346
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 2398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2444
telemt_me_reconnect_success_total 1780
telemt_me_reader_eof_total 1866
telemt_me_idle_close_by_peer_total 1866
telemt_me_route_drop_no_conn_total 55754
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151675
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 473
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1843
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1762
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 151693
telemt_user_connections_current{user="hello"} 793
telemt_user_octets_from_client{user="hello"} 2331265524 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 58120356336 (54.13 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 97
```