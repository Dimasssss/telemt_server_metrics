# Server Metrics 2026-03-12 20:01:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 50583.8 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1761459
telemt_connections_bad_total 20649
telemt_handshake_timeouts_total 18587
telemt_upstream_connect_attempt_total 9905
telemt_upstream_connect_success_total 9848
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 9905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 576
telemt_me_reconnect_attempts_total 16118
telemt_me_reconnect_success_total 7270
telemt_me_reader_eof_total 7871
telemt_me_idle_close_by_peer_total 7870
telemt_me_route_drop_no_conn_total 693921
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1644807
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8142
telemt_desync_full_logged_total 2095
telemt_desync_suppressed_total 6047
telemt_desync_frames_bucket_total{bucket="1_2"} 2129
telemt_desync_frames_bucket_total{bucket="3_10"} 2934
telemt_desync_frames_bucket_total{bucket="gt_10"} 3079
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7652
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7257
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 1644295
telemt_user_connections_current{user="hello"} 1199
telemt_user_octets_from_client{user="hello"} 25470723512 (23.72 GB)
telemt_user_octets_to_client{user="hello"} 566644127576 (527.73 GB)
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 80204.4 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746064
telemt_connections_bad_total 10428
telemt_handshake_timeouts_total 30115
telemt_upstream_connect_attempt_total 20330
telemt_upstream_connect_success_total 20301
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3377
telemt_me_reconnect_attempts_total 14705
telemt_me_reconnect_success_total 14617
telemt_me_reader_eof_total 15543
telemt_me_idle_close_by_peer_total 15543
telemt_me_route_drop_no_conn_total 239441
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672795
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2916
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 2023
telemt_desync_frames_bucket_total{bucket="1_2"} 1128
telemt_desync_frames_bucket_total{bucket="3_10"} 967
telemt_desync_frames_bucket_total{bucket="gt_10"} 821
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 14769
telemt_me_writer_restored_same_endpoint_total 14608
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 674674
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 11465975436 (10.68 GB)
telemt_user_octets_to_client{user="hello"} 254411530083 (236.94 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 80204.3 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1541912
telemt_connections_bad_total 7278
telemt_handshake_timeouts_total 105148
telemt_upstream_connect_attempt_total 18880
telemt_upstream_connect_success_total 18874
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 18880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1191
telemt_me_reconnect_attempts_total 15722
telemt_me_reconnect_success_total 14475
telemt_me_reader_eof_total 15271
telemt_me_idle_close_by_peer_total 15270
telemt_me_route_drop_no_conn_total 509693
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1186192
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
telemt_me_writer_removed_unexpected_total 14609
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14434
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 1185802
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 18496108652 (17.23 GB)
telemt_user_octets_to_client{user="hello"} 441437145861 (411.12 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 80205.0 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 945532
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 70364
telemt_upstream_connect_attempt_total 20526
telemt_upstream_connect_success_total 20445
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1660
telemt_me_reconnect_attempts_total 24139
telemt_me_reconnect_success_total 16414
telemt_me_reader_eof_total 17534
telemt_me_idle_close_by_peer_total 17534
telemt_me_route_drop_no_conn_total 336254
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 819018
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
telemt_me_writer_removed_unexpected_total 16789
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16393
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 818372
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 12794508520 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 334565474036 (311.59 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 80204.6 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1063369
telemt_connections_bad_total 12339
telemt_handshake_timeouts_total 8787
telemt_upstream_connect_attempt_total 24892
telemt_upstream_connect_success_total 24584
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 24891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 1405
telemt_me_reconnect_attempts_total 31583
telemt_me_reconnect_success_total 20546
telemt_me_reader_eof_total 21580
telemt_me_idle_close_by_peer_total 21580
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 397988
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 975423
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3647
telemt_desync_full_logged_total 1273
telemt_desync_suppressed_total 2374
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1213
telemt_desync_frames_bucket_total{bucket="gt_10"} 1405
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 21126
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20502
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 975293
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 12109540776 (11.28 GB)
telemt_user_octets_to_client{user="hello"} 337518734764 (314.34 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 70
```