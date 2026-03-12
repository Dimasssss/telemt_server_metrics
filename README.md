# Server Metrics 2026-03-12 04:17:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23561.3 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218170
telemt_connections_bad_total 1386
telemt_handshake_timeouts_total 3568
telemt_upstream_connect_attempt_total 5386
telemt_upstream_connect_success_total 5386
telemt_upstream_connect_attempts_per_request{bucket="1"} 5386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 4194
telemt_me_reconnect_success_total 4177
telemt_me_reader_eof_total 4415
telemt_me_idle_close_by_peer_total 4415
telemt_me_route_drop_no_conn_total 78543
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207237
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 437
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4221
telemt_me_writer_restored_same_endpoint_total 4161
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 207002
telemt_user_connections_current{user="hello"} 808
telemt_user_octets_from_client{user="hello"} 1902450272 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 64155060824 (59.75 GB)
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 23562.0 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73323
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 1396
telemt_upstream_connect_attempt_total 6591
telemt_upstream_connect_success_total 6588
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 5214
telemt_me_reconnect_success_total 5182
telemt_me_reader_eof_total 5506
telemt_me_idle_close_by_peer_total 5506
telemt_me_route_drop_no_conn_total 21297
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67489
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 193
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5222
telemt_me_writer_restored_same_endpoint_total 5173
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 67671
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 1107664143 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 22862648822 (21.29 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 23561.8 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347665
telemt_connections_bad_total 1780
telemt_handshake_timeouts_total 21686
telemt_upstream_connect_attempt_total 6929
telemt_upstream_connect_success_total 6927
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 5409
telemt_me_reconnect_success_total 5352
telemt_me_reader_eof_total 5579
telemt_me_idle_close_by_peer_total 5579
telemt_me_route_drop_no_conn_total 39388
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124536
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 403
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5320
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5311
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 124854
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 1141113048 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 39231715673 (36.54 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 23562.2 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110787
telemt_connections_bad_total 798
telemt_handshake_timeouts_total 6433
telemt_upstream_connect_attempt_total 7019
telemt_upstream_connect_success_total 6988
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 7019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 5793
telemt_me_reconnect_success_total 5771
telemt_me_reader_eof_total 6128
telemt_me_idle_close_by_peer_total 6128
telemt_me_route_drop_no_conn_total 37348
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102066
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5808
telemt_me_writer_restored_same_endpoint_total 5750
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 102050
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 803905504 (766.66 MB)
telemt_user_octets_to_client{user="hello"} 28954135524 (26.97 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 23562.1 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129942
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 766
telemt_upstream_connect_attempt_total 8885
telemt_upstream_connect_success_total 8794
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 8885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4204
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 131
telemt_me_reconnect_attempts_total 9068
telemt_me_reconnect_success_total 7566
telemt_me_reader_eof_total 7846
telemt_me_idle_close_by_peer_total 7846
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 35375
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124229
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 461
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 302
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 7673
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7549
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 124206
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 835734384 (797.02 MB)
telemt_user_octets_to_client{user="hello"} 27317790604 (25.44 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 62
```