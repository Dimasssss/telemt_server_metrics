# Server Metrics 2026-03-06 11:53:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 5521.1 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187687
telemt_connections_bad_total 396
telemt_handshake_timeouts_total 964
telemt_upstream_connect_attempt_total 1924
telemt_upstream_connect_success_total 1904
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 85
telemt_me_reconnect_success_total 87
telemt_me_reader_eof_total 85
telemt_me_idle_close_by_peer_total 85
telemt_me_route_drop_no_conn_total 47578
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 723
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 554
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 2
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 85
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 132039
telemt_user_connections_current{user="hello"} 1140
telemt_user_octets_from_client{user="hello"} 3431417852 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 51759192204 (48.20 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 5521.0 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60816
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 2495
telemt_upstream_connect_attempt_total 2100
telemt_upstream_connect_success_total 2092
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 52
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 53
telemt_me_idle_close_by_peer_total 53
telemt_me_route_drop_no_conn_total 22057
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 212
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 53
telemt_me_writer_restored_same_endpoint_total 52
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 53531
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 531769860 (507.14 MB)
telemt_user_octets_to_client{user="hello"} 24169421736 (22.51 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 5520.8 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108439
telemt_connections_bad_total 507
telemt_handshake_timeouts_total 9913
telemt_upstream_connect_attempt_total 3042
telemt_upstream_connect_success_total 3028
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 577
telemt_me_reconnect_success_total 576
telemt_me_reader_eof_total 597
telemt_me_idle_close_by_peer_total 597
telemt_me_route_drop_no_conn_total 41413
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 198
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_me_writer_removed_unexpected_total 597
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 95380
telemt_user_connections_current{user="hello"} 843
telemt_user_octets_from_client{user="hello"} 1037366980 (989.31 MB)
telemt_user_octets_to_client{user="hello"} 33435460124 (31.14 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 4837.0 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54077
telemt_connections_bad_total 4321
telemt_handshake_timeouts_total 1268
telemt_upstream_connect_attempt_total 2443
telemt_upstream_connect_success_total 2443
telemt_upstream_connect_attempts_per_request{bucket="1"} 2443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1010
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 367
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 369
telemt_me_idle_close_by_peer_total 369
telemt_me_route_drop_no_conn_total 18401
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 369
telemt_me_writer_restored_same_endpoint_total 364
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 47463
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 578867328 (552.05 MB)
telemt_user_octets_to_client{user="hello"} 17886749044 (16.66 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 5521.2 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107784
telemt_connections_bad_total 469
telemt_handshake_timeouts_total 1957
telemt_upstream_connect_attempt_total 1376
telemt_upstream_connect_success_total 1375
telemt_upstream_connect_attempts_per_request{bucket="1"} 1375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 18
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 43369
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 159
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 72
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_restored_same_endpoint_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 97775
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 11394123320 (10.61 GB)
telemt_user_octets_to_client{user="hello"} 50435017880 (46.97 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 122
```