# Server Metrics 2026-03-02 19:42:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 189135.7 (52h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3734549
telemt_connections_bad_total 56437
telemt_handshake_timeouts_total 311244
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 6548
telemt_me_reconnect_success_total 6550
telemt_me_route_drop_no_conn_total 1189459
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6641
telemt_desync_full_logged_total 2278
telemt_desync_suppressed_total 4363
telemt_desync_frames_bucket_total{bucket="1_2"} 2203
telemt_desync_frames_bucket_total{bucket="3_10"} 2200
telemt_desync_frames_bucket_total{bucket="gt_10"} 2238
telemt_pool_force_close_total 3295
telemt_pool_stale_pick_total 215055
telemt_me_writer_removed_unexpected_total 6483
telemt_me_writer_restored_same_endpoint_total 5853
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 3117211
telemt_user_connections_current{user="hello"} 779
telemt_user_octets_from_client{user="hello"} 76995662888 (71.71 GB)
telemt_user_octets_to_client{user="hello"} 1169947350508 (1.06 TB)
telemt_user_unique_ips_current{user="hello"} 71
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 188910.1 (52h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1687562
telemt_connections_bad_total 10215
telemt_handshake_timeouts_total 131725
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 7071
telemt_me_reconnect_success_total 7686
telemt_me_route_drop_no_conn_total 473001
telemt_desync_total 4045
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 2740
telemt_desync_frames_bucket_total{bucket="1_2"} 861
telemt_desync_frames_bucket_total{bucket="3_10"} 1692
telemt_desync_frames_bucket_total{bucket="gt_10"} 1492
telemt_pool_force_close_total 3319
telemt_pool_stale_pick_total 49687
telemt_me_writer_removed_unexpected_total 7447
telemt_me_writer_restored_same_endpoint_total 6575
telemt_me_writer_removed_unexpected_minus_restored_total 872
telemt_user_connections_total{user="hello"} 1303536
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 29654996780 (27.62 GB)
telemt_user_octets_to_client{user="hello"} 562647026140 (524.01 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 1800.3 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17373
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 182
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 165
telemt_me_reconnect_success_total 181
telemt_me_reader_eof_total 161
telemt_me_route_drop_no_conn_total 4015
telemt_me_kdf_drift_total 245
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_desync_total 54
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 163
telemt_me_writer_restored_same_endpoint_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 16175
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 1585680348 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 4150439112 (3.87 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 1761.2 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23531
telemt_connections_bad_total 10190
telemt_handshake_timeouts_total 1282
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 152
telemt_me_reconnect_success_total 177
telemt_me_reader_eof_total 158
telemt_me_route_drop_no_conn_total 3346
telemt_me_kdf_drift_total 230
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_me_writer_removed_unexpected_total 158
telemt_me_writer_restored_same_endpoint_total 146
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 11214
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 46786264 (44.62 MB)
telemt_user_octets_to_client{user="hello"} 3942762668 (3.67 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 188959.7 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2718721
telemt_connections_bad_total 38573
telemt_handshake_timeouts_total 270403
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 6448
telemt_me_reconnect_success_total 6932
telemt_me_route_drop_no_conn_total 999144
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4400
telemt_desync_full_logged_total 1264
telemt_desync_suppressed_total 3136
telemt_desync_frames_bucket_total{bucket="1_2"} 1204
telemt_desync_frames_bucket_total{bucket="3_10"} 1759
telemt_desync_frames_bucket_total{bucket="gt_10"} 1437
telemt_pool_force_close_total 3410
telemt_pool_stale_pick_total 108191
telemt_me_writer_removed_unexpected_total 6775
telemt_me_writer_restored_same_endpoint_total 6058
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 2262732
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 35288818288 (32.87 GB)
telemt_user_octets_to_client{user="hello"} 802202441924 (747.11 GB)
telemt_user_unique_ips_current{user="hello"} 49
```