# Server Metrics 2026-03-13 03:25:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 77208.7 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2135747
telemt_connections_bad_total 28003
telemt_handshake_timeouts_total 22860
telemt_upstream_connect_attempt_total 15285
telemt_upstream_connect_success_total 15201
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 15285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1295
telemt_me_reconnect_attempts_total 20220
telemt_me_reconnect_success_total 11358
telemt_me_reader_eof_total 12267
telemt_me_idle_close_by_peer_total 12266
telemt_me_route_drop_no_conn_total 819238
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1964748
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8770
telemt_desync_full_logged_total 2281
telemt_desync_suppressed_total 6489
telemt_desync_frames_bucket_total{bucket="1_2"} 2310
telemt_desync_frames_bucket_total{bucket="3_10"} 3164
telemt_desync_frames_bucket_total{bucket="gt_10"} 3296
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11794
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11345
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 1964197
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 28581186396 (26.62 GB)
telemt_user_octets_to_client{user="hello"} 678733893996 (632.12 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 106829.0 (29h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 870000
telemt_connections_bad_total 11845
telemt_handshake_timeouts_total 36947
telemt_upstream_connect_attempt_total 27244
telemt_upstream_connect_success_total 27215
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3462
telemt_me_reconnect_attempts_total 20366
telemt_me_reconnect_success_total 20255
telemt_me_reader_eof_total 21585
telemt_me_idle_close_by_peer_total 21585
telemt_me_route_drop_no_conn_total 279088
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 785553
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3115
telemt_desync_full_logged_total 979
telemt_desync_suppressed_total 2136
telemt_desync_frames_bucket_total{bucket="1_2"} 1264
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 20452
telemt_me_writer_restored_same_endpoint_total 20246
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 787457
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 12566392580 (11.70 GB)
telemt_user_octets_to_client{user="hello"} 302030102795 (281.29 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 106829.0 (29h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1800763
telemt_connections_bad_total 11138
telemt_handshake_timeouts_total 119932
telemt_upstream_connect_attempt_total 24926
telemt_upstream_connect_success_total 24916
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1621
telemt_me_reconnect_attempts_total 20514
telemt_me_reconnect_success_total 19249
telemt_me_reader_eof_total 20391
telemt_me_idle_close_by_peer_total 20390
telemt_me_route_drop_no_conn_total 584806
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1419487
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5056
telemt_desync_full_logged_total 1545
telemt_desync_suppressed_total 3511
telemt_desync_frames_bucket_total{bucket="1_2"} 808
telemt_desync_frames_bucket_total{bucket="3_10"} 1827
telemt_desync_frames_bucket_total{bucket="gt_10"} 2421
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 19429
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19208
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 1419081
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 24723807660 (23.03 GB)
telemt_user_octets_to_client{user="hello"} 509074875693 (474.11 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 106829.3 (29h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1121780
telemt_connections_bad_total 13146
telemt_handshake_timeouts_total 74100
telemt_upstream_connect_attempt_total 37181
telemt_upstream_connect_success_total 34901
telemt_upstream_connect_fail_total 2143
telemt_upstream_connect_attempts_per_request{bucket="1"} 36907
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2142
telemt_me_keepalive_timeout_total 11375
telemt_me_reconnect_attempts_total 32647
telemt_me_reconnect_success_total 23720
telemt_me_reader_eof_total 25608
telemt_me_idle_close_by_peer_total 25601
telemt_me_route_drop_no_conn_total 398102
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 962738
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24153
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23696
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 967908
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 14763539597 (13.75 GB)
telemt_user_octets_to_client{user="hello"} 381311074970 (355.12 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 106829.1 (29h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1242399
telemt_connections_bad_total 12861
telemt_handshake_timeouts_total 9665
telemt_upstream_connect_attempt_total 33596
telemt_upstream_connect_success_total 33187
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 33596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_keepalive_timeout_total 1904
telemt_me_reconnect_attempts_total 41604
telemt_me_reconnect_success_total 27874
telemt_me_reader_eof_total 29334
telemt_me_idle_close_by_peer_total 29334
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 463210
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1148964
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4257
telemt_desync_full_logged_total 1519
telemt_desync_suppressed_total 2738
telemt_desync_frames_bucket_total{bucket="1_2"} 1286
telemt_desync_frames_bucket_total{bucket="3_10"} 1398
telemt_desync_frames_bucket_total{bucket="gt_10"} 1573
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 28622
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27825
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 748
telemt_user_connections_total{user="hello"} 1148819
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 14182186976 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 396421448584 (369.20 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 54
```