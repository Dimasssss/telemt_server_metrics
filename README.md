# Server Metrics 2026-03-02 20:33:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 192221.0 (53h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3789632
telemt_connections_bad_total 56632
telemt_handshake_timeouts_total 312873
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 6746
telemt_me_reconnect_success_total 6749
telemt_me_route_drop_no_conn_total 1205784
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6755
telemt_desync_full_logged_total 2322
telemt_desync_suppressed_total 4433
telemt_desync_frames_bucket_total{bucket="1_2"} 2239
telemt_desync_frames_bucket_total{bucket="3_10"} 2237
telemt_desync_frames_bucket_total{bucket="gt_10"} 2279
telemt_pool_force_close_total 3362
telemt_pool_stale_pick_total 219804
telemt_me_writer_removed_unexpected_total 6683
telemt_me_writer_restored_same_endpoint_total 6044
telemt_me_writer_removed_unexpected_minus_restored_total 639
telemt_user_connections_total{user="hello"} 3167156
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 80116028228 (74.61 GB)
telemt_user_octets_to_client{user="hello"} 1190774391320 (1.08 TB)
telemt_user_unique_ips_current{user="hello"} 74
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 191995.4 (53h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1710951
telemt_connections_bad_total 10225
telemt_handshake_timeouts_total 132415
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7201
telemt_me_reconnect_success_total 7822
telemt_me_route_drop_no_conn_total 481032
telemt_desync_total 4168
telemt_desync_full_logged_total 1333
telemt_desync_suppressed_total 2835
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1742
telemt_desync_frames_bucket_total{bucket="gt_10"} 1525
telemt_pool_force_close_total 3391
telemt_pool_stale_pick_total 50561
telemt_me_writer_removed_unexpected_total 7585
telemt_me_writer_restored_same_endpoint_total 6692
telemt_me_writer_removed_unexpected_minus_restored_total 893
telemt_user_connections_total{user="hello"} 1325893
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 29860213688 (27.81 GB)
telemt_user_octets_to_client{user="hello"} 572256018108 (532.95 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 4885.8 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42395
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 437
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 682
telemt_me_reconnect_success_total 694
telemt_me_reader_eof_total 680
telemt_me_route_drop_no_conn_total 14886
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 886
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_desync_total 145
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_me_writer_removed_unexpected_total 682
telemt_me_writer_restored_same_endpoint_total 673
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 38710
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 1766922248 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 14735572040 (13.72 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 4846.5 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45579
telemt_connections_bad_total 15854
telemt_handshake_timeouts_total 3733
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 599
telemt_me_reconnect_success_total 624
telemt_me_reader_eof_total 607
telemt_me_route_drop_no_conn_total 10294
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 852
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 608
telemt_me_writer_restored_same_endpoint_total 590
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 24533
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 201241068 (191.92 MB)
telemt_user_octets_to_client{user="hello"} 10096700864 (9.40 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 192044.9 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2754557
telemt_connections_bad_total 38608
telemt_handshake_timeouts_total 270546
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6571
telemt_me_reconnect_success_total 7064
telemt_me_route_drop_no_conn_total 1020925
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4489
telemt_desync_full_logged_total 1292
telemt_desync_suppressed_total 3197
telemt_desync_frames_bucket_total{bucket="1_2"} 1234
telemt_desync_frames_bucket_total{bucket="3_10"} 1794
telemt_desync_frames_bucket_total{bucket="gt_10"} 1461
telemt_pool_force_close_total 3470
telemt_pool_stale_pick_total 114266
telemt_me_writer_removed_unexpected_total 6906
telemt_me_writer_restored_same_endpoint_total 6175
telemt_me_writer_removed_unexpected_minus_restored_total 731
telemt_user_connections_total{user="hello"} 2297143
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 35547073896 (33.11 GB)
telemt_user_octets_to_client{user="hello"} 810463590324 (754.80 GB)
telemt_user_unique_ips_current{user="hello"} 55
```