# Server Metrics 2026-03-02 20:28:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 191912.2 (53h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3785504
telemt_connections_bad_total 56622
telemt_handshake_timeouts_total 312746
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 6716
telemt_me_reconnect_success_total 6720
telemt_me_route_drop_no_conn_total 1204570
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6733
telemt_desync_full_logged_total 2313
telemt_desync_suppressed_total 4420
telemt_desync_frames_bucket_total{bucket="1_2"} 2231
telemt_desync_frames_bucket_total{bucket="3_10"} 2233
telemt_desync_frames_bucket_total{bucket="gt_10"} 2269
telemt_pool_force_close_total 3362
telemt_pool_stale_pick_total 219804
telemt_me_writer_removed_unexpected_total 6653
telemt_me_writer_restored_same_endpoint_total 6015
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3163337
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 80052378664 (74.55 GB)
telemt_user_octets_to_client{user="hello"} 1187568621352 (1.08 TB)
telemt_user_unique_ips_current{user="hello"} 80
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 191686.7 (53h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1708974
telemt_connections_bad_total 10225
telemt_handshake_timeouts_total 132405
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7185
telemt_me_reconnect_success_total 7807
telemt_me_route_drop_no_conn_total 480364
telemt_desync_total 4167
telemt_desync_full_logged_total 1332
telemt_desync_suppressed_total 2835
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1741
telemt_desync_frames_bucket_total{bucket="gt_10"} 1525
telemt_pool_force_close_total 3372
telemt_pool_stale_pick_total 50561
telemt_me_writer_removed_unexpected_total 7571
telemt_me_writer_restored_same_endpoint_total 6679
telemt_me_writer_removed_unexpected_minus_restored_total 892
telemt_user_connections_total{user="hello"} 1323960
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 29834532228 (27.79 GB)
telemt_user_octets_to_client{user="hello"} 571342321004 (532.10 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 4576.7 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40159
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 427
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 581
telemt_me_reconnect_success_total 594
telemt_me_reader_eof_total 578
telemt_me_route_drop_no_conn_total 13955
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 759
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_desync_total 134
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_me_writer_removed_unexpected_total 580
telemt_me_writer_restored_same_endpoint_total 573
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 36625
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 1758167252 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 14003798652 (13.04 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 4537.8 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44021
telemt_connections_bad_total 15854
telemt_handshake_timeouts_total 3487
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 516
telemt_me_reconnect_success_total 542
telemt_me_reader_eof_total 523
telemt_me_route_drop_no_conn_total 9623
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 743
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_desync_total 34
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 524
telemt_me_writer_restored_same_endpoint_total 508
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 23265
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 192596976 (183.67 MB)
telemt_user_octets_to_client{user="hello"} 9670380448 (9.01 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 191735.9 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2751835
telemt_connections_bad_total 38608
telemt_handshake_timeouts_total 270546
telemt_me_keepalive_timeout_total 231
telemt_me_reconnect_attempts_total 6555
telemt_me_reconnect_success_total 7045
telemt_me_route_drop_no_conn_total 1020108
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4475
telemt_desync_full_logged_total 1289
telemt_desync_suppressed_total 3186
telemt_desync_frames_bucket_total{bucket="1_2"} 1226
telemt_desync_frames_bucket_total{bucket="3_10"} 1790
telemt_desync_frames_bucket_total{bucket="gt_10"} 1459
telemt_pool_force_close_total 3470
telemt_pool_stale_pick_total 114266
telemt_me_writer_removed_unexpected_total 6888
telemt_me_writer_restored_same_endpoint_total 6159
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 2294487
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 35529524264 (33.09 GB)
telemt_user_octets_to_client{user="hello"} 809645455556 (754.04 GB)
telemt_user_unique_ips_current{user="hello"} 71
```