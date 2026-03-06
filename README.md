# Server Metrics 2026-03-06 11:23:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 3675.2 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129090
telemt_connections_bad_total 198
telemt_handshake_timeouts_total 718
telemt_upstream_connect_attempt_total 966
telemt_upstream_connect_success_total 955
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 14
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 13
telemt_me_idle_close_by_peer_total 13
telemt_me_route_drop_no_conn_total 29600
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 334
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 252
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 13
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 89398
telemt_user_connections_current{user="hello"} 1008
telemt_user_octets_from_client{user="hello"} 2641465268 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 29282989768 (27.27 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 3675.1 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37419
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 806
telemt_upstream_connect_attempt_total 1008
telemt_upstream_connect_success_total 1005
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 475
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 14
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 14
telemt_me_idle_close_by_peer_total 14
telemt_me_route_drop_no_conn_total 14839
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 142
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 14
telemt_me_writer_restored_same_endpoint_total 14
telemt_user_connections_total{user="hello"} 35396
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 367794600 (350.76 MB)
telemt_user_octets_to_client{user="hello"} 13489202608 (12.56 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 3675.0 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68466
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 3109
telemt_upstream_connect_attempt_total 1458
telemt_upstream_connect_success_total 1448
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 641
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 92
telemt_me_reconnect_success_total 93
telemt_me_reader_eof_total 94
telemt_me_idle_close_by_peer_total 94
telemt_me_route_drop_no_conn_total 26945
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 132
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_me_writer_removed_unexpected_total 94
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 63394
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 741091732 (706.76 MB)
telemt_user_octets_to_client{user="hello"} 17411722652 (16.22 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 2991.1 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33130
telemt_connections_bad_total 2670
telemt_handshake_timeouts_total 852
telemt_upstream_connect_attempt_total 1513
telemt_upstream_connect_success_total 1513
telemt_upstream_connect_attempts_per_request{bucket="1"} 1513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 612
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 190
telemt_me_reconnect_success_total 188
telemt_me_reader_eof_total 192
telemt_me_idle_close_by_peer_total 192
telemt_me_route_drop_no_conn_total 11986
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_me_writer_removed_unexpected_total 192
telemt_me_writer_restored_same_endpoint_total 188
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 28876
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 231747464 (221.01 MB)
telemt_user_octets_to_client{user="hello"} 7334400996 (6.83 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 3675.2 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72291
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 1567
telemt_upstream_connect_attempt_total 688
telemt_upstream_connect_success_total 687
telemt_upstream_connect_attempts_per_request{bucket="1"} 687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 22577
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 86
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 66250
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 11143267936 (10.38 GB)
telemt_user_octets_to_client{user="hello"} 27967497572 (26.05 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 85
```