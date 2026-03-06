# Server Metrics 2026-03-06 11:02:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 2443.8 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87121
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 574
telemt_upstream_connect_attempt_total 575
telemt_upstream_connect_success_total 571
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 10
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 19184
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 176
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 60321
telemt_user_connections_current{user="hello"} 961
telemt_user_octets_from_client{user="hello"} 2224799656 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 21594666080 (20.11 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 2443.7 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25581
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 477
telemt_upstream_connect_attempt_total 603
telemt_upstream_connect_success_total 601
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 9310
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 74
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 24470
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 218668748 (208.54 MB)
telemt_user_octets_to_client{user="hello"} 7138141720 (6.65 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 2443.5 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44168
telemt_connections_bad_total 106
telemt_handshake_timeouts_total 1263
telemt_upstream_connect_attempt_total 829
telemt_upstream_connect_success_total 821
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 23
telemt_me_reconnect_success_total 25
telemt_me_reader_eof_total 26
telemt_me_idle_close_by_peer_total 26
telemt_me_route_drop_no_conn_total 18000
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 47
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_writer_removed_unexpected_total 26
telemt_me_writer_restored_same_endpoint_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 41800
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 488609496 (465.97 MB)
telemt_user_octets_to_client{user="hello"} 9627568916 (8.97 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 1759.6 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19369
telemt_connections_bad_total 1566
telemt_handshake_timeouts_total 401
telemt_upstream_connect_attempt_total 609
telemt_upstream_connect_success_total 609
telemt_upstream_connect_attempts_per_request{bucket="1"} 609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 245
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 11
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 6875
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 27
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 11
telemt_user_connections_total{user="hello"} 16942
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 168296212 (160.50 MB)
telemt_user_octets_to_client{user="hello"} 4196102276 (3.91 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 2443.7 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48093
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 1112
telemt_upstream_connect_attempt_total 304
telemt_upstream_connect_success_total 304
telemt_upstream_connect_attempts_per_request{bucket="1"} 304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 2
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 14886
telemt_me_single_endpoint_shadow_rotate_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 44650
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 10977043320 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 17910848152 (16.68 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 95
```