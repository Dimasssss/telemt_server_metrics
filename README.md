# Server Metrics 2026-03-15 02:00:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 13562.8 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166955
telemt_connections_bad_total 1892
telemt_handshake_timeouts_total 541
telemt_upstream_connect_attempt_total 2852
telemt_upstream_connect_success_total 2843
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2156
telemt_me_reconnect_success_total 2144
telemt_me_reader_eof_total 2253
telemt_me_idle_close_by_peer_total 2253
telemt_me_route_drop_no_conn_total 51619
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146833
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 379
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2171
telemt_me_writer_restored_same_endpoint_total 2133
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 146821
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 1641894736 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 49968990844 (46.54 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 13563.2 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70204
telemt_connections_bad_total 12389
telemt_handshake_timeouts_total 3481
telemt_upstream_connect_attempt_total 4017
telemt_upstream_connect_success_total 3999
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3003
telemt_me_reconnect_success_total 2985
telemt_me_reader_eof_total 3113
telemt_me_idle_close_by_peer_total 3113
telemt_me_route_drop_no_conn_total 13414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52449
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
telemt_me_writer_removed_unexpected_total 2960
telemt_me_writer_restored_same_endpoint_total 2977
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 52745
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 1529162591 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 15323810472 (14.27 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 13563.4 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113403
telemt_connections_bad_total 2228
telemt_handshake_timeouts_total 10258
telemt_upstream_connect_attempt_total 3138
telemt_upstream_connect_success_total 3122
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2430
telemt_me_reconnect_success_total 2421
telemt_me_reader_eof_total 2547
telemt_me_idle_close_by_peer_total 2547
telemt_me_route_drop_no_conn_total 25036
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98535
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 226
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2448
telemt_me_writer_restored_same_endpoint_total 2402
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 98446
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 970878796 (925.90 MB)
telemt_user_octets_to_client{user="hello"} 32893862188 (30.63 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 13563.2 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98600
telemt_connections_bad_total 26419
telemt_handshake_timeouts_total 2614
telemt_upstream_connect_attempt_total 5142
telemt_upstream_connect_success_total 5031
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 5142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7875
telemt_me_reconnect_success_total 4328
telemt_me_reader_eof_total 4525
telemt_me_idle_close_by_peer_total 4525
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 18148
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67979
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
telemt_me_writer_removed_unexpected_total 4477
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4310
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 67981
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 402547236 (383.90 MB)
telemt_user_octets_to_client{user="hello"} 12408407940 (11.56 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 13563.9 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57820
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 709
telemt_upstream_connect_attempt_total 3028
telemt_upstream_connect_success_total 3014
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2321
telemt_me_reconnect_success_total 2312
telemt_me_reader_eof_total 2440
telemt_me_idle_close_by_peer_total 2440
telemt_me_route_drop_no_conn_total 14285
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55432
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 145
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2331
telemt_me_writer_restored_same_endpoint_total 2304
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 55431
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 503051504 (479.75 MB)
telemt_user_octets_to_client{user="hello"} 19332268064 (18.00 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 36
```