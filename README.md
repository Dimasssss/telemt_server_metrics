# Server Metrics 2026-03-15 06:55:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 31283.1 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521804
telemt_connections_bad_total 11849
telemt_handshake_timeouts_total 3649
telemt_upstream_connect_attempt_total 6573
telemt_upstream_connect_success_total 6547
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5015
telemt_me_reconnect_success_total 4989
telemt_me_reader_eof_total 5269
telemt_me_idle_close_by_peer_total 5269
telemt_me_route_drop_no_conn_total 159559
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441192
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1161
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 796
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5049
telemt_me_writer_restored_same_endpoint_total 4978
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 441202
telemt_user_connections_current{user="hello"} 1575
telemt_user_octets_from_client{user="hello"} 5135073788 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 156043107460 (145.33 GB)
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 31283.7 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187298
telemt_connections_bad_total 18330
telemt_handshake_timeouts_total 5697
telemt_upstream_connect_attempt_total 8824
telemt_upstream_connect_success_total 8779
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6940
telemt_me_reconnect_success_total 6902
telemt_me_reader_eof_total 7297
telemt_me_idle_close_by_peer_total 7297
telemt_me_route_drop_no_conn_total 47831
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157718
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 523
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6930
telemt_me_writer_restored_same_endpoint_total 6894
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 158010
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 2563031115 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 58161909604 (54.17 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 31283.9 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344815
telemt_connections_bad_total 9720
telemt_handshake_timeouts_total 31620
telemt_upstream_connect_attempt_total 7187
telemt_upstream_connect_success_total 7155
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5618
telemt_me_reconnect_success_total 5588
telemt_me_reader_eof_total 5913
telemt_me_idle_close_by_peer_total 5913
telemt_me_route_drop_no_conn_total 87997
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286005
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 557
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 325
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5649
telemt_me_writer_restored_same_endpoint_total 5569
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 285805
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 4442719136 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 120309767000 (112.05 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 31283.7 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236098
telemt_connections_bad_total 43183
telemt_handshake_timeouts_total 15001
telemt_upstream_connect_attempt_total 10494
telemt_upstream_connect_success_total 10254
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 10494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 18591
telemt_me_reconnect_success_total 8692
telemt_me_reader_eof_total 9276
telemt_me_idle_close_by_peer_total 9276
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 56360
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172799
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 275
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 9074
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 8666
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 172802
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 1471578796 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 59454008948 (55.37 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 31284.7 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174218
telemt_connections_bad_total 249
telemt_handshake_timeouts_total 1674
telemt_upstream_connect_attempt_total 6987
telemt_upstream_connect_success_total 6959
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5425
telemt_me_reconnect_success_total 5401
telemt_me_reader_eof_total 5763
telemt_me_idle_close_by_peer_total 5763
telemt_me_route_drop_no_conn_total 52159
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163540
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 659
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 443
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5453
telemt_me_writer_restored_same_endpoint_total 5393
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 163548
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 1592896004 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 60752182704 (56.58 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 91
```