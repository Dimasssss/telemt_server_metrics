# Server Metrics 2026-03-13 06:03:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 86698.8 (24h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2332935
telemt_connections_bad_total 35499
telemt_handshake_timeouts_total 24618
telemt_upstream_connect_attempt_total 17069
telemt_upstream_connect_success_total 16974
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 1318
telemt_me_reconnect_attempts_total 21517
telemt_me_reconnect_success_total 12648
telemt_me_reader_eof_total 13645
telemt_me_idle_close_by_peer_total 13644
telemt_me_route_drop_no_conn_total 885758
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2146157
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9549
telemt_desync_full_logged_total 2465
telemt_desync_suppressed_total 7084
telemt_desync_frames_bucket_total{bucket="1_2"} 2464
telemt_desync_frames_bucket_total{bucket="3_10"} 3500
telemt_desync_frames_bucket_total{bucket="gt_10"} 3585
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13099
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12635
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 2145557
telemt_user_connections_current{user="hello"} 1477
telemt_user_octets_from_client{user="hello"} 30957116752 (28.83 GB)
telemt_user_octets_to_client{user="hello"} 733266007756 (682.91 GB)
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 116319.4 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 943319
telemt_connections_bad_total 12464
telemt_handshake_timeouts_total 40792
telemt_upstream_connect_attempt_total 29374
telemt_upstream_connect_success_total 29343
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3559
telemt_me_reconnect_attempts_total 22021
telemt_me_reconnect_success_total 21903
telemt_me_reader_eof_total 23358
telemt_me_idle_close_by_peer_total 23358
telemt_me_route_drop_no_conn_total 300390
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851522
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3487
telemt_desync_full_logged_total 1094
telemt_desync_suppressed_total 2393
telemt_desync_frames_bucket_total{bucket="1_2"} 1358
telemt_desync_frames_bucket_total{bucket="3_10"} 1129
telemt_desync_frames_bucket_total{bucket="gt_10"} 1000
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22121
telemt_me_writer_restored_same_endpoint_total 21894
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 853427
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 13463084276 (12.54 GB)
telemt_user_octets_to_client{user="hello"} 324011764551 (301.76 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 116319.3 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1951154
telemt_connections_bad_total 22767
telemt_handshake_timeouts_total 129733
telemt_upstream_connect_attempt_total 27026
telemt_upstream_connect_success_total 27016
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12721
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1666
telemt_me_reconnect_attempts_total 22137
telemt_me_reconnect_success_total 20865
telemt_me_reader_eof_total 22105
telemt_me_idle_close_by_peer_total 22104
telemt_me_route_drop_no_conn_total 624873
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1534806
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5336
telemt_desync_full_logged_total 1617
telemt_desync_suppressed_total 3719
telemt_desync_frames_bucket_total{bucket="1_2"} 883
telemt_desync_frames_bucket_total{bucket="3_10"} 1939
telemt_desync_frames_bucket_total{bucket="gt_10"} 2514
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 21065
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20824
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 1534300
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 26350463236 (24.54 GB)
telemt_user_octets_to_client{user="hello"} 545199427485 (507.76 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 116319.6 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188218
telemt_connections_bad_total 13987
telemt_handshake_timeouts_total 77604
telemt_upstream_connect_attempt_total 39663
telemt_upstream_connect_success_total 37375
telemt_upstream_connect_fail_total 2151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39389
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2150
telemt_me_keepalive_timeout_total 11405
telemt_me_reconnect_attempts_total 34644
telemt_me_reconnect_success_total 25709
telemt_me_reader_eof_total 27718
telemt_me_idle_close_by_peer_total 27711
telemt_me_route_drop_no_conn_total 425840
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1023827
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2010
telemt_desync_full_logged_total 658
telemt_desync_suppressed_total 1352
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 677
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 26163
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25685
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 1028766
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 15632449713 (14.56 GB)
telemt_user_octets_to_client{user="hello"} 410965937634 (382.74 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 116319.4 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1339855
telemt_connections_bad_total 16430
telemt_handshake_timeouts_total 11000
telemt_upstream_connect_attempt_total 36831
telemt_upstream_connect_success_total 36384
telemt_upstream_connect_fail_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 36831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 447
telemt_me_keepalive_timeout_total 1991
telemt_me_reconnect_attempts_total 44320
telemt_me_reconnect_success_total 30582
telemt_me_reader_eof_total 32111
telemt_me_idle_close_by_peer_total 32111
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 493696
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1237808
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 46
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4453
telemt_desync_full_logged_total 1604
telemt_desync_suppressed_total 2849
telemt_desync_frames_bucket_total{bucket="1_2"} 1356
telemt_desync_frames_bucket_total{bucket="3_10"} 1445
telemt_desync_frames_bucket_total{bucket="gt_10"} 1652
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 31350
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30528
telemt_me_writer_restored_fallback_total 54
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 768
telemt_user_connections_total{user="hello"} 1237650
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 14917683624 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 420309641428 (391.44 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 104
```