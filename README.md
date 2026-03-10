# Server Metrics 2026-03-10 17:23:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 10566.2 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354533
telemt_connections_bad_total 1960
telemt_handshake_timeouts_total 1646
telemt_upstream_connect_attempt_total 1971
telemt_upstream_connect_success_total 1963
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 166
telemt_me_reconnect_attempts_total 9527
telemt_me_reconnect_success_total 1385
telemt_me_reader_eof_total 1601
telemt_me_idle_close_by_peer_total 1601
telemt_me_route_drop_no_conn_total 154214
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340437
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1571
telemt_desync_full_logged_total 436
telemt_desync_suppressed_total 1135
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1636
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 1379
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 340369
telemt_user_connections_current{user="hello"} 1214
telemt_user_octets_from_client{user="hello"} 4453065020 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 99887605164 (93.03 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10623.0 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141684
telemt_connections_bad_total 1684
telemt_handshake_timeouts_total 9444
telemt_upstream_connect_attempt_total 2424
telemt_upstream_connect_success_total 2413
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 1863
telemt_me_reconnect_success_total 1852
telemt_me_reader_eof_total 1916
telemt_me_idle_close_by_peer_total 1916
telemt_me_route_drop_no_conn_total 40385
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123145
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 580
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 413
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1862
telemt_me_writer_restored_same_endpoint_total 1831
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 123124
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 1590002272 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 32922338044 (30.66 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 10622.9 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272346
telemt_connections_bad_total 794
telemt_handshake_timeouts_total 30597
telemt_upstream_connect_attempt_total 3633
telemt_upstream_connect_success_total 3574
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 3633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 2002
telemt_me_reconnect_success_total 1961
telemt_me_reader_eof_total 2024
telemt_me_idle_close_by_peer_total 2024
telemt_me_route_drop_no_conn_total 86599
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218445
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 678
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1992
telemt_me_writer_restored_same_endpoint_total 1950
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 219421
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 3094474345 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 63673912585 (59.30 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 10623.3 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170496
telemt_connections_bad_total 10445
telemt_handshake_timeouts_total 16878
telemt_upstream_connect_attempt_total 2627
telemt_upstream_connect_success_total 2627
telemt_upstream_connect_attempts_per_request{bucket="1"} 2627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1213
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 2076
telemt_me_reconnect_success_total 2063
telemt_me_reader_eof_total 2142
telemt_me_idle_close_by_peer_total 2142
telemt_me_route_drop_no_conn_total 55478
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135716
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 437
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2078
telemt_me_writer_restored_same_endpoint_total 2052
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 135562
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 2265558844 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 37148081556 (34.60 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10622.9 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183454
telemt_connections_bad_total 795
telemt_handshake_timeouts_total 1422
telemt_upstream_connect_attempt_total 3279
telemt_upstream_connect_success_total 3269
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 2706
telemt_me_reconnect_success_total 2689
telemt_me_reader_eof_total 2748
telemt_me_idle_close_by_peer_total 2748
telemt_me_route_drop_no_conn_total 67750
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171966
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 889
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 577
telemt_desync_frames_bucket_total{bucket="1_2"} 358
telemt_desync_frames_bucket_total{bucket="3_10"} 385
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2711
telemt_me_writer_restored_same_endpoint_total 2689
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 171903
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 3988837492 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 52048728564 (48.47 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 91
```