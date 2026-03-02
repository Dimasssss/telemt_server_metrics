# Server Metrics 2026-03-02 21:15:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 194691.8 (54h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3815174
telemt_connections_bad_total 56673
telemt_handshake_timeouts_total 313132
telemt_me_keepalive_timeout_total 325
telemt_me_reconnect_attempts_total 6985
telemt_me_reconnect_success_total 6988
telemt_me_route_drop_no_conn_total 1214838
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6830
telemt_desync_full_logged_total 2342
telemt_desync_suppressed_total 4488
telemt_desync_frames_bucket_total{bucket="1_2"} 2265
telemt_desync_frames_bucket_total{bucket="3_10"} 2259
telemt_desync_frames_bucket_total{bucket="gt_10"} 2306
telemt_pool_force_close_total 3401
telemt_pool_stale_pick_total 222085
telemt_me_writer_removed_unexpected_total 6920
telemt_me_writer_restored_same_endpoint_total 6282
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3191407
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 80958355912 (75.40 GB)
telemt_user_octets_to_client{user="hello"} 1203080271028 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 194466.0 (54h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1724934
telemt_connections_bad_total 10239
telemt_handshake_timeouts_total 132506
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 7315
telemt_me_reconnect_success_total 7916
telemt_me_route_drop_no_conn_total 487792
telemt_desync_total 4367
telemt_desync_full_logged_total 1368
telemt_desync_suppressed_total 2999
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 1822
telemt_desync_frames_bucket_total{bucket="gt_10"} 1598
telemt_pool_force_close_total 3428
telemt_pool_stale_pick_total 50911
telemt_me_writer_removed_unexpected_total 7678
telemt_me_writer_restored_same_endpoint_total 6774
telemt_me_writer_removed_unexpected_minus_restored_total 904
telemt_user_connections_total{user="hello"} 1339546
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 30479090800 (28.39 GB)
telemt_user_octets_to_client{user="hello"} 576897162836 (537.28 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 7356.1 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59083
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 483
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 1141
telemt_me_reconnect_success_total 1154
telemt_me_reader_eof_total 1147
telemt_me_route_drop_no_conn_total 22505
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1415
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_desync_total 260
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 158
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1151
telemt_me_writer_restored_same_endpoint_total 1128
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 54154
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 1854167484 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 19802719644 (18.44 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 7317.1 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53344
telemt_connections_bad_total 15928
telemt_handshake_timeouts_total 4091
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1656
telemt_me_reconnect_success_total 1679
telemt_me_reader_eof_total 1656
telemt_me_route_drop_no_conn_total 15820
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 2045
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_desync_total 99
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 1676
telemt_me_writer_restored_same_endpoint_total 1645
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 31718
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 291159328 (277.67 MB)
telemt_user_octets_to_client{user="hello"} 11829462060 (11.02 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 194515.4 (54h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2788125
telemt_connections_bad_total 38611
telemt_handshake_timeouts_total 271173
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6593
telemt_me_reconnect_success_total 7088
telemt_me_route_drop_no_conn_total 1029650
telemt_me_route_drop_channel_closed_total 45
telemt_desync_total 4537
telemt_desync_full_logged_total 1304
telemt_desync_suppressed_total 3233
telemt_desync_frames_bucket_total{bucket="1_2"} 1247
telemt_desync_frames_bucket_total{bucket="3_10"} 1814
telemt_desync_frames_bucket_total{bucket="gt_10"} 1476
telemt_pool_force_close_total 3498
telemt_pool_stale_pick_total 116133
telemt_me_writer_removed_unexpected_total 6931
telemt_me_writer_restored_same_endpoint_total 6194
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 2327547
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 36907222468 (34.37 GB)
telemt_user_octets_to_client{user="hello"} 816148700368 (760.10 GB)
telemt_user_unique_ips_current{user="hello"} 31
```