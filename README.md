# Server Metrics 2026-03-14 20:24:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 25594.1 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 980863
telemt_connections_bad_total 40472
telemt_handshake_timeouts_total 14410
telemt_upstream_connect_attempt_total 4687
telemt_upstream_connect_success_total 4665
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 4140
telemt_me_reconnect_success_total 3333
telemt_me_reader_eof_total 3515
telemt_me_idle_close_by_peer_total 3515
telemt_me_route_drop_no_conn_total 376083
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 871099
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3010
telemt_desync_full_logged_total 850
telemt_desync_suppressed_total 2160
telemt_desync_frames_bucket_total{bucket="1_2"} 717
telemt_desync_frames_bucket_total{bucket="3_10"} 1106
telemt_desync_frames_bucket_total{bucket="gt_10"} 1187
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3415
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3324
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 871045
telemt_user_connections_current{user="hello"} 1537
telemt_user_octets_from_client{user="hello"} 15660123604 (14.58 GB)
telemt_user_octets_to_client{user="hello"} 294533346692 (274.31 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 25599.3 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385169
telemt_connections_bad_total 28206
telemt_handshake_timeouts_total 11566
telemt_upstream_connect_attempt_total 5493
telemt_upstream_connect_success_total 5437
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 5493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 475
telemt_me_reconnect_attempts_total 4902
telemt_me_reconnect_success_total 4108
telemt_me_reader_eof_total 4282
telemt_me_idle_close_by_peer_total 4282
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 115016
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322963
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1572
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 1159
telemt_desync_frames_bucket_total{bucket="1_2"} 656
telemt_desync_frames_bucket_total{bucket="3_10"} 543
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4221
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4085
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 322896
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 4813808376 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 113249071348 (105.47 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 25462.2 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824193
telemt_connections_bad_total 3338
telemt_handshake_timeouts_total 188234
telemt_upstream_connect_attempt_total 4930
telemt_upstream_connect_success_total 4913
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 7506
telemt_me_reconnect_success_total 3595
telemt_me_reader_eof_total 3859
telemt_me_idle_close_by_peer_total 3859
telemt_me_route_drop_no_conn_total 190845
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538485
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1995
telemt_desync_full_logged_total 780
telemt_desync_suppressed_total 1215
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 1027
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3755
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3562
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 538313
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 8109912540 (7.55 GB)
telemt_user_octets_to_client{user="hello"} 194614387624 (181.25 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 25316.6 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 447122
telemt_connections_bad_total 98265
telemt_handshake_timeouts_total 52624
telemt_upstream_connect_attempt_total 5886
telemt_upstream_connect_success_total 5885
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 5495
telemt_me_reconnect_success_total 4574
telemt_me_reader_eof_total 4793
telemt_me_idle_close_by_peer_total 4793
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 102236
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288761
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 654
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4656
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4563
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 288678
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 4146660272 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 89673457040 (83.51 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 25611.7 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375717
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 3882
telemt_upstream_connect_attempt_total 5492
telemt_upstream_connect_success_total 5383
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 5492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 4745
telemt_me_reconnect_success_total 4072
telemt_me_reader_eof_total 4292
telemt_me_idle_close_by_peer_total 4292
telemt_me_route_drop_no_conn_total 119252
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348169
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 890
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4165
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4054
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 348138
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 5654325308 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 148720015672 (138.51 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 71
```