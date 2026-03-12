# Server Metrics 2026-03-12 01:34:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13767.6 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112468
telemt_connections_bad_total 1344
telemt_handshake_timeouts_total 476
telemt_upstream_connect_attempt_total 3230
telemt_upstream_connect_success_total 3230
telemt_upstream_connect_attempts_per_request{bucket="1"} 3230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 2513
telemt_me_reconnect_success_total 2504
telemt_me_reader_eof_total 2641
telemt_me_idle_close_by_peer_total 2641
telemt_me_route_drop_no_conn_total 41620
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107044
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2534
telemt_me_writer_restored_same_endpoint_total 2488
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 106925
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 746720308 (712.13 MB)
telemt_user_octets_to_client{user="hello"} 29186133320 (27.18 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13768.3 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38629
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 415
telemt_upstream_connect_attempt_total 4049
telemt_upstream_connect_success_total 4046
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 3148
telemt_me_reconnect_success_total 3125
telemt_me_reader_eof_total 3310
telemt_me_idle_close_by_peer_total 3310
telemt_me_route_drop_no_conn_total 10747
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36483
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3147
telemt_me_writer_restored_same_endpoint_total 3116
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 36662
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 664337163 (633.56 MB)
telemt_user_octets_to_client{user="hello"} 12799455614 (11.92 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 13768.1 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137500
telemt_connections_bad_total 1108
telemt_handshake_timeouts_total 11615
telemt_upstream_connect_attempt_total 4396
telemt_upstream_connect_success_total 4393
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 3353
telemt_me_reconnect_success_total 3303
telemt_me_reader_eof_total 3396
telemt_me_idle_close_by_peer_total 3396
telemt_me_route_drop_no_conn_total 21083
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65008
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3248
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3262
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 65353
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 619756804 (591.05 MB)
telemt_user_octets_to_client{user="hello"} 24221823873 (22.56 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 13768.5 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59712
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 1240
telemt_upstream_connect_attempt_total 4188
telemt_upstream_connect_success_total 4166
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 3447
telemt_me_reconnect_success_total 3436
telemt_me_reader_eof_total 3633
telemt_me_idle_close_by_peer_total 3633
telemt_me_route_drop_no_conn_total 20928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57548
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3457
telemt_me_writer_restored_same_endpoint_total 3415
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 57542
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 326056644 (310.95 MB)
telemt_user_octets_to_client{user="hello"} 13447728240 (12.52 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13768.2 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76815
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 581
telemt_upstream_connect_attempt_total 5450
telemt_upstream_connect_success_total 5400
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 5450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 6151
telemt_me_reconnect_success_total 4658
telemt_me_reader_eof_total 4827
telemt_me_idle_close_by_peer_total 4827
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 19056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72665
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 199
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 4738
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4650
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 72646
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 332802556 (317.39 MB)
telemt_user_octets_to_client{user="hello"} 15706632200 (14.63 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 32
```