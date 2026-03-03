# Server Metrics 2026-03-03 20:46:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 51854.0 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1306290
telemt_connections_bad_total 10295
telemt_handshake_timeouts_total 14903
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4323
telemt_me_reconnect_success_total 4299
telemt_me_reader_eof_total 4321
telemt_me_route_drop_no_conn_total 505184
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 208
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 3216
telemt_desync_full_logged_total 1028
telemt_desync_suppressed_total 2188
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1092
telemt_desync_frames_bucket_total{bucket="gt_10"} 1236
telemt_pool_swap_total 16
telemt_pool_force_close_total 809
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4323
telemt_me_writer_restored_same_endpoint_total 4258
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 1080431
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 18537291812 (17.26 GB)
telemt_user_octets_to_client{user="hello"} 420153645172 (391.30 GB)
telemt_user_unique_ips_current{user="hello"} 70
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 51851.2 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 585959
telemt_connections_bad_total 5292
telemt_handshake_timeouts_total 35749
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 3930
telemt_me_reconnect_success_total 3926
telemt_me_reader_eof_total 3923
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 268346
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 693
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 20
telemt_pool_force_close_total 765
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 3996
telemt_me_writer_restored_same_endpoint_total 3866
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 530216
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 8573450404 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 211471667172 (196.95 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 4767.5 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58494
telemt_connections_bad_total 10535
telemt_handshake_timeouts_total 755
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 992
telemt_me_reconnect_success_total 1006
telemt_me_reader_eof_total 998
telemt_me_route_drop_no_conn_total 39344
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 220
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_me_writer_removed_unexpected_total 1001
telemt_me_writer_restored_same_endpoint_total 980
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 43511
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 313825876 (299.29 MB)
telemt_user_octets_to_client{user="hello"} 12305415940 (11.46 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 4499.7 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24342
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 2465
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 422
telemt_me_reconnect_success_total 452
telemt_me_reader_eof_total 434
telemt_me_route_drop_no_conn_total 8943
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 3
telemt_pool_force_close_total 46
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_restored_same_endpoint_total 414
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 21323
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 709970660 (677.08 MB)
telemt_user_octets_to_client{user="hello"} 10743009208 (10.01 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 49403.9 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796244
telemt_connections_bad_total 7232
telemt_handshake_timeouts_total 198583
telemt_me_keepalive_timeout_total 199
telemt_me_reconnect_attempts_total 8305
telemt_me_reconnect_success_total 8276
telemt_me_reader_eof_total 8340
telemt_me_route_drop_no_conn_total 318238
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 744
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 10
telemt_pool_force_close_total 433
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 8345
telemt_me_writer_restored_same_endpoint_total 8239
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 569945
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 9803881552 (9.13 GB)
telemt_user_octets_to_client{user="hello"} 191280130304 (178.14 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 30
```