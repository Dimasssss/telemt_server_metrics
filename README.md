# Server Metrics 2026-03-06 12:55:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 9220.5 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288046
telemt_connections_bad_total 1648
telemt_handshake_timeouts_total 1576
telemt_upstream_connect_attempt_total 3228
telemt_upstream_connect_success_total 3200
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 154
telemt_me_reconnect_success_total 150
telemt_me_reader_eof_total 155
telemt_me_idle_close_by_peer_total 155
telemt_me_route_drop_no_conn_total 85279
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1491
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 1132
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 606
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 155
telemt_me_writer_restored_same_endpoint_total 144
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 227298
telemt_user_connections_current{user="hello"} 1135
telemt_user_octets_from_client{user="hello"} 4436057088 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 95271700464 (88.73 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 9220.3 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106438
telemt_connections_bad_total 789
telemt_handshake_timeouts_total 3807
telemt_upstream_connect_attempt_total 4025
telemt_upstream_connect_success_total 4015
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 4025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 528
telemt_me_reconnect_success_total 524
telemt_me_reader_eof_total 560
telemt_me_idle_close_by_peer_total 560
telemt_me_route_drop_no_conn_total 40303
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 338
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 560
telemt_me_writer_restored_same_endpoint_total 524
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 95259
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 988651172 (942.85 MB)
telemt_user_octets_to_client{user="hello"} 42991239100 (40.04 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 9220.3 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211773
telemt_connections_bad_total 2824
telemt_handshake_timeouts_total 14462
telemt_upstream_connect_attempt_total 5474
telemt_upstream_connect_success_total 5443
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 1454
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1520
telemt_me_idle_close_by_peer_total 1520
telemt_me_route_drop_no_conn_total 95041
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 266
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 334
telemt_me_writer_removed_unexpected_total 1521
telemt_me_writer_restored_same_endpoint_total 1445
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 186896
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 1976906092 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 59023390500 (54.97 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 8536.2 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115896
telemt_connections_bad_total 24457
telemt_handshake_timeouts_total 2422
telemt_upstream_connect_attempt_total 4629
telemt_upstream_connect_success_total 4629
telemt_upstream_connect_attempts_per_request{bucket="1"} 4629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1975
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 719
telemt_me_reconnect_success_total 714
telemt_me_reader_eof_total 725
telemt_me_idle_close_by_peer_total 725
telemt_me_route_drop_no_conn_total 38604
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 725
telemt_me_writer_restored_same_endpoint_total 714
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 87277
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 1164727124 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 36743180304 (34.22 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 9220.6 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173412
telemt_connections_bad_total 4841
telemt_handshake_timeouts_total 2326
telemt_upstream_connect_attempt_total 2764
telemt_upstream_connect_success_total 2758
telemt_upstream_connect_attempts_per_request{bucket="1"} 2758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 110
telemt_me_reconnect_success_total 104
telemt_me_reader_eof_total 109
telemt_me_idle_close_by_peer_total 109
telemt_me_route_drop_no_conn_total 80029
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 270
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 110
telemt_me_writer_restored_same_endpoint_total 103
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 155623
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 13599204220 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 91171901844 (84.91 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 117
```