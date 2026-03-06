# Server Metrics 2026-03-06 11:38:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 4598.9 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159762
telemt_connections_bad_total 363
telemt_handshake_timeouts_total 870
telemt_upstream_connect_attempt_total 1385
telemt_upstream_connect_success_total 1372
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 34
telemt_me_reconnect_success_total 36
telemt_me_reader_eof_total 32
telemt_me_idle_close_by_peer_total 32
telemt_me_route_drop_no_conn_total 37493
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 586
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 110084
telemt_user_connections_current{user="hello"} 1047
telemt_user_octets_from_client{user="hello"} 3131954024 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 39495070312 (36.78 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 4598.9 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50595
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 1628
telemt_upstream_connect_attempt_total 1490
telemt_upstream_connect_success_total 1485
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 714
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 23
telemt_me_idle_close_by_peer_total 23
telemt_me_route_drop_no_conn_total 18340
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 188
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 44529
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 467580768 (445.92 MB)
telemt_user_octets_to_client{user="hello"} 17938848136 (16.71 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 4598.8 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87929
telemt_connections_bad_total 482
telemt_handshake_timeouts_total 6528
telemt_upstream_connect_attempt_total 2189
telemt_upstream_connect_success_total 2176
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 904
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 307
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 314
telemt_me_idle_close_by_peer_total 314
telemt_me_route_drop_no_conn_total 33176
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 152
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_me_writer_removed_unexpected_total 314
telemt_me_writer_restored_same_endpoint_total 301
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 78851
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 903479348 (861.63 MB)
telemt_user_octets_to_client{user="hello"} 24173173056 (22.51 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 3914.8 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43514
telemt_connections_bad_total 3501
telemt_handshake_timeouts_total 1035
telemt_upstream_connect_attempt_total 2217
telemt_upstream_connect_success_total 2217
telemt_upstream_connect_attempts_per_request{bucket="1"} 2217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 906
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 365
telemt_me_reconnect_success_total 362
telemt_me_reader_eof_total 367
telemt_me_idle_close_by_peer_total 367
telemt_me_route_drop_no_conn_total 15504
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_restored_same_endpoint_total 362
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 38092
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 467042440 (445.41 MB)
telemt_user_octets_to_client{user="hello"} 11055894628 (10.30 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 4599.2 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89233
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 1781
telemt_upstream_connect_attempt_total 1256
telemt_upstream_connect_success_total 1255
telemt_upstream_connect_attempts_per_request{bucket="1"} 1255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 17
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 14
telemt_me_idle_close_by_peer_total 14
telemt_me_route_drop_no_conn_total 28755
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 149
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 2
telemt_pool_force_close_total 20
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 81228
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 11285827640 (10.51 GB)
telemt_user_octets_to_client{user="hello"} 40817559544 (38.01 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 97
```