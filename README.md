# Server Metrics 2026-03-06 16:47:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 23113.4 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691262
telemt_connections_bad_total 11194
telemt_handshake_timeouts_total 3136
telemt_upstream_connect_attempt_total 11317
telemt_upstream_connect_success_total 11249
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 11277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 2088
telemt_me_reconnect_success_total 2072
telemt_me_reader_eof_total 2174
telemt_me_idle_close_by_peer_total 2174
telemt_me_route_drop_no_conn_total 297483
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3513
telemt_desync_full_logged_total 845
telemt_desync_suppressed_total 2668
telemt_desync_frames_bucket_total{bucket="1_2"} 840
telemt_desync_frames_bucket_total{bucket="3_10"} 1221
telemt_desync_frames_bucket_total{bucket="gt_10"} 1452
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2176
telemt_me_writer_restored_same_endpoint_total 2066
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 595289
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 13161462376 (12.26 GB)
telemt_user_octets_to_client{user="hello"} 219218493424 (204.16 GB)
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 23113.5 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260525
telemt_connections_bad_total 948
telemt_handshake_timeouts_total 7693
telemt_upstream_connect_attempt_total 10658
telemt_upstream_connect_success_total 10633
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 10658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 958
telemt_me_reconnect_success_total 938
telemt_me_reader_eof_total 989
telemt_me_idle_close_by_peer_total 989
telemt_me_route_drop_no_conn_total 146264
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 845
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 304
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_me_writer_removed_unexpected_total 990
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 239467
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 2767565360 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 98186739624 (91.44 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 23113.3 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 514241
telemt_connections_bad_total 5481
telemt_handshake_timeouts_total 51737
telemt_upstream_connect_attempt_total 19595
telemt_upstream_connect_success_total 19508
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 19578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 270
telemt_me_reconnect_attempts_total 6652
telemt_me_reconnect_success_total 6624
telemt_me_reader_eof_total 7025
telemt_me_idle_close_by_peer_total 7025
telemt_me_route_drop_no_conn_total 264629
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1139
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 800
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 433
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 7037
telemt_me_writer_restored_same_endpoint_total 6617
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 440784
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 6366725260 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 136526613168 (127.15 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 22429.4 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487239
telemt_connections_bad_total 167561
telemt_handshake_timeouts_total 12075
telemt_upstream_connect_attempt_total 13409
telemt_upstream_connect_success_total 13407
telemt_upstream_connect_attempts_per_request{bucket="1"} 13407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5632
telemt_me_keepalive_timeout_total 171
telemt_me_reconnect_attempts_total 3121
telemt_me_reconnect_success_total 3101
telemt_me_reader_eof_total 3208
telemt_me_idle_close_by_peer_total 3208
telemt_me_route_drop_no_conn_total 151851
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 354
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 3214
telemt_me_writer_restored_same_endpoint_total 3100
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 271013
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 4646494156 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 94725953848 (88.22 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 23113.6 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413792
telemt_connections_bad_total 11054
telemt_handshake_timeouts_total 3738
telemt_upstream_connect_attempt_total 10130
telemt_upstream_connect_success_total 10115
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 165
telemt_me_reconnect_attempts_total 1773
telemt_me_reconnect_success_total 1755
telemt_me_reader_eof_total 1850
telemt_me_idle_close_by_peer_total 1849
telemt_me_route_drop_no_conn_total 200756
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 781
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 504
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1854
telemt_me_writer_restored_same_endpoint_total 1752
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 379786
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 15577328316 (14.51 GB)
telemt_user_octets_to_client{user="hello"} 195031899088 (181.64 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 84
```