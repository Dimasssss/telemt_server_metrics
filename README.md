# Server Metrics 2026-03-06 16:57:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 23730.3 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 709496
telemt_connections_bad_total 11246
telemt_handshake_timeouts_total 3165
telemt_upstream_connect_attempt_total 11773
telemt_upstream_connect_success_total 11701
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 11731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2194
telemt_me_reconnect_success_total 2177
telemt_me_reader_eof_total 2282
telemt_me_idle_close_by_peer_total 2282
telemt_me_route_drop_no_conn_total 304534
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3589
telemt_desync_full_logged_total 863
telemt_desync_suppressed_total 2726
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 1244
telemt_desync_frames_bucket_total{bucket="gt_10"} 1483
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2285
telemt_me_writer_restored_same_endpoint_total 2171
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 609159
telemt_user_connections_current{user="hello"} 1033
telemt_user_octets_from_client{user="hello"} 13276364584 (12.36 GB)
telemt_user_octets_to_client{user="hello"} 222744157684 (207.45 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 23730.2 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266464
telemt_connections_bad_total 957
telemt_handshake_timeouts_total 7951
telemt_upstream_connect_attempt_total 10909
telemt_upstream_connect_success_total 10878
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 10908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 960
telemt_me_reconnect_success_total 939
telemt_me_reader_eof_total 991
telemt_me_idle_close_by_peer_total 991
telemt_me_route_drop_no_conn_total 148767
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 854
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_me_writer_removed_unexpected_total 992
telemt_me_writer_restored_same_endpoint_total 939
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 244977
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 2866612896 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 99464252280 (92.63 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 23730.1 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523965
telemt_connections_bad_total 5482
telemt_handshake_timeouts_total 51970
telemt_upstream_connect_attempt_total 20421
telemt_upstream_connect_success_total 20320
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 20392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 295
telemt_me_reconnect_attempts_total 6962
telemt_me_reconnect_success_total 6934
telemt_me_reader_eof_total 7361
telemt_me_idle_close_by_peer_total 7361
telemt_me_route_drop_no_conn_total 273696
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1205
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 846
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 461
telemt_desync_frames_bucket_total{bucket="gt_10"} 469
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 7376
telemt_me_writer_restored_same_endpoint_total 6927
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 449856
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 6466932208 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 138537610076 (129.02 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 23046.3 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499789
telemt_connections_bad_total 171751
telemt_handshake_timeouts_total 12616
telemt_upstream_connect_attempt_total 14298
telemt_upstream_connect_success_total 14296
telemt_upstream_connect_attempts_per_request{bucket="1"} 14296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6087
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 3512
telemt_me_reconnect_success_total 3491
telemt_me_reader_eof_total 3642
telemt_me_idle_close_by_peer_total 3642
telemt_me_route_drop_no_conn_total 157863
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 355
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 3648
telemt_me_writer_restored_same_endpoint_total 3490
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 278716
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 4721116636 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 97140583812 (90.47 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 23730.3 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425293
telemt_connections_bad_total 11056
telemt_handshake_timeouts_total 3832
telemt_upstream_connect_attempt_total 10428
telemt_upstream_connect_success_total 10411
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 171
telemt_me_reconnect_attempts_total 1778
telemt_me_reconnect_success_total 1759
telemt_me_reader_eof_total 1858
telemt_me_idle_close_by_peer_total 1857
telemt_me_route_drop_no_conn_total 209553
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 832
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 539
telemt_desync_frames_bucket_total{bucket="1_2"} 372
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1862
telemt_me_writer_restored_same_endpoint_total 1756
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 390716
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 18020087712 (16.78 GB)
telemt_user_octets_to_client{user="hello"} 198561206184 (184.92 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 80
```