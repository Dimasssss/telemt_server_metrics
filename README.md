# Server Metrics 2026-03-14 16:08:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 10232.3 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401894
telemt_connections_bad_total 16918
telemt_handshake_timeouts_total 4638
telemt_upstream_connect_attempt_total 2226
telemt_upstream_connect_success_total 2216
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 2426
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1695
telemt_me_idle_close_by_peer_total 1695
telemt_me_route_drop_no_conn_total 158459
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363884
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1162
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 818
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 477
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1686
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1628
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 363884
telemt_user_connections_current{user="hello"} 1878
telemt_user_octets_from_client{user="hello"} 6239728084 (5.81 GB)
telemt_user_octets_to_client{user="hello"} 111432108364 (103.78 GB)
telemt_user_unique_ips_current{user="hello"} 510
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 10237.7 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165579
telemt_connections_bad_total 15965
telemt_handshake_timeouts_total 5601
telemt_upstream_connect_attempt_total 2227
telemt_upstream_connect_success_total 2202
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 2227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 2399
telemt_me_reconnect_success_total 1623
telemt_me_reader_eof_total 1687
telemt_me_idle_close_by_peer_total 1687
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 50882
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132260
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 547
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 389
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1689
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1609
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 132199
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 1717289336 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 54459236256 (50.72 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 10100.6 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334864
telemt_connections_bad_total 1284
telemt_handshake_timeouts_total 79914
telemt_upstream_connect_attempt_total 2150
telemt_upstream_connect_success_total 2142
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 5471
telemt_me_reconnect_success_total 1575
telemt_me_reader_eof_total 1709
telemt_me_idle_close_by_peer_total 1709
telemt_me_route_drop_no_conn_total 85678
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229649
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 427
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1698
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1542
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 229551
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 3437128828 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 88671869964 (82.58 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 9955.0 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176682
telemt_connections_bad_total 35373
telemt_handshake_timeouts_total 30383
telemt_upstream_connect_attempt_total 2460
telemt_upstream_connect_success_total 2459
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 1932
telemt_me_reconnect_success_total 1918
telemt_me_reader_eof_total 1967
telemt_me_idle_close_by_peer_total 1967
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 39077
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108727
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 227
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1929
telemt_me_writer_restored_same_endpoint_total 1916
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 108693
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 1917161984 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 36374757612 (33.88 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 10250.5 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159235
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 2173
telemt_upstream_connect_attempt_total 2362
telemt_upstream_connect_success_total 2310
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 2362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2408
telemt_me_reconnect_success_total 1744
telemt_me_reader_eof_total 1829
telemt_me_idle_close_by_peer_total 1829
telemt_me_route_drop_no_conn_total 54079
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147032
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 450
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1806
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1726
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 147046
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 2221583164 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 55631801492 (51.81 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 123
```