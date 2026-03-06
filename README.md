# Server Metrics 2026-03-06 09:20:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 2890.9 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81313
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 250
telemt_upstream_connect_attempt_total 910
telemt_upstream_connect_success_total 906
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 416
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 21524
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 401
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 64513
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 955835372 (911.56 MB)
telemt_user_octets_to_client{user="hello"} 21538680692 (20.06 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 2888.1 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56530
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 29428
telemt_upstream_connect_attempt_total 1109
telemt_upstream_connect_success_total 1109
telemt_upstream_connect_attempts_per_request{bucket="1"} 1109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 539
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 31
telemt_me_reconnect_success_total 29
telemt_me_reader_eof_total 31
telemt_me_idle_close_by_peer_total 31
telemt_me_route_drop_no_conn_total 10118
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_me_writer_removed_unexpected_total 31
telemt_me_writer_restored_same_endpoint_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 26221
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 409244664 (390.29 MB)
telemt_user_octets_to_client{user="hello"} 9285547272 (8.65 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 2871.3 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60020
telemt_connections_bad_total 264
telemt_handshake_timeouts_total 8912
telemt_upstream_connect_attempt_total 1174
telemt_upstream_connect_success_total 1161
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 66
telemt_me_reconnect_success_total 58
telemt_me_reader_eof_total 58
telemt_me_idle_close_by_peer_total 57
telemt_me_route_drop_no_conn_total 18352
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 118
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_writer_removed_unexpected_total 61
telemt_me_writer_restored_same_endpoint_total 58
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 48391
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 935116420 (891.80 MB)
telemt_user_octets_to_client{user="hello"} 14352451696 (13.37 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 2855.9 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48784
telemt_connections_bad_total 2561
telemt_handshake_timeouts_total 11144
telemt_upstream_connect_attempt_total 1184
telemt_upstream_connect_success_total 1169
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 514
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 55
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 17836
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_restored_same_endpoint_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 33759
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 675198900 (643.92 MB)
telemt_user_octets_to_client{user="hello"} 10458196432 (9.74 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 2797.6 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42807
telemt_connections_bad_total 261
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 1175
telemt_upstream_connect_success_total 1150
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 102
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 97
telemt_me_idle_close_by_peer_total 97
telemt_me_route_drop_no_conn_total 17479
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 62
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 98
telemt_me_writer_restored_same_endpoint_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 38671
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 727918588 (694.20 MB)
telemt_user_octets_to_client{user="hello"} 16488655512 (15.36 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 98
```