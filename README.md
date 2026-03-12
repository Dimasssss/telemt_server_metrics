# Server Metrics 2026-03-12 01:03:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11932.7 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99242
telemt_connections_bad_total 1339
telemt_handshake_timeouts_total 269
telemt_upstream_connect_attempt_total 2808
telemt_upstream_connect_success_total 2808
telemt_upstream_connect_attempts_per_request{bucket="1"} 2808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2178
telemt_me_reconnect_success_total 2171
telemt_me_reader_eof_total 2285
telemt_me_idle_close_by_peer_total 2285
telemt_me_route_drop_no_conn_total 36587
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94210
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2199
telemt_me_writer_restored_same_endpoint_total 2155
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 94110
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 664248020 (633.48 MB)
telemt_user_octets_to_client{user="hello"} 27552069244 (25.66 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11933.3 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34083
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 393
telemt_upstream_connect_attempt_total 3579
telemt_upstream_connect_success_total 3576
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2764
telemt_me_reconnect_success_total 2742
telemt_me_reader_eof_total 2900
telemt_me_idle_close_by_peer_total 2900
telemt_me_route_drop_no_conn_total 9536
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32238
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2761
telemt_me_writer_restored_same_endpoint_total 2733
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 32417
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 607528959 (579.38 MB)
telemt_user_octets_to_client{user="hello"} 11519779734 (10.73 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 11933.1 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109596
telemt_connections_bad_total 855
telemt_handshake_timeouts_total 9425
telemt_upstream_connect_attempt_total 3922
telemt_upstream_connect_success_total 3920
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2965
telemt_me_reconnect_success_total 2917
telemt_me_reader_eof_total 2983
telemt_me_idle_close_by_peer_total 2983
telemt_me_route_drop_no_conn_total 18157
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57072
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 97
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2856
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2876
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 57416
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 582711180 (555.72 MB)
telemt_user_octets_to_client{user="hello"} 22569890337 (21.02 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 11933.4 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53832
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 916
telemt_upstream_connect_attempt_total 3621
telemt_upstream_connect_success_total 3603
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 2970
telemt_me_reconnect_success_total 2959
telemt_me_reader_eof_total 3117
telemt_me_idle_close_by_peer_total 3117
telemt_me_route_drop_no_conn_total 18309
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52061
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2977
telemt_me_writer_restored_same_endpoint_total 2938
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 52057
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 273817516 (261.13 MB)
telemt_user_octets_to_client{user="hello"} 12737302020 (11.86 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11933.4 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68130
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 549
telemt_upstream_connect_attempt_total 4935
telemt_upstream_connect_success_total 4894
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 4935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 5731
telemt_me_reconnect_success_total 4240
telemt_me_reader_eof_total 4385
telemt_me_idle_close_by_peer_total 4385
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 16641
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64197
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 163
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4310
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4232
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 64179
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 302320848 (288.32 MB)
telemt_user_octets_to_client{user="hello"} 14735521904 (13.72 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 36
```