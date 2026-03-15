# Server Metrics 2026-03-15 03:22:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 18453.9 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225043
telemt_connections_bad_total 2992
telemt_handshake_timeouts_total 895
telemt_upstream_connect_attempt_total 3926
telemt_upstream_connect_success_total 3911
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 2987
telemt_me_reconnect_success_total 2973
telemt_me_reader_eof_total 3140
telemt_me_idle_close_by_peer_total 3140
telemt_me_route_drop_no_conn_total 69562
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199229
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 532
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3007
telemt_me_writer_restored_same_endpoint_total 2962
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 199206
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 2143327976 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 71590424072 (66.67 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 18454.4 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90062
telemt_connections_bad_total 14729
telemt_handshake_timeouts_total 3755
telemt_upstream_connect_attempt_total 5479
telemt_upstream_connect_success_total 5455
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2462
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4225
telemt_me_reconnect_success_total 4204
telemt_me_reader_eof_total 4424
telemt_me_idle_close_by_peer_total 4424
telemt_me_route_drop_no_conn_total 18034
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69325
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 120
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4194
telemt_me_writer_restored_same_endpoint_total 4196
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 69621
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 1616455735 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 21289350444 (19.83 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 18454.6 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155270
telemt_connections_bad_total 3100
telemt_handshake_timeouts_total 14220
telemt_upstream_connect_attempt_total 4307
telemt_upstream_connect_success_total 4289
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3361
telemt_me_reconnect_success_total 3346
telemt_me_reader_eof_total 3532
telemt_me_idle_close_by_peer_total 3532
telemt_me_route_drop_no_conn_total 33636
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135089
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3380
telemt_me_writer_restored_same_endpoint_total 3327
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 134992
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 1190251708 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 41322338444 (38.48 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 18454.4 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125742
telemt_connections_bad_total 30208
telemt_handshake_timeouts_total 3929
telemt_upstream_connect_attempt_total 6497
telemt_upstream_connect_success_total 6364
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 6497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8970
telemt_me_reconnect_success_total 5419
telemt_me_reader_eof_total 5715
telemt_me_idle_close_by_peer_total 5715
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 25344
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89755
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5580
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5400
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 89764
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 651170292 (621.00 MB)
telemt_user_octets_to_client{user="hello"} 24483505320 (22.80 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 18455.4 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76956
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 976
telemt_upstream_connect_attempt_total 4262
telemt_upstream_connect_success_total 4244
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3315
telemt_me_reconnect_success_total 3302
telemt_me_reader_eof_total 3517
telemt_me_idle_close_by_peer_total 3517
telemt_me_route_drop_no_conn_total 19914
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73598
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 259
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3331
telemt_me_writer_restored_same_endpoint_total 3294
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 73596
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 621773516 (592.97 MB)
telemt_user_octets_to_client{user="hello"} 23551335304 (21.93 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 36
```