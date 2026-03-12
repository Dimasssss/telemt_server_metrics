# Server Metrics 2026-03-12 02:25:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16827.2 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139237
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 2454
telemt_upstream_connect_attempt_total 3902
telemt_upstream_connect_success_total 3902
telemt_upstream_connect_attempts_per_request{bucket="1"} 3902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 3056
telemt_me_reconnect_success_total 3043
telemt_me_reader_eof_total 3211
telemt_me_idle_close_by_peer_total 3211
telemt_me_route_drop_no_conn_total 50140
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131194
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3079
telemt_me_writer_restored_same_endpoint_total 3027
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 131043
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 911874828 (869.63 MB)
telemt_user_octets_to_client{user="hello"} 38616319292 (35.96 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 16828.0 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47433
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 793
telemt_upstream_connect_attempt_total 4894
telemt_upstream_connect_success_total 4891
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 3864
telemt_me_reconnect_success_total 3837
telemt_me_reader_eof_total 4063
telemt_me_idle_close_by_peer_total 4063
telemt_me_route_drop_no_conn_total 12710
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44151
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 50
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3866
telemt_me_writer_restored_same_endpoint_total 3828
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 44330
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 729682987 (695.88 MB)
telemt_user_octets_to_client{user="hello"} 15825104750 (14.74 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 16827.9 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219664
telemt_connections_bad_total 1163
telemt_handshake_timeouts_total 14594
telemt_upstream_connect_attempt_total 5194
telemt_upstream_connect_success_total 5192
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 4022
telemt_me_reconnect_success_total 3969
telemt_me_reader_eof_total 4104
telemt_me_idle_close_by_peer_total 4104
telemt_me_route_drop_no_conn_total 24936
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80649
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 157
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3921
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3928
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 80989
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 700846388 (668.38 MB)
telemt_user_octets_to_client{user="hello"} 26795504749 (24.96 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 16828.2 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71128
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 1752
telemt_upstream_connect_attempt_total 5030
telemt_upstream_connect_success_total 5003
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 4155
telemt_me_reconnect_success_total 4140
telemt_me_reader_eof_total 4379
telemt_me_idle_close_by_peer_total 4379
telemt_me_route_drop_no_conn_total 25155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68291
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 107
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4166
telemt_me_writer_restored_same_endpoint_total 4119
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 68281
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 411585068 (392.52 MB)
telemt_user_octets_to_client{user="hello"} 15569939804 (14.50 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16828.1 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91229
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 622
telemt_upstream_connect_attempt_total 6321
telemt_upstream_connect_success_total 6259
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3077
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 6881
telemt_me_reconnect_success_total 5385
telemt_me_reader_eof_total 5588
telemt_me_idle_close_by_peer_total 5588
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 23071
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86752
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 306
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5468
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5369
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 86731
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 492997500 (470.16 MB)
telemt_user_octets_to_client{user="hello"} 18529107432 (17.26 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 32
```