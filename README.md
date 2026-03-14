# Server Metrics 2026-03-14 20:39:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 26514.2 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008414
telemt_connections_bad_total 42322
telemt_handshake_timeouts_total 14577
telemt_upstream_connect_attempt_total 4859
telemt_upstream_connect_success_total 4836
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 4267
telemt_me_reconnect_success_total 3460
telemt_me_reader_eof_total 3649
telemt_me_idle_close_by_peer_total 3649
telemt_me_route_drop_no_conn_total 385942
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 895349
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3077
telemt_desync_full_logged_total 873
telemt_desync_suppressed_total 2204
telemt_desync_frames_bucket_total{bucket="1_2"} 727
telemt_desync_frames_bucket_total{bucket="3_10"} 1136
telemt_desync_frames_bucket_total{bucket="gt_10"} 1214
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3541
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3451
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 895301
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 16095197504 (14.99 GB)
telemt_user_octets_to_client{user="hello"} 303449035508 (282.61 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 26519.4 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395645
telemt_connections_bad_total 29796
telemt_handshake_timeouts_total 12065
telemt_upstream_connect_attempt_total 5733
telemt_upstream_connect_success_total 5674
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 5733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 478
telemt_me_reconnect_attempts_total 5097
telemt_me_reconnect_success_total 4300
telemt_me_reader_eof_total 4493
telemt_me_idle_close_by_peer_total 4493
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 117122
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331156
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1606
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 1181
telemt_desync_frames_bucket_total{bucket="1_2"} 670
telemt_desync_frames_bucket_total{bucket="3_10"} 558
telemt_desync_frames_bucket_total{bucket="gt_10"} 378
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4416
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4277
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 331095
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 4892576004 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 116069615040 (108.10 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 26382.4 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854021
telemt_connections_bad_total 3349
telemt_handshake_timeouts_total 202812
telemt_upstream_connect_attempt_total 5130
telemt_upstream_connect_success_total 5113
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 7663
telemt_me_reconnect_success_total 3752
telemt_me_reader_eof_total 4025
telemt_me_idle_close_by_peer_total 4025
telemt_me_route_drop_no_conn_total 194425
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 550573
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2047
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 1252
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 1050
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3914
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3719
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 550401
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 8235760124 (7.67 GB)
telemt_user_octets_to_client{user="hello"} 199976754520 (186.24 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 26236.7 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458265
telemt_connections_bad_total 98971
telemt_handshake_timeouts_total 53178
telemt_upstream_connect_attempt_total 6072
telemt_upstream_connect_success_total 6071
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 210
telemt_me_reconnect_attempts_total 5638
telemt_me_reconnect_success_total 4716
telemt_me_reader_eof_total 4941
telemt_me_idle_close_by_peer_total 4941
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 105374
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298349
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 659
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4801
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4704
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 298264
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 4232062740 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 92724643604 (86.36 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 26532.1 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384488
telemt_connections_bad_total 1372
telemt_handshake_timeouts_total 3924
telemt_upstream_connect_attempt_total 5666
telemt_upstream_connect_success_total 5555
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 5666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 4875
telemt_me_reconnect_success_total 4200
telemt_me_reader_eof_total 4431
telemt_me_idle_close_by_peer_total 4431
telemt_me_route_drop_no_conn_total 121666
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356535
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 907
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 581
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 327
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4298
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4182
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 356502
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 5792427236 (5.39 GB)
telemt_user_octets_to_client{user="hello"} 151293249908 (140.90 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 58
```