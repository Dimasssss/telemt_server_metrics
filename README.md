# Server Metrics 2026-03-14 15:42:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 8674.7 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338876
telemt_connections_bad_total 11212
telemt_handshake_timeouts_total 4221
telemt_upstream_connect_attempt_total 1845
telemt_upstream_connect_success_total 1837
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 2136
telemt_me_reconnect_success_total 1352
telemt_me_reader_eof_total 1402
telemt_me_idle_close_by_peer_total 1402
telemt_me_route_drop_no_conn_total 134539
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309665
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 897
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 633
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1392
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1343
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 309659
telemt_user_connections_current{user="hello"} 1586
telemt_user_octets_from_client{user="hello"} 5211742104 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 93461756560 (87.04 GB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 8680.1 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139062
telemt_connections_bad_total 11859
telemt_handshake_timeouts_total 4883
telemt_upstream_connect_attempt_total 1882
telemt_upstream_connect_success_total 1859
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 259
telemt_me_reconnect_attempts_total 2143
telemt_me_reconnect_success_total 1370
telemt_me_reader_eof_total 1422
telemt_me_idle_close_by_peer_total 1422
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 43461
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112417
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 364
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1430
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1359
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 112378
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 1503995200 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 47466520476 (44.21 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 8543.0 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287881
telemt_connections_bad_total 916
telemt_handshake_timeouts_total 72564
telemt_upstream_connect_attempt_total 1905
telemt_upstream_connect_success_total 1897
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 5313
telemt_me_reconnect_success_total 1420
telemt_me_reader_eof_total 1540
telemt_me_idle_close_by_peer_total 1540
telemt_me_route_drop_no_conn_total 72425
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196232
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 321
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1538
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1387
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 196152
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 2771290048 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 73062507900 (68.04 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 8397.5 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142820
telemt_connections_bad_total 31451
telemt_handshake_timeouts_total 20380
telemt_upstream_connect_attempt_total 2193
telemt_upstream_connect_success_total 2192
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1732
telemt_me_reconnect_success_total 1721
telemt_me_reader_eof_total 1758
telemt_me_idle_close_by_peer_total 1758
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 32669
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88921
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1727
telemt_me_writer_restored_same_endpoint_total 1719
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 88894
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 1624621836 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 28469146312 (26.51 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 8692.8 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135381
telemt_connections_bad_total 331
telemt_handshake_timeouts_total 1924
telemt_upstream_connect_attempt_total 2082
telemt_upstream_connect_success_total 2035
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 2219
telemt_me_reconnect_success_total 1556
telemt_me_reader_eof_total 1626
telemt_me_idle_close_by_peer_total 1626
telemt_me_route_drop_no_conn_total 46031
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125215
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 379
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1613
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1538
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 125220
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 1890941912 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 46855835972 (43.64 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 82
```