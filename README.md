# Server Metrics 2026-03-14 13:54:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 2240.3 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88927
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 1163
telemt_upstream_connect_attempt_total 435
telemt_upstream_connect_success_total 433
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 276
telemt_me_reconnect_success_total 267
telemt_me_reader_eof_total 248
telemt_me_idle_close_by_peer_total 248
telemt_me_route_drop_no_conn_total 33330
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84383
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_me_writer_removed_unexpected_total 270
telemt_me_writer_restored_same_endpoint_total 258
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 84377
telemt_user_connections_current{user="hello"} 1673
telemt_user_octets_from_client{user="hello"} 1515520796 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 18469997884 (17.20 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 2245.6 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36559
telemt_connections_bad_total 1984
telemt_handshake_timeouts_total 1390
telemt_upstream_connect_attempt_total 497
telemt_upstream_connect_success_total 494
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 341
telemt_me_reconnect_success_total 335
telemt_me_reader_eof_total 307
telemt_me_idle_close_by_peer_total 307
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 11670
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30522
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 219
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_me_writer_removed_unexpected_total 332
telemt_me_writer_restored_same_endpoint_total 324
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_user_connections_total{user="hello"} 30487
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 505260972 (481.85 MB)
telemt_user_octets_to_client{user="hello"} 13459660932 (12.54 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 2108.4 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59407
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 8083
telemt_upstream_connect_attempt_total 408
telemt_upstream_connect_success_total 405
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 250
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 210
telemt_me_idle_close_by_peer_total 210
telemt_me_route_drop_no_conn_total 15403
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47026
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 231
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 47003
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 740579832 (706.27 MB)
telemt_user_octets_to_client{user="hello"} 13825920824 (12.88 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 1962.9 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25844
telemt_connections_bad_total 10869
telemt_handshake_timeouts_total 3701
telemt_upstream_connect_attempt_total 532
telemt_upstream_connect_success_total 532
telemt_upstream_connect_attempts_per_request{bucket="1"} 532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 221
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 375
telemt_me_reconnect_success_total 371
telemt_me_reader_eof_total 352
telemt_me_idle_close_by_peer_total 352
telemt_me_route_drop_no_conn_total 4723
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11008
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 360
telemt_me_writer_restored_same_endpoint_total 371
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 10991
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 472615688 (450.72 MB)
telemt_user_octets_to_client{user="hello"} 2193835812 (2.04 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 2258.3 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35325
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 189
telemt_upstream_connect_attempt_total 500
telemt_upstream_connect_success_total 489
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 334
telemt_me_reconnect_success_total 331
telemt_me_reader_eof_total 315
telemt_me_idle_close_by_peer_total 315
telemt_me_route_drop_no_conn_total 11851
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32264
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 134
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_me_writer_removed_unexpected_total 338
telemt_me_writer_restored_same_endpoint_total 313
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 32269
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 417312320 (397.98 MB)
telemt_user_octets_to_client{user="hello"} 14176162848 (13.20 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 93
```