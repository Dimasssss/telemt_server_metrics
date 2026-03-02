# Server Metrics 2026-03-02 20:59:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 193763.6 (53h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3805877
telemt_connections_bad_total 56673
telemt_handshake_timeouts_total 313084
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 6900
telemt_me_reconnect_success_total 6903
telemt_me_route_drop_no_conn_total 1211596
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6810
telemt_desync_full_logged_total 2338
telemt_desync_suppressed_total 4472
telemt_desync_frames_bucket_total{bucket="1_2"} 2264
telemt_desync_frames_bucket_total{bucket="3_10"} 2250
telemt_desync_frames_bucket_total{bucket="gt_10"} 2296
telemt_pool_force_close_total 3381
telemt_pool_stale_pick_total 221735
telemt_me_writer_removed_unexpected_total 6836
telemt_me_writer_restored_same_endpoint_total 6198
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3182410
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 80525012956 (74.99 GB)
telemt_user_octets_to_client{user="hello"} 1198799675596 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 193538.2 (53h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1719812
telemt_connections_bad_total 10237
telemt_handshake_timeouts_total 132485
telemt_me_keepalive_timeout_total 290
telemt_me_reconnect_attempts_total 7255
telemt_me_reconnect_success_total 7871
telemt_me_route_drop_no_conn_total 485525
telemt_desync_total 4304
telemt_desync_full_logged_total 1351
telemt_desync_suppressed_total 2953
telemt_desync_frames_bucket_total{bucket="1_2"} 936
telemt_desync_frames_bucket_total{bucket="3_10"} 1795
telemt_desync_frames_bucket_total{bucket="gt_10"} 1573
telemt_pool_force_close_total 3411
telemt_pool_stale_pick_total 50808
telemt_me_writer_removed_unexpected_total 7633
telemt_me_writer_restored_same_endpoint_total 6736
telemt_me_writer_removed_unexpected_minus_restored_total 897
telemt_user_connections_total{user="hello"} 1334537
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 30439492544 (28.35 GB)
telemt_user_octets_to_client{user="hello"} 575324803536 (535.81 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 6428.3 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52912
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 466
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1072
telemt_me_reconnect_success_total 1082
telemt_me_reader_eof_total 1076
telemt_me_route_drop_no_conn_total 20995
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1319
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_desync_total 212
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_me_writer_removed_unexpected_total 1078
telemt_me_writer_restored_same_endpoint_total 1061
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 48410
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 1833084972 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 18119986416 (16.88 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 6389.5 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50375
telemt_connections_bad_total 15867
telemt_handshake_timeouts_total 4079
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 1075
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 1082
telemt_me_route_drop_no_conn_total 14017
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1389
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_desync_total 98
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 1083
telemt_me_writer_restored_same_endpoint_total 1064
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 28903
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 259643104 (247.61 MB)
telemt_user_octets_to_client{user="hello"} 11207365732 (10.44 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 193587.3 (53h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2773933
telemt_connections_bad_total 38611
telemt_handshake_timeouts_total 270893
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6592
telemt_me_reconnect_success_total 7087
telemt_me_route_drop_no_conn_total 1026765
telemt_me_route_drop_channel_closed_total 45
telemt_desync_total 4537
telemt_desync_full_logged_total 1304
telemt_desync_suppressed_total 3233
telemt_desync_frames_bucket_total{bucket="1_2"} 1247
telemt_desync_frames_bucket_total{bucket="3_10"} 1814
telemt_desync_frames_bucket_total{bucket="gt_10"} 1476
telemt_pool_force_close_total 3487
telemt_pool_stale_pick_total 115811
telemt_me_writer_removed_unexpected_total 6930
telemt_me_writer_restored_same_endpoint_total 6193
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 2314927
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 36878699416 (34.35 GB)
telemt_user_octets_to_client{user="hello"} 814916745864 (758.95 GB)
telemt_user_unique_ips_current{user="hello"} 37
```