# Server Metrics 2026-03-04 03:20:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 22190.1 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141470
telemt_connections_bad_total 1533
telemt_handshake_timeouts_total 2347
telemt_upstream_connect_attempt_total 17232
telemt_upstream_connect_success_total 17159
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 17159
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 4249
telemt_me_reconnect_success_total 4239
telemt_me_reader_eof_total 4340
telemt_me_idle_close_by_peer_total 4340
telemt_me_route_drop_no_conn_total 49280
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 266
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 4
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 4340
telemt_me_writer_restored_same_endpoint_total 4219
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 134445
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 1240794432 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 39959040632 (37.21 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 22186.7 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66370
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 17034
telemt_upstream_connect_attempt_total 55666
telemt_upstream_connect_success_total 55104
telemt_upstream_connect_fail_total 265
telemt_upstream_connect_attempts_per_request{bucket="1"} 55098
telemt_upstream_connect_attempts_per_request{bucket="2"} 271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 265
telemt_me_keepalive_timeout_total 900
telemt_me_reconnect_attempts_total 34963
telemt_me_reconnect_success_total 34938
telemt_me_reader_eof_total 35852
telemt_me_idle_close_by_peer_total 35851
telemt_me_route_drop_no_conn_total 21673
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 133
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_me_writer_removed_unexpected_total 35913
telemt_me_writer_restored_same_endpoint_total 34918
telemt_me_writer_removed_unexpected_minus_restored_total 995
telemt_user_connections_total{user="hello"} 48274
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 401199600 (382.61 MB)
telemt_user_octets_to_client{user="hello"} 25053310776 (23.33 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 22185.5 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154899
telemt_connections_bad_total 56423
telemt_handshake_timeouts_total 3512
telemt_upstream_connect_attempt_total 29166
telemt_upstream_connect_success_total 28962
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 28962
telemt_upstream_connect_attempts_per_request{bucket="2"} 96
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 366
telemt_me_reconnect_attempts_total 11486
telemt_me_reconnect_success_total 11462
telemt_me_reader_eof_total 12046
telemt_me_idle_close_by_peer_total 12043
telemt_me_route_drop_no_conn_total 30043
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
telemt_me_writer_removed_unexpected_total 12048
telemt_me_writer_restored_same_endpoint_total 11441
telemt_me_writer_removed_unexpected_minus_restored_total 607
telemt_user_connections_total{user="hello"} 91489
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 572909096 (546.37 MB)
telemt_user_octets_to_client{user="hello"} 23477999176 (21.87 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 22184.4 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72178
telemt_connections_bad_total 827
telemt_handshake_timeouts_total 663
telemt_upstream_connect_attempt_total 14148
telemt_upstream_connect_success_total 14077
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 14077
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 1939
telemt_me_reconnect_success_total 1943
telemt_me_reader_eof_total 1951
telemt_me_idle_close_by_peer_total 1951
telemt_me_route_drop_no_conn_total 24386
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 68
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 1951
telemt_me_writer_restored_same_endpoint_total 1922
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 68594
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 614654416 (586.18 MB)
telemt_user_octets_to_client{user="hello"} 23921742716 (22.28 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 22183.0 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168568
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 76826
telemt_upstream_connect_attempt_total 33213
telemt_upstream_connect_success_total 33009
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 33009
telemt_upstream_connect_attempts_per_request{bucket="2"} 97
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 16519
telemt_me_reconnect_success_total 16513
telemt_me_reader_eof_total 17499
telemt_me_idle_close_by_peer_total 17498
telemt_me_route_drop_no_conn_total 44912
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 122
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_pool_stale_pick_total 2568
telemt_me_writer_removed_unexpected_total 17504
telemt_me_writer_restored_same_endpoint_total 16489
telemt_me_writer_removed_unexpected_minus_restored_total 1015
telemt_user_connections_total{user="hello"} 88442
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 516163728 (492.25 MB)
telemt_user_octets_to_client{user="hello"} 20158536572 (18.77 GB)
telemt_user_unique_ips_current{user="hello"} 26
```