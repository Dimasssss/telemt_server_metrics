# Server Metrics 2026-03-10 19:35:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18530.6 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578650
telemt_connections_bad_total 8000
telemt_handshake_timeouts_total 4366
telemt_upstream_connect_attempt_total 3702
telemt_upstream_connect_success_total 3693
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 325
telemt_me_reconnect_attempts_total 13158
telemt_me_reconnect_success_total 2697
telemt_me_reader_eof_total 3042
telemt_me_idle_close_by_peer_total 3042
telemt_me_route_drop_no_conn_total 240779
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546429
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2931
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 2150
telemt_desync_frames_bucket_total{bucket="1_2"} 787
telemt_desync_frames_bucket_total{bucket="3_10"} 1126
telemt_desync_frames_bucket_total{bucket="gt_10"} 1018
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3038
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2691
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 546316
telemt_user_connections_current{user="hello"} 1089
telemt_user_octets_from_client{user="hello"} 8056336664 (7.50 GB)
telemt_user_octets_to_client{user="hello"} 158098941212 (147.24 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18587.5 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249923
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 16557
telemt_upstream_connect_attempt_total 9076
telemt_upstream_connect_success_total 6331
telemt_upstream_connect_fail_total 2745
telemt_upstream_connect_attempts_per_request{bucket="1"} 9076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1882
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2745
telemt_me_keepalive_timeout_total 711
telemt_me_reconnect_attempts_total 4159
telemt_me_reconnect_success_total 3372
telemt_me_reader_eof_total 3521
telemt_me_idle_close_by_peer_total 3519
telemt_me_route_drop_no_conn_total 138701
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213273
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1050
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 764
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3435
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3351
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 214572
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 2269073738 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 52692951494 (49.07 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 18587.4 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414353
telemt_connections_bad_total 1379
telemt_handshake_timeouts_total 32171
telemt_upstream_connect_attempt_total 5714
telemt_upstream_connect_success_total 5627
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 5714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 7048
telemt_me_reconnect_success_total 3594
telemt_me_reader_eof_total 3816
telemt_me_idle_close_by_peer_total 3816
telemt_me_route_drop_no_conn_total 141467
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355638
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1128
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 817
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3767
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3583
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 356588
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 5165056525 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 112535603341 (104.81 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 18587.9 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275316
telemt_connections_bad_total 18428
telemt_handshake_timeouts_total 24176
telemt_upstream_connect_attempt_total 5048
telemt_upstream_connect_success_total 5048
telemt_upstream_connect_attempts_per_request{bucket="1"} 5048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 5090
telemt_me_reconnect_success_total 4076
telemt_me_reader_eof_total 4263
telemt_me_idle_close_by_peer_total 4263
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 90056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221526
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 582
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 4147
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4063
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 221294
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 3517980960 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 65059116568 (60.59 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18587.4 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289326
telemt_connections_bad_total 829
telemt_handshake_timeouts_total 1919
telemt_upstream_connect_attempt_total 5697
telemt_upstream_connect_success_total 5675
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2678
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 4715
telemt_me_reconnect_success_total 4677
telemt_me_reader_eof_total 4811
telemt_me_idle_close_by_peer_total 4811
telemt_me_route_drop_no_conn_total 107266
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273348
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1529
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 968
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 640
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4748
telemt_me_writer_restored_same_endpoint_total 4677
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 273272
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 5455561540 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 87131584464 (81.15 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 83
```