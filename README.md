# Server Metrics 2026-03-14 21:56:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 31114.0 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1107561
telemt_connections_bad_total 42861
telemt_handshake_timeouts_total 14919
telemt_upstream_connect_attempt_total 5672
telemt_upstream_connect_success_total 5649
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 4865
telemt_me_reconnect_success_total 4056
telemt_me_reader_eof_total 4284
telemt_me_idle_close_by_peer_total 4284
telemt_me_route_drop_no_conn_total 422192
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 988033
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3252
telemt_desync_full_logged_total 954
telemt_desync_suppressed_total 2298
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 1233
telemt_desync_frames_bucket_total{bucket="gt_10"} 1254
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4147
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 4047
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 988001
telemt_user_connections_current{user="hello"} 1085
telemt_user_octets_from_client{user="hello"} 21017543236 (19.57 GB)
telemt_user_octets_to_client{user="hello"} 332687507472 (309.84 GB)
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 31119.1 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438027
telemt_connections_bad_total 34230
telemt_handshake_timeouts_total 13479
telemt_upstream_connect_attempt_total 6662
telemt_upstream_connect_success_total 6597
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 6662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 491
telemt_me_reconnect_attempts_total 5805
telemt_me_reconnect_success_total 5001
telemt_me_reader_eof_total 5244
telemt_me_idle_close_by_peer_total 5244
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 127647
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366215
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1831
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1350
telemt_desync_frames_bucket_total{bucket="1_2"} 741
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 448
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5131
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4978
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 366159
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 5735953368 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 128586683176 (119.76 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 30982.1 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958731
telemt_connections_bad_total 3974
telemt_handshake_timeouts_total 246736
telemt_upstream_connect_attempt_total 6069
telemt_upstream_connect_success_total 6050
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 6069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 8384
telemt_me_reconnect_success_total 4469
telemt_me_reader_eof_total 4789
telemt_me_idle_close_by_peer_total 4789
telemt_me_route_drop_no_conn_total 210702
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 607272
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2245
telemt_desync_full_logged_total 857
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 781
telemt_desync_frames_bucket_total{bucket="gt_10"} 1118
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4642
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4436
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 607094
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 9655228920 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 225553064648 (210.06 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 30836.6 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503456
telemt_connections_bad_total 102604
telemt_handshake_timeouts_total 56376
telemt_upstream_connect_attempt_total 7073
telemt_upstream_connect_success_total 7072
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 6423
telemt_me_reconnect_success_total 5499
telemt_me_reader_eof_total 5785
telemt_me_idle_close_by_peer_total 5785
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 117910
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336122
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 739
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 478
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5592
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5486
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 336036
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 4626836676 (4.31 GB)
telemt_user_octets_to_client{user="hello"} 103838600504 (96.71 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 31132.2 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422549
telemt_connections_bad_total 1406
telemt_handshake_timeouts_total 4175
telemt_upstream_connect_attempt_total 6584
telemt_upstream_connect_success_total 6456
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 6584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 5561
telemt_me_reconnect_success_total 4882
telemt_me_reader_eof_total 5160
telemt_me_idle_close_by_peer_total 5160
telemt_me_route_drop_no_conn_total 132223
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392429
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1179
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 766
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4987
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4864
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 392394
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 6280190816 (5.85 GB)
telemt_user_octets_to_client{user="hello"} 164072503248 (152.80 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 42
```