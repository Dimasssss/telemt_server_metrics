# Server Metrics 2026-03-06 11:18:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 3366.6 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118546
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 698
telemt_upstream_connect_attempt_total 847
telemt_upstream_connect_success_total 837
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 13
telemt_me_idle_close_by_peer_total 13
telemt_me_route_drop_no_conn_total 27150
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 263
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 13
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 82096
telemt_user_connections_current{user="hello"} 1016
telemt_user_octets_from_client{user="hello"} 2547227756 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 27215732100 (25.35 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 3366.5 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34199
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 894
telemt_upstream_connect_success_total 892
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 426
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 14
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 14
telemt_me_idle_close_by_peer_total 14
telemt_me_route_drop_no_conn_total 13754
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 14
telemt_me_writer_restored_same_endpoint_total 14
telemt_user_connections_total{user="hello"} 32688
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 321493768 (306.60 MB)
telemt_user_octets_to_client{user="hello"} 11146981100 (10.38 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 3366.3 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62728
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 3059
telemt_upstream_connect_attempt_total 1291
telemt_upstream_connect_success_total 1283
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 567
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 67
telemt_me_reconnect_success_total 68
telemt_me_reader_eof_total 69
telemt_me_idle_close_by_peer_total 69
telemt_me_route_drop_no_conn_total 23785
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 122
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 69
telemt_me_writer_restored_same_endpoint_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 57903
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 685121444 (653.38 MB)
telemt_user_octets_to_client{user="hello"} 14737593988 (13.73 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 2682.4 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29533
telemt_connections_bad_total 2403
telemt_handshake_timeouts_total 650
telemt_upstream_connect_attempt_total 1231
telemt_upstream_connect_success_total 1230
telemt_upstream_connect_attempts_per_request{bucket="1"} 1230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 502
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 122
telemt_me_reconnect_success_total 120
telemt_me_reader_eof_total 124
telemt_me_idle_close_by_peer_total 124
telemt_me_route_drop_no_conn_total 10813
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 31
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_me_writer_removed_unexpected_total 124
telemt_me_writer_restored_same_endpoint_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 25845
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 213437268 (203.55 MB)
telemt_user_octets_to_client{user="hello"} 6683486852 (6.22 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 3366.9 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67011
telemt_connections_bad_total 91
telemt_handshake_timeouts_total 1493
telemt_upstream_connect_attempt_total 542
telemt_upstream_connect_success_total 542
telemt_upstream_connect_attempts_per_request{bucket="1"} 542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 2
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 20822
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 68
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 61518
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 11087563432 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 25351778088 (23.61 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 91
```