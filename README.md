# Server Metrics 2026-03-06 00:37:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 8168.4 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57985
telemt_connections_bad_total 14468
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 5456
telemt_upstream_connect_success_total 5407
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5407
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 994
telemt_me_reconnect_success_total 988
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_route_drop_no_conn_total 11149
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 92
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 1013
telemt_me_writer_restored_same_endpoint_total 983
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 41773
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 540041828 (515.02 MB)
telemt_user_octets_to_client{user="hello"} 14699616268 (13.69 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 8164.0 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18106
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 268
telemt_upstream_connect_attempt_total 6885
telemt_upstream_connect_success_total 6883
telemt_upstream_connect_attempts_per_request{bucket="1"} 6883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1468
telemt_me_reconnect_success_total 1464
telemt_me_reader_eof_total 1478
telemt_me_idle_close_by_peer_total 1478
telemt_me_route_drop_no_conn_total 5613
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1479
telemt_me_writer_restored_same_endpoint_total 1460
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 17439
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 129882764 (123.87 MB)
telemt_user_octets_to_client{user="hello"} 3628860116 (3.38 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 8161.4 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32616
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 150
telemt_upstream_connect_attempt_total 8839
telemt_upstream_connect_success_total 8775
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 8775
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3164
telemt_me_reconnect_success_total 3157
telemt_me_reader_eof_total 3318
telemt_me_idle_close_by_peer_total 3318
telemt_me_route_drop_no_conn_total 8663
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 77
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3319
telemt_me_writer_restored_same_endpoint_total 3151
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 31222
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 431285440 (411.31 MB)
telemt_user_octets_to_client{user="hello"} 11966425264 (11.14 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 8158.1 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24953
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 727
telemt_upstream_connect_attempt_total 4109
telemt_upstream_connect_success_total 4091
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 4091
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1742
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 391
telemt_me_reconnect_success_total 386
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 11322
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 393
telemt_me_writer_restored_same_endpoint_total 381
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 22816
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 243892380 (232.59 MB)
telemt_user_octets_to_client{user="hello"} 16589234456 (15.45 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 8157.0 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33708
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 146
telemt_upstream_connect_attempt_total 4877
telemt_upstream_connect_success_total 4869
telemt_upstream_connect_attempts_per_request{bucket="1"} 4869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 682
telemt_me_reconnect_success_total 682
telemt_me_reader_eof_total 694
telemt_me_idle_close_by_peer_total 694
telemt_me_route_drop_no_conn_total 11927
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 13
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 2
telemt_pool_force_close_total 42
telemt_me_writer_removed_unexpected_total 694
telemt_me_writer_restored_same_endpoint_total 677
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 33092
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 10983697972 (10.23 GB)
telemt_user_octets_to_client{user="hello"} 17926919568 (16.70 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 31
```