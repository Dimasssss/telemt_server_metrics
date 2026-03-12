# Server Metrics 2026-03-12 21:43:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 56708.3 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1883728
telemt_connections_bad_total 26055
telemt_handshake_timeouts_total 20656
telemt_upstream_connect_attempt_total 11014
telemt_upstream_connect_success_total 10952
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 592
telemt_me_reconnect_attempts_total 16964
telemt_me_reconnect_success_total 8111
telemt_me_reader_eof_total 8772
telemt_me_idle_close_by_peer_total 8771
telemt_me_route_drop_no_conn_total 737198
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1753182
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8440
telemt_desync_full_logged_total 2191
telemt_desync_suppressed_total 6249
telemt_desync_frames_bucket_total{bucket="1_2"} 2218
telemt_desync_frames_bucket_total{bucket="3_10"} 3038
telemt_desync_frames_bucket_total{bucket="gt_10"} 3184
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8505
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8098
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 1752662
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 26670069120 (24.84 GB)
telemt_user_octets_to_client{user="hello"} 619890989104 (577.32 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86328.7 (23h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783626
telemt_connections_bad_total 11689
telemt_handshake_timeouts_total 31064
telemt_upstream_connect_attempt_total 21777
telemt_upstream_connect_success_total 21748
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3399
telemt_me_reconnect_attempts_total 15893
telemt_me_reconnect_success_total 15800
telemt_me_reader_eof_total 16802
telemt_me_idle_close_by_peer_total 16802
telemt_me_route_drop_no_conn_total 253659
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707182
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2980
telemt_desync_full_logged_total 923
telemt_desync_suppressed_total 2057
telemt_desync_frames_bucket_total{bucket="1_2"} 1172
telemt_desync_frames_bucket_total{bucket="3_10"} 981
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 15960
telemt_me_writer_restored_same_endpoint_total 15791
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 709059
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 11990937448 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 271875515535 (253.20 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 86328.6 (23h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1623978
telemt_connections_bad_total 7736
telemt_handshake_timeouts_total 112690
telemt_upstream_connect_attempt_total 20159
telemt_upstream_connect_success_total 20153
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1214
telemt_me_reconnect_attempts_total 16742
telemt_me_reconnect_success_total 15494
telemt_me_reader_eof_total 16364
telemt_me_idle_close_by_peer_total 16363
telemt_me_route_drop_no_conn_total 536120
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1258864
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4949
telemt_desync_full_logged_total 1517
telemt_desync_suppressed_total 3432
telemt_desync_frames_bucket_total{bucket="1_2"} 789
telemt_desync_frames_bucket_total{bucket="3_10"} 1788
telemt_desync_frames_bucket_total{bucket="gt_10"} 2372
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15640
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15453
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1258470
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 19594100544 (18.25 GB)
telemt_user_octets_to_client{user="hello"} 467613861113 (435.50 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 86329.1 (23h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1000707
telemt_connections_bad_total 12985
telemt_handshake_timeouts_total 71106
telemt_upstream_connect_attempt_total 21987
telemt_upstream_connect_success_total 21898
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 21987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 1678
telemt_me_reconnect_attempts_total 25330
telemt_me_reconnect_success_total 17601
telemt_me_reader_eof_total 18796
telemt_me_idle_close_by_peer_total 18796
telemt_me_route_drop_no_conn_total 358200
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 871213
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1843
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1231
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 17983
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17580
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 870562
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 13836717208 (12.89 GB)
telemt_user_octets_to_client{user="hello"} 349902714836 (325.87 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86328.7 (23h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1119878
telemt_connections_bad_total 12521
telemt_handshake_timeouts_total 9067
telemt_upstream_connect_attempt_total 26550
telemt_upstream_connect_success_total 26225
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 26550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 1435
telemt_me_reconnect_attempts_total 32953
telemt_me_reconnect_success_total 21915
telemt_me_reader_eof_total 23036
telemt_me_idle_close_by_peer_total 23036
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 420146
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1029922
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3878
telemt_desync_full_logged_total 1351
telemt_desync_suppressed_total 2527
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 1278
telemt_desync_frames_bucket_total{bucket="gt_10"} 1458
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 22511
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21871
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 1029785
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 12747987476 (11.87 GB)
telemt_user_octets_to_client{user="hello"} 363622931996 (338.65 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 53
```