# Server Metrics 2026-03-06 11:43:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 4906.3 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169787
telemt_connections_bad_total 374
telemt_handshake_timeouts_total 900
telemt_upstream_connect_attempt_total 1572
telemt_upstream_connect_success_total 1558
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 55
telemt_me_reconnect_success_total 57
telemt_me_reader_eof_total 54
telemt_me_idle_close_by_peer_total 54
telemt_me_route_drop_no_conn_total 40651
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 625
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_restored_same_endpoint_total 52
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 116983
telemt_user_connections_current{user="hello"} 1052
telemt_user_octets_from_client{user="hello"} 3229067496 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 43082894860 (40.12 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 4906.2 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53940
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 1757
telemt_upstream_connect_attempt_total 1700
telemt_upstream_connect_success_total 1695
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 36
telemt_me_reconnect_success_total 36
telemt_me_reader_eof_total 37
telemt_me_idle_close_by_peer_total 37
telemt_me_route_drop_no_conn_total 19294
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 200
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 37
telemt_me_writer_restored_same_endpoint_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 47556
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 488126300 (465.51 MB)
telemt_user_octets_to_client{user="hello"} 20170983788 (18.79 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 4906.2 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94337
telemt_connections_bad_total 483
telemt_handshake_timeouts_total 7510
telemt_upstream_connect_attempt_total 2479
telemt_upstream_connect_success_total 2467
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 396
telemt_me_reconnect_success_total 395
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 35344
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 176
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_me_writer_removed_unexpected_total 406
telemt_me_writer_restored_same_endpoint_total 390
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 84096
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 950497036 (906.46 MB)
telemt_user_octets_to_client{user="hello"} 26799054388 (24.96 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 4222.1 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46813
telemt_connections_bad_total 3779
telemt_handshake_timeouts_total 1124
telemt_upstream_connect_attempt_total 2264
telemt_upstream_connect_success_total 2264
telemt_upstream_connect_attempts_per_request{bucket="1"} 2264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 932
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 365
telemt_me_reconnect_success_total 362
telemt_me_reader_eof_total 367
telemt_me_idle_close_by_peer_total 367
telemt_me_route_drop_no_conn_total 16398
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 62
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_restored_same_endpoint_total 362
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 40984
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 507037008 (483.55 MB)
telemt_user_octets_to_client{user="hello"} 13387428324 (12.47 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 4906.3 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95780
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 1812
telemt_upstream_connect_attempt_total 1289
telemt_upstream_connect_success_total 1287
telemt_upstream_connect_attempts_per_request{bucket="1"} 1287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 35460
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 149
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 28
telemt_me_writer_removed_unexpected_total 18
telemt_me_writer_restored_same_endpoint_total 17
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 87349
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 11316883432 (10.54 GB)
telemt_user_octets_to_client{user="hello"} 44477479632 (41.42 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 101
```