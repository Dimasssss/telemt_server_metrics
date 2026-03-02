# Server Metrics 2026-03-02 20:08:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 190678.7 (52h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3765434
telemt_connections_bad_total 56549
telemt_handshake_timeouts_total 312194
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 6612
telemt_me_reconnect_success_total 6618
telemt_me_route_drop_no_conn_total 1198287
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6708
telemt_desync_full_logged_total 2302
telemt_desync_suppressed_total 4406
telemt_desync_frames_bucket_total{bucket="1_2"} 2224
telemt_desync_frames_bucket_total{bucket="3_10"} 2224
telemt_desync_frames_bucket_total{bucket="gt_10"} 2260
telemt_pool_force_close_total 3337
telemt_pool_stale_pick_total 217995
telemt_me_writer_removed_unexpected_total 6550
telemt_me_writer_restored_same_endpoint_total 5913
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 3145392
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 79667764224 (74.20 GB)
telemt_user_octets_to_client{user="hello"} 1177953110228 (1.07 TB)
telemt_user_unique_ips_current{user="hello"} 97
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 190453.2 (52h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1701024
telemt_connections_bad_total 10224
telemt_handshake_timeouts_total 132352
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7126
telemt_me_reconnect_success_total 7748
telemt_me_route_drop_no_conn_total 477860
telemt_desync_total 4119
telemt_desync_full_logged_total 1320
telemt_desync_suppressed_total 2799
telemt_desync_frames_bucket_total{bucket="1_2"} 890
telemt_desync_frames_bucket_total{bucket="3_10"} 1720
telemt_desync_frames_bucket_total{bucket="gt_10"} 1509
telemt_pool_force_close_total 3355
telemt_pool_stale_pick_total 49926
telemt_me_writer_removed_unexpected_total 7509
telemt_me_writer_restored_same_endpoint_total 6626
telemt_me_writer_removed_unexpected_minus_restored_total 883
telemt_user_connections_total{user="hello"} 1316166
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 29752519488 (27.71 GB)
telemt_user_octets_to_client{user="hello"} 568486433248 (529.44 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 3343.4 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29808
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 371
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 395
telemt_me_reconnect_success_total 410
telemt_me_reader_eof_total 394
telemt_me_route_drop_no_conn_total 8333
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 541
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_desync_total 84
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_me_writer_removed_unexpected_total 396
telemt_me_writer_restored_same_endpoint_total 389
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 27180
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 1703623748 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 11660677980 (10.86 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 3304.4 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35921
telemt_connections_bad_total 13665
telemt_handshake_timeouts_total 2466
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 363
telemt_me_reconnect_success_total 389
telemt_me_reader_eof_total 370
telemt_me_route_drop_no_conn_total 6926
telemt_me_kdf_drift_total 544
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_desync_total 24
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 371
telemt_me_writer_restored_same_endpoint_total 355
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 18528
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 119332204 (113.80 MB)
telemt_user_octets_to_client{user="hello"} 7072499972 (6.59 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 190502.7 (52h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2737815
telemt_connections_bad_total 38598
telemt_handshake_timeouts_total 270534
telemt_me_keepalive_timeout_total 230
telemt_me_reconnect_attempts_total 6509
telemt_me_reconnect_success_total 6994
telemt_me_route_drop_no_conn_total 1009307
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4432
telemt_desync_full_logged_total 1276
telemt_desync_suppressed_total 3156
telemt_desync_frames_bucket_total{bucket="1_2"} 1209
telemt_desync_frames_bucket_total{bucket="3_10"} 1774
telemt_desync_frames_bucket_total{bucket="gt_10"} 1449
telemt_pool_force_close_total 3434
telemt_pool_stale_pick_total 113530
telemt_me_writer_removed_unexpected_total 6838
telemt_me_writer_restored_same_endpoint_total 6119
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 2280918
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 35411245460 (32.98 GB)
telemt_user_octets_to_client{user="hello"} 806517311536 (751.13 GB)
telemt_user_unique_ips_current{user="hello"} 31
```