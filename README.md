# Server Metrics 2026-03-02 20:13:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 190987.6 (53h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3770727
telemt_connections_bad_total 56551
telemt_handshake_timeouts_total 312323
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 6635
telemt_me_reconnect_success_total 6641
telemt_me_route_drop_no_conn_total 1200000
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6713
telemt_desync_full_logged_total 2305
telemt_desync_suppressed_total 4408
telemt_desync_frames_bucket_total{bucket="1_2"} 2227
telemt_desync_frames_bucket_total{bucket="3_10"} 2226
telemt_desync_frames_bucket_total{bucket="gt_10"} 2260
telemt_pool_force_close_total 3337
telemt_pool_stale_pick_total 217995
telemt_me_writer_removed_unexpected_total 6573
telemt_me_writer_restored_same_endpoint_total 5936
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 3150302
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 79772752080 (74.29 GB)
telemt_user_octets_to_client{user="hello"} 1179564347016 (1.07 TB)
telemt_user_unique_ips_current{user="hello"} 84
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 190761.8 (52h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1703060
telemt_connections_bad_total 10224
telemt_handshake_timeouts_total 132356
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7138
telemt_me_reconnect_success_total 7759
telemt_me_route_drop_no_conn_total 478592
telemt_desync_total 4127
telemt_desync_full_logged_total 1324
telemt_desync_suppressed_total 2803
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1723
telemt_desync_frames_bucket_total{bucket="gt_10"} 1512
telemt_pool_force_close_total 3355
telemt_pool_stale_pick_total 50336
telemt_me_writer_removed_unexpected_total 7521
telemt_me_writer_restored_same_endpoint_total 6634
telemt_me_writer_removed_unexpected_minus_restored_total 887
telemt_user_connections_total{user="hello"} 1318188
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 29774285484 (27.73 GB)
telemt_user_octets_to_client{user="hello"} 569118209272 (530.03 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 3652.1 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32920
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 381
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 421
telemt_me_reconnect_success_total 436
telemt_me_reader_eof_total 420
telemt_me_route_drop_no_conn_total 10283
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 568
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_desync_total 101
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_restored_same_endpoint_total 415
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 30102
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 1723171888 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 12410149444 (11.56 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 3613.0 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38105
telemt_connections_bad_total 14367
telemt_handshake_timeouts_total 2687
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 372
telemt_me_reconnect_success_total 398
telemt_me_reader_eof_total 379
telemt_me_route_drop_no_conn_total 7726
telemt_me_kdf_drift_total 553
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_desync_total 25
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 380
telemt_me_writer_restored_same_endpoint_total 364
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 19761
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 166402596 (158.69 MB)
telemt_user_octets_to_client{user="hello"} 7483749576 (6.97 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 190811.6 (53h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2741260
telemt_connections_bad_total 38599
telemt_handshake_timeouts_total 270536
telemt_me_keepalive_timeout_total 230
telemt_me_reconnect_attempts_total 6520
telemt_me_reconnect_success_total 7007
telemt_me_route_drop_no_conn_total 1010413
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4447
telemt_desync_full_logged_total 1279
telemt_desync_suppressed_total 3168
telemt_desync_frames_bucket_total{bucket="1_2"} 1216
telemt_desync_frames_bucket_total{bucket="3_10"} 1777
telemt_desync_frames_bucket_total{bucket="gt_10"} 1454
telemt_pool_force_close_total 3450
telemt_pool_stale_pick_total 113987
telemt_me_writer_removed_unexpected_total 6850
telemt_me_writer_restored_same_endpoint_total 6128
telemt_me_writer_removed_unexpected_minus_restored_total 722
telemt_user_connections_total{user="hello"} 2284208
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 35447165748 (33.01 GB)
telemt_user_octets_to_client{user="hello"} 807774192924 (752.30 GB)
telemt_user_unique_ips_current{user="hello"} 61
```