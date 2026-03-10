# Server Metrics 2026-03-10 17:28:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 10871.7 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363305
telemt_connections_bad_total 2536
telemt_handshake_timeouts_total 1712
telemt_upstream_connect_attempt_total 2044
telemt_upstream_connect_success_total 2036
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 233
telemt_me_reconnect_attempts_total 9585
telemt_me_reconnect_success_total 1443
telemt_me_reader_eof_total 1657
telemt_me_idle_close_by_peer_total 1657
telemt_me_route_drop_no_conn_total 157703
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348425
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 1184
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 617
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1694
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 1437
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 348357
telemt_user_connections_current{user="hello"} 1279
telemt_user_octets_from_client{user="hello"} 4577214948 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 102739658152 (95.68 GB)
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10928.4 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144872
telemt_connections_bad_total 1691
telemt_handshake_timeouts_total 9622
telemt_upstream_connect_attempt_total 2499
telemt_upstream_connect_success_total 2486
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 1893
telemt_me_reconnect_success_total 1881
telemt_me_reader_eof_total 1946
telemt_me_idle_close_by_peer_total 1946
telemt_me_route_drop_no_conn_total 41306
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125982
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 589
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1892
telemt_me_writer_restored_same_endpoint_total 1860
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 125961
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 1612029548 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 33637462912 (31.33 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 10928.1 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277867
telemt_connections_bad_total 795
telemt_handshake_timeouts_total 30708
telemt_upstream_connect_attempt_total 3771
telemt_upstream_connect_success_total 3705
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2157
telemt_me_reconnect_success_total 2052
telemt_me_reader_eof_total 2118
telemt_me_idle_close_by_peer_total 2118
telemt_me_route_drop_no_conn_total 88584
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223784
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 688
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2086
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2041
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 224759
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 3118721469 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 65452389989 (60.96 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 10928.6 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175197
telemt_connections_bad_total 10719
telemt_handshake_timeouts_total 17460
telemt_upstream_connect_attempt_total 2712
telemt_upstream_connect_success_total 2712
telemt_upstream_connect_attempts_per_request{bucket="1"} 2712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1250
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 2118
telemt_me_reconnect_success_total 2104
telemt_me_reader_eof_total 2185
telemt_me_idle_close_by_peer_total 2185
telemt_me_route_drop_no_conn_total 56635
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139421
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 442
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2121
telemt_me_writer_restored_same_endpoint_total 2093
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 139258
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 2316043616 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 38891357004 (36.22 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10928.3 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188012
telemt_connections_bad_total 795
telemt_handshake_timeouts_total 1498
telemt_upstream_connect_attempt_total 3381
telemt_upstream_connect_success_total 3371
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 2765
telemt_me_reconnect_success_total 2748
telemt_me_reader_eof_total 2813
telemt_me_idle_close_by_peer_total 2813
telemt_me_route_drop_no_conn_total 69116
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176307
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 930
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 607
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 402
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2771
telemt_me_writer_restored_same_endpoint_total 2748
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 176244
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 4010690228 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 52914806496 (49.28 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 96
```