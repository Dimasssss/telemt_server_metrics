# Server Metrics 2026-03-04 03:15:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 21882.8 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139050
telemt_connections_bad_total 1386
telemt_handshake_timeouts_total 2165
telemt_upstream_connect_attempt_total 17101
telemt_upstream_connect_success_total 17028
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 17028
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 4249
telemt_me_reconnect_success_total 4239
telemt_me_reader_eof_total 4340
telemt_me_idle_close_by_peer_total 4340
telemt_me_route_drop_no_conn_total 48507
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 262
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 170
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 4
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 4340
telemt_me_writer_restored_same_endpoint_total 4219
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 132366
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 1181465048 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 39199204396 (36.51 GB)
telemt_user_unique_ips_current{user="hello"} 78
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 21879.3 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65235
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 16822
telemt_upstream_connect_attempt_total 54580
telemt_upstream_connect_success_total 54024
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 54018
telemt_upstream_connect_attempts_per_request{bucket="2"} 267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 890
telemt_me_reconnect_attempts_total 34190
telemt_me_reconnect_success_total 34168
telemt_me_reader_eof_total 35032
telemt_me_idle_close_by_peer_total 35031
telemt_me_route_drop_no_conn_total 21303
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 118
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_me_writer_removed_unexpected_total 35093
telemt_me_writer_restored_same_endpoint_total 34148
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 47365
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 392351404 (374.18 MB)
telemt_user_octets_to_client{user="hello"} 24825080992 (23.12 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 21878.2 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152963
telemt_connections_bad_total 55612
telemt_handshake_timeouts_total 3449
telemt_upstream_connect_attempt_total 28333
telemt_upstream_connect_success_total 28136
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 28136
telemt_upstream_connect_attempts_per_request{bucket="2"} 92
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 360
telemt_me_reconnect_attempts_total 10948
telemt_me_reconnect_success_total 10924
telemt_me_reader_eof_total 11459
telemt_me_idle_close_by_peer_total 11456
telemt_me_route_drop_no_conn_total 29717
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 290
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 11461
telemt_me_writer_restored_same_endpoint_total 10903
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 90446
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 563546564 (537.44 MB)
telemt_user_octets_to_client{user="hello"} 22833278504 (21.27 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 21877.1 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70108
telemt_connections_bad_total 557
telemt_handshake_timeouts_total 658
telemt_upstream_connect_attempt_total 13978
telemt_upstream_connect_success_total 13907
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 13907
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 1927
telemt_me_reconnect_success_total 1931
telemt_me_reader_eof_total 1939
telemt_me_idle_close_by_peer_total 1939
telemt_me_route_drop_no_conn_total 23845
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 59
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 1939
telemt_me_writer_restored_same_endpoint_total 1910
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 67454
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 549642368 (524.18 MB)
telemt_user_octets_to_client{user="hello"} 23274208300 (21.68 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 21875.8 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166168
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 75635
telemt_upstream_connect_attempt_total 32545
telemt_upstream_connect_success_total 32342
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 32342
telemt_upstream_connect_attempts_per_request{bucket="2"} 97
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 16128
telemt_me_reconnect_success_total 16124
telemt_me_reader_eof_total 17095
telemt_me_idle_close_by_peer_total 17094
telemt_me_route_drop_no_conn_total 44597
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 121
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 2523
telemt_me_writer_removed_unexpected_total 17100
telemt_me_writer_restored_same_endpoint_total 16100
telemt_me_writer_removed_unexpected_minus_restored_total 1000
telemt_user_connections_total{user="hello"} 87283
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 512518524 (488.78 MB)
telemt_user_octets_to_client{user="hello"} 20025968484 (18.65 GB)
telemt_user_unique_ips_current{user="hello"} 30
```