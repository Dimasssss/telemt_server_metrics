# Server Metrics 2026-03-15 02:10:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 14173.0 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173698
telemt_connections_bad_total 1972
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 3011
telemt_upstream_connect_success_total 3002
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2293
telemt_me_reconnect_success_total 2281
telemt_me_reader_eof_total 2399
telemt_me_idle_close_by_peer_total 2399
telemt_me_route_drop_no_conn_total 53694
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152991
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 395
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2308
telemt_me_writer_restored_same_endpoint_total 2270
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 152979
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 1720748388 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 51846584480 (48.29 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 14173.6 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73100
telemt_connections_bad_total 12871
telemt_handshake_timeouts_total 3514
telemt_upstream_connect_attempt_total 4178
telemt_upstream_connect_success_total 4160
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3146
telemt_me_reconnect_success_total 3126
telemt_me_reader_eof_total 3267
telemt_me_idle_close_by_peer_total 3267
telemt_me_route_drop_no_conn_total 13937
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54778
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3103
telemt_me_writer_restored_same_endpoint_total 3118
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 55074
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1539380155 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 16277725440 (15.16 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 14173.8 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118330
telemt_connections_bad_total 2345
telemt_handshake_timeouts_total 10541
telemt_upstream_connect_attempt_total 3291
telemt_upstream_connect_success_total 3275
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2563
telemt_me_reconnect_success_total 2553
telemt_me_reader_eof_total 2688
telemt_me_idle_close_by_peer_total 2688
telemt_me_route_drop_no_conn_total 25958
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102982
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 233
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2580
telemt_me_writer_restored_same_endpoint_total 2534
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 102893
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 1019836308 (972.59 MB)
telemt_user_octets_to_client{user="hello"} 33857432008 (31.53 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 14173.7 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101712
telemt_connections_bad_total 26890
telemt_handshake_timeouts_total 2622
telemt_upstream_connect_attempt_total 5351
telemt_upstream_connect_success_total 5236
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 5351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8059
telemt_me_reconnect_success_total 4511
telemt_me_reader_eof_total 4734
telemt_me_idle_close_by_peer_total 4734
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 18989
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70590
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 4662
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4492
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 70592
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 420035708 (400.58 MB)
telemt_user_octets_to_client{user="hello"} 12688353284 (11.82 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 14174.4 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60171
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 719
telemt_upstream_connect_attempt_total 3200
telemt_upstream_connect_success_total 3185
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 2473
telemt_me_reconnect_success_total 2464
telemt_me_reader_eof_total 2605
telemt_me_idle_close_by_peer_total 2605
telemt_me_route_drop_no_conn_total 14822
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57658
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 204
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2483
telemt_me_writer_restored_same_endpoint_total 2456
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 57657
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 516358468 (492.44 MB)
telemt_user_octets_to_client{user="hello"} 19609628952 (18.26 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 33
```