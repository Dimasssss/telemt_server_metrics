# Server Metrics 2026-03-03 22:33:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 4992.6 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46309
telemt_connections_bad_total 601
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 2191
telemt_upstream_connect_success_total 2175
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2175
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 915
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 200
telemt_me_reconnect_success_total 212
telemt_me_reader_eof_total 195
telemt_me_idle_close_by_peer_total 195
telemt_me_route_drop_no_conn_total 17668
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 80
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 195
telemt_me_writer_restored_same_endpoint_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 44591
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 441543236 (421.09 MB)
telemt_user_octets_to_client{user="hello"} 16918670048 (15.76 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 4989.2 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19581
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 3712
telemt_upstream_connect_attempt_total 4727
telemt_upstream_connect_success_total 4574
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 4574
telemt_upstream_connect_attempts_per_request{bucket="2"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1495
telemt_me_reconnect_success_total 1508
telemt_me_reader_eof_total 1519
telemt_me_idle_close_by_peer_total 1518
telemt_me_route_drop_no_conn_total 7529
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_me_writer_removed_unexpected_total 1519
telemt_me_writer_restored_same_endpoint_total 1488
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 15568
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 91028352 (86.81 MB)
telemt_user_octets_to_client{user="hello"} 4422871556 (4.12 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 4988.0 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49487
telemt_connections_bad_total 13628
telemt_handshake_timeouts_total 1412
telemt_upstream_connect_attempt_total 3935
telemt_upstream_connect_success_total 3901
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3901
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 776
telemt_me_reconnect_success_total 791
telemt_me_reader_eof_total 796
telemt_me_idle_close_by_peer_total 796
telemt_me_route_drop_no_conn_total 10186
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 120
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 796
telemt_me_writer_restored_same_endpoint_total 770
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 33359
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 233087332 (222.29 MB)
telemt_user_octets_to_client{user="hello"} 11857837096 (11.04 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 4986.9 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22424
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 336
telemt_upstream_connect_attempt_total 2661
telemt_upstream_connect_success_total 2642
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2642
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 262
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 262
telemt_me_idle_close_by_peer_total 262
telemt_me_route_drop_no_conn_total 8745
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 262
telemt_me_writer_restored_same_endpoint_total 260
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 21713
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 180064084 (171.72 MB)
telemt_user_octets_to_client{user="hello"} 7521510720 (7.00 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 4985.5 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46796
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 14228
telemt_upstream_connect_attempt_total 2506
telemt_upstream_connect_success_total 2462
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 2462
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 445
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 450
telemt_me_idle_close_by_peer_total 450
telemt_me_route_drop_no_conn_total 27285
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 450
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 31733
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 175432088 (167.31 MB)
telemt_user_octets_to_client{user="hello"} 7793469276 (7.26 GB)
telemt_user_unique_ips_current{user="hello"} 17
```