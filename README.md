# Server Metrics 2026-03-03 22:49:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 5914.0 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51933
telemt_connections_bad_total 640
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 2721
telemt_upstream_connect_success_total 2701
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2701
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 243
telemt_me_reconnect_success_total 254
telemt_me_reader_eof_total 237
telemt_me_idle_close_by_peer_total 237
telemt_me_route_drop_no_conn_total 19692
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_pool_force_close_total 39
telemt_me_writer_removed_unexpected_total 237
telemt_me_writer_restored_same_endpoint_total 234
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 50066
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 472763596 (450.86 MB)
telemt_user_octets_to_client{user="hello"} 17686794612 (16.47 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 5910.7 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23061
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 4534
telemt_upstream_connect_attempt_total 6481
telemt_upstream_connect_success_total 6320
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 6320
telemt_upstream_connect_attempts_per_request{bucket="2"} 78
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 2348
telemt_me_reconnect_success_total 2360
telemt_me_reader_eof_total 2387
telemt_me_idle_close_by_peer_total 2386
telemt_me_route_drop_no_conn_total 8439
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 54
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_me_writer_removed_unexpected_total 2387
telemt_me_writer_restored_same_endpoint_total 2340
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 18191
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 108437352 (103.41 MB)
telemt_user_octets_to_client{user="hello"} 7458472144 (6.95 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 5909.3 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56886
telemt_connections_bad_total 16090
telemt_handshake_timeouts_total 1618
telemt_upstream_connect_attempt_total 5369
telemt_upstream_connect_success_total 5331
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5331
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 1338
telemt_me_reconnect_success_total 1352
telemt_me_reader_eof_total 1384
telemt_me_idle_close_by_peer_total 1383
telemt_me_route_drop_no_conn_total 11722
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 1385
telemt_me_writer_restored_same_endpoint_total 1331
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 38104
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 282161064 (269.09 MB)
telemt_user_octets_to_client{user="hello"} 12325159624 (11.48 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 5908.4 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24959
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 378
telemt_upstream_connect_attempt_total 3251
telemt_upstream_connect_success_total 3230
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3230
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 288
telemt_me_reconnect_success_total 303
telemt_me_reader_eof_total 286
telemt_me_idle_close_by_peer_total 286
telemt_me_route_drop_no_conn_total 9748
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_restored_same_endpoint_total 284
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 24180
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 202748916 (193.36 MB)
telemt_user_octets_to_client{user="hello"} 8121412668 (7.56 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 5907.0 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54760
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 18923
telemt_upstream_connect_attempt_total 3168
telemt_upstream_connect_success_total 3120
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3120
telemt_upstream_connect_attempts_per_request{bucket="2"} 22
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 585
telemt_me_reconnect_success_total 602
telemt_me_reader_eof_total 596
telemt_me_idle_close_by_peer_total 596
telemt_me_route_drop_no_conn_total 28367
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 598
telemt_me_writer_restored_same_endpoint_total 578
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 34919
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 185790496 (177.18 MB)
telemt_user_octets_to_client{user="hello"} 8542066644 (7.96 GB)
telemt_user_unique_ips_current{user="hello"} 20
```