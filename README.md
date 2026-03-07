# Server Metrics 2026-03-07 00:45:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 23820.8 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302269
telemt_connections_bad_total 3034
telemt_handshake_timeouts_total 9407
telemt_upstream_connect_attempt_total 67159
telemt_upstream_connect_success_total 65354
telemt_upstream_connect_fail_total 1668
telemt_upstream_connect_attempts_per_request{bucket="1"} 67022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1668
telemt_me_keepalive_timeout_total 1616
telemt_me_reconnect_attempts_total 38153
telemt_me_reconnect_success_total 36542
telemt_me_reader_eof_total 39245
telemt_me_idle_close_by_peer_total 39245
telemt_me_route_drop_no_conn_total 116188
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
telemt_pool_force_close_total 512
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 39358
telemt_me_writer_restored_same_endpoint_total 36439
telemt_me_writer_restored_fallback_total 97
telemt_me_async_recovery_trigger_total 30883
telemt_me_writer_removed_unexpected_minus_restored_total 2822
telemt_user_connections_total{user="hello"} 274932
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 4224454236 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 120477346304 (112.20 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 23820.8 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129434
telemt_connections_bad_total 115
telemt_handshake_timeouts_total 15304
telemt_upstream_connect_attempt_total 130307
telemt_upstream_connect_success_total 130303
telemt_upstream_connect_attempts_per_request{bucket="1"} 130303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 1162
telemt_me_reconnect_attempts_total 96795
telemt_me_reconnect_success_total 96522
telemt_me_reader_eof_total 88544
telemt_me_idle_close_by_peer_total 88539
telemt_me_route_drop_no_conn_total 41885
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 808
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 16
telemt_pool_force_close_total 1029
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 88573
telemt_me_writer_restored_same_endpoint_total 96520
telemt_me_async_recovery_trigger_total 30876
telemt_user_connections_total{user="hello"} 107657
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 1559380328 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 37535060768 (34.96 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 23820.8 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233973
telemt_connections_bad_total 1228
telemt_handshake_timeouts_total 3579
telemt_upstream_connect_attempt_total 100566
telemt_upstream_connect_success_total 100392
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 100455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 2074
telemt_me_reconnect_attempts_total 71428
telemt_me_reconnect_success_total 71362
telemt_me_reader_eof_total 73109
telemt_me_idle_close_by_peer_total 73104
telemt_me_route_drop_no_conn_total 88556
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1038
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 13
telemt_pool_force_close_total 362
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 73277
telemt_me_writer_restored_same_endpoint_total 71355
telemt_me_async_recovery_trigger_total 92429
telemt_me_writer_removed_unexpected_minus_restored_total 1922
telemt_user_connections_total{user="hello"} 218387
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 19550925920 (18.21 GB)
telemt_user_octets_to_client{user="hello"} 62336702360 (58.06 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 23821.2 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236958
telemt_connections_bad_total 66616
telemt_handshake_timeouts_total 16687
telemt_upstream_connect_attempt_total 42569
telemt_upstream_connect_success_total 42484
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 42522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 835
telemt_me_reconnect_attempts_total 13759
telemt_me_reconnect_success_total 13733
telemt_me_reader_eof_total 18731
telemt_me_idle_close_by_peer_total 18729
telemt_me_route_drop_no_conn_total 63460
telemt_me_single_endpoint_shadow_rotate_total 200
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 208
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 473
telemt_me_writer_removed_unexpected_total 18736
telemt_me_writer_restored_same_endpoint_total 13728
telemt_me_writer_removed_unexpected_minus_restored_total 5008
telemt_user_connections_total{user="hello"} 149660
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 1727705988 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 49029025012 (45.66 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 23819.7 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204833
telemt_connections_bad_total 509
telemt_handshake_timeouts_total 2347
telemt_upstream_connect_attempt_total 38551
telemt_upstream_connect_success_total 38400
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 38419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1098
telemt_me_reconnect_attempts_total 11038
telemt_me_reconnect_success_total 11004
telemt_me_reader_eof_total 14905
telemt_me_idle_close_by_peer_total 14903
telemt_me_route_drop_no_conn_total 68681
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 196
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 786
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 583
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 14
telemt_pool_force_close_total 428
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 14972
telemt_me_writer_restored_same_endpoint_total 11000
telemt_me_writer_removed_unexpected_minus_restored_total 3972
telemt_user_connections_total{user="hello"} 188157
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 10135835840 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 65846876376 (61.32 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 32
```