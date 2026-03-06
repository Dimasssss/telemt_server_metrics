# Server Metrics 2026-03-06 13:57:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 12915.8 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386922
telemt_connections_bad_total 1829
telemt_handshake_timeouts_total 2095
telemt_upstream_connect_attempt_total 6321
telemt_upstream_connect_success_total 6278
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 1140
telemt_me_reconnect_success_total 1132
telemt_me_reader_eof_total 1191
telemt_me_idle_close_by_peer_total 1191
telemt_me_route_drop_no_conn_total 129000
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2096
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1595
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 710
telemt_desync_frames_bucket_total{bucket="gt_10"} 901
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 1192
telemt_me_writer_restored_same_endpoint_total 1126
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 321452
telemt_user_connections_current{user="hello"} 1221
telemt_user_octets_from_client{user="hello"} 7827216704 (7.29 GB)
telemt_user_octets_to_client{user="hello"} 133497267540 (124.33 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 12915.8 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145014
telemt_connections_bad_total 819
telemt_handshake_timeouts_total 4554
telemt_upstream_connect_attempt_total 5898
telemt_upstream_connect_success_total 5882
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 595
telemt_me_reconnect_success_total 587
telemt_me_reader_eof_total 626
telemt_me_idle_close_by_peer_total 626
telemt_me_route_drop_no_conn_total 65928
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 529
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 353
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 626
telemt_me_writer_restored_same_endpoint_total 587
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 132076
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 1442009484 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 62073747708 (57.81 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 12915.7 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307370
telemt_connections_bad_total 5051
telemt_handshake_timeouts_total 30825
telemt_upstream_connect_attempt_total 8291
telemt_upstream_connect_success_total 8248
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 8284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 2096
telemt_me_reconnect_success_total 2087
telemt_me_reader_eof_total 2200
telemt_me_idle_close_by_peer_total 2200
telemt_me_route_drop_no_conn_total 143959
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 513
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 368
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 2201
telemt_me_writer_restored_same_endpoint_total 2082
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 260806
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 2613256776 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 83262677532 (77.54 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 12231.8 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192146
telemt_connections_bad_total 39824
telemt_handshake_timeouts_total 3480
telemt_upstream_connect_attempt_total 5903
telemt_upstream_connect_success_total 5903
telemt_upstream_connect_attempts_per_request{bucket="1"} 5903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2484
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 766
telemt_me_reconnect_success_total 757
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 769
telemt_me_route_drop_no_conn_total 72118
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 242
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 769
telemt_me_writer_restored_same_endpoint_total 757
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 134330
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 1603208496 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 53526902588 (49.85 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 12915.8 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233718
telemt_connections_bad_total 7882
telemt_handshake_timeouts_total 2473
telemt_upstream_connect_attempt_total 5008
telemt_upstream_connect_success_total 5000
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 585
telemt_me_reconnect_success_total 576
telemt_me_reader_eof_total 596
telemt_me_idle_close_by_peer_total 596
telemt_me_route_drop_no_conn_total 120260
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 355
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 598
telemt_me_writer_restored_same_endpoint_total 575
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 211367
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 13974356380 (13.01 GB)
telemt_user_octets_to_client{user="hello"} 120550920372 (112.27 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 88
```