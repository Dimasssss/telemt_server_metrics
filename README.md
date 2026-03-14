# Server Metrics 2026-03-14 22:06:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 31727.1 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1118827
telemt_connections_bad_total 42924
telemt_handshake_timeouts_total 14963
telemt_upstream_connect_attempt_total 5794
telemt_upstream_connect_success_total 5771
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 4944
telemt_me_reconnect_success_total 4135
telemt_me_reader_eof_total 4370
telemt_me_idle_close_by_peer_total 4370
telemt_me_route_drop_no_conn_total 426294
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 998568
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3285
telemt_desync_full_logged_total 969
telemt_desync_suppressed_total 2316
telemt_desync_frames_bucket_total{bucket="1_2"} 776
telemt_desync_frames_bucket_total{bucket="3_10"} 1242
telemt_desync_frames_bucket_total{bucket="gt_10"} 1267
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4228
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 4126
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 998535
telemt_user_connections_current{user="hello"} 1156
telemt_user_octets_from_client{user="hello"} 21124144672 (19.67 GB)
telemt_user_octets_to_client{user="hello"} 335840371468 (312.78 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 31732.1 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443398
telemt_connections_bad_total 35281
telemt_handshake_timeouts_total 13601
telemt_upstream_connect_attempt_total 6831
telemt_upstream_connect_success_total 6765
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 6831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 492
telemt_me_reconnect_attempts_total 5929
telemt_me_reconnect_success_total 5125
telemt_me_reader_eof_total 5368
telemt_me_idle_close_by_peer_total 5368
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 129116
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370147
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1869
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 1377
telemt_desync_frames_bucket_total{bucket="1_2"} 747
telemt_desync_frames_bucket_total{bucket="3_10"} 660
telemt_desync_frames_bucket_total{bucket="gt_10"} 462
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5255
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 5102
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 370091
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 5892791064 (5.49 GB)
telemt_user_octets_to_client{user="hello"} 129772023928 (120.86 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 31595.2 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 968804
telemt_connections_bad_total 3974
telemt_handshake_timeouts_total 249946
telemt_upstream_connect_attempt_total 6181
telemt_upstream_connect_success_total 6161
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 6181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 8459
telemt_me_reconnect_success_total 4544
telemt_me_reader_eof_total 4866
telemt_me_idle_close_by_peer_total 4866
telemt_me_route_drop_no_conn_total 212394
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614043
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2254
telemt_desync_full_logged_total 861
telemt_desync_suppressed_total 1393
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 782
telemt_desync_frames_bucket_total{bucket="gt_10"} 1123
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4719
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4511
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 613865
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 9752629640 (9.08 GB)
telemt_user_octets_to_client{user="hello"} 227888380232 (212.24 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 31449.6 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508146
telemt_connections_bad_total 103089
telemt_handshake_timeouts_total 56618
telemt_upstream_connect_attempt_total 7169
telemt_upstream_connect_success_total 7168
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 223
telemt_me_reconnect_attempts_total 6519
telemt_me_reconnect_success_total 5594
telemt_me_reader_eof_total 5880
telemt_me_idle_close_by_peer_total 5880
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 119293
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340042
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 743
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 480
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5687
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5581
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 339956
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 4650004604 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 105167892132 (97.95 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 31745.3 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427063
telemt_connections_bad_total 1406
telemt_handshake_timeouts_total 4219
telemt_upstream_connect_attempt_total 6715
telemt_upstream_connect_success_total 6585
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 6715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3352
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 155
telemt_me_reconnect_attempts_total 5647
telemt_me_reconnect_success_total 4968
telemt_me_reader_eof_total 5255
telemt_me_idle_close_by_peer_total 5255
telemt_me_route_drop_no_conn_total 133519
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396691
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1211
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 785
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 447
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5075
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4950
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 396656
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 6645237220 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 165051696096 (153.72 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 40
```