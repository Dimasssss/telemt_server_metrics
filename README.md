# Server Metrics 2026-03-07 00:50:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 24129.2 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304026
telemt_connections_bad_total 3218
telemt_handshake_timeouts_total 9409
telemt_upstream_connect_attempt_total 68687
telemt_upstream_connect_success_total 66811
telemt_upstream_connect_fail_total 1739
telemt_upstream_connect_attempts_per_request{bucket="1"} 68550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1739
telemt_me_keepalive_timeout_total 1629
telemt_me_reconnect_attempts_total 39234
telemt_me_reconnect_success_total 37552
telemt_me_reader_eof_total 40233
telemt_me_idle_close_by_peer_total 40233
telemt_me_route_drop_no_conn_total 116655
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1004
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 732
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 452
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 10
telemt_pool_force_close_total 514
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 40346
telemt_me_writer_restored_same_endpoint_total 37445
telemt_me_writer_restored_fallback_total 101
telemt_me_async_recovery_trigger_total 32109
telemt_me_writer_removed_unexpected_minus_restored_total 2800
telemt_user_connections_total{user="hello"} 276364
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 4236378496 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 121007190960 (112.70 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 24129.1 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130344
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 15532
telemt_upstream_connect_attempt_total 134493
telemt_upstream_connect_success_total 134490
telemt_upstream_connect_attempts_per_request{bucket="1"} 134490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 1172
telemt_me_reconnect_attempts_total 100398
telemt_me_reconnect_success_total 100118
telemt_me_reader_eof_total 92038
telemt_me_idle_close_by_peer_total 92033
telemt_me_route_drop_no_conn_total 42133
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 809
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 16
telemt_pool_force_close_total 1029
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 92067
telemt_me_writer_restored_same_endpoint_total 100116
telemt_me_async_recovery_trigger_total 32102
telemt_user_connections_total{user="hello"} 108321
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 1562471940 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 37657327356 (35.07 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 24129.1 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235424
telemt_connections_bad_total 1240
telemt_handshake_timeouts_total 3584
telemt_upstream_connect_attempt_total 102797
telemt_upstream_connect_success_total 102622
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 102686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 2104
telemt_me_reconnect_attempts_total 73201
telemt_me_reconnect_success_total 73135
telemt_me_reader_eof_total 74973
telemt_me_idle_close_by_peer_total 74968
telemt_me_route_drop_no_conn_total 88992
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1044
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 778
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 13
telemt_pool_force_close_total 362
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 75141
telemt_me_writer_restored_same_endpoint_total 73128
telemt_me_async_recovery_trigger_total 96104
telemt_me_writer_removed_unexpected_minus_restored_total 2013
telemt_user_connections_total{user="hello"} 219807
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 19814216852 (18.45 GB)
telemt_user_octets_to_client{user="hello"} 63018440976 (58.69 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 24129.3 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238795
telemt_connections_bad_total 67607
telemt_handshake_timeouts_total 16757
telemt_upstream_connect_attempt_total 42949
telemt_upstream_connect_success_total 42864
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 42902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 837
telemt_me_reconnect_attempts_total 13778
telemt_me_reconnect_success_total 13751
telemt_me_reader_eof_total 18759
telemt_me_idle_close_by_peer_total 18757
telemt_me_route_drop_no_conn_total 63694
telemt_me_single_endpoint_shadow_rotate_total 200
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 213
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 18764
telemt_me_writer_restored_same_endpoint_total 13746
telemt_me_writer_removed_unexpected_minus_restored_total 5018
telemt_user_connections_total{user="hello"} 150459
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 1730850396 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 49213856104 (45.83 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 24127.7 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206067
telemt_connections_bad_total 509
telemt_handshake_timeouts_total 2383
telemt_upstream_connect_attempt_total 39333
telemt_upstream_connect_success_total 39183
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 39202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1116
telemt_me_reconnect_attempts_total 11363
telemt_me_reconnect_success_total 11330
telemt_me_reader_eof_total 15396
telemt_me_idle_close_by_peer_total 15394
telemt_me_route_drop_no_conn_total 69039
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 196
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 796
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 591
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 14
telemt_pool_force_close_total 428
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 15463
telemt_me_writer_restored_same_endpoint_total 11326
telemt_me_writer_removed_unexpected_minus_restored_total 4137
telemt_user_connections_total{user="hello"} 189325
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 10153467692 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 66885960332 (62.29 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 18
```