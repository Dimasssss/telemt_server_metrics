# Server Metrics 2026-03-14 20:13:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 24980.7 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 963153
telemt_connections_bad_total 40409
telemt_handshake_timeouts_total 14315
telemt_upstream_connect_attempt_total 4563
telemt_upstream_connect_success_total 4543
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 4060
telemt_me_reconnect_success_total 3255
telemt_me_reader_eof_total 3428
telemt_me_idle_close_by_peer_total 3428
telemt_me_route_drop_no_conn_total 369764
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854573
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2972
telemt_desync_full_logged_total 836
telemt_desync_suppressed_total 2136
telemt_desync_frames_bucket_total{bucket="1_2"} 708
telemt_desync_frames_bucket_total{bucket="3_10"} 1086
telemt_desync_frames_bucket_total{bucket="gt_10"} 1178
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3335
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3246
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 854522
telemt_user_connections_current{user="hello"} 1482
telemt_user_octets_from_client{user="hello"} 15377614620 (14.32 GB)
telemt_user_octets_to_client{user="hello"} 284133240452 (264.62 GB)
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 24986.1 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376133
telemt_connections_bad_total 27147
telemt_handshake_timeouts_total 11221
telemt_upstream_connect_attempt_total 5301
telemt_upstream_connect_success_total 5246
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 5301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 446
telemt_me_reconnect_attempts_total 4755
telemt_me_reconnect_success_total 3961
telemt_me_reader_eof_total 4141
telemt_me_idle_close_by_peer_total 4141
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 113652
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317061
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1533
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 1127
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 525
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4070
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3939
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 316994
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 4777208800 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 111760936436 (104.09 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 24849.0 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808430
telemt_connections_bad_total 3193
telemt_handshake_timeouts_total 183090
telemt_upstream_connect_attempt_total 4791
telemt_upstream_connect_success_total 4775
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 7411
telemt_me_reconnect_success_total 3500
telemt_me_reader_eof_total 3756
telemt_me_idle_close_by_peer_total 3756
telemt_me_route_drop_no_conn_total 188379
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530508
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1965
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 1011
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3660
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3467
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 530337
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 7880342312 (7.34 GB)
telemt_user_octets_to_client{user="hello"} 190934219604 (177.82 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 24703.3 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438419
telemt_connections_bad_total 97418
telemt_handshake_timeouts_total 51908
telemt_upstream_connect_attempt_total 5777
telemt_upstream_connect_success_total 5776
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 195
telemt_me_reconnect_attempts_total 5429
telemt_me_reconnect_success_total 4508
telemt_me_reader_eof_total 4724
telemt_me_idle_close_by_peer_total 4724
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 100081
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281787
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 628
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4587
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4497
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 281704
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 3960726992 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 87507271384 (81.50 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 24998.9 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369296
telemt_connections_bad_total 1332
telemt_handshake_timeouts_total 3851
telemt_upstream_connect_attempt_total 5352
telemt_upstream_connect_success_total 5244
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 5352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 4649
telemt_me_reconnect_success_total 3976
telemt_me_reader_eof_total 4190
telemt_me_idle_close_by_peer_total 4190
telemt_me_route_drop_no_conn_total 116952
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342121
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 859
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4068
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3958
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 342091
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 5567540764 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 145273659872 (135.30 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 77
```