# Server Metrics 2026-03-14 13:49:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 1934.5 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77108
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 1030
telemt_upstream_connect_attempt_total 334
telemt_upstream_connect_success_total 332
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 178
telemt_me_reconnect_success_total 174
telemt_me_reader_eof_total 153
telemt_me_idle_close_by_peer_total 153
telemt_me_route_drop_no_conn_total 29105
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73183
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 125
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_me_writer_removed_unexpected_total 175
telemt_me_writer_restored_same_endpoint_total 165
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 73177
telemt_user_connections_current{user="hello"} 1585
telemt_user_octets_from_client{user="hello"} 1346477728 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 15559447180 (14.49 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 1939.9 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32333
telemt_connections_bad_total 1632
telemt_handshake_timeouts_total 1291
telemt_upstream_connect_attempt_total 403
telemt_upstream_connect_success_total 401
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 247
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 216
telemt_me_idle_close_by_peer_total 216
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 10114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26862
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_me_writer_removed_unexpected_total 240
telemt_me_writer_restored_same_endpoint_total 234
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_user_connections_total{user="hello"} 26827
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 477663300 (455.54 MB)
telemt_user_octets_to_client{user="hello"} 11722426192 (10.92 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 1802.9 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50884
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 7414
telemt_upstream_connect_attempt_total 265
telemt_upstream_connect_success_total 262
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 153
telemt_me_reconnect_success_total 148
telemt_me_reader_eof_total 113
telemt_me_idle_close_by_peer_total 113
telemt_me_route_drop_no_conn_total 13070
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40334
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 86
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 134
telemt_me_writer_restored_same_endpoint_total 115
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 40310
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 638128844 (608.57 MB)
telemt_user_octets_to_client{user="hello"} 12142317660 (11.31 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 1657.3 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20896
telemt_connections_bad_total 9582
telemt_handshake_timeouts_total 3095
telemt_upstream_connect_attempt_total 421
telemt_upstream_connect_success_total 421
telemt_upstream_connect_attempts_per_request{bucket="1"} 421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 173
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 310
telemt_me_reconnect_success_total 307
telemt_me_reader_eof_total 287
telemt_me_idle_close_by_peer_total 287
telemt_me_route_drop_no_conn_total 3799
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7972
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_restored_same_endpoint_total 307
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 7955
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 450324476 (429.46 MB)
telemt_user_octets_to_client{user="hello"} 1604654340 (1.49 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 1953.0 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30951
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 156
telemt_upstream_connect_attempt_total 405
telemt_upstream_connect_success_total 394
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 239
telemt_me_reconnect_success_total 236
telemt_me_reader_eof_total 220
telemt_me_idle_close_by_peer_total 220
telemt_me_route_drop_no_conn_total 10444
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28173
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 28178
telemt_user_connections_current{user="hello"} 775
telemt_user_octets_from_client{user="hello"} 390267788 (372.19 MB)
telemt_user_octets_to_client{user="hello"} 12589796864 (11.73 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 101
```