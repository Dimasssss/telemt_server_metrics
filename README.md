# Server Metrics 2026-03-06 10:57:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 2136.7 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76217
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 552
telemt_upstream_connect_attempt_total 539
telemt_upstream_connect_success_total 535
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 10
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 16830
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 53099
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 1390880440 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 18910315400 (17.61 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 2136.7 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22433
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 450
telemt_upstream_connect_attempt_total 576
telemt_upstream_connect_success_total 574
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 277
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 7192
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 63
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 21403
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 186726028 (178.08 MB)
telemt_user_octets_to_client{user="hello"} 5202383268 (4.85 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 2136.4 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39396
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 1144
telemt_upstream_connect_attempt_total 679
telemt_upstream_connect_success_total 670
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 16375
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 43
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 37285
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 461756904 (440.37 MB)
telemt_user_octets_to_client{user="hello"} 8618943064 (8.03 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 1452.5 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16531
telemt_connections_bad_total 1292
telemt_handshake_timeouts_total 373
telemt_upstream_connect_attempt_total 482
telemt_upstream_connect_success_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 193
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 5649
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 18
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_restored_same_endpoint_total 9
telemt_user_connections_total{user="hello"} 14456
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 147936856 (141.08 MB)
telemt_user_octets_to_client{user="hello"} 3669911304 (3.42 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 2136.7 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41066
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 941
telemt_upstream_connect_attempt_total 295
telemt_upstream_connect_success_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 2
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 12353
telemt_me_single_endpoint_shadow_rotate_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 21
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 38318
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 10940835436 (10.19 GB)
telemt_user_octets_to_client{user="hello"} 15388737952 (14.33 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 101
```