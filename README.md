# Server Metrics 2026-03-10 23:14:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 31667.6 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755656
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8460
telemt_upstream_connect_attempt_total 6829
telemt_upstream_connect_success_total 6820
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3358
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 366
telemt_me_reconnect_attempts_total 16806
telemt_me_reconnect_success_total 5145
telemt_me_reader_eof_total 5664
telemt_me_idle_close_by_peer_total 5664
telemt_me_route_drop_no_conn_total 313492
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715151
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 5551
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5139
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 406
telemt_user_connections_total{user="hello"} 714941
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 10098704920 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 215357803916 (200.57 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 31724.2 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327755
telemt_connections_bad_total 2372
telemt_handshake_timeouts_total 17599
telemt_upstream_connect_attempt_total 13620
telemt_upstream_connect_success_total 10747
telemt_upstream_connect_fail_total 2873
telemt_upstream_connect_attempts_per_request{bucket="1"} 13620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2873
telemt_me_keepalive_timeout_total 1387
telemt_me_reconnect_attempts_total 6966
telemt_me_reconnect_success_total 6157
telemt_me_reader_eof_total 6479
telemt_me_idle_close_by_peer_total 6477
telemt_me_route_drop_no_conn_total 169104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277559
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1696
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 1228
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 597
telemt_desync_frames_bucket_total{bucket="gt_10"} 576
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6247
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6136
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 279828
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2749504666 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 67090987208 (62.48 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 31724.1 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542059
telemt_connections_bad_total 3510
telemt_handshake_timeouts_total 33938
telemt_upstream_connect_attempt_total 8645
telemt_upstream_connect_success_total 8523
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 8645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 221
telemt_me_reconnect_attempts_total 16864
telemt_me_reconnect_success_total 5807
telemt_me_reader_eof_total 6378
telemt_me_idle_close_by_peer_total 6378
telemt_me_route_drop_no_conn_total 187326
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476211
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
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 6241
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5796
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 477143
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 6713963993 (6.25 GB)
telemt_user_octets_to_client{user="hello"} 150590268857 (140.25 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 31724.5 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387085
telemt_connections_bad_total 30416
telemt_handshake_timeouts_total 35179
telemt_upstream_connect_attempt_total 8838
telemt_upstream_connect_success_total 8838
telemt_upstream_connect_attempts_per_request{bucket="1"} 8838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 8222
telemt_me_reconnect_success_total 7196
telemt_me_reader_eof_total 7582
telemt_me_idle_close_by_peer_total 7582
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 122379
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308541
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7302
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7182
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 308216
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 4082656228 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 88285862224 (82.22 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 31724.1 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408830
telemt_connections_bad_total 3192
telemt_handshake_timeouts_total 2660
telemt_upstream_connect_attempt_total 9735
telemt_upstream_connect_success_total 9696
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 11780
telemt_me_reconnect_success_total 8020
telemt_me_reader_eof_total 8420
telemt_me_idle_close_by_peer_total 8420
telemt_me_route_drop_no_conn_total 140327
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379405
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2205
telemt_desync_full_logged_total 850
telemt_desync_suppressed_total 1355
telemt_desync_frames_bucket_total{bucket="1_2"} 809
telemt_desync_frames_bucket_total{bucket="3_10"} 948
telemt_desync_frames_bucket_total{bucket="gt_10"} 448
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 8248
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8020
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 379206
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 6483083536 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 140693866224 (131.03 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```