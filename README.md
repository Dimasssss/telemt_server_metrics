# Server Metrics 2026-03-12 02:40:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 17745.1 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147259
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 2617
telemt_upstream_connect_attempt_total 4105
telemt_upstream_connect_success_total 4105
telemt_upstream_connect_attempts_per_request{bucket="1"} 4105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 3216
telemt_me_reconnect_success_total 3203
telemt_me_reader_eof_total 3384
telemt_me_idle_close_by_peer_total 3384
telemt_me_route_drop_no_conn_total 53412
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138895
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 209
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3240
telemt_me_writer_restored_same_endpoint_total 3187
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 138735
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 986441500 (940.74 MB)
telemt_user_octets_to_client{user="hello"} 42136148400 (39.24 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17745.7 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50248
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 839
telemt_upstream_connect_attempt_total 5117
telemt_upstream_connect_success_total 5114
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 4043
telemt_me_reconnect_success_total 4016
telemt_me_reader_eof_total 4255
telemt_me_idle_close_by_peer_total 4255
telemt_me_route_drop_no_conn_total 13401
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46841
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4045
telemt_me_writer_restored_same_endpoint_total 4007
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 47020
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 749899515 (715.16 MB)
telemt_user_octets_to_client{user="hello"} 17394394734 (16.20 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 17745.5 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245580
telemt_connections_bad_total 1327
telemt_handshake_timeouts_total 15436
telemt_upstream_connect_attempt_total 5437
telemt_upstream_connect_success_total 5435
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2314
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 4222
telemt_me_reconnect_success_total 4168
telemt_me_reader_eof_total 4316
telemt_me_idle_close_by_peer_total 4316
telemt_me_route_drop_no_conn_total 26539
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85622
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 171
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4124
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4127
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 85960
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 727041856 (693.36 MB)
telemt_user_octets_to_client{user="hello"} 27613020397 (25.72 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 17745.9 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77829
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 2357
telemt_upstream_connect_attempt_total 5302
telemt_upstream_connect_success_total 5274
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 4383
telemt_me_reconnect_success_total 4367
telemt_me_reader_eof_total 4621
telemt_me_idle_close_by_peer_total 4621
telemt_me_route_drop_no_conn_total 26591
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74303
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4395
telemt_me_writer_restored_same_endpoint_total 4346
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 74291
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 469708572 (447.95 MB)
telemt_user_octets_to_client{user="hello"} 16642910096 (15.50 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17745.7 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95959
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 634
telemt_upstream_connect_attempt_total 6595
telemt_upstream_connect_success_total 6530
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 6595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 7108
telemt_me_reconnect_success_total 5612
telemt_me_reader_eof_total 5828
telemt_me_idle_close_by_peer_total 5828
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 24425
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91337
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 327
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5696
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5596
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 91314
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 538858116 (513.90 MB)
telemt_user_octets_to_client{user="hello"} 20036234236 (18.66 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 36
```