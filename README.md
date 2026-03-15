# Server Metrics 2026-03-15 01:50:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 12952.2 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160239
telemt_connections_bad_total 1809
telemt_handshake_timeouts_total 535
telemt_upstream_connect_attempt_total 2745
telemt_upstream_connect_success_total 2736
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2071
telemt_me_reconnect_success_total 2059
telemt_me_reader_eof_total 2168
telemt_me_idle_close_by_peer_total 2168
telemt_me_route_drop_no_conn_total 49764
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140714
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 258
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2086
telemt_me_writer_restored_same_endpoint_total 2048
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 140701
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 1546278464 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 47019822524 (43.79 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 12952.9 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67286
telemt_connections_bad_total 11888
telemt_handshake_timeouts_total 3323
telemt_upstream_connect_attempt_total 3876
telemt_upstream_connect_success_total 3858
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2887
telemt_me_reconnect_success_total 2870
telemt_me_reader_eof_total 2998
telemt_me_idle_close_by_peer_total 2998
telemt_me_route_drop_no_conn_total 12895
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50213
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2845
telemt_me_writer_restored_same_endpoint_total 2862
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 50509
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 1500045351 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 13064790136 (12.17 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 12953.1 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107869
telemt_connections_bad_total 2228
telemt_handshake_timeouts_total 9360
telemt_upstream_connect_attempt_total 3019
telemt_upstream_connect_success_total 3003
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2334
telemt_me_reconnect_success_total 2326
telemt_me_reader_eof_total 2450
telemt_me_idle_close_by_peer_total 2450
telemt_me_route_drop_no_conn_total 23984
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94186
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 214
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2351
telemt_me_writer_restored_same_endpoint_total 2307
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 94102
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 929442536 (886.39 MB)
telemt_user_octets_to_client{user="hello"} 32259651364 (30.04 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 12952.9 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95599
telemt_connections_bad_total 25953
telemt_handshake_timeouts_total 2580
telemt_upstream_connect_attempt_total 4930
telemt_upstream_connect_success_total 4819
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 4930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7685
telemt_me_reconnect_success_total 4138
telemt_me_reader_eof_total 4334
telemt_me_idle_close_by_peer_total 4334
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 17514
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65508
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4286
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4120
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 65510
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 387918320 (369.95 MB)
telemt_user_octets_to_client{user="hello"} 12215861736 (11.38 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 12953.4 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55877
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 701
telemt_upstream_connect_attempt_total 2917
telemt_upstream_connect_success_total 2902
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2235
telemt_me_reconnect_success_total 2225
telemt_me_reader_eof_total 2353
telemt_me_idle_close_by_peer_total 2353
telemt_me_route_drop_no_conn_total 13826
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53565
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2244
telemt_me_writer_restored_same_endpoint_total 2217
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 53564
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 495606376 (472.65 MB)
telemt_user_octets_to_client{user="hello"} 19168349416 (17.85 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 29
```