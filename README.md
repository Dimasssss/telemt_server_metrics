# Server Metrics 2026-03-02 20:44:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 192838.4 (53h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3796368
telemt_connections_bad_total 56652
telemt_handshake_timeouts_total 313049
telemt_me_keepalive_timeout_total 323
telemt_me_reconnect_attempts_total 6804
telemt_me_reconnect_success_total 6808
telemt_me_route_drop_no_conn_total 1208112
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6770
telemt_desync_full_logged_total 2327
telemt_desync_suppressed_total 4443
telemt_desync_frames_bucket_total{bucket="1_2"} 2246
telemt_desync_frames_bucket_total{bucket="3_10"} 2240
telemt_desync_frames_bucket_total{bucket="gt_10"} 2284
telemt_pool_force_close_total 3381
telemt_pool_stale_pick_total 220454
telemt_me_writer_removed_unexpected_total 6741
telemt_me_writer_restored_same_endpoint_total 6103
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3173360
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 80188669044 (74.68 GB)
telemt_user_octets_to_client{user="hello"} 1195157813764 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 89
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 192612.7 (53h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1714354
telemt_connections_bad_total 10236
telemt_handshake_timeouts_total 132463
telemt_me_keepalive_timeout_total 264
telemt_me_reconnect_attempts_total 7214
telemt_me_reconnect_success_total 7836
telemt_me_route_drop_no_conn_total 482034
telemt_desync_total 4178
telemt_desync_full_logged_total 1336
telemt_desync_suppressed_total 2842
telemt_desync_frames_bucket_total{bucket="1_2"} 902
telemt_desync_frames_bucket_total{bucket="3_10"} 1747
telemt_desync_frames_bucket_total{bucket="gt_10"} 1529
telemt_pool_force_close_total 3391
telemt_pool_stale_pick_total 50710
telemt_me_writer_removed_unexpected_total 7599
telemt_me_writer_restored_same_endpoint_total 6705
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 1329191
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 29895002620 (27.84 GB)
telemt_user_octets_to_client{user="hello"} 573736657764 (534.33 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 5503.0 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46531
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 451
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 806
telemt_me_reconnect_success_total 817
telemt_me_reader_eof_total 806
telemt_me_route_drop_no_conn_total 17351
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1027
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_desync_total 179
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_me_writer_removed_unexpected_total 808
telemt_me_writer_restored_same_endpoint_total 796
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 42559
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 1799382640 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 16040656488 (14.94 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 5463.7 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47775
telemt_connections_bad_total 15854
telemt_handshake_timeouts_total 4078
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 755
telemt_me_reconnect_success_total 779
telemt_me_reader_eof_total 762
telemt_me_route_drop_no_conn_total 11773
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1031
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_desync_total 65
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 763
telemt_me_writer_restored_same_endpoint_total 745
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 26376
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 226392912 (215.91 MB)
telemt_user_octets_to_client{user="hello"} 10455057344 (9.74 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 192662.2 (53h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2759629
telemt_connections_bad_total 38610
telemt_handshake_timeouts_total 270554
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6592
telemt_me_reconnect_success_total 7087
telemt_me_route_drop_no_conn_total 1022645
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4510
telemt_desync_full_logged_total 1297
telemt_desync_suppressed_total 3213
telemt_desync_frames_bucket_total{bucket="1_2"} 1239
telemt_desync_frames_bucket_total{bucket="3_10"} 1803
telemt_desync_frames_bucket_total{bucket="gt_10"} 1468
telemt_pool_force_close_total 3487
telemt_pool_stale_pick_total 114652
telemt_me_writer_removed_unexpected_total 6930
telemt_me_writer_restored_same_endpoint_total 6193
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 2302063
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 35569048468 (33.13 GB)
telemt_user_octets_to_client{user="hello"} 812452511444 (756.66 GB)
telemt_user_unique_ips_current{user="hello"} 48
```