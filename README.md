# Server Metrics 2026-03-06 13:11:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 10146.3 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314753
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 1738
telemt_upstream_connect_attempt_total 3749
telemt_upstream_connect_success_total 3718
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 248
telemt_me_reconnect_success_total 243
telemt_me_reader_eof_total 249
telemt_me_idle_close_by_peer_total 249
telemt_me_route_drop_no_conn_total 96133
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1700
telemt_desync_full_logged_total 401
telemt_desync_suppressed_total 1299
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 717
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 249
telemt_me_writer_restored_same_endpoint_total 237
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 251901
telemt_user_connections_current{user="hello"} 1198
telemt_user_octets_from_client{user="hello"} 4689402820 (4.37 GB)
telemt_user_octets_to_client{user="hello"} 106058279544 (98.77 GB)
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 10146.2 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116852
telemt_connections_bad_total 805
telemt_handshake_timeouts_total 4015
telemt_upstream_connect_attempt_total 4306
telemt_upstream_connect_success_total 4293
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 532
telemt_me_reconnect_success_total 527
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 45161
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 361
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_restored_same_endpoint_total 527
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 105167
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 1098922244 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 47974438860 (44.68 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 10146.2 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238316
telemt_connections_bad_total 3476
telemt_handshake_timeouts_total 15952
telemt_upstream_connect_attempt_total 5805
telemt_upstream_connect_success_total 5772
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 5798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 1470
telemt_me_reconnect_success_total 1465
telemt_me_reader_eof_total 1538
telemt_me_idle_close_by_peer_total 1538
telemt_me_route_drop_no_conn_total 110238
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 321
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 225
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 373
telemt_me_writer_removed_unexpected_total 1539
telemt_me_writer_restored_same_endpoint_total 1460
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 210346
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 2127012224 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 68028229968 (63.36 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 9462.2 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131910
telemt_connections_bad_total 28599
telemt_handshake_timeouts_total 2633
telemt_upstream_connect_attempt_total 4890
telemt_upstream_connect_success_total 4890
telemt_upstream_connect_attempts_per_request{bucket="1"} 4890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2081
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 726
telemt_me_reconnect_success_total 720
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 731
telemt_me_route_drop_no_conn_total 50988
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 186
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 731
telemt_me_writer_restored_same_endpoint_total 720
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 98803
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 1275620900 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 40719143740 (37.92 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 10146.3 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191506
telemt_connections_bad_total 6316
telemt_handshake_timeouts_total 2359
telemt_upstream_connect_attempt_total 3124
telemt_upstream_connect_success_total 3118
telemt_upstream_connect_attempts_per_request{bucket="1"} 3118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 126
telemt_me_reconnect_success_total 119
telemt_me_reader_eof_total 125
telemt_me_idle_close_by_peer_total 125
telemt_me_route_drop_no_conn_total 94014
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 302
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 126
telemt_me_writer_restored_same_endpoint_total 118
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 171830
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 13705250508 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 98399440624 (91.64 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 94
```