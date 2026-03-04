# Server Metrics 2026-03-04 22:50:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 7009.0 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76076
telemt_connections_bad_total 1346
telemt_handshake_timeouts_total 479
telemt_upstream_connect_attempt_total 6636
telemt_upstream_connect_success_total 6553
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6552
telemt_upstream_connect_attempts_per_request{bucket="2"} 27
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 2084
telemt_me_reconnect_success_total 2090
telemt_me_reader_eof_total 2136
telemt_me_idle_close_by_peer_total 2136
telemt_me_route_drop_no_conn_total 19378
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 2171
telemt_me_writer_restored_same_endpoint_total 2070
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 64005
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 2601639740 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 34681209324 (32.30 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 7003.9 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26788
telemt_connections_bad_total 701
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 7491
telemt_upstream_connect_success_total 7375
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 7372
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 504
telemt_me_reconnect_attempts_total 2701
telemt_me_reconnect_success_total 2696
telemt_me_reader_eof_total 2755
telemt_me_idle_close_by_peer_total 2754
telemt_me_route_drop_no_conn_total 8490
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 2809
telemt_me_writer_restored_same_endpoint_total 2677
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 25148
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 227479600 (216.94 MB)
telemt_user_octets_to_client{user="hello"} 7345438912 (6.84 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 7000.5 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60472
telemt_connections_bad_total 1023
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 2926
telemt_upstream_connect_success_total 2898
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2898
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 178
telemt_me_reconnect_success_total 191
telemt_me_reader_eof_total 180
telemt_me_idle_close_by_peer_total 180
telemt_me_route_drop_no_conn_total 19108
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 139
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_restored_same_endpoint_total 171
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 55605
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 921261904 (878.58 MB)
telemt_user_octets_to_client{user="hello"} 23191054404 (21.60 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 39048.8 (10h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523949
telemt_connections_bad_total 70865
telemt_handshake_timeouts_total 14681
telemt_upstream_connect_attempt_total 16875
telemt_upstream_connect_success_total 16875
telemt_upstream_connect_attempts_per_request{bucket="1"} 16875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 2184
telemt_me_reconnect_success_total 2169
telemt_me_reader_eof_total 2211
telemt_me_idle_close_by_peer_total 2211
telemt_me_route_drop_no_conn_total 179666
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 699
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 15
telemt_pool_force_close_total 456
telemt_pool_stale_pick_total 15
telemt_me_writer_removed_unexpected_total 2212
telemt_me_writer_restored_same_endpoint_total 2143
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 410121
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 5718831912 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 155030550232 (144.38 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 39408.1 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521525
telemt_connections_bad_total 3772
telemt_handshake_timeouts_total 5758
telemt_upstream_connect_attempt_total 23832
telemt_upstream_connect_success_total 23701
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 23701
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 4992
telemt_me_reconnect_success_total 4977
telemt_me_reader_eof_total 5161
telemt_me_idle_close_by_peer_total 5161
telemt_me_route_drop_no_conn_total 229957
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 827
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 5164
telemt_me_writer_restored_same_endpoint_total 4956
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 471418
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 7271503336 (6.77 GB)
telemt_user_octets_to_client{user="hello"} 154959899352 (144.32 GB)
telemt_user_unique_ips_current{user="hello"} 25
```