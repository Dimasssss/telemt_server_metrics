# Server Metrics 2026-03-02 21:04:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 194073.2 (53h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3809053
telemt_connections_bad_total 56673
telemt_handshake_timeouts_total 313104
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 6925
telemt_me_reconnect_success_total 6928
telemt_me_route_drop_no_conn_total 1212541
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6817
telemt_desync_full_logged_total 2340
telemt_desync_suppressed_total 4477
telemt_desync_frames_bucket_total{bucket="1_2"} 2264
telemt_desync_frames_bucket_total{bucket="3_10"} 2253
telemt_desync_frames_bucket_total{bucket="gt_10"} 2300
telemt_pool_force_close_total 3401
telemt_pool_stale_pick_total 221735
telemt_me_writer_removed_unexpected_total 6861
telemt_me_writer_restored_same_endpoint_total 6223
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3185484
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 80586116224 (75.05 GB)
telemt_user_octets_to_client{user="hello"} 1200405143240 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 193847.8 (53h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1721665
telemt_connections_bad_total 10238
telemt_handshake_timeouts_total 132487
telemt_me_keepalive_timeout_total 291
telemt_me_reconnect_attempts_total 7292
telemt_me_reconnect_success_total 7890
telemt_me_route_drop_no_conn_total 486086
telemt_desync_total 4325
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2970
telemt_desync_frames_bucket_total{bucket="1_2"} 941
telemt_desync_frames_bucket_total{bucket="3_10"} 1804
telemt_desync_frames_bucket_total{bucket="gt_10"} 1580
telemt_pool_force_close_total 3428
telemt_pool_stale_pick_total 50901
telemt_me_writer_removed_unexpected_total 7654
telemt_me_writer_restored_same_endpoint_total 6753
telemt_me_writer_removed_unexpected_minus_restored_total 901
telemt_user_connections_total{user="hello"} 1336363
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 30457491700 (28.37 GB)
telemt_user_octets_to_client{user="hello"} 575789587388 (536.25 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 6738.1 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55106
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 470
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1103
telemt_me_reconnect_success_total 1113
telemt_me_reader_eof_total 1108
telemt_me_route_drop_no_conn_total 21627
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1366
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_desync_total 229
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1110
telemt_me_writer_restored_same_endpoint_total 1092
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 50471
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1840903604 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 18741278436 (17.45 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 6698.8 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51531
telemt_connections_bad_total 15927
telemt_handshake_timeouts_total 4091
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1225
telemt_me_reconnect_success_total 1247
telemt_me_reader_eof_total 1234
telemt_me_route_drop_no_conn_total 14677
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1583
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_desync_total 98
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 1235
telemt_me_writer_restored_same_endpoint_total 1213
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 29941
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 268035512 (255.62 MB)
telemt_user_octets_to_client{user="hello"} 11320788840 (10.54 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 193896.9 (53h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2779020
telemt_connections_bad_total 38611
telemt_handshake_timeouts_total 270990
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6592
telemt_me_reconnect_success_total 7087
telemt_me_route_drop_no_conn_total 1027832
telemt_me_route_drop_channel_closed_total 45
telemt_desync_total 4537
telemt_desync_full_logged_total 1304
telemt_desync_suppressed_total 3233
telemt_desync_frames_bucket_total{bucket="1_2"} 1247
telemt_desync_frames_bucket_total{bucket="3_10"} 1814
telemt_desync_frames_bucket_total{bucket="gt_10"} 1476
telemt_pool_force_close_total 3498
telemt_pool_stale_pick_total 115811
telemt_me_writer_removed_unexpected_total 6930
telemt_me_writer_restored_same_endpoint_total 6193
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 2319374
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 36886661000 (34.35 GB)
telemt_user_octets_to_client{user="hello"} 815419908788 (759.42 GB)
telemt_user_unique_ips_current{user="hello"} 43
```