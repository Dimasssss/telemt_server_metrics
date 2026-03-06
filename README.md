# Server Metrics 2026-03-06 00:17:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 6940.3 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51293
telemt_connections_bad_total 14116
telemt_handshake_timeouts_total 447
telemt_upstream_connect_attempt_total 4407
telemt_upstream_connect_success_total 4362
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4362
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 806
telemt_me_reconnect_success_total 802
telemt_me_reader_eof_total 821
telemt_me_idle_close_by_peer_total 821
telemt_me_route_drop_no_conn_total 9350
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 821
telemt_me_writer_restored_same_endpoint_total 797
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 35768
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 474738376 (452.75 MB)
telemt_user_octets_to_client{user="hello"} 13603552348 (12.67 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 6935.9 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15870
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 6085
telemt_upstream_connect_success_total 6083
telemt_upstream_connect_attempts_per_request{bucket="1"} 6083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 1431
telemt_me_reconnect_success_total 1428
telemt_me_reader_eof_total 1439
telemt_me_idle_close_by_peer_total 1439
telemt_me_route_drop_no_conn_total 5126
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 45
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1440
telemt_me_writer_restored_same_endpoint_total 1424
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 15261
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 115809816 (110.44 MB)
telemt_user_octets_to_client{user="hello"} 3283237224 (3.06 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 6933.3 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27556
telemt_connections_bad_total 167
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 7644
telemt_upstream_connect_success_total 7585
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 7585
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 2609
telemt_me_reconnect_success_total 2602
telemt_me_reader_eof_total 2717
telemt_me_idle_close_by_peer_total 2717
telemt_me_route_drop_no_conn_total 7577
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 2718
telemt_me_writer_restored_same_endpoint_total 2597
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 26816
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 398611376 (380.15 MB)
telemt_user_octets_to_client{user="hello"} 7833629388 (7.30 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 6930.0 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21541
telemt_connections_bad_total 161
telemt_handshake_timeouts_total 575
telemt_upstream_connect_attempt_total 3474
telemt_upstream_connect_success_total 3459
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 3459
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1462
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 335
telemt_me_reconnect_success_total 331
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 9674
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 336
telemt_me_writer_restored_same_endpoint_total 326
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 19610
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 185249528 (176.67 MB)
telemt_user_octets_to_client{user="hello"} 15735791504 (14.66 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 6928.7 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29357
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 4141
telemt_upstream_connect_success_total 4136
telemt_upstream_connect_attempts_per_request{bucket="1"} 4136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1273
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 661
telemt_me_reconnect_success_total 661
telemt_me_reader_eof_total 671
telemt_me_idle_close_by_peer_total 671
telemt_me_route_drop_no_conn_total 10926
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 13
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 2
telemt_pool_force_close_total 42
telemt_me_writer_removed_unexpected_total 671
telemt_me_writer_restored_same_endpoint_total 656
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 28800
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 10956846024 (10.20 GB)
telemt_user_octets_to_client{user="hello"} 17449239744 (16.25 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```