# Server Metrics 2026-03-04 21:43:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 3015.0 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36766
telemt_connections_bad_total 88
telemt_handshake_timeouts_total 381
telemt_upstream_connect_attempt_total 1352
telemt_upstream_connect_success_total 1325
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1325
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 119
telemt_me_reconnect_success_total 135
telemt_me_reader_eof_total 115
telemt_me_idle_close_by_peer_total 115
telemt_me_route_drop_no_conn_total 8634
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 94
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 115
telemt_me_writer_restored_same_endpoint_total 115
telemt_user_connections_total{user="hello"} 30977
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 2066404468 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 13143278024 (12.24 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 3010.0 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14349
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 1441
telemt_upstream_connect_success_total 1411
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1411
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 633
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 101
telemt_me_reconnect_success_total 114
telemt_me_reader_eof_total 95
telemt_me_idle_close_by_peer_total 95
telemt_me_route_drop_no_conn_total 3894
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 95
telemt_me_writer_restored_same_endpoint_total 95
telemt_user_connections_total{user="hello"} 13080
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 135129492 (128.87 MB)
telemt_user_octets_to_client{user="hello"} 3974759056 (3.70 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 3006.5 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32086
telemt_connections_bad_total 488
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 861
telemt_upstream_connect_success_total 847
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 847
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 14
telemt_me_reconnect_success_total 30
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 8699
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 28970
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 453592976 (432.58 MB)
telemt_user_octets_to_client{user="hello"} 10500116032 (9.78 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 35054.7 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497249
telemt_connections_bad_total 64157
telemt_handshake_timeouts_total 14633
telemt_upstream_connect_attempt_total 14957
telemt_upstream_connect_success_total 14957
telemt_upstream_connect_attempts_per_request{bucket="1"} 14957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 2027
telemt_me_reconnect_success_total 2015
telemt_me_reader_eof_total 2047
telemt_me_idle_close_by_peer_total 2047
telemt_me_route_drop_no_conn_total 172373
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 664
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 12
telemt_pool_force_close_total 397
telemt_me_writer_removed_unexpected_total 2048
telemt_me_writer_restored_same_endpoint_total 1991
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 390481
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 5578592432 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 151094853876 (140.72 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 35414.1 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497999
telemt_connections_bad_total 3757
telemt_handshake_timeouts_total 5425
telemt_upstream_connect_attempt_total 21430
telemt_upstream_connect_success_total 21318
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 21318
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 4559
telemt_me_reconnect_success_total 4547
telemt_me_reader_eof_total 4711
telemt_me_idle_close_by_peer_total 4711
telemt_me_route_drop_no_conn_total 223001
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 822
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4714
telemt_me_writer_restored_same_endpoint_total 4526
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 449363
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 7054956908 (6.57 GB)
telemt_user_octets_to_client{user="hello"} 144893605380 (134.94 GB)
telemt_user_unique_ips_current{user="hello"} 38
```