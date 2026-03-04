# Server Metrics 2026-03-04 21:12:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 1168.0 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18693
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 262
telemt_upstream_connect_success_total 251
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 251
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 3117
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 14415
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 1079278980 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 4092373252 (3.81 GB)
telemt_user_unique_ips_current{user="hello"} 62
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 1162.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6304
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 297
telemt_upstream_connect_success_total 289
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 289
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 1694
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 36
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 5542
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 42228720 (40.27 MB)
telemt_user_octets_to_client{user="hello"} 1661751524 (1.55 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 1159.4 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14066
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 136
telemt_upstream_connect_attempt_total 284
telemt_upstream_connect_success_total 274
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 274
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 3562
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 13129
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 89771596 (85.61 MB)
telemt_user_octets_to_client{user="hello"} 4178904116 (3.89 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 33207.6 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482772
telemt_connections_bad_total 60949
telemt_handshake_timeouts_total 14575
telemt_upstream_connect_attempt_total 14169
telemt_upstream_connect_success_total 14169
telemt_upstream_connect_attempts_per_request{bucket="1"} 14169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 190
telemt_me_reconnect_attempts_total 1949
telemt_me_reconnect_success_total 1939
telemt_me_reader_eof_total 1968
telemt_me_idle_close_by_peer_total 1968
telemt_me_route_drop_no_conn_total 168256
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 628
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 11
telemt_pool_force_close_total 363
telemt_me_writer_removed_unexpected_total 1969
telemt_me_writer_restored_same_endpoint_total 1915
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 381298
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 5495419744 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 146087694172 (136.05 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 33566.8 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487391
telemt_connections_bad_total 3750
telemt_handshake_timeouts_total 5349
telemt_upstream_connect_attempt_total 19194
telemt_upstream_connect_success_total 19090
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 19090
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 3784
telemt_me_reconnect_success_total 3775
telemt_me_reader_eof_total 3905
telemt_me_idle_close_by_peer_total 3905
telemt_me_route_drop_no_conn_total 219476
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 819
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 524
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 7
telemt_pool_force_close_total 339
telemt_pool_stale_pick_total 177
telemt_me_writer_removed_unexpected_total 3906
telemt_me_writer_restored_same_endpoint_total 3754
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 439109
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 6921862752 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 142436777284 (132.65 GB)
telemt_user_unique_ips_current{user="hello"} 35
```