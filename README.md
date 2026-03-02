# Server Metrics 2026-03-02 19:58:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 190062.0 (52h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3753324
telemt_connections_bad_total 56549
telemt_handshake_timeouts_total 311850
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 6581
telemt_me_reconnect_success_total 6583
telemt_me_route_drop_no_conn_total 1194669
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6670
telemt_desync_full_logged_total 2289
telemt_desync_suppressed_total 4381
telemt_desync_frames_bucket_total{bucket="1_2"} 2215
telemt_desync_frames_bucket_total{bucket="3_10"} 2209
telemt_desync_frames_bucket_total{bucket="gt_10"} 2246
telemt_pool_force_close_total 3316
telemt_pool_stale_pick_total 216950
telemt_me_writer_removed_unexpected_total 6515
telemt_me_writer_restored_same_endpoint_total 5882
telemt_me_writer_removed_unexpected_minus_restored_total 633
telemt_user_connections_total{user="hello"} 3134257
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 79420032452 (73.97 GB)
telemt_user_octets_to_client{user="hello"} 1174981050104 (1.07 TB)
telemt_user_unique_ips_current{user="hello"} 75
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 189836.5 (52h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1695300
telemt_connections_bad_total 10223
telemt_handshake_timeouts_total 131780
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7102
telemt_me_reconnect_success_total 7721
telemt_me_route_drop_no_conn_total 475077
telemt_desync_total 4073
telemt_desync_full_logged_total 1312
telemt_desync_suppressed_total 2761
telemt_desync_frames_bucket_total{bucket="1_2"} 873
telemt_desync_frames_bucket_total{bucket="3_10"} 1701
telemt_desync_frames_bucket_total{bucket="gt_10"} 1499
telemt_pool_force_close_total 3339
telemt_pool_stale_pick_total 49926
telemt_me_writer_removed_unexpected_total 7481
telemt_me_writer_restored_same_endpoint_total 6602
telemt_me_writer_removed_unexpected_minus_restored_total 879
telemt_user_connections_total{user="hello"} 1311092
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 29703542456 (27.66 GB)
telemt_user_octets_to_client{user="hello"} 566183606936 (527.30 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 2726.7 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24700
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 308
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 293
telemt_me_reconnect_success_total 308
telemt_me_reader_eof_total 289
telemt_me_route_drop_no_conn_total 6409
telemt_me_kdf_drift_total 407
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_desync_total 67
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_removed_unexpected_total 291
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 22786
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 1662392736 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 8212527196 (7.65 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 2687.5 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31143
telemt_connections_bad_total 12290
telemt_handshake_timeouts_total 2027
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 285
telemt_me_reconnect_success_total 310
telemt_me_reader_eof_total 291
telemt_me_route_drop_no_conn_total 5443
telemt_me_kdf_drift_total 403
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_desync_total 11
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 292
telemt_me_writer_restored_same_endpoint_total 279
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 15722
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 96836188 (92.35 MB)
telemt_user_octets_to_client{user="hello"} 6184227032 (5.76 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 189885.8 (52h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2731512
telemt_connections_bad_total 38594
telemt_handshake_timeouts_total 270531
telemt_me_keepalive_timeout_total 228
telemt_me_reconnect_attempts_total 6481
telemt_me_reconnect_success_total 6966
telemt_me_route_drop_no_conn_total 1007243
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4425
telemt_desync_full_logged_total 1272
telemt_desync_suppressed_total 3153
telemt_desync_frames_bucket_total{bucket="1_2"} 1207
telemt_desync_frames_bucket_total{bucket="3_10"} 1769
telemt_desync_frames_bucket_total{bucket="gt_10"} 1449
telemt_pool_force_close_total 3434
telemt_pool_stale_pick_total 113530
telemt_me_writer_removed_unexpected_total 6810
telemt_me_writer_restored_same_endpoint_total 6091
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 2274835
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 35381972164 (32.95 GB)
telemt_user_octets_to_client{user="hello"} 804968908224 (749.69 GB)
telemt_user_unique_ips_current{user="hello"} 69
```