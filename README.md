# Server Metrics 2026-03-06 12:14:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 6753.5 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221742
telemt_connections_bad_total 531
telemt_handshake_timeouts_total 1273
telemt_upstream_connect_attempt_total 2178
telemt_upstream_connect_success_total 2156
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 94
telemt_me_reconnect_success_total 94
telemt_me_reader_eof_total 96
telemt_me_idle_close_by_peer_total 96
telemt_me_route_drop_no_conn_total 59672
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1012
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 371
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 96
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 164815
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 3672987416 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 68840139528 (64.11 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 6753.2 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73700
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 3046
telemt_upstream_connect_attempt_total 3217
telemt_upstream_connect_success_total 3208
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 354
telemt_me_reconnect_success_total 351
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 28158
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 241
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 372
telemt_me_writer_restored_same_endpoint_total 351
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 65631
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 654730928 (624.40 MB)
telemt_user_octets_to_client{user="hello"} 31798764980 (29.61 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 6753.2 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134764
telemt_connections_bad_total 908
telemt_handshake_timeouts_total 10640
telemt_upstream_connect_attempt_total 4420
telemt_upstream_connect_success_total 4402
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1152
telemt_me_reconnect_success_total 1148
telemt_me_reader_eof_total 1209
telemt_me_idle_close_by_peer_total 1209
telemt_me_route_drop_no_conn_total 62316
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 221
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 1210
telemt_me_writer_restored_same_endpoint_total 1143
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 119895
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 1347789776 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 44666514152 (41.60 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 6069.3 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71453
telemt_connections_bad_total 8083
telemt_handshake_timeouts_total 1567
telemt_upstream_connect_attempt_total 2995
telemt_upstream_connect_success_total 2994
telemt_upstream_connect_attempts_per_request{bucket="1"} 2994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1264
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 386
telemt_me_reconnect_success_total 383
telemt_me_reader_eof_total 388
telemt_me_idle_close_by_peer_total 388
telemt_me_route_drop_no_conn_total 25555
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 105
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 388
telemt_me_writer_restored_same_endpoint_total 383
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 60546
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 677821348 (646.42 MB)
telemt_user_octets_to_client{user="hello"} 27111056892 (25.25 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 6753.4 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131683
telemt_connections_bad_total 1679
telemt_handshake_timeouts_total 2117
telemt_upstream_connect_attempt_total 1815
telemt_upstream_connect_success_total 1811
telemt_upstream_connect_attempts_per_request{bucket="1"} 1811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 38
telemt_me_reconnect_success_total 32
telemt_me_reader_eof_total 34
telemt_me_idle_close_by_peer_total 34
telemt_me_route_drop_no_conn_total 59455
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 197
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 128
telemt_me_writer_removed_unexpected_total 35
telemt_me_writer_restored_same_endpoint_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 118463
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 12377959820 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 63034103708 (58.71 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 93
```