# Server Metrics 2026-03-03 22:13:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 3764.3 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37185
telemt_connections_bad_total 266
telemt_handshake_timeouts_total 87
telemt_upstream_connect_attempt_total 1888
telemt_upstream_connect_success_total 1878
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1878
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 196
telemt_me_reconnect_success_total 209
telemt_me_reader_eof_total 192
telemt_me_idle_close_by_peer_total 192
telemt_me_route_drop_no_conn_total 14178
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 192
telemt_me_writer_restored_same_endpoint_total 189
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 35949
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 377408612 (359.92 MB)
telemt_user_octets_to_client{user="hello"} 14949560920 (13.92 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 3761.0 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15206
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 2797
telemt_upstream_connect_attempt_total 2640
telemt_upstream_connect_success_total 2534
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 2534
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 605
telemt_me_reconnect_success_total 619
telemt_me_reader_eof_total 611
telemt_me_idle_close_by_peer_total 610
telemt_me_route_drop_no_conn_total 5613
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 43
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 611
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 12178
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 64862408 (61.86 MB)
telemt_user_octets_to_client{user="hello"} 3042330680 (2.83 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 3759.7 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38395
telemt_connections_bad_total 10288
telemt_handshake_timeouts_total 576
telemt_upstream_connect_attempt_total 2358
telemt_upstream_connect_success_total 2338
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2338
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 318
telemt_me_reconnect_success_total 334
telemt_me_reader_eof_total 320
telemt_me_idle_close_by_peer_total 320
telemt_me_route_drop_no_conn_total 8086
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 103
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 320
telemt_me_writer_restored_same_endpoint_total 313
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 26563
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 193351752 (184.39 MB)
telemt_user_octets_to_client{user="hello"} 10454616088 (9.74 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 3758.7 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17023
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 238
telemt_upstream_connect_attempt_total 2269
telemt_upstream_connect_success_total 2254
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2254
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 257
telemt_me_reconnect_success_total 274
telemt_me_reader_eof_total 257
telemt_me_idle_close_by_peer_total 257
telemt_me_route_drop_no_conn_total 6963
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 257
telemt_me_writer_restored_same_endpoint_total 255
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 16488
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 150136792 (143.18 MB)
telemt_user_octets_to_client{user="hello"} 6575964404 (6.12 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 3757.3 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34779
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 8286
telemt_upstream_connect_attempt_total 2107
telemt_upstream_connect_success_total 2076
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2076
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 418
telemt_me_reconnect_success_total 433
telemt_me_reader_eof_total 422
telemt_me_idle_close_by_peer_total 422
telemt_me_route_drop_no_conn_total 25290
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_restored_same_endpoint_total 412
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 25967
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 152739228 (145.66 MB)
telemt_user_octets_to_client{user="hello"} 6399934656 (5.96 GB)
telemt_user_unique_ips_current{user="hello"} 30
```