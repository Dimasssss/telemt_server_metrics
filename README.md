# Server Metrics 2026-03-06 12:45:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 8604.1 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270868
telemt_connections_bad_total 1640
telemt_handshake_timeouts_total 1474
telemt_upstream_connect_attempt_total 2916
telemt_upstream_connect_success_total 2889
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 129
telemt_me_reconnect_success_total 125
telemt_me_reader_eof_total 128
telemt_me_idle_close_by_peer_total 128
telemt_me_route_drop_no_conn_total 78993
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1368
telemt_desync_full_logged_total 325
telemt_desync_suppressed_total 1043
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 491
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 128
telemt_me_writer_restored_same_endpoint_total 119
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 211396
telemt_user_connections_current{user="hello"} 1372
telemt_user_octets_from_client{user="hello"} 4213938568 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 89427194788 (83.29 GB)
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 8603.9 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98262
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 3693
telemt_upstream_connect_attempt_total 3909
telemt_upstream_connect_success_total 3899
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 525
telemt_me_reconnect_success_total 522
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 36605
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 319
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 208
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 558
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 87815
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 920710404 (878.06 MB)
telemt_user_octets_to_client{user="hello"} 40340068156 (37.57 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 8603.9 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192532
telemt_connections_bad_total 2396
telemt_handshake_timeouts_total 13854
telemt_upstream_connect_attempt_total 5277
telemt_upstream_connect_success_total 5248
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 1452
telemt_me_reconnect_success_total 1448
telemt_me_reader_eof_total 1518
telemt_me_idle_close_by_peer_total 1518
telemt_me_route_drop_no_conn_total 84299
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1519
telemt_me_writer_restored_same_endpoint_total 1443
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 169821
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 1815645156 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 55543435956 (51.73 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 7920.0 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101930
telemt_connections_bad_total 18074
telemt_handshake_timeouts_total 2263
telemt_upstream_connect_attempt_total 4337
telemt_upstream_connect_success_total 4337
telemt_upstream_connect_attempts_per_request{bucket="1"} 4337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1845
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 652
telemt_me_reconnect_success_total 647
telemt_me_reader_eof_total 657
telemt_me_idle_close_by_peer_total 657
telemt_me_route_drop_no_conn_total 35146
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 142
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 657
telemt_me_writer_restored_same_endpoint_total 647
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 79993
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 995359384 (949.25 MB)
telemt_user_octets_to_client{user="hello"} 35033753356 (32.63 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 8604.0 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163114
telemt_connections_bad_total 3858
telemt_handshake_timeouts_total 2247
telemt_upstream_connect_attempt_total 2601
telemt_upstream_connect_success_total 2596
telemt_upstream_connect_attempts_per_request{bucket="1"} 2596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 103
telemt_me_reconnect_success_total 96
telemt_me_reader_eof_total 100
telemt_me_idle_close_by_peer_total 100
telemt_me_route_drop_no_conn_total 75783
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 251
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_restored_same_endpoint_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 146708
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 13496558556 (12.57 GB)
telemt_user_octets_to_client{user="hello"} 84172648052 (78.39 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 135
```