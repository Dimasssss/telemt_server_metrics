# Server Metrics 2026-03-03 21:01:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 52775.8 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1315275
telemt_connections_bad_total 10313
telemt_handshake_timeouts_total 14948
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 4435
telemt_me_reconnect_success_total 4410
telemt_me_reader_eof_total 4436
telemt_me_route_drop_no_conn_total 509923
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 212
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 3227
telemt_desync_full_logged_total 1035
telemt_desync_suppressed_total 2192
telemt_desync_frames_bucket_total{bucket="1_2"} 889
telemt_desync_frames_bucket_total{bucket="3_10"} 1098
telemt_desync_frames_bucket_total{bucket="gt_10"} 1240
telemt_pool_swap_total 16
telemt_pool_force_close_total 809
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4438
telemt_me_writer_restored_same_endpoint_total 4369
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1089181
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 18600969216 (17.32 GB)
telemt_user_octets_to_client{user="hello"} 426206758328 (396.94 GB)
telemt_user_unique_ips_current{user="hello"} 69
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 52773.0 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 589897
telemt_connections_bad_total 5293
telemt_handshake_timeouts_total 36234
telemt_me_keepalive_timeout_total 431
telemt_me_reconnect_attempts_total 4032
telemt_me_reconnect_success_total 4028
telemt_me_reader_eof_total 4024
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 270124
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 217
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 721
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 475
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 20
telemt_pool_force_close_total 765
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 4098
telemt_me_writer_restored_same_endpoint_total 3967
telemt_me_writer_restored_fallback_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 533632
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 8597120772 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 213985592376 (199.29 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 5689.2 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68945
telemt_connections_bad_total 12902
telemt_handshake_timeouts_total 848
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 1305
telemt_me_reconnect_success_total 1316
telemt_me_reader_eof_total 1318
telemt_me_route_drop_no_conn_total 42834
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 249
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_me_writer_removed_unexpected_total 1321
telemt_me_writer_restored_same_endpoint_total 1290
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 50827
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 340741616 (324.96 MB)
telemt_user_octets_to_client{user="hello"} 14436607024 (13.45 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 5421.6 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28612
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 2536
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 452
telemt_me_reconnect_success_total 481
telemt_me_reader_eof_total 463
telemt_me_route_drop_no_conn_total 10369
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 21
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 4
telemt_pool_force_close_total 66
telemt_me_writer_removed_unexpected_total 463
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 25342
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 749687144 (714.96 MB)
telemt_user_octets_to_client{user="hello"} 15253903560 (14.21 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 50325.9 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806331
telemt_connections_bad_total 7234
telemt_handshake_timeouts_total 201663
telemt_me_keepalive_timeout_total 201
telemt_me_reconnect_attempts_total 8603
telemt_me_reconnect_success_total 8570
telemt_me_reader_eof_total 8641
telemt_me_route_drop_no_conn_total 321373
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 199
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
telemt_me_writer_removed_unexpected_total 8646
telemt_me_writer_restored_same_endpoint_total 8533
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 576858
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 9936605840 (9.25 GB)
telemt_user_octets_to_client{user="hello"} 193914302560 (180.60 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 33
```