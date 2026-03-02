# Server Metrics 2026-03-02 21:25:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 195307.9 (54h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3821810
telemt_connections_bad_total 56673
telemt_handshake_timeouts_total 313199
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 7012
telemt_me_reconnect_success_total 7014
telemt_me_route_drop_no_conn_total 1216462
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6840
telemt_desync_full_logged_total 2346
telemt_desync_suppressed_total 4494
telemt_desync_frames_bucket_total{bucket="1_2"} 2268
telemt_desync_frames_bucket_total{bucket="3_10"} 2265
telemt_desync_frames_bucket_total{bucket="gt_10"} 2307
telemt_pool_force_close_total 3420
telemt_pool_stale_pick_total 222085
telemt_me_writer_removed_unexpected_total 6949
telemt_me_writer_restored_same_endpoint_total 6308
telemt_me_writer_removed_unexpected_minus_restored_total 641
telemt_user_connections_total{user="hello"} 3197703
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 81350994340 (75.76 GB)
telemt_user_octets_to_client{user="hello"} 1205102117000 (1.10 TB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 195082.2 (54h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1728304
telemt_connections_bad_total 10239
telemt_handshake_timeouts_total 132507
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 7340
telemt_me_reconnect_success_total 7945
telemt_me_route_drop_no_conn_total 488933
telemt_desync_total 4395
telemt_desync_full_logged_total 1377
telemt_desync_suppressed_total 3018
telemt_desync_frames_bucket_total{bucket="1_2"} 952
telemt_desync_frames_bucket_total{bucket="3_10"} 1833
telemt_desync_frames_bucket_total{bucket="gt_10"} 1610
telemt_pool_force_close_total 3448
telemt_pool_stale_pick_total 51108
telemt_me_writer_removed_unexpected_total 7705
telemt_me_writer_restored_same_endpoint_total 6796
telemt_me_writer_removed_unexpected_minus_restored_total 909
telemt_user_connections_total{user="hello"} 1342862
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 30497038904 (28.40 GB)
telemt_user_octets_to_client{user="hello"} 578447088548 (538.72 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 7971.9 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62556
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 502
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 1235
telemt_me_reconnect_success_total 1247
telemt_me_reader_eof_total 1242
telemt_me_route_drop_no_conn_total 23309
telemt_me_route_drop_channel_closed_total 2
telemt_me_kdf_drift_total 1538
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_desync_total 294
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1246
telemt_me_writer_restored_same_endpoint_total 1221
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 57389
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1875893452 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 20755703980 (19.33 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 7933.1 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55414
telemt_connections_bad_total 15928
telemt_handshake_timeouts_total 4099
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2102
telemt_me_reconnect_success_total 2125
telemt_me_reader_eof_total 2106
telemt_me_route_drop_no_conn_total 17044
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 2544
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_desync_total 99
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 2127
telemt_me_writer_restored_same_endpoint_total 2091
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 33742
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 306219068 (292.03 MB)
telemt_user_octets_to_client{user="hello"} 12169629572 (11.33 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 195131.6 (54h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2795627
telemt_connections_bad_total 38611
telemt_handshake_timeouts_total 271270
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6616
telemt_me_reconnect_success_total 7114
telemt_me_route_drop_no_conn_total 1030919
telemt_me_route_drop_channel_closed_total 45
telemt_desync_total 4543
telemt_desync_full_logged_total 1306
telemt_desync_suppressed_total 3237
telemt_desync_frames_bucket_total{bucket="1_2"} 1250
telemt_desync_frames_bucket_total{bucket="3_10"} 1816
telemt_desync_frames_bucket_total{bucket="gt_10"} 1477
telemt_pool_force_close_total 3509
telemt_pool_stale_pick_total 116133
telemt_me_writer_removed_unexpected_total 6959
telemt_me_writer_restored_same_endpoint_total 6215
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 2334332
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 36925633228 (34.39 GB)
telemt_user_octets_to_client{user="hello"} 816973127776 (760.87 GB)
telemt_user_unique_ips_current{user="hello"} 41
```