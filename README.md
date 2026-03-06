# Server Metrics 2026-03-06 13:21:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 10763.2 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329889
telemt_connections_bad_total 1660
telemt_handshake_timeouts_total 1786
telemt_upstream_connect_attempt_total 4159
telemt_upstream_connect_success_total 4127
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 341
telemt_me_reconnect_success_total 336
telemt_me_reader_eof_total 345
telemt_me_idle_close_by_peer_total 345
telemt_me_route_drop_no_conn_total 101824
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1766
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 1341
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 610
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 345
telemt_me_writer_restored_same_endpoint_total 330
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 266595
telemt_user_connections_current{user="hello"} 1186
telemt_user_octets_from_client{user="hello"} 5126276600 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 113614768400 (105.81 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 10763.1 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122923
telemt_connections_bad_total 806
telemt_handshake_timeouts_total 4085
telemt_upstream_connect_attempt_total 4559
telemt_upstream_connect_success_total 4546
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2491
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 534
telemt_me_reconnect_success_total 529
telemt_me_reader_eof_total 567
telemt_me_idle_close_by_peer_total 567
telemt_me_route_drop_no_conn_total 49181
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 367
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 567
telemt_me_writer_restored_same_endpoint_total 529
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 110993
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 1151959504 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 52504909396 (48.90 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 10763.0 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255355
telemt_connections_bad_total 3919
telemt_handshake_timeouts_total 20465
telemt_upstream_connect_attempt_total 6111
telemt_upstream_connect_success_total 6078
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 1478
telemt_me_reconnect_success_total 1472
telemt_me_reader_eof_total 1545
telemt_me_idle_close_by_peer_total 1545
telemt_me_route_drop_no_conn_total 119354
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 361
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 256
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 1546
telemt_me_writer_restored_same_endpoint_total 1467
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 222076
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 2242526064 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 72720683352 (67.73 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 10079.2 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142889
telemt_connections_bad_total 31842
telemt_handshake_timeouts_total 2849
telemt_upstream_connect_attempt_total 5158
telemt_upstream_connect_success_total 5158
telemt_upstream_connect_attempts_per_request{bucket="1"} 5158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2194
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 735
telemt_me_reconnect_success_total 728
telemt_me_reader_eof_total 740
telemt_me_idle_close_by_peer_total 740
telemt_me_route_drop_no_conn_total 57830
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 192
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_restored_same_endpoint_total 728
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 106134
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 1320159132 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 44233378780 (41.20 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 10763.3 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201792
telemt_connections_bad_total 7279
telemt_handshake_timeouts_total 2386
telemt_upstream_connect_attempt_total 3422
telemt_upstream_connect_success_total 3416
telemt_upstream_connect_attempts_per_request{bucket="1"} 3416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 161
telemt_me_reconnect_success_total 154
telemt_me_reader_eof_total 160
telemt_me_idle_close_by_peer_total 160
telemt_me_route_drop_no_conn_total 103346
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 312
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 161
telemt_me_writer_restored_same_endpoint_total 153
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 180950
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 13770531812 (12.82 GB)
telemt_user_octets_to_client{user="hello"} 103957786064 (96.82 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 85
```