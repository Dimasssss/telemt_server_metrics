# Server Metrics 2026-03-07 02:02:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 28450.1 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325815
telemt_connections_bad_total 3884
telemt_handshake_timeouts_total 9590
telemt_upstream_connect_attempt_total 92395
telemt_upstream_connect_success_total 89699
telemt_upstream_connect_fail_total 2556
telemt_upstream_connect_attempts_per_request{bucket="1"} 92255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 99
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2556
telemt_me_keepalive_timeout_total 1917
telemt_me_reconnect_attempts_total 57222
telemt_me_reconnect_success_total 54752
telemt_me_reader_eof_total 56736
telemt_me_idle_close_by_peer_total 56734
telemt_me_route_drop_no_conn_total 122564
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1092
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 793
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 300
telemt_pool_swap_total 14
telemt_pool_force_close_total 627
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 56849
telemt_me_writer_restored_same_endpoint_total 54596
telemt_me_writer_restored_fallback_total 150
telemt_me_async_recovery_trigger_total 49295
telemt_me_writer_removed_unexpected_minus_restored_total 2103
telemt_user_connections_total{user="hello"} 296406
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 4424401640 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 128350984520 (119.54 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 28450.2 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142079
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 18519
telemt_upstream_connect_attempt_total 189797
telemt_upstream_connect_success_total 189794
telemt_upstream_connect_attempts_per_request{bucket="1"} 189794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1478
telemt_me_reconnect_attempts_total 148706
telemt_me_reconnect_success_total 148297
telemt_me_reader_eof_total 134217
telemt_me_idle_close_by_peer_total 134212
telemt_me_route_drop_no_conn_total 44069
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 247
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 835
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 21
telemt_pool_force_close_total 1379
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 134257
telemt_me_writer_restored_same_endpoint_total 148295
telemt_me_async_recovery_trigger_total 49289
telemt_user_connections_total{user="hello"} 116471
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 1593831840 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 39178822948 (36.49 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 28450.1 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253996
telemt_connections_bad_total 1443
telemt_handshake_timeouts_total 4320
telemt_upstream_connect_attempt_total 142416
telemt_upstream_connect_success_total 142198
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 142279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 2633
telemt_me_reconnect_attempts_total 106675
telemt_me_reconnect_success_total 106588
telemt_me_reader_eof_total 107760
telemt_me_idle_close_by_peer_total 107755
telemt_me_route_drop_no_conn_total 93783
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 235
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1079
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 799
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 16
telemt_pool_force_close_total 405
telemt_pool_stale_pick_total 127
telemt_me_writer_removed_unexpected_total 107950
telemt_me_writer_restored_same_endpoint_total 106581
telemt_me_async_recovery_trigger_total 147625
telemt_me_writer_removed_unexpected_minus_restored_total 1369
telemt_user_connections_total{user="hello"} 237237
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 22924758484 (21.35 GB)
telemt_user_octets_to_client{user="hello"} 67082485184 (62.48 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 28450.3 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263480
telemt_connections_bad_total 81437
telemt_handshake_timeouts_total 17006
telemt_upstream_connect_attempt_total 55755
telemt_upstream_connect_success_total 55666
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 55708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1068
telemt_me_reconnect_attempts_total 19927
telemt_me_reconnect_success_total 19895
telemt_me_reader_eof_total 26982
telemt_me_idle_close_by_peer_total 26980
telemt_me_route_drop_no_conn_total 71496
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 249
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 14
telemt_pool_force_close_total 498
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 26987
telemt_me_writer_restored_same_endpoint_total 19890
telemt_me_writer_removed_unexpected_minus_restored_total 7097
telemt_user_connections_total{user="hello"} 160839
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 1775709148 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 51147495052 (47.63 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 28448.9 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221247
telemt_connections_bad_total 517
telemt_handshake_timeouts_total 2804
telemt_upstream_connect_attempt_total 48221
telemt_upstream_connect_success_total 48039
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 48063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1299
telemt_me_reconnect_attempts_total 14291
telemt_me_reconnect_success_total 14250
telemt_me_reader_eof_total 19667
telemt_me_idle_close_by_peer_total 19665
telemt_me_route_drop_no_conn_total 73177
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 234
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 807
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 597
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 17
telemt_pool_force_close_total 477
telemt_pool_stale_pick_total 218
telemt_me_writer_removed_unexpected_total 19736
telemt_me_writer_restored_same_endpoint_total 14242
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5490
telemt_user_connections_total{user="hello"} 203173
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 10265943924 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 70917275456 (66.05 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 16
```