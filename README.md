# Server Metrics 2026-03-06 11:59:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 5831.0 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195904
telemt_connections_bad_total 397
telemt_handshake_timeouts_total 1020
telemt_upstream_connect_attempt_total 1960
telemt_upstream_connect_success_total 1940
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 87
telemt_me_reconnect_success_total 89
telemt_me_reader_eof_total 87
telemt_me_idle_close_by_peer_total 87
telemt_me_route_drop_no_conn_total 49814
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 783
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 600
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_restored_same_endpoint_total 83
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 139954
telemt_user_connections_current{user="hello"} 1055
telemt_user_octets_from_client{user="hello"} 3491912376 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 55908574748 (52.07 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 5831.0 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63412
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 2571
telemt_upstream_connect_attempt_total 2354
telemt_upstream_connect_success_total 2346
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 102
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 104
telemt_me_idle_close_by_peer_total 104
telemt_me_route_drop_no_conn_total 23013
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 231
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 104
telemt_me_writer_restored_same_endpoint_total 101
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 56027
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 571714140 (545.23 MB)
telemt_user_octets_to_client{user="hello"} 24783571060 (23.08 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 5830.7 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114303
telemt_connections_bad_total 508
telemt_handshake_timeouts_total 10062
telemt_upstream_connect_attempt_total 3384
telemt_upstream_connect_success_total 3370
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 726
telemt_me_reconnect_success_total 724
telemt_me_reader_eof_total 752
telemt_me_idle_close_by_peer_total 752
telemt_me_route_drop_no_conn_total 44772
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 211
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_me_writer_removed_unexpected_total 752
telemt_me_writer_restored_same_endpoint_total 719
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 100972
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 1081805136 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 36485340068 (33.98 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 5146.8 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57595
telemt_connections_bad_total 4601
telemt_handshake_timeouts_total 1329
telemt_upstream_connect_attempt_total 2546
telemt_upstream_connect_success_total 2546
telemt_upstream_connect_attempts_per_request{bucket="1"} 2546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1053
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 372
telemt_me_reconnect_success_total 369
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 19693
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 374
telemt_me_writer_restored_same_endpoint_total 369
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 50584
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 600286184 (572.48 MB)
telemt_user_octets_to_client{user="hello"} 20791283052 (19.36 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 5831.2 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113416
telemt_connections_bad_total 794
telemt_handshake_timeouts_total 1997
telemt_upstream_connect_attempt_total 1460
telemt_upstream_connect_success_total 1459
telemt_upstream_connect_attempts_per_request{bucket="1"} 1459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 18
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 45518
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 163
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 89
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_restored_same_endpoint_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 102378
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 11456462276 (10.67 GB)
telemt_user_octets_to_client{user="hello"} 54703118644 (50.95 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 99
```