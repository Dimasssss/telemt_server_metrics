# Server Metrics 2026-03-06 15:09:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 17241.9 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510390
telemt_connections_bad_total 3913
telemt_handshake_timeouts_total 2701
telemt_upstream_connect_attempt_total 8801
telemt_upstream_connect_success_total 8747
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 8771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 1838
telemt_me_reconnect_success_total 1828
telemt_me_reader_eof_total 1923
telemt_me_idle_close_by_peer_total 1923
telemt_me_route_drop_no_conn_total 184204
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2748
telemt_desync_full_logged_total 674
telemt_desync_suppressed_total 2074
telemt_desync_frames_bucket_total{bucket="1_2"} 647
telemt_desync_frames_bucket_total{bucket="3_10"} 918
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1925
telemt_me_writer_restored_same_endpoint_total 1822
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 438360
telemt_user_connections_current{user="hello"} 1167
telemt_user_octets_from_client{user="hello"} 11454757996 (10.67 GB)
telemt_user_octets_to_client{user="hello"} 174118244452 (162.16 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 17242.0 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195743
telemt_connections_bad_total 857
telemt_handshake_timeouts_total 6075
telemt_upstream_connect_attempt_total 7975
telemt_upstream_connect_success_total 7955
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 7975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 732
telemt_me_reconnect_success_total 718
telemt_me_reader_eof_total 763
telemt_me_idle_close_by_peer_total 763
telemt_me_route_drop_no_conn_total 98947
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 688
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 763
telemt_me_writer_restored_same_endpoint_total 718
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 180074
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 1995105364 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 79109454940 (73.68 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 17241.7 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393619
telemt_connections_bad_total 5264
telemt_handshake_timeouts_total 37177
telemt_upstream_connect_attempt_total 15211
telemt_upstream_connect_success_total 15142
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 15199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 5324
telemt_me_reconnect_success_total 5305
telemt_me_reader_eof_total 5620
telemt_me_idle_close_by_peer_total 5620
telemt_me_route_drop_no_conn_total 189743
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 707
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 491
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 2
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5624
telemt_me_writer_restored_same_endpoint_total 5300
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 338411
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 3604576568 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 107522278640 (100.14 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 16557.8 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292369
telemt_connections_bad_total 58461
telemt_handshake_timeouts_total 10137
telemt_upstream_connect_attempt_total 9243
telemt_upstream_connect_success_total 9243
telemt_upstream_connect_attempts_per_request{bucket="1"} 9243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3660
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 1925
telemt_me_reconnect_success_total 1912
telemt_me_reader_eof_total 1947
telemt_me_idle_close_by_peer_total 1947
telemt_me_route_drop_no_conn_total 100380
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 276
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 179
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1947
telemt_me_writer_restored_same_endpoint_total 1912
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 189918
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 2278063696 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 71345221064 (66.45 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 17242.0 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308146
telemt_connections_bad_total 9471
telemt_handshake_timeouts_total 2699
telemt_upstream_connect_attempt_total 8302
telemt_upstream_connect_success_total 8290
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 1670
telemt_me_reconnect_success_total 1656
telemt_me_reader_eof_total 1750
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 161717
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 537
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1754
telemt_me_writer_restored_same_endpoint_total 1655
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 282374
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 14673461436 (13.67 GB)
telemt_user_octets_to_client{user="hello"} 155480281316 (144.80 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 102
```