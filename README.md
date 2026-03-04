# Server Metrics 2026-03-04 21:23:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 1785.3 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24810
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 283
telemt_upstream_connect_attempt_total 512
telemt_upstream_connect_success_total 501
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 501
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 5028
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 57
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 20207
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 1739674412 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 7744839292 (7.21 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 1780.0 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9064
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 562
telemt_upstream_connect_success_total 554
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 554
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 270
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 24
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 2435
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 65
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 8201
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 92528248 (88.24 MB)
telemt_user_octets_to_client{user="hello"} 2240154424 (2.09 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 1776.7 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19084
telemt_connections_bad_total 312
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 545
telemt_upstream_connect_success_total 531
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 531
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 5259
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 47
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 18036
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 126798516 (120.92 MB)
telemt_user_octets_to_client{user="hello"} 6879160212 (6.41 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 33824.9 (9h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488474
telemt_connections_bad_total 62090
telemt_handshake_timeouts_total 14603
telemt_upstream_connect_attempt_total 14443
telemt_upstream_connect_success_total 14443
telemt_upstream_connect_attempts_per_request{bucket="1"} 14443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 1998
telemt_me_reconnect_success_total 1988
telemt_me_reader_eof_total 2018
telemt_me_idle_close_by_peer_total 2018
telemt_me_route_drop_no_conn_total 169727
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 637
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 12
telemt_pool_force_close_total 397
telemt_me_writer_removed_unexpected_total 2019
telemt_me_writer_restored_same_endpoint_total 1964
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 384689
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 5527832972 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 148093343860 (137.92 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 34184.4 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490869
telemt_connections_bad_total 3751
telemt_handshake_timeouts_total 5364
telemt_upstream_connect_attempt_total 19886
telemt_upstream_connect_success_total 19776
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 19776
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 293
telemt_me_reconnect_attempts_total 3982
telemt_me_reconnect_success_total 3972
telemt_me_reader_eof_total 4108
telemt_me_idle_close_by_peer_total 4108
telemt_me_route_drop_no_conn_total 220632
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 819
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 524
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 7
telemt_pool_force_close_total 339
telemt_pool_stale_pick_total 181
telemt_me_writer_removed_unexpected_total 4111
telemt_me_writer_restored_same_endpoint_total 3951
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 442505
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 6990068140 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 143339077212 (133.49 GB)
telemt_user_unique_ips_current{user="hello"} 38
```