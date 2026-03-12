# Server Metrics 2026-03-12 00:53:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11321.1 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95058
telemt_connections_bad_total 1338
telemt_handshake_timeouts_total 263
telemt_upstream_connect_attempt_total 2662
telemt_upstream_connect_success_total 2662
telemt_upstream_connect_attempts_per_request{bucket="1"} 2662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2075
telemt_me_reconnect_success_total 2068
telemt_me_reader_eof_total 2173
telemt_me_idle_close_by_peer_total 2173
telemt_me_route_drop_no_conn_total 34791
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90126
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2095
telemt_me_writer_restored_same_endpoint_total 2052
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 90032
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 645280128 (615.39 MB)
telemt_user_octets_to_client{user="hello"} 26968432824 (25.12 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11321.7 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32829
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 390
telemt_upstream_connect_attempt_total 3404
telemt_upstream_connect_success_total 3401
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2632
telemt_me_reconnect_success_total 2610
telemt_me_reader_eof_total 2754
telemt_me_idle_close_by_peer_total 2754
telemt_me_route_drop_no_conn_total 8936
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31039
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2628
telemt_me_writer_restored_same_endpoint_total 2601
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 31218
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 603095091 (575.16 MB)
telemt_user_octets_to_client{user="hello"} 11199290574 (10.43 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 11321.6 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101622
telemt_connections_bad_total 723
telemt_handshake_timeouts_total 8821
telemt_upstream_connect_attempt_total 3733
telemt_upstream_connect_success_total 3731
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 2819
telemt_me_reconnect_success_total 2772
telemt_me_reader_eof_total 2823
telemt_me_idle_close_by_peer_total 2823
telemt_me_route_drop_no_conn_total 17153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54482
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2710
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2731
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 54826
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 574858908 (548.23 MB)
telemt_user_octets_to_client{user="hello"} 22209312269 (20.68 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 11321.9 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51293
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 785
telemt_upstream_connect_attempt_total 3427
telemt_upstream_connect_success_total 3411
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 2821
telemt_me_reconnect_success_total 2811
telemt_me_reader_eof_total 2951
telemt_me_idle_close_by_peer_total 2951
telemt_me_route_drop_no_conn_total 17422
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49672
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 89
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2827
telemt_me_writer_restored_same_endpoint_total 2790
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 49668
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 253489840 (241.75 MB)
telemt_user_octets_to_client{user="hello"} 12437429684 (11.58 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11321.9 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65444
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 540
telemt_upstream_connect_attempt_total 4757
telemt_upstream_connect_success_total 4719
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 4757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 5599
telemt_me_reconnect_success_total 4108
telemt_me_reader_eof_total 4239
telemt_me_idle_close_by_peer_total 4239
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 15852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61565
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 156
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 4176
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4100
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 61547
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 295358500 (281.68 MB)
telemt_user_octets_to_client{user="hello"} 14573992284 (13.57 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 31
```