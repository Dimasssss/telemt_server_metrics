# Server Metrics 2026-03-06 14:48:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 15996.4 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475648
telemt_connections_bad_total 2702
telemt_handshake_timeouts_total 2610
telemt_upstream_connect_attempt_total 8310
telemt_upstream_connect_success_total 8260
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1831
telemt_me_reconnect_success_total 1821
telemt_me_reader_eof_total 1916
telemt_me_idle_close_by_peer_total 1916
telemt_me_route_drop_no_conn_total 169241
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2594
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1962
telemt_desync_frames_bucket_total{bucket="1_2"} 620
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 1103
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1918
telemt_me_writer_restored_same_endpoint_total 1815
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 406287
telemt_user_connections_current{user="hello"} 1053
telemt_user_octets_from_client{user="hello"} 11112567860 (10.35 GB)
telemt_user_octets_to_client{user="hello"} 164859645948 (153.54 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 15996.3 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181590
telemt_connections_bad_total 852
telemt_handshake_timeouts_total 5884
telemt_upstream_connect_attempt_total 6999
telemt_upstream_connect_success_total 6983
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3707
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 634
telemt_me_reconnect_success_total 622
telemt_me_reader_eof_total 665
telemt_me_idle_close_by_peer_total 665
telemt_me_route_drop_no_conn_total 91053
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
telemt_me_writer_removed_unexpected_total 665
telemt_me_writer_restored_same_endpoint_total 622
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 166488
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 1874022644 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 75353427072 (70.18 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 15996.1 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370553
telemt_connections_bad_total 5245
telemt_handshake_timeouts_total 36346
telemt_upstream_connect_attempt_total 12947
telemt_upstream_connect_success_total 12892
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 12937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 4170
telemt_me_reconnect_success_total 4154
telemt_me_reader_eof_total 4401
telemt_me_idle_close_by_peer_total 4401
telemt_me_route_drop_no_conn_total 177254
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 663
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 4403
telemt_me_writer_restored_same_endpoint_total 4149
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 316604
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 3384010416 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 101323009236 (94.36 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 15312.3 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273625
telemt_connections_bad_total 55504
telemt_handshake_timeouts_total 9700
telemt_upstream_connect_attempt_total 7978
telemt_upstream_connect_success_total 7978
telemt_upstream_connect_attempts_per_request{bucket="1"} 7978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3224
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 1367
telemt_me_reconnect_success_total 1355
telemt_me_reader_eof_total 1380
telemt_me_idle_close_by_peer_total 1380
telemt_me_route_drop_no_conn_total 93951
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 267
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 1380
telemt_me_writer_restored_same_endpoint_total 1355
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 174709
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 2094833224 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 66125284292 (61.58 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 15996.4 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286834
telemt_connections_bad_total 9004
telemt_handshake_timeouts_total 2601
telemt_upstream_connect_attempt_total 7882
telemt_upstream_connect_success_total 7871
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 1664
telemt_me_reconnect_success_total 1651
telemt_me_reader_eof_total 1745
telemt_me_idle_close_by_peer_total 1744
telemt_me_route_drop_no_conn_total 152877
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 496
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1749
telemt_me_writer_restored_same_endpoint_total 1650
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 261995
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 14406043356 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 145234146092 (135.26 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 108
```