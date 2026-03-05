# Server Metrics 2026-03-05 23:36:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 4483.2 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36761
telemt_connections_bad_total 11650
telemt_handshake_timeouts_total 333
telemt_upstream_connect_attempt_total 3170
telemt_upstream_connect_success_total 3139
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3139
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 703
telemt_me_reconnect_success_total 701
telemt_me_reader_eof_total 714
telemt_me_idle_close_by_peer_total 714
telemt_me_route_drop_no_conn_total 6414
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 73
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 714
telemt_me_writer_restored_same_endpoint_total 697
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 24043
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 409347424 (390.38 MB)
telemt_user_octets_to_client{user="hello"} 8970469012 (8.35 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 4478.7 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11218
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 185
telemt_upstream_connect_attempt_total 2931
telemt_upstream_connect_success_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 2929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 334
telemt_me_reconnect_success_total 335
telemt_me_reader_eof_total 337
telemt_me_idle_close_by_peer_total 337
telemt_me_route_drop_no_conn_total 3579
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_pool_force_close_total 9
telemt_me_writer_removed_unexpected_total 338
telemt_me_writer_restored_same_endpoint_total 331
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 10730
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 88942984 (84.82 MB)
telemt_user_octets_to_client{user="hello"} 1930490068 (1.80 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 4476.1 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18324
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 3490
telemt_upstream_connect_success_total 3447
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3447
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 775
telemt_me_reconnect_success_total 774
telemt_me_reader_eof_total 805
telemt_me_idle_close_by_peer_total 805
telemt_me_route_drop_no_conn_total 5503
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 806
telemt_me_writer_restored_same_endpoint_total 769
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 17794
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 355443580 (338.98 MB)
telemt_user_octets_to_client{user="hello"} 5676157712 (5.29 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 4472.8 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15061
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 398
telemt_upstream_connect_attempt_total 2337
telemt_upstream_connect_success_total 2326
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2326
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 974
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 264
telemt_me_reconnect_success_total 261
telemt_me_reader_eof_total 266
telemt_me_idle_close_by_peer_total 266
telemt_me_route_drop_no_conn_total 7669
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 55
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 1
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 266
telemt_me_writer_restored_same_endpoint_total 257
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 13782
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 162489716 (154.96 MB)
telemt_user_octets_to_client{user="hello"} 13704057856 (12.76 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 4471.6 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18876
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 88
telemt_upstream_connect_attempt_total 2666
telemt_upstream_connect_success_total 2664
telemt_upstream_connect_attempts_per_request{bucket="1"} 2664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 457
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 466
telemt_me_idle_close_by_peer_total 466
telemt_me_route_drop_no_conn_total 7801
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_restored_same_endpoint_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 18460
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 10924524336 (10.17 GB)
telemt_user_octets_to_client{user="hello"} 15461110868 (14.40 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```