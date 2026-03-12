# Server Metrics 2026-03-12 20:11:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 51197.0 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1776045
telemt_connections_bad_total 20721
telemt_handshake_timeouts_total 19035
telemt_upstream_connect_attempt_total 9964
telemt_upstream_connect_success_total 9907
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 9964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 579
telemt_me_reconnect_attempts_total 16177
telemt_me_reconnect_success_total 7329
telemt_me_reader_eof_total 7934
telemt_me_idle_close_by_peer_total 7933
telemt_me_route_drop_no_conn_total 700108
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1658037
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8184
telemt_desync_full_logged_total 2108
telemt_desync_suppressed_total 6076
telemt_desync_frames_bucket_total{bucket="1_2"} 2144
telemt_desync_frames_bucket_total{bucket="3_10"} 2951
telemt_desync_frames_bucket_total{bucket="gt_10"} 3089
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7712
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7316
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 1657523
telemt_user_connections_current{user="hello"} 1199
telemt_user_octets_from_client{user="hello"} 25591981704 (23.83 GB)
telemt_user_octets_to_client{user="hello"} 571790272520 (532.52 GB)
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 80817.6 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 750770
telemt_connections_bad_total 10611
telemt_handshake_timeouts_total 30205
telemt_upstream_connect_attempt_total 20465
telemt_upstream_connect_success_total 20436
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3380
telemt_me_reconnect_attempts_total 14840
telemt_me_reconnect_success_total 14751
telemt_me_reader_eof_total 15681
telemt_me_idle_close_by_peer_total 15681
telemt_me_route_drop_no_conn_total 241031
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 677129
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2929
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 2033
telemt_desync_frames_bucket_total{bucket="1_2"} 1130
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 14903
telemt_me_writer_restored_same_endpoint_total 14742
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 679008
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 11536187620 (10.74 GB)
telemt_user_octets_to_client{user="hello"} 256695614903 (239.07 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 80817.4 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1550967
telemt_connections_bad_total 7446
telemt_handshake_timeouts_total 105958
telemt_upstream_connect_attempt_total 19002
telemt_upstream_connect_success_total 18996
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1202
telemt_me_reconnect_attempts_total 15844
telemt_me_reconnect_success_total 14597
telemt_me_reader_eof_total 15402
telemt_me_idle_close_by_peer_total 15401
telemt_me_route_drop_no_conn_total 512865
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1194082
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4791
telemt_desync_full_logged_total 1478
telemt_desync_suppressed_total 3313
telemt_desync_frames_bucket_total{bucket="1_2"} 759
telemt_desync_frames_bucket_total{bucket="3_10"} 1736
telemt_desync_frames_bucket_total{bucket="gt_10"} 2296
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 14732
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14556
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 1193691
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 18604059840 (17.33 GB)
telemt_user_octets_to_client{user="hello"} 444770005445 (414.22 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 80818.0 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 951910
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 70465
telemt_upstream_connect_attempt_total 20650
telemt_upstream_connect_success_total 20569
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1666
telemt_me_reconnect_attempts_total 24261
telemt_me_reconnect_success_total 16535
telemt_me_reader_eof_total 17662
telemt_me_idle_close_by_peer_total 17662
telemt_me_route_drop_no_conn_total 338785
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 824997
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1749
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 491
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16910
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16514
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 824347
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 12855448156 (11.97 GB)
telemt_user_octets_to_client{user="hello"} 338820948496 (315.55 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 80817.6 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1070172
telemt_connections_bad_total 12365
telemt_handshake_timeouts_total 8821
telemt_upstream_connect_attempt_total 25190
telemt_upstream_connect_success_total 24882
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 25190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 1418
telemt_me_reconnect_attempts_total 31868
telemt_me_reconnect_success_total 20830
telemt_me_reader_eof_total 21868
telemt_me_idle_close_by_peer_total 21868
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 400530
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 981880
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3683
telemt_desync_full_logged_total 1287
telemt_desync_suppressed_total 2396
telemt_desync_frames_bucket_total{bucket="1_2"} 1048
telemt_desync_frames_bucket_total{bucket="3_10"} 1221
telemt_desync_frames_bucket_total{bucket="gt_10"} 1414
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 21413
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20786
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 981749
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 12225731528 (11.39 GB)
telemt_user_octets_to_client{user="hello"} 341129036232 (317.70 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 70
```