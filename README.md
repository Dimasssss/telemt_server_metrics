# Server Metrics 2026-03-14 22:47:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 1963.2 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34028
telemt_connections_bad_total 229
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 362
telemt_upstream_connect_success_total 360
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 211
telemt_me_reconnect_success_total 209
telemt_me_reader_eof_total 195
telemt_me_idle_close_by_peer_total 195
telemt_me_route_drop_no_conn_total 9448
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31473
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 131
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 217
telemt_me_writer_restored_same_endpoint_total 198
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 31473
telemt_user_connections_current{user="hello"} 845
telemt_user_octets_from_client{user="hello"} 434356876 (414.23 MB)
telemt_user_octets_to_client{user="hello"} 10651544316 (9.92 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 1963.7 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15565
telemt_connections_bad_total 2323
telemt_handshake_timeouts_total 1156
telemt_upstream_connect_attempt_total 926
telemt_upstream_connect_success_total 916
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 462
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 421
telemt_me_idle_close_by_peer_total 421
telemt_me_route_drop_no_conn_total 2963
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11295
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 412
telemt_me_writer_restored_same_endpoint_total 446
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 11591
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 1122095823 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 3293556928 (3.07 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 1964.1 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21980
telemt_connections_bad_total 503
telemt_handshake_timeouts_total 1130
telemt_upstream_connect_attempt_total 374
telemt_upstream_connect_success_total 368
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 216
telemt_me_reconnect_success_total 215
telemt_me_reader_eof_total 199
telemt_me_idle_close_by_peer_total 199
telemt_me_route_drop_no_conn_total 4009
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19936
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 217
telemt_me_writer_restored_same_endpoint_total 196
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 19935
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 378481432 (360.95 MB)
telemt_user_octets_to_client{user="hello"} 4477808812 (4.17 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 1963.9 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14070
telemt_connections_bad_total 1642
telemt_handshake_timeouts_total 714
telemt_upstream_connect_attempt_total 523
telemt_upstream_connect_success_total 486
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 349
telemt_me_reconnect_success_total 330
telemt_me_reader_eof_total 311
telemt_me_idle_close_by_peer_total 311
telemt_me_route_drop_no_conn_total 2722
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11495
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_me_writer_removed_unexpected_total 335
telemt_me_writer_restored_same_endpoint_total 319
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 11495
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 73904708 (70.48 MB)
telemt_user_octets_to_client{user="hello"} 3429990948 (3.19 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 1964.7 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11897
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 465
telemt_upstream_connect_attempt_total 331
telemt_upstream_connect_success_total 327
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 177
telemt_me_reconnect_success_total 175
telemt_me_reader_eof_total 160
telemt_me_idle_close_by_peer_total 160
telemt_me_route_drop_no_conn_total 2515
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11118
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 74
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_restored_same_endpoint_total 167
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 11118
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 79901884 (76.20 MB)
telemt_user_octets_to_client{user="hello"} 4436627228 (4.13 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 28
```