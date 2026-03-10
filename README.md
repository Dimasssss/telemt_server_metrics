# Server Metrics 2026-03-10 20:21:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 21284.1 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633904
telemt_connections_bad_total 8008
telemt_handshake_timeouts_total 6767
telemt_upstream_connect_attempt_total 4464
telemt_upstream_connect_success_total 4455
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 337
telemt_me_reconnect_attempts_total 14963
telemt_me_reconnect_success_total 3313
telemt_me_reader_eof_total 3700
telemt_me_idle_close_by_peer_total 3700
telemt_me_route_drop_no_conn_total 265607
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598084
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3111
telemt_desync_full_logged_total 841
telemt_desync_suppressed_total 2270
telemt_desync_frames_bucket_total{bucket="1_2"} 871
telemt_desync_frames_bucket_total{bucket="3_10"} 1176
telemt_desync_frames_bucket_total{bucket="gt_10"} 1064
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3696
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3307
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 597908
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 8569743980 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 178207100044 (165.97 GB)
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21340.7 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279796
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 16873
telemt_upstream_connect_attempt_total 10171
telemt_upstream_connect_success_total 7325
telemt_upstream_connect_fail_total 2846
telemt_upstream_connect_attempts_per_request{bucket="1"} 10171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2846
telemt_me_keepalive_timeout_total 735
telemt_me_reconnect_attempts_total 4729
telemt_me_reconnect_success_total 3937
telemt_me_reader_eof_total 4116
telemt_me_idle_close_by_peer_total 4114
telemt_me_route_drop_no_conn_total 154565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234896
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1271
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 925
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4012
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3916
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 236496
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 2424634226 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 56562476282 (52.68 GB)
telemt_user_msgs_from_client{user="hello"} 5762
telemt_user_msgs_to_client{user="hello"} 6647
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 21340.6 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452886
telemt_connections_bad_total 2176
telemt_handshake_timeouts_total 32473
telemt_upstream_connect_attempt_total 6446
telemt_upstream_connect_success_total 6350
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 6446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 11148
telemt_me_reconnect_success_total 4174
telemt_me_reader_eof_total 4514
telemt_me_idle_close_by_peer_total 4514
telemt_me_route_drop_no_conn_total 156327
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392569
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1332
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 962
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 572
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4466
telemt_me_refill_failed_total 216
telemt_me_writer_restored_same_endpoint_total 4163
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 393513
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 5629182961 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 121826933889 (113.46 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 21341.2 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305534
telemt_connections_bad_total 20976
telemt_handshake_timeouts_total 26486
telemt_upstream_connect_attempt_total 5839
telemt_upstream_connect_success_total 5839
telemt_upstream_connect_attempts_per_request{bucket="1"} 5839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 5749
telemt_me_reconnect_success_total 4732
telemt_me_reader_eof_total 4957
telemt_me_idle_close_by_peer_total 4957
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 99336
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246251
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 394
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4811
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4719
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 245951
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 3750679228 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 76474840272 (71.22 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21341.0 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321627
telemt_connections_bad_total 987
telemt_handshake_timeouts_total 2042
telemt_upstream_connect_attempt_total 6787
telemt_upstream_connect_success_total 6760
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 8033
telemt_me_reconnect_success_total 5626
telemt_me_reader_eof_total 5845
telemt_me_idle_close_by_peer_total 5845
telemt_me_route_drop_no_conn_total 117236
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302798
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1738
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1086
telemt_desync_frames_bucket_total{bucket="1_2"} 679
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5783
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 5626
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 302708
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 5927598252 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 100622714952 (93.71 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 68
```