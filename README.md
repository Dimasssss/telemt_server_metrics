# Server Metrics 2026-03-12 01:29:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13461.5 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110045
telemt_connections_bad_total 1344
telemt_handshake_timeouts_total 441
telemt_upstream_connect_attempt_total 3119
telemt_upstream_connect_success_total 3119
telemt_upstream_connect_attempts_per_request{bucket="1"} 3119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 2446
telemt_me_reconnect_success_total 2437
telemt_me_reader_eof_total 2565
telemt_me_idle_close_by_peer_total 2565
telemt_me_route_drop_no_conn_total 40778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104703
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2467
telemt_me_writer_restored_same_endpoint_total 2421
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 104589
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 736012568 (701.92 MB)
telemt_user_octets_to_client{user="hello"} 28722099692 (26.75 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13462.3 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37721
telemt_connections_bad_total 116
telemt_handshake_timeouts_total 414
telemt_upstream_connect_attempt_total 3921
telemt_upstream_connect_success_total 3918
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 3063
telemt_me_reconnect_success_total 3040
telemt_me_reader_eof_total 3213
telemt_me_idle_close_by_peer_total 3213
telemt_me_route_drop_no_conn_total 10583
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35732
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3063
telemt_me_writer_restored_same_endpoint_total 3031
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 35911
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 654492727 (624.17 MB)
telemt_user_octets_to_client{user="hello"} 12631436446 (11.76 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 13462.1 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131574
telemt_connections_bad_total 951
telemt_handshake_timeouts_total 11241
telemt_upstream_connect_attempt_total 4285
telemt_upstream_connect_success_total 4283
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 3285
telemt_me_reconnect_success_total 3236
telemt_me_reader_eof_total 3319
telemt_me_idle_close_by_peer_total 3319
telemt_me_route_drop_no_conn_total 20484
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63383
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 111
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3180
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3195
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 63728
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 614568408 (586.10 MB)
telemt_user_octets_to_client{user="hello"} 24039138477 (22.39 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 13462.5 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58810
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 1219
telemt_upstream_connect_attempt_total 4060
telemt_upstream_connect_success_total 4040
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 3364
telemt_me_reconnect_success_total 3353
telemt_me_reader_eof_total 3538
telemt_me_idle_close_by_peer_total 3538
telemt_me_route_drop_no_conn_total 20438
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56685
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3374
telemt_me_writer_restored_same_endpoint_total 3332
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 56679
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 320560216 (305.71 MB)
telemt_user_octets_to_client{user="hello"} 13345422820 (12.43 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13462.3 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75346
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 578
telemt_upstream_connect_attempt_total 5327
telemt_upstream_connect_success_total 5280
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 5327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 6074
telemt_me_reconnect_success_total 4581
telemt_me_reader_eof_total 4734
telemt_me_idle_close_by_peer_total 4734
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 18784
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71226
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 184
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4661
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4573
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 71207
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 326970136 (311.82 MB)
telemt_user_octets_to_client{user="hello"} 15580304496 (14.51 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 30
```