# Server Metrics 2026-03-14 19:43:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 23140.5 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912806
telemt_connections_bad_total 40377
telemt_handshake_timeouts_total 13607
telemt_upstream_connect_attempt_total 4274
telemt_upstream_connect_success_total 4257
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 3860
telemt_me_reconnect_success_total 3056
telemt_me_reader_eof_total 3217
telemt_me_idle_close_by_peer_total 3217
telemt_me_route_drop_no_conn_total 349812
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 807531
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2774
telemt_desync_full_logged_total 792
telemt_desync_suppressed_total 1982
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 1022
telemt_desync_frames_bucket_total{bucket="gt_10"} 1093
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3134
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3047
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 807478
telemt_user_connections_current{user="hello"} 1562
telemt_user_octets_from_client{user="hello"} 14393619492 (13.41 GB)
telemt_user_octets_to_client{user="hello"} 265310846528 (247.09 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 23145.7 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352976
telemt_connections_bad_total 24326
telemt_handshake_timeouts_total 10455
telemt_upstream_connect_attempt_total 4923
telemt_upstream_connect_success_total 4869
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 441
telemt_me_reconnect_attempts_total 4464
telemt_me_reconnect_success_total 3671
telemt_me_reader_eof_total 3825
telemt_me_idle_close_by_peer_total 3825
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 108966
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298024
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1426
telemt_desync_full_logged_total 387
telemt_desync_suppressed_total 1039
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3778
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3649
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 297955
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 4018423816 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 104419085700 (97.25 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 23008.5 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744226
telemt_connections_bad_total 2896
telemt_handshake_timeouts_total 153251
telemt_upstream_connect_attempt_total 4468
telemt_upstream_connect_success_total 4452
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 7174
telemt_me_reconnect_success_total 3265
telemt_me_reader_eof_total 3507
telemt_me_idle_close_by_peer_total 3507
telemt_me_route_drop_no_conn_total 178612
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502765
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1822
telemt_desync_full_logged_total 710
telemt_desync_suppressed_total 1112
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 636
telemt_desync_frames_bucket_total{bucket="gt_10"} 937
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3422
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3232
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 502594
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 7407090212 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 180364559728 (167.98 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 22863.0 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410823
telemt_connections_bad_total 92166
telemt_handshake_timeouts_total 48807
telemt_upstream_connect_attempt_total 5392
telemt_upstream_connect_success_total 5391
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 5130
telemt_me_reconnect_success_total 4211
telemt_me_reader_eof_total 4407
telemt_me_idle_close_by_peer_total 4407
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 94783
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262824
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 575
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4287
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4200
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 262741
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 3740163116 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 83719290488 (77.97 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 23158.3 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348322
telemt_connections_bad_total 1313
telemt_handshake_timeouts_total 3765
telemt_upstream_connect_attempt_total 4847
telemt_upstream_connect_success_total 4747
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 4847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 4238
telemt_me_reconnect_success_total 3567
telemt_me_reader_eof_total 3756
telemt_me_idle_close_by_peer_total 3756
telemt_me_route_drop_no_conn_total 110369
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322507
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 517
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3655
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3549
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 322480
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 5001015372 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 136946891496 (127.54 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 75
```