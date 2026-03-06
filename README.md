# Server Metrics 2026-03-06 14:43:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 15689.3 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466832
telemt_connections_bad_total 2410
telemt_handshake_timeouts_total 2551
telemt_upstream_connect_attempt_total 8239
telemt_upstream_connect_success_total 8189
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 1830
telemt_me_reconnect_success_total 1820
telemt_me_reader_eof_total 1915
telemt_me_idle_close_by_peer_total 1915
telemt_me_route_drop_no_conn_total 166216
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2541
telemt_desync_full_logged_total 620
telemt_desync_suppressed_total 1921
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 859
telemt_desync_frames_bucket_total{bucket="gt_10"} 1076
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1917
telemt_me_writer_restored_same_endpoint_total 1814
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 398096
telemt_user_connections_current{user="hello"} 1273
telemt_user_octets_from_client{user="hello"} 11037943836 (10.28 GB)
telemt_user_octets_to_client{user="hello"} 161651162792 (150.55 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 15689.3 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178430
telemt_connections_bad_total 846
telemt_handshake_timeouts_total 5738
telemt_upstream_connect_attempt_total 6818
telemt_upstream_connect_success_total 6802
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3619
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 617
telemt_me_reconnect_success_total 607
telemt_me_reader_eof_total 649
telemt_me_idle_close_by_peer_total 649
telemt_me_route_drop_no_conn_total 89571
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 672
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 649
telemt_me_writer_restored_same_endpoint_total 607
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 163542
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 1828075344 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 74854208452 (69.71 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 15689.1 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365069
telemt_connections_bad_total 5228
telemt_handshake_timeouts_total 36183
telemt_upstream_connect_attempt_total 12444
telemt_upstream_connect_success_total 12391
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 12436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 167
telemt_me_reconnect_attempts_total 3927
telemt_me_reconnect_success_total 3912
telemt_me_reader_eof_total 4153
telemt_me_idle_close_by_peer_total 4153
telemt_me_route_drop_no_conn_total 173992
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 643
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 4155
telemt_me_writer_restored_same_endpoint_total 3907
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 311416
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 3330320872 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 99544703664 (92.71 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 15005.2 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269296
telemt_connections_bad_total 55231
telemt_handshake_timeouts_total 9502
telemt_upstream_connect_attempt_total 7740
telemt_upstream_connect_success_total 7740
telemt_upstream_connect_attempts_per_request{bucket="1"} 7740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3140
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 1272
telemt_me_reconnect_success_total 1260
telemt_me_reader_eof_total 1281
telemt_me_idle_close_by_peer_total 1281
telemt_me_route_drop_no_conn_total 92415
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
telemt_me_writer_removed_unexpected_total 1281
telemt_me_writer_restored_same_endpoint_total 1260
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 171137
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 2057882632 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 64440059348 (60.01 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 15689.4 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280877
telemt_connections_bad_total 8253
telemt_handshake_timeouts_total 2591
telemt_upstream_connect_attempt_total 7839
telemt_upstream_connect_success_total 7828
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 1663
telemt_me_reconnect_success_total 1650
telemt_me_reader_eof_total 1744
telemt_me_idle_close_by_peer_total 1743
telemt_me_route_drop_no_conn_total 151095
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 482
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1748
telemt_me_writer_restored_same_endpoint_total 1649
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 256911
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 14361450948 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 144042322828 (134.15 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 96
```