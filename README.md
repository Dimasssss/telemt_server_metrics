# Server Metrics 2026-03-02 21:20:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 194999.8 (54h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3818657
telemt_connections_bad_total 56673
telemt_handshake_timeouts_total 313154
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 7004
telemt_me_reconnect_success_total 7006
telemt_me_route_drop_no_conn_total 1215735
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6840
telemt_desync_full_logged_total 2346
telemt_desync_suppressed_total 4494
telemt_desync_frames_bucket_total{bucket="1_2"} 2268
telemt_desync_frames_bucket_total{bucket="3_10"} 2265
telemt_desync_frames_bucket_total{bucket="gt_10"} 2307
telemt_pool_force_close_total 3420
telemt_pool_stale_pick_total 222085
telemt_me_writer_removed_unexpected_total 6941
telemt_me_writer_restored_same_endpoint_total 6300
telemt_me_writer_removed_unexpected_minus_restored_total 641
telemt_user_connections_total{user="hello"} 3194714
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 81173460308 (75.60 GB)
telemt_user_octets_to_client{user="hello"} 1204231077660 (1.10 TB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 194774.2 (54h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1726910
telemt_connections_bad_total 10239
telemt_handshake_timeouts_total 132507
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 7329
telemt_me_reconnect_success_total 7934
telemt_me_route_drop_no_conn_total 488372
telemt_desync_total 4384
telemt_desync_full_logged_total 1374
telemt_desync_suppressed_total 3010
telemt_desync_frames_bucket_total{bucket="1_2"} 951
telemt_desync_frames_bucket_total{bucket="3_10"} 1828
telemt_desync_frames_bucket_total{bucket="gt_10"} 1605
telemt_pool_force_close_total 3448
telemt_pool_stale_pick_total 51108
telemt_me_writer_removed_unexpected_total 7693
telemt_me_writer_restored_same_endpoint_total 6788
telemt_me_writer_removed_unexpected_minus_restored_total 905
telemt_user_connections_total{user="hello"} 1341500
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 30489888892 (28.40 GB)
telemt_user_octets_to_client{user="hello"} 577973456216 (538.28 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 7664.1 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60936
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 490
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 1197
telemt_me_reconnect_success_total 1209
telemt_me_reader_eof_total 1203
telemt_me_route_drop_no_conn_total 22912
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1497
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_desync_total 274
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 170
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1207
telemt_me_writer_restored_same_endpoint_total 1183
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 55887
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 1860281100 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 20301878112 (18.91 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 7625.2 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54597
telemt_connections_bad_total 15928
telemt_handshake_timeouts_total 4097
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1868
telemt_me_reconnect_success_total 1891
telemt_me_reader_eof_total 1871
telemt_me_route_drop_no_conn_total 16419
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 2285
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_desync_total 99
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 1892
telemt_me_writer_restored_same_endpoint_total 1857
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 32930
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 303447596 (289.39 MB)
telemt_user_octets_to_client{user="hello"} 12007778128 (11.18 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 194823.4 (54h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2792475
telemt_connections_bad_total 38611
telemt_handshake_timeouts_total 271229
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6605
telemt_me_reconnect_success_total 7103
telemt_me_route_drop_no_conn_total 1030352
telemt_me_route_drop_channel_closed_total 45
telemt_desync_total 4540
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 3235
telemt_desync_frames_bucket_total{bucket="1_2"} 1249
telemt_desync_frames_bucket_total{bucket="3_10"} 1815
telemt_desync_frames_bucket_total{bucket="gt_10"} 1476
telemt_pool_force_close_total 3509
telemt_pool_stale_pick_total 116133
telemt_me_writer_removed_unexpected_total 6945
telemt_me_writer_restored_same_endpoint_total 6206
telemt_me_writer_removed_unexpected_minus_restored_total 739
telemt_user_connections_total{user="hello"} 2331407
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 36915751596 (34.38 GB)
telemt_user_octets_to_client{user="hello"} 816565329144 (760.49 GB)
telemt_user_unique_ips_current{user="hello"} 48
```