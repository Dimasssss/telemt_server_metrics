# Server Metrics 2026-03-14 19:58:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 24060.3 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937596
telemt_connections_bad_total 40388
telemt_handshake_timeouts_total 14114
telemt_upstream_connect_attempt_total 4418
telemt_upstream_connect_success_total 4400
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 3960
telemt_me_reconnect_success_total 3155
telemt_me_reader_eof_total 3323
telemt_me_idle_close_by_peer_total 3323
telemt_me_route_drop_no_conn_total 359773
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830631
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2867
telemt_desync_full_logged_total 814
telemt_desync_suppressed_total 2053
telemt_desync_frames_bucket_total{bucket="1_2"} 682
telemt_desync_frames_bucket_total{bucket="3_10"} 1052
telemt_desync_frames_bucket_total{bucket="gt_10"} 1133
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3235
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3146
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 830580
telemt_user_connections_current{user="hello"} 1503
telemt_user_octets_from_client{user="hello"} 14869848424 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 274175738932 (255.35 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 24065.6 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364146
telemt_connections_bad_total 25719
telemt_handshake_timeouts_total 10800
telemt_upstream_connect_attempt_total 5119
telemt_upstream_connect_success_total 5065
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 5119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 443
telemt_me_reconnect_attempts_total 4617
telemt_me_reconnect_success_total 3824
telemt_me_reader_eof_total 3998
telemt_me_idle_close_by_peer_total 3998
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 111347
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307236
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1468
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 1072
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 505
telemt_desync_frames_bucket_total{bucket="gt_10"} 346
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3933
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3802
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 307169
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 4611087644 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 107147049884 (99.79 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 23928.4 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 775482
telemt_connections_bad_total 3187
telemt_handshake_timeouts_total 167473
telemt_upstream_connect_attempt_total 4623
telemt_upstream_connect_success_total 4607
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 7286
telemt_me_reconnect_success_total 3377
telemt_me_reader_eof_total 3625
telemt_me_idle_close_by_peer_total 3625
telemt_me_route_drop_no_conn_total 183883
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516761
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1859
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1132
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3535
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3344
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 516592
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 7591275800 (7.07 GB)
telemt_user_octets_to_client{user="hello"} 184872342640 (172.18 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 23782.9 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424991
telemt_connections_bad_total 94651
telemt_handshake_timeouts_total 50717
telemt_upstream_connect_attempt_total 5575
telemt_upstream_connect_success_total 5574
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 192
telemt_me_reconnect_attempts_total 5270
telemt_me_reconnect_success_total 4350
telemt_me_reader_eof_total 4554
telemt_me_idle_close_by_peer_total 4554
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 97377
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 598
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 388
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4428
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4339
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 272495
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 3863230084 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 85715605856 (79.83 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 24078.6 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358574
telemt_connections_bad_total 1328
telemt_handshake_timeouts_total 3806
telemt_upstream_connect_attempt_total 5146
telemt_upstream_connect_success_total 5040
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 5146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 4488
telemt_me_reconnect_success_total 3815
telemt_me_reader_eof_total 4006
telemt_me_idle_close_by_peer_total 4006
telemt_me_route_drop_no_conn_total 113664
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332116
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 816
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 520
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3905
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3797
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 332088
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 5443066904 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 141625660904 (131.90 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 86
```