# Server Metrics 2026-03-06 14:12:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 13841.7 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413341
telemt_connections_bad_total 1838
telemt_handshake_timeouts_total 2253
telemt_upstream_connect_attempt_total 7307
telemt_upstream_connect_success_total 7259
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 1532
telemt_me_reconnect_success_total 1523
telemt_me_reader_eof_total 1596
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 144619
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2287
telemt_desync_full_logged_total 549
telemt_desync_suppressed_total 1738
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 780
telemt_desync_frames_bucket_total{bucket="gt_10"} 973
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 1598
telemt_me_writer_restored_same_endpoint_total 1517
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 346898
telemt_user_connections_current{user="hello"} 1263
telemt_user_octets_from_client{user="hello"} 10269459136 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 143867860268 (133.99 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 13841.7 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156750
telemt_connections_bad_total 820
telemt_handshake_timeouts_total 4927
telemt_upstream_connect_attempt_total 6056
telemt_upstream_connect_success_total 6040
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 596
telemt_me_reconnect_success_total 588
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 627
telemt_me_route_drop_no_conn_total 77479
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 602
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_restored_same_endpoint_total 588
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 143185
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 1580048008 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 67538460248 (62.90 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 13841.5 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330188
telemt_connections_bad_total 5111
telemt_handshake_timeouts_total 35060
telemt_upstream_connect_attempt_total 9597
telemt_upstream_connect_success_total 9549
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 9590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 2653
telemt_me_reconnect_success_total 2641
telemt_me_reader_eof_total 2789
telemt_me_idle_close_by_peer_total 2789
telemt_me_route_drop_no_conn_total 155072
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 559
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 2790
telemt_me_writer_restored_same_endpoint_total 2636
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 278392
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 2926939180 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 88866526044 (82.76 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 13157.6 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226489
telemt_connections_bad_total 41886
telemt_handshake_timeouts_total 7120
telemt_upstream_connect_attempt_total 6336
telemt_upstream_connect_success_total 6336
telemt_upstream_connect_attempts_per_request{bucket="1"} 6336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2651
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 807
telemt_me_reconnect_success_total 797
telemt_me_reader_eof_total 809
telemt_me_idle_close_by_peer_total 809
telemt_me_route_drop_no_conn_total 81866
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 250
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 809
telemt_me_writer_restored_same_endpoint_total 797
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 147682
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 1744346820 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 57723198908 (53.76 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 13841.7 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249923
telemt_connections_bad_total 7888
telemt_handshake_timeouts_total 2513
telemt_upstream_connect_attempt_total 5925
telemt_upstream_connect_success_total 5917
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 904
telemt_me_reader_eof_total 932
telemt_me_idle_close_by_peer_total 931
telemt_me_route_drop_no_conn_total 131532
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 399
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 258
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 935
telemt_me_writer_restored_same_endpoint_total 903
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 227151
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 14094783124 (13.13 GB)
telemt_user_octets_to_client{user="hello"} 129253860240 (120.38 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 116
```