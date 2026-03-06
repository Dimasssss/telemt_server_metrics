# Server Metrics 2026-03-06 12:19:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 7061.0 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229370
telemt_connections_bad_total 638
telemt_handshake_timeouts_total 1296
telemt_upstream_connect_attempt_total 2251
telemt_upstream_connect_success_total 2229
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 94
telemt_me_reconnect_success_total 94
telemt_me_reader_eof_total 96
telemt_me_idle_close_by_peer_total 96
telemt_me_route_drop_no_conn_total 62868
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1092
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 834
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 96
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 172131
telemt_user_connections_current{user="hello"} 1201
telemt_user_octets_from_client{user="hello"} 3803857168 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 73330425112 (68.29 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 7060.8 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76978
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 3119
telemt_upstream_connect_attempt_total 3561
telemt_upstream_connect_success_total 3553
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1932
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 462
telemt_me_reconnect_success_total 459
telemt_me_reader_eof_total 491
telemt_me_idle_close_by_peer_total 491
telemt_me_route_drop_no_conn_total 29919
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 254
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 491
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 68688
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 686924560 (655.10 MB)
telemt_user_octets_to_client{user="hello"} 33394353576 (31.10 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 7060.6 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141748
telemt_connections_bad_total 1114
telemt_handshake_timeouts_total 11576
telemt_upstream_connect_attempt_total 4812
telemt_upstream_connect_success_total 4792
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 1320
telemt_me_reconnect_success_total 1316
telemt_me_reader_eof_total 1381
telemt_me_idle_close_by_peer_total 1381
telemt_me_route_drop_no_conn_total 66516
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 236
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 1382
telemt_me_writer_restored_same_endpoint_total 1311
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 125606
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 1387580160 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 47131482984 (43.89 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 6376.7 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77147
telemt_connections_bad_total 10448
telemt_handshake_timeouts_total 1687
telemt_upstream_connect_attempt_total 3175
telemt_upstream_connect_success_total 3175
telemt_upstream_connect_attempts_per_request{bucket="1"} 3175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1347
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 403
telemt_me_reconnect_success_total 400
telemt_me_reader_eof_total 405
telemt_me_idle_close_by_peer_total 405
telemt_me_route_drop_no_conn_total 27173
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 107
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 405
telemt_me_writer_restored_same_endpoint_total 400
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 63706
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 701292596 (668.80 MB)
telemt_user_octets_to_client{user="hello"} 28563456132 (26.60 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 7060.9 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136964
telemt_connections_bad_total 1975
telemt_handshake_timeouts_total 2141
telemt_upstream_connect_attempt_total 1924
telemt_upstream_connect_success_total 1920
telemt_upstream_connect_attempts_per_request{bucket="1"} 1920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 39
telemt_me_reconnect_success_total 33
telemt_me_reader_eof_total 35
telemt_me_idle_close_by_peer_total 35
telemt_me_route_drop_no_conn_total 62536
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 200
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 134
telemt_me_writer_removed_unexpected_total 36
telemt_me_writer_restored_same_endpoint_total 33
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 123251
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 12894197756 (12.01 GB)
telemt_user_octets_to_client{user="hello"} 67877480292 (63.22 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 92
```