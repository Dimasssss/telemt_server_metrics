# Server Metrics 2026-03-02 20:18:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 191295.9 (53h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3776389
telemt_connections_bad_total 56553
telemt_handshake_timeouts_total 312476
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 6655
telemt_me_reconnect_success_total 6660
telemt_me_route_drop_no_conn_total 1201428
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6718
telemt_desync_full_logged_total 2308
telemt_desync_suppressed_total 4410
telemt_desync_frames_bucket_total{bucket="1_2"} 2229
telemt_desync_frames_bucket_total{bucket="3_10"} 2228
telemt_desync_frames_bucket_total{bucket="gt_10"} 2261
telemt_pool_force_close_total 3337
telemt_pool_stale_pick_total 217995
telemt_me_writer_removed_unexpected_total 6592
telemt_me_writer_restored_same_endpoint_total 5955
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 3154824
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 79902855008 (74.42 GB)
telemt_user_octets_to_client{user="hello"} 1181996204432 (1.08 TB)
telemt_user_unique_ips_current{user="hello"} 74
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 191070.2 (53h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1705383
telemt_connections_bad_total 10225
telemt_handshake_timeouts_total 132377
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7161
telemt_me_reconnect_success_total 7782
telemt_me_route_drop_no_conn_total 479167
telemt_desync_total 4127
telemt_desync_full_logged_total 1324
telemt_desync_suppressed_total 2803
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1723
telemt_desync_frames_bucket_total{bucket="gt_10"} 1512
telemt_pool_force_close_total 3372
telemt_pool_stale_pick_total 50336
telemt_me_writer_removed_unexpected_total 7544
telemt_me_writer_restored_same_endpoint_total 6657
telemt_me_writer_removed_unexpected_minus_restored_total 887
telemt_user_connections_total{user="hello"} 1320467
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 29792615640 (27.75 GB)
telemt_user_octets_to_client{user="hello"} 569791941416 (530.66 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 3960.1 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35260
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 393
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 474
telemt_me_reconnect_success_total 486
telemt_me_reader_eof_total 472
telemt_me_route_drop_no_conn_total 11618
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 648
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_desync_total 110
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_me_writer_removed_unexpected_total 474
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 32299
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 1731645448 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 13038508812 (12.14 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 3921.0 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40265
telemt_connections_bad_total 15116
telemt_handshake_timeouts_total 2955
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 386
telemt_me_reconnect_success_total 412
telemt_me_reader_eof_total 393
telemt_me_route_drop_no_conn_total 8619
telemt_me_kdf_drift_total 583
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
telemt_me_writer_removed_unexpected_total 394
telemt_me_writer_restored_same_endpoint_total 378
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 20864
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 172234924 (164.26 MB)
telemt_user_octets_to_client{user="hello"} 8533904364 (7.95 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 191119.5 (53h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2744634
telemt_connections_bad_total 38606
telemt_handshake_timeouts_total 270538
telemt_me_keepalive_timeout_total 231
telemt_me_reconnect_attempts_total 6529
telemt_me_reconnect_success_total 7019
telemt_me_route_drop_no_conn_total 1011438
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4454
telemt_desync_full_logged_total 1281
telemt_desync_suppressed_total 3173
telemt_desync_frames_bucket_total{bucket="1_2"} 1219
telemt_desync_frames_bucket_total{bucket="3_10"} 1780
telemt_desync_frames_bucket_total{bucket="gt_10"} 1455
telemt_pool_force_close_total 3450
telemt_pool_stale_pick_total 113987
telemt_me_writer_removed_unexpected_total 6862
telemt_me_writer_restored_same_endpoint_total 6137
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 2287450
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 35466995660 (33.03 GB)
telemt_user_octets_to_client{user="hello"} 808320039960 (752.81 GB)
telemt_user_unique_ips_current{user="hello"} 44
```