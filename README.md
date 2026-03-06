# Server Metrics 2026-03-06 10:37:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 903.7 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33993
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 383
telemt_upstream_connect_attempt_total 125
telemt_upstream_connect_success_total 122
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 6783
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="static"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 52
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 23664
telemt_user_connections_current{user="hello"} 1013
telemt_user_octets_from_client{user="hello"} 554740720 (529.04 MB)
telemt_user_octets_to_client{user="hello"} 7372830144 (6.87 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 903.6 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9774
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 206
telemt_upstream_connect_attempt_total 132
telemt_upstream_connect_success_total 131
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 2
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 2454
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="static"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 33
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 9230
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 71785708 (68.46 MB)
telemt_user_octets_to_client{user="hello"} 2209237040 (2.06 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 903.4 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16730
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 296
telemt_upstream_connect_attempt_total 174
telemt_upstream_connect_success_total 171
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 4907
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="static"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 20
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 15986
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 219877392 (209.69 MB)
telemt_user_octets_to_client{user="hello"} 3664842104 (3.41 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 219.6 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2717
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 89
telemt_upstream_connect_success_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 89
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_me_keepalive_timeout_total 1
telemt_me_route_drop_no_conn_total 545
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 2409
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 18149204 (17.31 MB)
telemt_user_octets_to_client{user="hello"} 313860908 (299.32 MB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 904.1 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12314
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 187
telemt_upstream_connect_success_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 78
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 4396
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="static"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 11846
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 9746877948 (9.08 GB)
telemt_user_octets_to_client{user="hello"} 5374826808 (5.01 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 84
```