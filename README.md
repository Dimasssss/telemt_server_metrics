# Server Metrics 2026-03-04 21:17:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 1475.5 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21993
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 231
telemt_upstream_connect_attempt_total 388
telemt_upstream_connect_success_total 377
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 377
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 4040
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 47
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 17534
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 1392120596 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 5984040856 (5.57 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 1470.1 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7636
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 435
telemt_upstream_connect_success_total 427
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 427
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 24
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 2165
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 49
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 6838
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 52756116 (50.31 MB)
telemt_user_octets_to_client{user="hello"} 1921481068 (1.79 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 1466.8 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16608
telemt_connections_bad_total 281
telemt_handshake_timeouts_total 147
telemt_upstream_connect_attempt_total 412
telemt_upstream_connect_success_total 399
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 399
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 4449
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
telemt_user_connections_total{user="hello"} 15634
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 109018000 (103.97 MB)
telemt_user_octets_to_client{user="hello"} 5360268988 (4.99 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 33514.9 (9h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485840
telemt_connections_bad_total 61525
telemt_handshake_timeouts_total 14591
telemt_upstream_connect_attempt_total 14377
telemt_upstream_connect_success_total 14377
telemt_upstream_connect_attempts_per_request{bucket="1"} 14377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 1994
telemt_me_reconnect_success_total 1984
telemt_me_reader_eof_total 2014
telemt_me_idle_close_by_peer_total 2014
telemt_me_route_drop_no_conn_total 169142
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 631
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 12
telemt_pool_force_close_total 397
telemt_me_writer_removed_unexpected_total 2015
telemt_me_writer_restored_same_endpoint_total 1960
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 383130
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 5512598552 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 147424631736 (137.30 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 33874.2 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489074
telemt_connections_bad_total 3751
telemt_handshake_timeouts_total 5360
telemt_upstream_connect_attempt_total 19558
telemt_upstream_connect_success_total 19452
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 19452
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 284
telemt_me_reconnect_attempts_total 3895
telemt_me_reconnect_success_total 3885
telemt_me_reader_eof_total 4017
telemt_me_idle_close_by_peer_total 4017
telemt_me_route_drop_no_conn_total 220038
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
telemt_pool_stale_pick_total 178
telemt_me_writer_removed_unexpected_total 4019
telemt_me_writer_restored_same_endpoint_total 3864
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 440742
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 6949998364 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 142706596416 (132.91 GB)
telemt_user_unique_ips_current{user="hello"} 43
```