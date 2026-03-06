# Server Metrics 2026-03-06 11:48:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 5213.9 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178747
telemt_connections_bad_total 396
telemt_handshake_timeouts_total 937
telemt_upstream_connect_attempt_total 1746
telemt_upstream_connect_success_total 1731
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 75
telemt_me_reconnect_success_total 77
telemt_me_reader_eof_total 75
telemt_me_idle_close_by_peer_total 75
telemt_me_route_drop_no_conn_total 43641
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 684
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 75
telemt_me_writer_restored_same_endpoint_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 123887
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 3346434880 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 46240436612 (43.06 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 5213.9 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57561
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 2144
telemt_upstream_connect_attempt_total 1892
telemt_upstream_connect_success_total 1887
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 939
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 48
telemt_me_reconnect_success_total 48
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 20662
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 201
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_restored_same_endpoint_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 50645
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 507593048 (484.08 MB)
telemt_user_octets_to_client{user="hello"} 21371640108 (19.90 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 5213.7 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101213
telemt_connections_bad_total 495
telemt_handshake_timeouts_total 8751
telemt_upstream_connect_attempt_total 2750
telemt_upstream_connect_success_total 2738
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 491
telemt_me_reconnect_success_total 490
telemt_me_reader_eof_total 509
telemt_me_idle_close_by_peer_total 509
telemt_me_route_drop_no_conn_total 37699
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 194
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 145
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_me_writer_removed_unexpected_total 509
telemt_me_writer_restored_same_endpoint_total 485
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 89425
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 994268300 (948.21 MB)
telemt_user_octets_to_client{user="hello"} 29093516144 (27.10 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 4529.9 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50229
telemt_connections_bad_total 4045
telemt_handshake_timeouts_total 1194
telemt_upstream_connect_attempt_total 2314
telemt_upstream_connect_success_total 2314
telemt_upstream_connect_attempts_per_request{bucket="1"} 2314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 958
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 366
telemt_me_reconnect_success_total 363
telemt_me_reader_eof_total 368
telemt_me_idle_close_by_peer_total 368
telemt_me_route_drop_no_conn_total 17334
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 66
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 368
telemt_me_writer_restored_same_endpoint_total 363
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 44022
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 556128052 (530.37 MB)
telemt_user_octets_to_client{user="hello"} 14662120568 (13.66 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 5213.9 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101775
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 1870
telemt_upstream_connect_attempt_total 1308
telemt_upstream_connect_success_total 1307
telemt_upstream_connect_attempts_per_request{bucket="1"} 1307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 40862
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 43
telemt_me_writer_removed_unexpected_total 18
telemt_me_writer_restored_same_endpoint_total 17
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 92579
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 11367032152 (10.59 GB)
telemt_user_octets_to_client{user="hello"} 47094990620 (43.86 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 101
```