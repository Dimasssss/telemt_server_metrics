# Server Metrics 2026-03-06 10:52:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 1828.4 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65517
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 504
telemt_upstream_connect_attempt_total 448
telemt_upstream_connect_success_total 444
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 14543
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 110
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 45597
telemt_user_connections_current{user="hello"} 1052
telemt_user_octets_from_client{user="hello"} 1042948900 (994.63 MB)
telemt_user_octets_to_client{user="hello"} 15553185028 (14.49 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 1828.3 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18953
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 398
telemt_upstream_connect_attempt_total 493
telemt_upstream_connect_success_total 491
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 6084
telemt_me_single_endpoint_shadow_rotate_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 51
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 18058
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 128877844 (122.91 MB)
telemt_user_octets_to_client{user="hello"} 4270518428 (3.98 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 1828.2 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33927
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 889
telemt_upstream_connect_attempt_total 494
telemt_upstream_connect_success_total 488
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 13869
telemt_me_single_endpoint_shadow_rotate_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 38
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 32255
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 425366016 (405.66 MB)
telemt_user_octets_to_client{user="hello"} 7237082528 (6.74 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 1144.2 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13605
telemt_connections_bad_total 1023
telemt_handshake_timeouts_total 355
telemt_upstream_connect_attempt_total 353
telemt_upstream_connect_success_total 353
telemt_upstream_connect_attempts_per_request{bucket="1"} 353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 4336
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 15
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 11865
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 135594912 (129.31 MB)
telemt_user_octets_to_client{user="hello"} 2849343896 (2.65 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 1828.3 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33394
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 691
telemt_upstream_connect_attempt_total 235
telemt_upstream_connect_success_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 97
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 10252
telemt_me_single_endpoint_shadow_rotate_total 6
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
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 31395
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 10894460204 (10.15 GB)
telemt_user_octets_to_client{user="hello"} 12620909580 (11.75 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 72
```