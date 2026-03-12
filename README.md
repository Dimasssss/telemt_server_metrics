# Server Metrics 2026-03-12 00:33:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 10096.9 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86824
telemt_connections_bad_total 1334
telemt_handshake_timeouts_total 249
telemt_upstream_connect_attempt_total 2408
telemt_upstream_connect_success_total 2408
telemt_upstream_connect_attempts_per_request{bucket="1"} 2408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1864
telemt_me_reconnect_success_total 1857
telemt_me_reader_eof_total 1949
telemt_me_idle_close_by_peer_total 1949
telemt_me_route_drop_no_conn_total 31727
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82043
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 197
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1880
telemt_me_writer_restored_same_endpoint_total 1841
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 81980
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 594057552 (566.54 MB)
telemt_user_octets_to_client{user="hello"} 24253012900 (22.59 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10097.6 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30390
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 374
telemt_upstream_connect_attempt_total 3029
telemt_upstream_connect_success_total 3026
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 2300
telemt_me_reconnect_success_total 2279
telemt_me_reader_eof_total 2406
telemt_me_idle_close_by_peer_total 2406
telemt_me_route_drop_no_conn_total 8243
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28744
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 35
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2296
telemt_me_writer_restored_same_endpoint_total 2270
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 28923
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 582714975 (555.72 MB)
telemt_user_octets_to_client{user="hello"} 10673407106 (9.94 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 10097.4 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87832
telemt_connections_bad_total 722
telemt_handshake_timeouts_total 7489
telemt_upstream_connect_attempt_total 3377
telemt_upstream_connect_success_total 3375
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2507
telemt_me_reconnect_success_total 2461
telemt_me_reader_eof_total 2498
telemt_me_idle_close_by_peer_total 2498
telemt_me_route_drop_no_conn_total 14862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49506
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2397
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2420
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 49850
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 547139632 (521.79 MB)
telemt_user_octets_to_client{user="hello"} 21810781045 (20.31 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 10097.7 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46777
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 670
telemt_upstream_connect_attempt_total 3067
telemt_upstream_connect_success_total 3053
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 2506
telemt_me_reconnect_success_total 2496
telemt_me_reader_eof_total 2618
telemt_me_idle_close_by_peer_total 2618
telemt_me_route_drop_no_conn_total 15765
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45294
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2510
telemt_me_writer_restored_same_endpoint_total 2475
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 45290
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 233056712 (222.26 MB)
telemt_user_octets_to_client{user="hello"} 12077991916 (11.25 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10097.6 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60253
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 530
telemt_upstream_connect_attempt_total 4431
telemt_upstream_connect_success_total 4393
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 4431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 5316
telemt_me_reconnect_success_total 3824
telemt_me_reader_eof_total 3942
telemt_me_idle_close_by_peer_total 3942
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 14312
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56460
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 135
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3892
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3818
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 56442
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 277493004 (264.64 MB)
telemt_user_octets_to_client{user="hello"} 13486778692 (12.56 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 42
```