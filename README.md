# Server Metrics 2026-03-04 02:19:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 18504.5 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119511
telemt_connections_bad_total 1378
telemt_handshake_timeouts_total 1003
telemt_upstream_connect_attempt_total 15143
telemt_upstream_connect_success_total 15082
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 15082
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 4043
telemt_me_reconnect_success_total 4037
telemt_me_reader_eof_total 4129
telemt_me_idle_close_by_peer_total 4129
telemt_me_route_drop_no_conn_total 42983
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 191
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4129
telemt_me_writer_restored_same_endpoint_total 4017
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 114450
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 921702160 (879.00 MB)
telemt_user_octets_to_client{user="hello"} 34163086748 (31.82 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 18501.3 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56133
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 14395
telemt_upstream_connect_attempt_total 42442
telemt_upstream_connect_success_total 41972
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 41966
telemt_upstream_connect_attempts_per_request{bucket="2"} 224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 782
telemt_me_reconnect_attempts_total 25651
telemt_me_reconnect_success_total 25633
telemt_me_reader_eof_total 26308
telemt_me_idle_close_by_peer_total 26307
telemt_me_route_drop_no_conn_total 19004
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 80
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 26369
telemt_me_writer_restored_same_endpoint_total 25613
telemt_me_writer_removed_unexpected_minus_restored_total 756
telemt_user_connections_total{user="hello"} 40786
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 322968356 (308.01 MB)
telemt_user_octets_to_client{user="hello"} 23025492048 (21.44 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 18499.9 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132075
telemt_connections_bad_total 46850
telemt_handshake_timeouts_total 3166
telemt_upstream_connect_attempt_total 21188
telemt_upstream_connect_success_total 21047
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 21047
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 7078
telemt_me_reconnect_success_total 7064
telemt_me_reader_eof_total 7361
telemt_me_idle_close_by_peer_total 7359
telemt_me_route_drop_no_conn_total 25118
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 264
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 7362
telemt_me_writer_restored_same_endpoint_total 7043
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 78831
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 483791904 (461.38 MB)
telemt_user_octets_to_client{user="hello"} 19568798936 (18.22 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 18498.8 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58987
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 599
telemt_upstream_connect_attempt_total 11412
telemt_upstream_connect_success_total 11359
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11359
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 1554
telemt_me_reconnect_success_total 1561
telemt_me_reader_eof_total 1566
telemt_me_idle_close_by_peer_total 1566
telemt_me_route_drop_no_conn_total 20073
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 20
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1566
telemt_me_writer_restored_same_endpoint_total 1541
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 57138
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 465374332 (443.82 MB)
telemt_user_octets_to_client{user="hello"} 18420287852 (17.16 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 18497.5 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141979
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 63387
telemt_upstream_connect_attempt_total 27058
telemt_upstream_connect_success_total 26888
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 26888
telemt_upstream_connect_attempts_per_request{bucket="2"} 81
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 359
telemt_me_reconnect_attempts_total 13837
telemt_me_reconnect_success_total 13836
telemt_me_reader_eof_total 14712
telemt_me_idle_close_by_peer_total 14711
telemt_me_route_drop_no_conn_total 40807
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 106
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1897
telemt_me_writer_removed_unexpected_total 14717
telemt_me_writer_restored_same_endpoint_total 13812
telemt_me_writer_removed_unexpected_minus_restored_total 905
telemt_user_connections_total{user="hello"} 75866
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 382905836 (365.17 MB)
telemt_user_octets_to_client{user="hello"} 17012056804 (15.84 GB)
telemt_user_unique_ips_current{user="hello"} 25
```