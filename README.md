# Server Metrics 2026-03-06 11:28:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 3982.6 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139252
telemt_connections_bad_total 268
telemt_handshake_timeouts_total 824
telemt_upstream_connect_attempt_total 1116
telemt_upstream_connect_success_total 1105
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 24
telemt_me_reader_eof_total 20
telemt_me_idle_close_by_peer_total 20
telemt_me_route_drop_no_conn_total 31829
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 398
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 20
telemt_me_writer_restored_same_endpoint_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 96084
telemt_user_connections_current{user="hello"} 976
telemt_user_octets_from_client{user="hello"} 2766869264 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 30996488064 (28.87 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 3982.5 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41772
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 1024
telemt_upstream_connect_attempt_total 1179
telemt_upstream_connect_success_total 1176
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 552
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 23
telemt_me_idle_close_by_peer_total 23
telemt_me_route_drop_no_conn_total 15872
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 158
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 38238
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 398281072 (379.83 MB)
telemt_user_octets_to_client{user="hello"} 14493056080 (13.50 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 3982.5 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74807
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 3905
telemt_upstream_connect_attempt_total 1678
telemt_upstream_connect_success_total 1666
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 729
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 137
telemt_me_reconnect_success_total 137
telemt_me_reader_eof_total 144
telemt_me_idle_close_by_peer_total 144
telemt_me_route_drop_no_conn_total 28908
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 136
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_me_writer_removed_unexpected_total 144
telemt_me_writer_restored_same_endpoint_total 132
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 68698
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 779525304 (743.41 MB)
telemt_user_octets_to_client{user="hello"} 18952549292 (17.65 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 3298.3 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36452
telemt_connections_bad_total 2948
telemt_handshake_timeouts_total 903
telemt_upstream_connect_attempt_total 1781
telemt_upstream_connect_success_total 1781
telemt_upstream_connect_attempts_per_request{bucket="1"} 1781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 723
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 261
telemt_me_reconnect_success_total 259
telemt_me_reader_eof_total 264
telemt_me_idle_close_by_peer_total 264
telemt_me_route_drop_no_conn_total 13038
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 45
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 264
telemt_me_writer_restored_same_endpoint_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 31823
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 262063936 (249.92 MB)
telemt_user_octets_to_client{user="hello"} 8584085076 (7.99 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 3982.7 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78290
telemt_connections_bad_total 93
telemt_handshake_timeouts_total 1660
telemt_upstream_connect_attempt_total 885
telemt_upstream_connect_success_total 884
telemt_upstream_connect_attempts_per_request{bucket="1"} 884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 10
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 24677
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 112
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_restored_same_endpoint_total 8
telemt_user_connections_total{user="hello"} 71467
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 11194694756 (10.43 GB)
telemt_user_octets_to_client{user="hello"} 31302008000 (29.15 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 93
```