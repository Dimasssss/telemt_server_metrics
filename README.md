# Server Metrics 2026-03-06 15:14:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 17569.9 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520099
telemt_connections_bad_total 4224
telemt_handshake_timeouts_total 2732
telemt_upstream_connect_attempt_total 8968
telemt_upstream_connect_success_total 8911
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 8935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1857
telemt_me_reconnect_success_total 1847
telemt_me_reader_eof_total 1942
telemt_me_idle_close_by_peer_total 1942
telemt_me_route_drop_no_conn_total 187201
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2796
telemt_desync_full_logged_total 684
telemt_desync_suppressed_total 2112
telemt_desync_frames_bucket_total{bucket="1_2"} 661
telemt_desync_frames_bucket_total{bucket="3_10"} 939
telemt_desync_frames_bucket_total{bucket="gt_10"} 1196
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1944
telemt_me_writer_restored_same_endpoint_total 1841
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 446517
telemt_user_connections_current{user="hello"} 1077
telemt_user_octets_from_client{user="hello"} 11543715180 (10.75 GB)
telemt_user_octets_to_client{user="hello"} 176625569368 (164.50 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 17548.9 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198796
telemt_connections_bad_total 860
telemt_handshake_timeouts_total 6248
telemt_upstream_connect_attempt_total 8291
telemt_upstream_connect_success_total 8271
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4306
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 807
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 839
telemt_me_idle_close_by_peer_total 839
telemt_me_route_drop_no_conn_total 100245
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 700
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 839
telemt_me_writer_restored_same_endpoint_total 793
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 182884
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 2077632980 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 80089510404 (74.59 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 17548.8 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399499
telemt_connections_bad_total 5288
telemt_handshake_timeouts_total 37212
telemt_upstream_connect_attempt_total 15277
telemt_upstream_connect_success_total 15208
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 15265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 5328
telemt_me_reconnect_success_total 5308
telemt_me_reader_eof_total 5623
telemt_me_idle_close_by_peer_total 5623
telemt_me_route_drop_no_conn_total 191550
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 727
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 506
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5627
telemt_me_writer_restored_same_endpoint_total 5303
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 344136
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 3677596572 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 109356764908 (101.85 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 16864.7 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296451
telemt_connections_bad_total 58726
telemt_handshake_timeouts_total 10235
telemt_upstream_connect_attempt_total 9279
telemt_upstream_connect_success_total 9279
telemt_upstream_connect_attempts_per_request{bucket="1"} 9279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3681
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 1925
telemt_me_reconnect_success_total 1912
telemt_me_reader_eof_total 1947
telemt_me_idle_close_by_peer_total 1947
telemt_me_route_drop_no_conn_total 101481
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 279
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1947
telemt_me_writer_restored_same_endpoint_total 1912
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 193545
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 2330478700 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 72638430064 (67.65 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 17549.1 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312530
telemt_connections_bad_total 9697
telemt_handshake_timeouts_total 2708
telemt_upstream_connect_attempt_total 8459
telemt_upstream_connect_success_total 8447
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 1690
telemt_me_reconnect_success_total 1676
telemt_me_reader_eof_total 1770
telemt_me_idle_close_by_peer_total 1769
telemt_me_route_drop_no_conn_total 163408
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 549
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 353
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1774
telemt_me_writer_restored_same_endpoint_total 1675
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 286432
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 14713305912 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 157292799152 (146.49 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 90
```