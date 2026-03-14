# Server Metrics 2026-03-14 19:22:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 21904.6 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 874198
telemt_connections_bad_total 40367
telemt_handshake_timeouts_total 12839
telemt_upstream_connect_attempt_total 4109
telemt_upstream_connect_success_total 4092
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 3738
telemt_me_reconnect_success_total 2935
telemt_me_reader_eof_total 3090
telemt_me_idle_close_by_peer_total 3090
telemt_me_route_drop_no_conn_total 334647
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771417
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2644
telemt_desync_full_logged_total 756
telemt_desync_suppressed_total 1888
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3011
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2926
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 771363
telemt_user_connections_current{user="hello"} 1646
telemt_user_octets_from_client{user="hello"} 13724417824 (12.78 GB)
telemt_user_octets_to_client{user="hello"} 255875079032 (238.30 GB)
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 21910.1 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337470
telemt_connections_bad_total 23142
telemt_handshake_timeouts_total 10135
telemt_upstream_connect_attempt_total 4577
telemt_upstream_connect_success_total 4524
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 4577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 388
telemt_me_reconnect_attempts_total 4162
telemt_me_reconnect_success_total 3369
telemt_me_reader_eof_total 3528
telemt_me_idle_close_by_peer_total 3528
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 104844
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284636
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1204
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 833
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3464
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3352
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 284567
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 3873535680 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 99226562604 (92.41 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 21773.0 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705668
telemt_connections_bad_total 2881
telemt_handshake_timeouts_total 139067
telemt_upstream_connect_attempt_total 4260
telemt_upstream_connect_success_total 4245
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 7010
telemt_me_reconnect_success_total 3101
telemt_me_reader_eof_total 3334
telemt_me_idle_close_by_peer_total 3334
telemt_me_route_drop_no_conn_total 171271
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482173
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1706
telemt_desync_full_logged_total 658
telemt_desync_suppressed_total 1048
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 597
telemt_desync_frames_bucket_total{bucket="gt_10"} 877
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3254
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3068
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 482000
telemt_user_connections_current{user="hello"} 996
telemt_user_octets_from_client{user="hello"} 7084479500 (6.60 GB)
telemt_user_octets_to_client{user="hello"} 172158697304 (160.34 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 21627.4 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391424
telemt_connections_bad_total 88964
telemt_handshake_timeouts_total 46437
telemt_upstream_connect_attempt_total 5092
telemt_upstream_connect_success_total 5091
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 4908
telemt_me_reconnect_success_total 3991
telemt_me_reader_eof_total 4172
telemt_me_idle_close_by_peer_total 4172
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 88455
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249676
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4066
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3981
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 249607
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 3675955040 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 79906109072 (74.42 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 21922.7 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332982
telemt_connections_bad_total 1263
telemt_handshake_timeouts_total 3611
telemt_upstream_connect_attempt_total 4574
telemt_upstream_connect_success_total 4481
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 4574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 4015
telemt_me_reconnect_success_total 3344
telemt_me_reader_eof_total 3529
telemt_me_idle_close_by_peer_total 3529
telemt_me_route_drop_no_conn_total 103590
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308610
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 774
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3428
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3326
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 308598
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 4756852392 (4.43 GB)
telemt_user_octets_to_client{user="hello"} 131686403256 (122.64 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 100
```