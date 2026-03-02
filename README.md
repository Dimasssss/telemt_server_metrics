# Server Metrics 2026-03-02 19:52:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 189753.3 (52h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3747835
telemt_connections_bad_total 56549
telemt_handshake_timeouts_total 311668
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 6568
telemt_me_reconnect_success_total 6570
telemt_me_route_drop_no_conn_total 1192993
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6646
telemt_desync_full_logged_total 2282
telemt_desync_suppressed_total 4364
telemt_desync_frames_bucket_total{bucket="1_2"} 2205
telemt_desync_frames_bucket_total{bucket="3_10"} 2201
telemt_desync_frames_bucket_total{bucket="gt_10"} 2240
telemt_pool_force_close_total 3316
telemt_pool_stale_pick_total 216950
telemt_me_writer_removed_unexpected_total 6503
telemt_me_writer_restored_same_endpoint_total 5872
telemt_me_writer_removed_unexpected_minus_restored_total 631
telemt_user_connections_total{user="hello"} 3129253
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 79325802372 (73.88 GB)
telemt_user_octets_to_client{user="hello"} 1173334444712 (1.07 TB)
telemt_user_unique_ips_current{user="hello"} 102
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 189527.5 (52h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1692494
telemt_connections_bad_total 10223
telemt_handshake_timeouts_total 131761
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7091
telemt_me_reconnect_success_total 7707
telemt_me_route_drop_no_conn_total 474240
telemt_desync_total 4053
telemt_desync_full_logged_total 1308
telemt_desync_suppressed_total 2745
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 1697
telemt_desync_frames_bucket_total{bucket="gt_10"} 1494
telemt_pool_force_close_total 3339
telemt_pool_stale_pick_total 49687
telemt_me_writer_removed_unexpected_total 7469
telemt_me_writer_restored_same_endpoint_total 6591
telemt_me_writer_removed_unexpected_minus_restored_total 878
telemt_user_connections_total{user="hello"} 1308332
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 29691332684 (27.65 GB)
telemt_user_octets_to_client{user="hello"} 565306574948 (526.48 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 2418.0 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22089
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 220
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 264
telemt_me_reconnect_success_total 280
telemt_me_reader_eof_total 261
telemt_me_route_drop_no_conn_total 5747
telemt_me_kdf_drift_total 379
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_desync_total 63
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_removed_unexpected_total 263
telemt_me_writer_restored_same_endpoint_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 20553
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 1639315672 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 6550783072 (6.10 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 2378.7 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28707
telemt_connections_bad_total 11573
telemt_handshake_timeouts_total 1784
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 236
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 242
telemt_me_route_drop_no_conn_total 4984
telemt_me_kdf_drift_total 344
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_desync_total 4
telemt_desync_full_logged_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 14325
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 66902496 (63.80 MB)
telemt_user_octets_to_client{user="hello"} 5645930884 (5.26 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 189577.1 (52h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2727889
telemt_connections_bad_total 38594
telemt_handshake_timeouts_total 270520
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 6468
telemt_me_reconnect_success_total 6952
telemt_me_route_drop_no_conn_total 1005672
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4411
telemt_desync_full_logged_total 1269
telemt_desync_suppressed_total 3142
telemt_desync_frames_bucket_total{bucket="1_2"} 1206
telemt_desync_frames_bucket_total{bucket="3_10"} 1765
telemt_desync_frames_bucket_total{bucket="gt_10"} 1440
telemt_pool_force_close_total 3410
telemt_pool_stale_pick_total 112857
telemt_me_writer_removed_unexpected_total 6797
telemt_me_writer_restored_same_endpoint_total 6078
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 2271326
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 35339772724 (32.91 GB)
telemt_user_octets_to_client{user="hello"} 804223123888 (748.99 GB)
telemt_user_unique_ips_current{user="hello"} 53
```