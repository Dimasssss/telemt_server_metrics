# Server Metrics 2026-03-06 11:12:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 3059.3 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108315
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 670
telemt_upstream_connect_attempt_total 733
telemt_upstream_connect_success_total 725
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 24562
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 188
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 75162
telemt_user_connections_current{user="hello"} 961
telemt_user_octets_from_client{user="hello"} 2446591208 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 25528691064 (23.78 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 3059.3 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31372
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 660
telemt_upstream_connect_attempt_total 787
telemt_upstream_connect_success_total 785
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 10
telemt_me_reconnect_success_total 10
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 12715
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_restored_same_endpoint_total 10
telemt_user_connections_total{user="hello"} 29972
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 291585504 (278.08 MB)
telemt_user_octets_to_client{user="hello"} 9062913892 (8.44 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 3059.0 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56043
telemt_connections_bad_total 391
telemt_handshake_timeouts_total 1845
telemt_upstream_connect_attempt_total 1153
telemt_upstream_connect_success_total 1145
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 47
telemt_me_reconnect_success_total 49
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 22072
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 97
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 50
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 52503
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 610148916 (581.88 MB)
telemt_user_octets_to_client{user="hello"} 13330606004 (12.42 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 2375.1 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26090
telemt_connections_bad_total 2118
telemt_handshake_timeouts_total 537
telemt_upstream_connect_attempt_total 1046
telemt_upstream_connect_success_total 1046
telemt_upstream_connect_attempts_per_request{bucket="1"} 1046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 424
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 82
telemt_me_reconnect_success_total 81
telemt_me_reader_eof_total 84
telemt_me_idle_close_by_peer_total 84
telemt_me_route_drop_no_conn_total 9581
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 30
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_writer_removed_unexpected_total 84
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 22849
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 201951244 (192.60 MB)
telemt_user_octets_to_client{user="hello"} 6000584876 (5.59 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 3059.3 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61427
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 1410
telemt_upstream_connect_attempt_total 432
telemt_upstream_connect_success_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 2
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 18928
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 54
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 56535
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 11057844536 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 22905628384 (21.33 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 85
```