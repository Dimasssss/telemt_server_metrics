# Server Metrics 2026-03-03 23:50:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 9598.6 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72184
telemt_connections_bad_total 659
telemt_handshake_timeouts_total 221
telemt_upstream_connect_attempt_total 6932
telemt_upstream_connect_success_total 6898
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6898
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 1444
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1469
telemt_me_idle_close_by_peer_total 1469
telemt_me_route_drop_no_conn_total 28685
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1469
telemt_me_writer_restored_same_endpoint_total 1430
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 69871
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 583240028 (556.22 MB)
telemt_user_octets_to_client{user="hello"} 21353103336 (19.89 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 9595.3 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34098
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 7182
telemt_upstream_connect_attempt_total 15095
telemt_upstream_connect_success_total 14890
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 14890
telemt_upstream_connect_attempts_per_request{bucket="2"} 100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 130
telemt_me_reconnect_attempts_total 7332
telemt_me_reconnect_success_total 7339
telemt_me_reader_eof_total 7464
telemt_me_idle_close_by_peer_total 7463
telemt_me_route_drop_no_conn_total 13128
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 7464
telemt_me_writer_restored_same_endpoint_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 26475
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 169703552 (161.84 MB)
telemt_user_octets_to_client{user="hello"} 13902066928 (12.95 GB)
telemt_user_unique_ips_current{user="hello"} 12
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 9594.0 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79699
telemt_connections_bad_total 23536
telemt_handshake_timeouts_total 1789
telemt_upstream_connect_attempt_total 10854
telemt_upstream_connect_success_total 10784
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 10784
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 4025
telemt_me_reconnect_success_total 4029
telemt_me_reader_eof_total 4204
telemt_me_idle_close_by_peer_total 4203
telemt_me_route_drop_no_conn_total 16614
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 171
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4205
telemt_me_writer_restored_same_endpoint_total 4008
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 53177
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 338978540 (323.28 MB)
telemt_user_octets_to_client{user="hello"} 14348291304 (13.36 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 9593.0 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35943
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 5846
telemt_upstream_connect_success_total 5821
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 5821
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 657
telemt_me_reconnect_success_total 670
telemt_me_reader_eof_total 660
telemt_me_idle_close_by_peer_total 660
telemt_me_route_drop_no_conn_total 13363
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_restored_same_endpoint_total 651
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 34815
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 351049820 (334.79 MB)
telemt_user_octets_to_client{user="hello"} 10081234944 (9.39 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 9591.6 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85097
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 34136
telemt_upstream_connect_attempt_total 8870
telemt_upstream_connect_success_total 8769
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 8769
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3013
telemt_me_reconnect_success_total 3025
telemt_me_reader_eof_total 3150
telemt_me_idle_close_by_peer_total 3150
telemt_me_route_drop_no_conn_total 33658
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 43
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 3153
telemt_me_writer_restored_same_endpoint_total 3001
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 49422
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 237961348 (226.94 MB)
telemt_user_octets_to_client{user="hello"} 13538224060 (12.61 GB)
telemt_user_unique_ips_current{user="hello"} 12
```