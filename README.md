# Server Metrics 2026-03-15 06:04:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 28228.5 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407797
telemt_connections_bad_total 6471
telemt_handshake_timeouts_total 2010
telemt_upstream_connect_attempt_total 5995
telemt_upstream_connect_success_total 5971
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4569
telemt_me_reconnect_success_total 4545
telemt_me_reader_eof_total 4800
telemt_me_idle_close_by_peer_total 4800
telemt_me_route_drop_no_conn_total 128925
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358469
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 920
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 635
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4596
telemt_me_writer_restored_same_endpoint_total 4534
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 358483
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 4056615812 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 129559692080 (120.66 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 28229.2 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153789
telemt_connections_bad_total 18312
telemt_handshake_timeouts_total 5265
telemt_upstream_connect_attempt_total 8185
telemt_upstream_connect_success_total 8146
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 6436
telemt_me_reconnect_success_total 6404
telemt_me_reader_eof_total 6779
telemt_me_idle_close_by_peer_total 6779
telemt_me_route_drop_no_conn_total 37144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126026
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 344
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6424
telemt_me_writer_restored_same_endpoint_total 6396
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 126322
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 2170475839 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 42512289192 (39.59 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 28229.6 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287470
telemt_connections_bad_total 7112
telemt_handshake_timeouts_total 29503
telemt_upstream_connect_attempt_total 6595
telemt_upstream_connect_success_total 6566
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 6595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 5158
telemt_me_reconnect_success_total 5132
telemt_me_reader_eof_total 5427
telemt_me_idle_close_by_peer_total 5427
telemt_me_route_drop_no_conn_total 71290
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238913
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 441
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5187
telemt_me_writer_restored_same_endpoint_total 5113
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 238717
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 3928144576 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 98959085692 (92.16 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 28229.3 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202544
telemt_connections_bad_total 38102
telemt_handshake_timeouts_total 13757
telemt_upstream_connect_attempt_total 9741
telemt_upstream_connect_success_total 9530
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 9741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14092
telemt_me_reconnect_success_total 8100
telemt_me_reader_eof_total 8555
telemt_me_idle_close_by_peer_total 8555
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 47227
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146674
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8353
telemt_me_refill_failed_total 186
telemt_me_writer_restored_same_endpoint_total 8074
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 146677
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 1256177744 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 51157747928 (47.64 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 28229.8 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138413
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 1471
telemt_upstream_connect_attempt_total 6428
telemt_upstream_connect_success_total 6401
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4997
telemt_me_reconnect_success_total 4976
telemt_me_reader_eof_total 5313
telemt_me_idle_close_by_peer_total 5313
telemt_me_route_drop_no_conn_total 38670
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131415
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 518
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5026
telemt_me_writer_restored_same_endpoint_total 4968
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 131425
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 1259082084 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 45179698532 (42.08 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 87
```