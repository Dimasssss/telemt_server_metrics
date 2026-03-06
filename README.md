# Server Metrics 2026-03-06 14:38:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 15381.2 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458153
telemt_connections_bad_total 2125
telemt_handshake_timeouts_total 2510
telemt_upstream_connect_attempt_total 8122
telemt_upstream_connect_success_total 8072
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 1830
telemt_me_reconnect_success_total 1820
telemt_me_reader_eof_total 1915
telemt_me_idle_close_by_peer_total 1915
telemt_me_route_drop_no_conn_total 163399
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2480
telemt_desync_full_logged_total 604
telemt_desync_suppressed_total 1876
telemt_desync_frames_bucket_total{bucket="1_2"} 585
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 1060
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1917
telemt_me_writer_restored_same_endpoint_total 1814
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 389961
telemt_user_connections_current{user="hello"} 1264
telemt_user_octets_from_client{user="hello"} 10918630012 (10.17 GB)
telemt_user_octets_to_client{user="hello"} 158451553948 (147.57 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 15381.0 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175202
telemt_connections_bad_total 831
telemt_handshake_timeouts_total 5642
telemt_upstream_connect_attempt_total 6632
telemt_upstream_connect_success_total 6616
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3522
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 611
telemt_me_reconnect_success_total 601
telemt_me_reader_eof_total 643
telemt_me_idle_close_by_peer_total 643
telemt_me_route_drop_no_conn_total 87684
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 634
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 429
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 643
telemt_me_writer_restored_same_endpoint_total 601
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 160501
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 1765970900 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 73931908560 (68.85 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 15380.7 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359035
telemt_connections_bad_total 5228
telemt_handshake_timeouts_total 35973
telemt_upstream_connect_attempt_total 11934
telemt_upstream_connect_success_total 11881
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 11926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5457
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 3694
telemt_me_reconnect_success_total 3680
telemt_me_reader_eof_total 3904
telemt_me_idle_close_by_peer_total 3904
telemt_me_route_drop_no_conn_total 171057
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 607
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 3906
telemt_me_writer_restored_same_endpoint_total 3675
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 305721
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 3206741064 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 97752506844 (91.04 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 14697.0 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261409
telemt_connections_bad_total 51733
telemt_handshake_timeouts_total 9395
telemt_upstream_connect_attempt_total 7467
telemt_upstream_connect_success_total 7467
telemt_upstream_connect_attempts_per_request{bucket="1"} 7467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3055
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 1146
telemt_me_reconnect_success_total 1134
telemt_me_reader_eof_total 1154
telemt_me_idle_close_by_peer_total 1154
telemt_me_route_drop_no_conn_total 90881
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 266
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 1154
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 166921
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 2007852848 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 63212438508 (58.87 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 15381.1 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275625
telemt_connections_bad_total 7893
telemt_handshake_timeouts_total 2579
telemt_upstream_connect_attempt_total 7793
telemt_upstream_connect_success_total 7782
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 1663
telemt_me_reconnect_success_total 1650
telemt_me_reader_eof_total 1744
telemt_me_idle_close_by_peer_total 1743
telemt_me_route_drop_no_conn_total 149238
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 465
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 305
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 4
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1748
telemt_me_writer_restored_same_endpoint_total 1649
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 252175
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 14315067444 (13.33 GB)
telemt_user_octets_to_client{user="hello"} 142704675308 (132.90 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 96
```