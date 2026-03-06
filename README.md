# Server Metrics 2026-03-06 10:42:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 1212.0 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44066
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 409
telemt_upstream_connect_attempt_total 249
telemt_upstream_connect_success_total 245
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 9129
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 30265
telemt_user_connections_current{user="hello"} 959
telemt_user_octets_from_client{user="hello"} 666860452 (635.97 MB)
telemt_user_octets_to_client{user="hello"} 9227914244 (8.59 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 1212.0 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12781
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 273
telemt_upstream_connect_attempt_total 272
telemt_upstream_connect_success_total 270
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 2
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 3796
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 38
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 12133
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 85859324 (81.88 MB)
telemt_user_octets_to_client{user="hello"} 2965814040 (2.76 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 1211.8 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22004
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 350
telemt_upstream_connect_attempt_total 298
telemt_upstream_connect_success_total 292
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 6443
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 23
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 21099
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 271390452 (258.82 MB)
telemt_user_octets_to_client{user="hello"} 5073259808 (4.72 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 527.9 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6409
telemt_connections_bad_total 470
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 143
telemt_upstream_connect_success_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_me_keepalive_timeout_total 1
telemt_me_route_drop_no_conn_total 2109
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_user_connections_total{user="hello"} 5596
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 49520500 (47.23 MB)
telemt_user_octets_to_client{user="hello"} 1026316980 (978.77 MB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 1212.1 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18745
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 232
telemt_upstream_connect_success_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 6272
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 17882
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 10804260676 (10.06 GB)
telemt_user_octets_to_client{user="hello"} 7460697688 (6.95 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 101
```