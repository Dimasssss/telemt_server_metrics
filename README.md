# Server Metrics 2026-03-12 22:45:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 60387.4 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1928074
telemt_connections_bad_total 26064
telemt_handshake_timeouts_total 21095
telemt_upstream_connect_attempt_total 11902
telemt_upstream_connect_success_total 11834
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 603
telemt_me_reconnect_attempts_total 17639
telemt_me_reconnect_success_total 8783
telemt_me_reader_eof_total 9486
telemt_me_idle_close_by_peer_total 9485
telemt_me_route_drop_no_conn_total 753318
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1793704
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8514
telemt_desync_full_logged_total 2219
telemt_desync_suppressed_total 6295
telemt_desync_frames_bucket_total{bucket="1_2"} 2240
telemt_desync_frames_bucket_total{bucket="3_10"} 3062
telemt_desync_frames_bucket_total{bucket="gt_10"} 3212
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9184
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8770
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 1793176
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 27023314508 (25.17 GB)
telemt_user_octets_to_client{user="hello"} 639792844492 (595.85 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90007.8 (25h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798406
telemt_connections_bad_total 11706
telemt_handshake_timeouts_total 31350
telemt_upstream_connect_attempt_total 22736
telemt_upstream_connect_success_total 22707
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3413
telemt_me_reconnect_attempts_total 16678
telemt_me_reconnect_success_total 16583
telemt_me_reader_eof_total 17644
telemt_me_idle_close_by_peer_total 17644
telemt_me_route_drop_no_conn_total 258156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 721380
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 2068
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16750
telemt_me_writer_restored_same_endpoint_total 16574
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 723260
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 12078387504 (11.25 GB)
telemt_user_octets_to_client{user="hello"} 279311977803 (260.13 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 90007.5 (25h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1662130
telemt_connections_bad_total 8032
telemt_handshake_timeouts_total 113296
telemt_upstream_connect_attempt_total 20914
telemt_upstream_connect_success_total 20908
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1222
telemt_me_reconnect_attempts_total 17325
telemt_me_reconnect_success_total 16075
telemt_me_reader_eof_total 16990
telemt_me_idle_close_by_peer_total 16989
telemt_me_route_drop_no_conn_total 546161
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1295403
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4968
telemt_desync_full_logged_total 1524
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 16229
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16034
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 1295009
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 19745062644 (18.39 GB)
telemt_user_octets_to_client{user="hello"} 478982643593 (446.09 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 90008.0 (25h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1023468
telemt_connections_bad_total 13004
telemt_handshake_timeouts_total 71459
telemt_upstream_connect_attempt_total 23023
telemt_upstream_connect_success_total 22930
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 23023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1694
telemt_me_reconnect_attempts_total 26190
telemt_me_reconnect_success_total 18458
telemt_me_reader_eof_total 19715
telemt_me_idle_close_by_peer_total 19715
telemt_me_route_drop_no_conn_total 366238
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892224
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1862
telemt_desync_full_logged_total 614
telemt_desync_suppressed_total 1248
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 728
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 18845
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18437
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 891570
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 14226264024 (13.25 GB)
telemt_user_octets_to_client{user="hello"} 355251843516 (330.85 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90007.9 (25h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1144984
telemt_connections_bad_total 12537
telemt_handshake_timeouts_total 9210
telemt_upstream_connect_attempt_total 27508
telemt_upstream_connect_success_total 27166
telemt_upstream_connect_fail_total 342
telemt_upstream_connect_attempts_per_request{bucket="1"} 27508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 342
telemt_me_keepalive_timeout_total 1448
telemt_me_reconnect_attempts_total 33722
telemt_me_reconnect_success_total 22682
telemt_me_reader_eof_total 23849
telemt_me_idle_close_by_peer_total 23849
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 427898
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1054523
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3965
telemt_desync_full_logged_total 1380
telemt_desync_suppressed_total 2585
telemt_desync_frames_bucket_total{bucket="1_2"} 1159
telemt_desync_frames_bucket_total{bucket="3_10"} 1310
telemt_desync_frames_bucket_total{bucket="gt_10"} 1496
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 23290
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22638
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 608
telemt_user_connections_total{user="hello"} 1054382
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 13452622912 (12.53 GB)
telemt_user_octets_to_client{user="hello"} 373904150552 (348.23 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 45
```