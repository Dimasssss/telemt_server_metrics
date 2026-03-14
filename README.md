# Server Metrics 2026-03-14 16:03:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 9925.4 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388097
telemt_connections_bad_total 15227
telemt_handshake_timeouts_total 4530
telemt_upstream_connect_attempt_total 2080
telemt_upstream_connect_success_total 2072
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 2327
telemt_me_reconnect_success_total 1541
telemt_me_reader_eof_total 1595
telemt_me_idle_close_by_peer_total 1595
telemt_me_route_drop_no_conn_total 153025
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352693
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1114
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 781
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 410
telemt_desync_frames_bucket_total{bucket="gt_10"} 459
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1585
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1532
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 352692
telemt_user_connections_current{user="hello"} 1938
telemt_user_octets_from_client{user="hello"} 6086769292 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 108065516096 (100.64 GB)
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 9930.8 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160026
telemt_connections_bad_total 15268
telemt_handshake_timeouts_total 5491
telemt_upstream_connect_attempt_total 2122
telemt_upstream_connect_success_total 2097
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 2122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 2334
telemt_me_reconnect_success_total 1559
telemt_me_reader_eof_total 1615
telemt_me_idle_close_by_peer_total 1615
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 49357
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127635
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 541
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 388
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1625
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1545
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 127574
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 1650151764 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 52787273384 (49.16 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 9793.6 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323773
telemt_connections_bad_total 1284
telemt_handshake_timeouts_total 77798
telemt_upstream_connect_attempt_total 2068
telemt_upstream_connect_success_total 2059
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 5432
telemt_me_reconnect_success_total 1535
telemt_me_reader_eof_total 1666
telemt_me_idle_close_by_peer_total 1666
telemt_me_route_drop_no_conn_total 82763
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222142
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1659
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1502
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 222045
telemt_user_connections_current{user="hello"} 883
telemt_user_octets_from_client{user="hello"} 3240043780 (3.02 GB)
telemt_user_octets_to_client{user="hello"} 86105761596 (80.19 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 9648.0 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170687
telemt_connections_bad_total 34637
telemt_handshake_timeouts_total 29260
telemt_upstream_connect_attempt_total 2406
telemt_upstream_connect_success_total 2405
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1902
telemt_me_reconnect_success_total 1889
telemt_me_reader_eof_total 1936
telemt_me_idle_close_by_peer_total 1936
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 37766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104617
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 217
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1898
telemt_me_writer_restored_same_endpoint_total 1887
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 104583
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 1875008336 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 34674709976 (32.29 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 9943.7 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153935
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 2088
telemt_upstream_connect_attempt_total 2271
telemt_upstream_connect_success_total 2221
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 2271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2350
telemt_me_reconnect_success_total 1687
telemt_me_reader_eof_total 1767
telemt_me_idle_close_by_peer_total 1767
telemt_me_route_drop_no_conn_total 52148
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142449
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 442
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 267
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1749
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1669
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 142452
telemt_user_connections_current{user="hello"} 848
telemt_user_octets_from_client{user="hello"} 2121449320 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 53694161904 (50.01 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 120
```