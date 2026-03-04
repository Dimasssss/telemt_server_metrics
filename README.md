# Server Metrics 2026-03-04 21:38:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 2707.9 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33440
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 380
telemt_upstream_connect_attempt_total 1085
telemt_upstream_connect_success_total 1067
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1067
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 66
telemt_me_reconnect_success_total 82
telemt_me_reader_eof_total 62
telemt_me_idle_close_by_peer_total 62
telemt_me_route_drop_no_conn_total 7665
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 85
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 62
telemt_me_writer_restored_same_endpoint_total 62
telemt_user_connections_total{user="hello"} 28125
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 2053588860 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 12435210756 (11.58 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 2702.5 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13232
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 1157
telemt_upstream_connect_success_total 1139
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1139
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 516
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 68
telemt_me_reconnect_success_total 81
telemt_me_reader_eof_total 62
telemt_me_idle_close_by_peer_total 62
telemt_me_route_drop_no_conn_total 3580
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 62
telemt_me_writer_restored_same_endpoint_total 62
telemt_user_connections_total{user="hello"} 11978
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 124097196 (118.35 MB)
telemt_user_octets_to_client{user="hello"} 3598068336 (3.35 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 2699.4 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28088
telemt_connections_bad_total 474
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 735
telemt_upstream_connect_success_total 721
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 721
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 12
telemt_me_reconnect_success_total 28
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 7382
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 25967
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 271166788 (258.60 MB)
telemt_user_octets_to_client{user="hello"} 9394843460 (8.75 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 34747.5 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495190
telemt_connections_bad_total 63642
telemt_handshake_timeouts_total 14625
telemt_upstream_connect_attempt_total 14814
telemt_upstream_connect_success_total 14814
telemt_upstream_connect_attempts_per_request{bucket="1"} 14814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 2018
telemt_me_reconnect_success_total 2006
telemt_me_reader_eof_total 2036
telemt_me_idle_close_by_peer_total 2036
telemt_me_route_drop_no_conn_total 171783
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 659
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 12
telemt_pool_force_close_total 397
telemt_me_writer_removed_unexpected_total 2037
telemt_me_writer_restored_same_endpoint_total 1982
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 388970
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 5567979996 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 150646283400 (140.30 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 35106.9 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495144
telemt_connections_bad_total 3754
telemt_handshake_timeouts_total 5382
telemt_upstream_connect_attempt_total 21263
telemt_upstream_connect_success_total 21151
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 21151
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 305
telemt_me_reconnect_attempts_total 4512
telemt_me_reconnect_success_total 4500
telemt_me_reader_eof_total 4663
telemt_me_idle_close_by_peer_total 4663
telemt_me_route_drop_no_conn_total 222205
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 822
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 7
telemt_pool_force_close_total 339
telemt_pool_stale_pick_total 188
telemt_me_writer_removed_unexpected_total 4666
telemt_me_writer_restored_same_endpoint_total 4479
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 446701
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 7040509712 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 144504215932 (134.58 GB)
telemt_user_unique_ips_current{user="hello"} 30
```