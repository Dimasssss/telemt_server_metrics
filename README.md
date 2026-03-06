# Server Metrics 2026-03-06 10:47:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 1521.2 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54882
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 455
telemt_upstream_connect_attempt_total 346
telemt_upstream_connect_success_total 342
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 11851
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 77
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 38019
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 764356408 (728.95 MB)
telemt_user_octets_to_client{user="hello"} 11902814840 (11.09 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 1520.9 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16034
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 339
telemt_upstream_connect_attempt_total 376
telemt_upstream_connect_success_total 374
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 4990
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 15231
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 105476056 (100.59 MB)
telemt_user_octets_to_client{user="hello"} 3563601620 (3.32 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 1520.9 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27923
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 397
telemt_upstream_connect_success_total 391
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 9932
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 29
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 26686
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 355212644 (338.76 MB)
telemt_user_octets_to_client{user="hello"} 6147889676 (5.73 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 837.0 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10423
telemt_connections_bad_total 748
telemt_handshake_timeouts_total 269
telemt_upstream_connect_attempt_total 208
telemt_upstream_connect_success_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 80
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 3278
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 9053
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 99956928 (95.33 MB)
telemt_user_octets_to_client{user="hello"} 1782331380 (1.66 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 1521.2 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25633
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 453
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
telemt_me_route_drop_no_conn_total 8106
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 17
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 24259
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 10839060824 (10.09 GB)
telemt_user_octets_to_client{user="hello"} 10143371340 (9.45 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 92
```