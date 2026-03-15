# Server Metrics 2026-03-15 05:49:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 27312.5 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377540
telemt_connections_bad_total 5858
telemt_handshake_timeouts_total 1777
telemt_upstream_connect_attempt_total 5814
telemt_upstream_connect_success_total 5792
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 4434
telemt_me_reconnect_success_total 4412
telemt_me_reader_eof_total 4667
telemt_me_idle_close_by_peer_total 4667
telemt_me_route_drop_no_conn_total 120949
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336507
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 825
telemt_desync_full_logged_total 255
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4463
telemt_me_writer_restored_same_endpoint_total 4401
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 336522
telemt_user_connections_current{user="hello"} 1129
telemt_user_octets_from_client{user="hello"} 3803283424 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 122526911784 (114.11 GB)
telemt_user_unique_ips_current{user="hello"} 389
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 27313.2 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145018
telemt_connections_bad_total 18312
telemt_handshake_timeouts_total 4903
telemt_upstream_connect_attempt_total 7981
telemt_upstream_connect_success_total 7943
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 7981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6277
telemt_me_reconnect_success_total 6246
telemt_me_reader_eof_total 6609
telemt_me_idle_close_by_peer_total 6609
telemt_me_route_drop_no_conn_total 33980
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118064
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 315
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6265
telemt_me_writer_restored_same_endpoint_total 6238
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 118360
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 2073004899 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 39017492576 (36.34 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 27313.4 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272158
telemt_connections_bad_total 5962
telemt_handshake_timeouts_total 28649
telemt_upstream_connect_attempt_total 6388
telemt_upstream_connect_success_total 6361
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4998
telemt_me_reconnect_success_total 4973
telemt_me_reader_eof_total 5265
telemt_me_idle_close_by_peer_total 5265
telemt_me_route_drop_no_conn_total 66885
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225914
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 404
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5025
telemt_me_writer_restored_same_endpoint_total 4954
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 225718
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 3754221460 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 93329010572 (86.92 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 27313.3 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194795
telemt_connections_bad_total 37355
telemt_handshake_timeouts_total 13605
telemt_upstream_connect_attempt_total 9375
telemt_upstream_connect_success_total 9175
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 9375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12597
telemt_me_reconnect_success_total 7790
telemt_me_reader_eof_total 8202
telemt_me_idle_close_by_peer_total 8202
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 44018
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139977
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 232
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8000
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 7764
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 139980
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 1181995528 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 48860711144 (45.51 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 27314.0 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129406
telemt_connections_bad_total 231
telemt_handshake_timeouts_total 1410
telemt_upstream_connect_attempt_total 6276
telemt_upstream_connect_success_total 6249
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4888
telemt_me_reconnect_success_total 4867
telemt_me_reader_eof_total 5197
telemt_me_idle_close_by_peer_total 5197
telemt_me_route_drop_no_conn_total 36018
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123211
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 495
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4915
telemt_me_writer_restored_same_endpoint_total 4859
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 123216
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 1171845032 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 42975744220 (40.02 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 77
```