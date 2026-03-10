# Server Metrics 2026-03-10 22:54:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 30449.7 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 747060
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8400
telemt_upstream_connect_attempt_total 6532
telemt_upstream_connect_success_total 6523
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3220
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 365
telemt_me_reconnect_attempts_total 16596
telemt_me_reconnect_success_total 4935
telemt_me_reader_eof_total 5436
telemt_me_idle_close_by_peer_total 5436
telemt_me_route_drop_no_conn_total 310734
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706746
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3483
telemt_desync_full_logged_total 971
telemt_desync_suppressed_total 2512
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 1175
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5339
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4929
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 706549
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 10056339408 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 212935183392 (198.31 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 30506.4 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324156
telemt_connections_bad_total 2372
telemt_handshake_timeouts_total 17584
telemt_upstream_connect_attempt_total 13247
telemt_upstream_connect_success_total 10378
telemt_upstream_connect_fail_total 2869
telemt_upstream_connect_attempts_per_request{bucket="1"} 13247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2869
telemt_me_keepalive_timeout_total 1382
telemt_me_reconnect_attempts_total 6683
telemt_me_reconnect_success_total 5876
telemt_me_reader_eof_total 6169
telemt_me_idle_close_by_peer_total 6167
telemt_me_route_drop_no_conn_total 168371
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274070
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1646
telemt_desync_full_logged_total 458
telemt_desync_suppressed_total 1188
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5965
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5855
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 276339
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 2695684222 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 65007464748 (60.54 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 30506.2 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535393
telemt_connections_bad_total 3463
telemt_handshake_timeouts_total 33890
telemt_upstream_connect_attempt_total 8326
telemt_upstream_connect_success_total 8204
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 8326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 217
telemt_me_reconnect_attempts_total 16632
telemt_me_reconnect_success_total 5576
telemt_me_reader_eof_total 6124
telemt_me_idle_close_by_peer_total 6124
telemt_me_route_drop_no_conn_total 185384
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 469672
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1514
telemt_desync_full_logged_total 429
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 653
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6006
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5565
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 470604
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 6683012041 (6.22 GB)
telemt_user_octets_to_client{user="hello"} 149466963529 (139.20 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 30506.5 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379607
telemt_connections_bad_total 29302
telemt_handshake_timeouts_total 34309
telemt_upstream_connect_attempt_total 8471
telemt_upstream_connect_success_total 8471
telemt_upstream_connect_attempts_per_request{bucket="1"} 8471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 7942
telemt_me_reconnect_success_total 6917
telemt_me_reader_eof_total 7271
telemt_me_idle_close_by_peer_total 7271
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 120832
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303073
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 690
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 410
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 7021
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6903
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 302748
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 4066540340 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 87717238912 (81.69 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 30506.2 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400936
telemt_connections_bad_total 3190
telemt_handshake_timeouts_total 2630
telemt_upstream_connect_attempt_total 9403
telemt_upstream_connect_success_total 9365
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 9403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 202
telemt_me_reconnect_attempts_total 11535
telemt_me_reconnect_success_total 7775
telemt_me_reader_eof_total 8148
telemt_me_idle_close_by_peer_total 8148
telemt_me_route_drop_no_conn_total 139007
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372446
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2159
telemt_desync_full_logged_total 833
telemt_desync_suppressed_total 1326
telemt_desync_frames_bucket_total{bucket="1_2"} 797
telemt_desync_frames_bucket_total{bucket="3_10"} 926
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 8001
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7775
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 372259
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 6451267516 (6.01 GB)
telemt_user_octets_to_client{user="hello"} 139520113276 (129.94 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 31
```