# Server Metrics 2026-03-14 16:44:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 12394.9 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495196
telemt_connections_bad_total 24587
telemt_handshake_timeouts_total 6734
telemt_upstream_connect_attempt_total 2598
telemt_upstream_connect_success_total 2586
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 2710
telemt_me_reconnect_success_total 1915
telemt_me_reader_eof_total 1994
telemt_me_idle_close_by_peer_total 1994
telemt_me_route_drop_no_conn_total 191966
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442132
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1520
telemt_desync_full_logged_total 440
telemt_desync_suppressed_total 1080
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 568
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1969
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1906
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 442058
telemt_user_connections_current{user="hello"} 1798
telemt_user_octets_from_client{user="hello"} 8038562852 (7.49 GB)
telemt_user_octets_to_client{user="hello"} 133840216228 (124.65 GB)
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 12400.2 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202144
telemt_connections_bad_total 20623
telemt_handshake_timeouts_total 6236
telemt_upstream_connect_attempt_total 2682
telemt_upstream_connect_success_total 2653
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 2763
telemt_me_reconnect_success_total 1982
telemt_me_reader_eof_total 2060
telemt_me_idle_close_by_peer_total 2060
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 61764
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162033
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 601
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2057
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1967
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 161985
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 2399568108 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 65331901736 (60.85 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 12263.1 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408699
telemt_connections_bad_total 1465
telemt_handshake_timeouts_total 88304
telemt_upstream_connect_attempt_total 2568
telemt_upstream_connect_success_total 2560
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 5800
telemt_me_reconnect_success_total 1902
telemt_me_reader_eof_total 2046
telemt_me_idle_close_by_peer_total 2046
telemt_me_route_drop_no_conn_total 104684
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280694
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2029
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1869
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 280579
telemt_user_connections_current{user="hello"} 1055
telemt_user_octets_from_client{user="hello"} 4126515900 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 103830150140 (96.70 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 12117.5 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218149
telemt_connections_bad_total 46584
telemt_handshake_timeouts_total 34990
telemt_upstream_connect_attempt_total 3107
telemt_upstream_connect_success_total 3106
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3365
telemt_me_reconnect_success_total 2453
telemt_me_reader_eof_total 2537
telemt_me_idle_close_by_peer_total 2537
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 48673
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133648
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2505
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2446
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 133611
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 2210754904 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 44574068432 (41.51 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 12413.1 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194658
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 2665
telemt_upstream_connect_attempt_total 2797
telemt_upstream_connect_success_total 2740
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 2797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 2750
telemt_me_reconnect_success_total 2085
telemt_me_reader_eof_total 2179
telemt_me_idle_close_by_peer_total 2179
telemt_me_route_drop_no_conn_total 64223
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179083
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 490
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2150
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2067
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 179099
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 2802564684 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 70569074012 (65.72 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 104
```