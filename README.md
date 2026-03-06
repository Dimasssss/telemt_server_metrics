# Server Metrics 2026-03-06 12:29:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 7676.1 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246415
telemt_connections_bad_total 1248
telemt_handshake_timeouts_total 1380
telemt_upstream_connect_attempt_total 2505
telemt_upstream_connect_success_total 2482
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 104
telemt_me_idle_close_by_peer_total 104
telemt_me_route_drop_no_conn_total 69943
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1196
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 915
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 433
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 104
telemt_me_writer_restored_same_endpoint_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 188014
telemt_user_connections_current{user="hello"} 1236
telemt_user_octets_from_client{user="hello"} 3986086476 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 80155468444 (74.65 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 7676.2 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84941
telemt_connections_bad_total 590
telemt_handshake_timeouts_total 3277
telemt_upstream_connect_attempt_total 3837
telemt_upstream_connect_success_total 3828
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2094
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 525
telemt_me_reconnect_success_total 522
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 32628
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 281
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 2
telemt_pool_force_close_total 76
telemt_me_writer_removed_unexpected_total 558
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 75910
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 832577600 (794.01 MB)
telemt_user_octets_to_client{user="hello"} 36271009768 (33.78 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 7676.0 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160591
telemt_connections_bad_total 1739
telemt_handshake_timeouts_total 12452
telemt_upstream_connect_attempt_total 5151
telemt_upstream_connect_success_total 5131
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 1452
telemt_me_reconnect_success_total 1448
telemt_me_reader_eof_total 1518
telemt_me_idle_close_by_peer_total 1518
telemt_me_route_drop_no_conn_total 74178
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 247
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 110
telemt_me_writer_removed_unexpected_total 1519
telemt_me_writer_restored_same_endpoint_total 1443
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 142113
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 1570084732 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 50692067424 (47.21 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 6992.1 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86524
telemt_connections_bad_total 13168
telemt_handshake_timeouts_total 1888
telemt_upstream_connect_attempt_total 3568
telemt_upstream_connect_success_total 3568
telemt_upstream_connect_attempts_per_request{bucket="1"} 3568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1527
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 464
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 466
telemt_me_idle_close_by_peer_total 466
telemt_me_route_drop_no_conn_total 30408
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 113
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_restored_same_endpoint_total 460
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 70044
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 756711864 (721.66 MB)
telemt_user_octets_to_client{user="hello"} 30728684172 (28.62 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 7676.4 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148031
telemt_connections_bad_total 2551
telemt_handshake_timeouts_total 2192
telemt_upstream_connect_attempt_total 2233
telemt_upstream_connect_success_total 2229
telemt_upstream_connect_attempts_per_request{bucket="1"} 2229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 48
telemt_me_reconnect_success_total 42
telemt_me_reader_eof_total 44
telemt_me_idle_close_by_peer_total 44
telemt_me_route_drop_no_conn_total 68521
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 230
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 153
telemt_me_writer_removed_unexpected_total 45
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 133387
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 13214192536 (12.31 GB)
telemt_user_octets_to_client{user="hello"} 74474547332 (69.36 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 98
```