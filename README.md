# Server Metrics 2026-03-11 22:15:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1834.8 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22231
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 121
telemt_upstream_connect_attempt_total 309
telemt_upstream_connect_success_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 190
telemt_me_reconnect_success_total 189
telemt_me_reader_eof_total 172
telemt_me_idle_close_by_peer_total 172
telemt_me_route_drop_no_conn_total 6886
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19863
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 192
telemt_me_writer_restored_same_endpoint_total 173
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 19860
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 136740544 (130.41 MB)
telemt_user_octets_to_client{user="hello"} 6057368120 (5.64 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 1835.5 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7629
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 418
telemt_upstream_connect_success_total 418
telemt_upstream_connect_attempts_per_request{bucket="1"} 418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 212
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 294
telemt_me_reconnect_success_total 290
telemt_me_reader_eof_total 274
telemt_me_idle_close_by_peer_total 274
telemt_me_route_drop_no_conn_total 1880
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7203
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_restored_same_endpoint_total 281
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_user_connections_total{user="hello"} 7201
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 61063480 (58.23 MB)
telemt_user_octets_to_client{user="hello"} 3356474336 (3.13 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 1835.3 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16952
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 1830
telemt_upstream_connect_attempt_total 1010
telemt_upstream_connect_success_total 1010
telemt_upstream_connect_attempts_per_request{bucket="1"} 1010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 569
telemt_me_reconnect_success_total 532
telemt_me_reader_eof_total 441
telemt_me_idle_close_by_peer_total 441
telemt_me_route_drop_no_conn_total 3275
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13972
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 446
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 491
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 14326
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 92298284 (88.02 MB)
telemt_user_octets_to_client{user="hello"} 3791150485 (3.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 1835.6 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10866
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 264
telemt_upstream_connect_attempt_total 476
telemt_upstream_connect_success_total 472
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 357
telemt_me_reconnect_success_total 353
telemt_me_reader_eof_total 324
telemt_me_idle_close_by_peer_total 324
telemt_me_route_drop_no_conn_total 2745
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10387
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 347
telemt_me_writer_restored_same_endpoint_total 332
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 10390
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 79749456 (76.06 MB)
telemt_user_octets_to_client{user="hello"} 3925416136 (3.66 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1835.7 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12670
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 88
telemt_upstream_connect_attempt_total 435
telemt_upstream_connect_success_total 430
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 317
telemt_me_reconnect_success_total 309
telemt_me_reader_eof_total 276
telemt_me_idle_close_by_peer_total 276
telemt_me_route_drop_no_conn_total 2907
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11864
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 20
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_restored_same_endpoint_total 307
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 11860
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 104630596 (99.78 MB)
telemt_user_octets_to_client{user="hello"} 4114429440 (3.83 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 37
```