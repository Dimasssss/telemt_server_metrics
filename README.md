# Server Metrics 2026-03-10 23:09:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 31363.2 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753776
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8447
telemt_upstream_connect_attempt_total 6742
telemt_upstream_connect_success_total 6733
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 365
telemt_me_reconnect_attempts_total 16762
telemt_me_reconnect_success_total 5101
telemt_me_reader_eof_total 5616
telemt_me_idle_close_by_peer_total 5616
telemt_me_route_drop_no_conn_total 312776
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 713319
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5507
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5095
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 406
telemt_user_connections_total{user="hello"} 713108
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 10089966900 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 214594612164 (199.86 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 31419.8 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326718
telemt_connections_bad_total 2372
telemt_handshake_timeouts_total 17594
telemt_upstream_connect_attempt_total 13504
telemt_upstream_connect_success_total 10634
telemt_upstream_connect_fail_total 2870
telemt_upstream_connect_attempts_per_request{bucket="1"} 13504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2870
telemt_me_keepalive_timeout_total 1387
telemt_me_reconnect_attempts_total 6896
telemt_me_reconnect_success_total 6087
telemt_me_reader_eof_total 6396
telemt_me_idle_close_by_peer_total 6394
telemt_me_route_drop_no_conn_total 168879
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276555
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1683
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 1218
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6177
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6066
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 278824
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2742858542 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 65957535604 (61.43 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 31419.8 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540296
telemt_connections_bad_total 3470
telemt_handshake_timeouts_total 33933
telemt_upstream_connect_attempt_total 8540
telemt_upstream_connect_success_total 8418
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 8540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 16803
telemt_me_reconnect_success_total 5747
telemt_me_reader_eof_total 6309
telemt_me_idle_close_by_peer_total 6309
telemt_me_route_drop_no_conn_total 186754
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474499
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1517
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6179
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5736
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 475431
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 6708921761 (6.25 GB)
telemt_user_octets_to_client{user="hello"} 150318565277 (140.00 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 31420.1 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385283
telemt_connections_bad_total 30136
telemt_handshake_timeouts_total 34883
telemt_upstream_connect_attempt_total 8724
telemt_upstream_connect_success_total 8724
telemt_upstream_connect_attempts_per_request{bucket="1"} 8724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 8152
telemt_me_reconnect_success_total 7126
telemt_me_reader_eof_total 7499
telemt_me_idle_close_by_peer_total 7499
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 122069
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307335
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7232
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7112
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 307010
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 4079004848 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 88078160168 (82.03 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 31419.8 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406912
telemt_connections_bad_total 3190
telemt_handshake_timeouts_total 2652
telemt_upstream_connect_attempt_total 9629
telemt_upstream_connect_success_total 9590
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 11717
telemt_me_reconnect_success_total 7957
telemt_me_reader_eof_total 8348
telemt_me_idle_close_by_peer_total 8348
telemt_me_route_drop_no_conn_total 140065
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377734
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2200
telemt_desync_full_logged_total 846
telemt_desync_suppressed_total 1354
telemt_desync_frames_bucket_total{bucket="1_2"} 808
telemt_desync_frames_bucket_total{bucket="3_10"} 944
telemt_desync_frames_bucket_total{bucket="gt_10"} 448
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8185
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7957
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 377538
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 6464076896 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 140247742900 (130.62 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 34
```