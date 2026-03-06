# Server Metrics 2026-03-06 12:09:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 6446.0 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213000
telemt_connections_bad_total 501
telemt_handshake_timeouts_total 1228
telemt_upstream_connect_attempt_total 2078
telemt_upstream_connect_success_total 2056
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 87
telemt_me_reconnect_success_total 89
telemt_me_reader_eof_total 87
telemt_me_idle_close_by_peer_total 87
telemt_me_route_drop_no_conn_total 56355
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 923
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 704
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 342
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_restored_same_endpoint_total 83
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 156348
telemt_user_connections_current{user="hello"} 1216
telemt_user_octets_from_client{user="hello"} 3606941476 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 64447441124 (60.02 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 6445.8 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70099
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 2778
telemt_upstream_connect_attempt_total 2912
telemt_upstream_connect_success_total 2904
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1539
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 247
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 26304
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 239
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 259
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 62369
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 627414864 (598.35 MB)
telemt_user_octets_to_client{user="hello"} 29904753720 (27.85 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 6445.7 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128111
telemt_connections_bad_total 700
telemt_handshake_timeouts_total 10493
telemt_upstream_connect_attempt_total 4060
telemt_upstream_connect_success_total 4042
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1012
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 1059
telemt_me_idle_close_by_peer_total 1059
telemt_me_route_drop_no_conn_total 56522
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 219
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 1060
telemt_me_writer_restored_same_endpoint_total 1003
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 113777
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 1260075000 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 40931737068 (38.12 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 5761.8 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65811
telemt_connections_bad_total 5728
telemt_handshake_timeouts_total 1474
telemt_upstream_connect_attempt_total 2849
telemt_upstream_connect_success_total 2849
telemt_upstream_connect_attempts_per_request{bucket="1"} 2849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1198
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 379
telemt_me_reconnect_success_total 376
telemt_me_reader_eof_total 381
telemt_me_idle_close_by_peer_total 381
telemt_me_route_drop_no_conn_total 23644
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 101
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 381
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 57410
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 655569512 (625.20 MB)
telemt_user_octets_to_client{user="hello"} 25578825496 (23.82 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 6446.0 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125919
telemt_connections_bad_total 1391
telemt_handshake_timeouts_total 2105
telemt_upstream_connect_attempt_total 1681
telemt_upstream_connect_success_total 1677
telemt_upstream_connect_attempts_per_request{bucket="1"} 1677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 26
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 55027
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 191
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 114
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 113154
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 11892777696 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 60255966776 (56.12 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 115
```