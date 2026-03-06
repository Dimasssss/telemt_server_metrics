# Server Metrics 2026-03-06 14:02:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 13223.3 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395362
telemt_connections_bad_total 1830
telemt_handshake_timeouts_total 2142
telemt_upstream_connect_attempt_total 6649
telemt_upstream_connect_success_total 6606
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 1284
telemt_me_reconnect_success_total 1276
telemt_me_reader_eof_total 1343
telemt_me_idle_close_by_peer_total 1343
telemt_me_route_drop_no_conn_total 132251
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2142
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 1631
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 729
telemt_desync_frames_bucket_total{bucket="gt_10"} 920
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 1344
telemt_me_writer_restored_same_endpoint_total 1270
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 329572
telemt_user_connections_current{user="hello"} 1301
telemt_user_octets_from_client{user="hello"} 10083149140 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 136186694052 (126.83 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 13223.2 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148076
telemt_connections_bad_total 819
telemt_handshake_timeouts_total 4646
telemt_upstream_connect_attempt_total 5918
telemt_upstream_connect_success_total 5902
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 595
telemt_me_reconnect_success_total 587
telemt_me_reader_eof_total 626
telemt_me_idle_close_by_peer_total 626
telemt_me_route_drop_no_conn_total 68609
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 554
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 201
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 626
telemt_me_writer_restored_same_endpoint_total 587
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 135006
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 1481551336 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 64497590024 (60.07 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 13223.1 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317072
telemt_connections_bad_total 5051
telemt_handshake_timeouts_total 34796
telemt_upstream_connect_attempt_total 8697
telemt_upstream_connect_success_total 8654
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 8690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2273
telemt_me_reconnect_success_total 2263
telemt_me_reader_eof_total 2388
telemt_me_idle_close_by_peer_total 2388
telemt_me_route_drop_no_conn_total 147649
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 529
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 2389
telemt_me_writer_restored_same_endpoint_total 2258
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 266698
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 2658040504 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 84930583176 (79.10 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 12539.3 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202954
telemt_connections_bad_total 40805
telemt_handshake_timeouts_total 4374
telemt_upstream_connect_attempt_total 6016
telemt_upstream_connect_success_total 6016
telemt_upstream_connect_attempts_per_request{bucket="1"} 6016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2524
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 766
telemt_me_reconnect_success_total 757
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 769
telemt_me_route_drop_no_conn_total 74061
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 247
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 769
telemt_me_writer_restored_same_endpoint_total 757
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 138268
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 1636283268 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 54698687968 (50.94 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 13223.4 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238353
telemt_connections_bad_total 7883
telemt_handshake_timeouts_total 2481
telemt_upstream_connect_attempt_total 5293
telemt_upstream_connect_success_total 5285
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 678
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 690
telemt_me_idle_close_by_peer_total 690
telemt_me_route_drop_no_conn_total 122731
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 364
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 692
telemt_me_writer_restored_same_endpoint_total 667
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 215902
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 14002360464 (13.04 GB)
telemt_user_octets_to_client{user="hello"} 122736544604 (114.31 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 124
```