# Server Metrics 2026-03-06 12:35:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 7984.0 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254627
telemt_connections_bad_total 1546
telemt_handshake_timeouts_total 1415
telemt_upstream_connect_attempt_total 2608
telemt_upstream_connect_success_total 2583
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 106
telemt_me_reconnect_success_total 103
telemt_me_reader_eof_total 106
telemt_me_idle_close_by_peer_total 106
telemt_me_route_drop_no_conn_total 73393
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1263
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 962
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 458
telemt_desync_frames_bucket_total{bucket="gt_10"} 494
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 106
telemt_me_writer_restored_same_endpoint_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 195658
telemt_user_connections_current{user="hello"} 1165
telemt_user_octets_from_client{user="hello"} 4035677052 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 82214635768 (76.57 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 7983.8 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88878
telemt_connections_bad_total 746
telemt_handshake_timeouts_total 3358
telemt_upstream_connect_attempt_total 3842
telemt_upstream_connect_success_total 3833
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2099
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 525
telemt_me_reconnect_success_total 522
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 33666
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 289
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 2
telemt_pool_force_close_total 76
telemt_me_writer_removed_unexpected_total 558
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 79346
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 854976332 (815.37 MB)
telemt_user_octets_to_client{user="hello"} 37450129748 (34.88 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 7983.8 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172083
telemt_connections_bad_total 1951
telemt_handshake_timeouts_total 13065
telemt_upstream_connect_attempt_total 5151
telemt_upstream_connect_success_total 5131
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 1452
telemt_me_reconnect_success_total 1448
telemt_me_reader_eof_total 1518
telemt_me_idle_close_by_peer_total 1518
telemt_me_route_drop_no_conn_total 78390
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 249
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 1519
telemt_me_writer_restored_same_endpoint_total 1443
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 152022
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 1633813020 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 51895010164 (48.33 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 7299.9 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91945
telemt_connections_bad_total 15032
telemt_handshake_timeouts_total 2017
telemt_upstream_connect_attempt_total 3789
telemt_upstream_connect_success_total 3789
telemt_upstream_connect_attempts_per_request{bucket="1"} 3789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1620
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 497
telemt_me_reconnect_success_total 493
telemt_me_reader_eof_total 500
telemt_me_idle_close_by_peer_total 500
telemt_me_route_drop_no_conn_total 31640
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 113
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 500
telemt_me_writer_restored_same_endpoint_total 493
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 73399
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 823968644 (785.80 MB)
telemt_user_octets_to_client{user="hello"} 31461993604 (29.30 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 7984.0 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152887
telemt_connections_bad_total 2844
telemt_handshake_timeouts_total 2205
telemt_upstream_connect_attempt_total 2406
telemt_upstream_connect_success_total 2401
telemt_upstream_connect_attempts_per_request{bucket="1"} 2401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 86
telemt_me_reconnect_success_total 79
telemt_me_reader_eof_total 82
telemt_me_idle_close_by_peer_total 82
telemt_me_route_drop_no_conn_total 72137
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 244
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 158
telemt_me_writer_removed_unexpected_total 83
telemt_me_writer_restored_same_endpoint_total 79
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 137783
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 13309284704 (12.40 GB)
telemt_user_octets_to_client{user="hello"} 78360197428 (72.98 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 97
```