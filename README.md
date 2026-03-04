# Server Metrics 2026-03-04 21:28:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 2092.7 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27857
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 328
telemt_upstream_connect_attempt_total 704
telemt_upstream_connect_success_total 687
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 687
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 31
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 5898
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 69
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 11
telemt_user_connections_total{user="hello"} 23092
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 2023563600 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 9686048056 (9.02 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 2087.2 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10504
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 757
telemt_upstream_connect_success_total 739
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 739
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 35
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 2830
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_restored_same_endpoint_total 16
telemt_user_connections_total{user="hello"} 9585
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 109638840 (104.56 MB)
telemt_user_octets_to_client{user="hello"} 2538854016 (2.36 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 2084.0 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22732
telemt_connections_bad_total 312
telemt_handshake_timeouts_total 161
telemt_upstream_connect_attempt_total 662
telemt_upstream_connect_success_total 648
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 648
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 6015
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 54
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 20867
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 146878772 (140.07 MB)
telemt_user_octets_to_client{user="hello"} 7854441872 (7.32 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 34132.4 (9h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491053
telemt_connections_bad_total 62602
telemt_handshake_timeouts_total 14621
telemt_upstream_connect_attempt_total 14515
telemt_upstream_connect_success_total 14515
telemt_upstream_connect_attempts_per_request{bucket="1"} 14515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 198
telemt_me_reconnect_attempts_total 1998
telemt_me_reconnect_success_total 1988
telemt_me_reader_eof_total 2018
telemt_me_idle_close_by_peer_total 2018
telemt_me_route_drop_no_conn_total 170196
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 650
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 12
telemt_pool_force_close_total 397
telemt_me_writer_removed_unexpected_total 2019
telemt_me_writer_restored_same_endpoint_total 1964
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 386230
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 5543523564 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 149237208248 (138.99 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 34491.7 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492402
telemt_connections_bad_total 3752
telemt_handshake_timeouts_total 5368
telemt_upstream_connect_attempt_total 20346
telemt_upstream_connect_success_total 20235
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 20235
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 295
telemt_me_reconnect_attempts_total 4141
telemt_me_reconnect_success_total 4129
telemt_me_reader_eof_total 4277
telemt_me_idle_close_by_peer_total 4277
telemt_me_route_drop_no_conn_total 221245
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
telemt_pool_stale_pick_total 183
telemt_me_writer_removed_unexpected_total 4280
telemt_me_writer_restored_same_endpoint_total 4108
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 444017
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 7002697804 (6.52 GB)
telemt_user_octets_to_client{user="hello"} 144105674988 (134.21 GB)
telemt_user_unique_ips_current{user="hello"} 29
```