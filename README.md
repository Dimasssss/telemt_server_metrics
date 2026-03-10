# Server Metrics 2026-03-10 19:30:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18224.7 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571170
telemt_connections_bad_total 8000
telemt_handshake_timeouts_total 4111
telemt_upstream_connect_attempt_total 3670
telemt_upstream_connect_success_total 3661
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 322
telemt_me_reconnect_attempts_total 13126
telemt_me_reconnect_success_total 2665
telemt_me_reader_eof_total 3009
telemt_me_idle_close_by_peer_total 3009
telemt_me_route_drop_no_conn_total 238052
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539429
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2860
telemt_desync_full_logged_total 767
telemt_desync_suppressed_total 2093
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 1102
telemt_desync_frames_bucket_total{bucket="gt_10"} 994
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3004
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2659
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 539332
telemt_user_connections_current{user="hello"} 1068
telemt_user_octets_from_client{user="hello"} 7985598904 (7.44 GB)
telemt_user_octets_to_client{user="hello"} 155670047432 (144.98 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18281.5 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247260
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 16537
telemt_upstream_connect_attempt_total 9015
telemt_upstream_connect_success_total 6269
telemt_upstream_connect_fail_total 2745
telemt_upstream_connect_attempts_per_request{bucket="1"} 9014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1882
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2745
telemt_me_keepalive_timeout_total 710
telemt_me_reconnect_attempts_total 4098
telemt_me_reconnect_success_total 3311
telemt_me_reader_eof_total 3458
telemt_me_idle_close_by_peer_total 3456
telemt_me_route_drop_no_conn_total 138060
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210735
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1011
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 732
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 320
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3372
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3290
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 212034
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 2247691430 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 51360547350 (47.83 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 18281.4 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410035
telemt_connections_bad_total 1333
telemt_handshake_timeouts_total 32160
telemt_upstream_connect_attempt_total 5619
telemt_upstream_connect_success_total 5533
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 5619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 6953
telemt_me_reconnect_success_total 3502
telemt_me_reader_eof_total 3722
telemt_me_idle_close_by_peer_total 3722
telemt_me_route_drop_no_conn_total 139612
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351422
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1116
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3673
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3491
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 352372
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 5091830661 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 111232932185 (103.59 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 18281.9 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271628
telemt_connections_bad_total 18113
telemt_handshake_timeouts_total 23864
telemt_upstream_connect_attempt_total 4991
telemt_upstream_connect_success_total 4990
telemt_upstream_connect_attempts_per_request{bucket="1"} 4990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 5033
telemt_me_reconnect_success_total 4018
telemt_me_reader_eof_total 4206
telemt_me_idle_close_by_peer_total 4206
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 88890
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218517
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 4090
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4005
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 218286
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 3493380092 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 63903653824 (59.51 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18281.5 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285560
telemt_connections_bad_total 829
telemt_handshake_timeouts_total 1903
telemt_upstream_connect_attempt_total 5578
telemt_upstream_connect_success_total 5558
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 5578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 4596
telemt_me_reconnect_success_total 4561
telemt_me_reader_eof_total 4694
telemt_me_idle_close_by_peer_total 4694
telemt_me_route_drop_no_conn_total 105955
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269878
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1515
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 962
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4628
telemt_me_writer_restored_same_endpoint_total 4561
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 269804
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 5436166508 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 84642412584 (78.83 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 79
```