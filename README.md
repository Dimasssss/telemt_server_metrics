# Server Metrics 2026-03-02 20:54:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 193455.5 (53h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3803140
telemt_connections_bad_total 56662
telemt_handshake_timeouts_total 313072
telemt_me_keepalive_timeout_total 323
telemt_me_reconnect_attempts_total 6860
telemt_me_reconnect_success_total 6863
telemt_me_route_drop_no_conn_total 1210414
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6800
telemt_desync_full_logged_total 2334
telemt_desync_suppressed_total 4466
telemt_desync_frames_bucket_total{bucket="1_2"} 2260
telemt_desync_frames_bucket_total{bucket="3_10"} 2246
telemt_desync_frames_bucket_total{bucket="gt_10"} 2294
telemt_pool_force_close_total 3381
telemt_pool_stale_pick_total 220454
telemt_me_writer_removed_unexpected_total 6796
telemt_me_writer_restored_same_endpoint_total 6158
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3179766
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 80474458348 (74.95 GB)
telemt_user_octets_to_client{user="hello"} 1197447037260 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 193230.0 (53h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1718338
telemt_connections_bad_total 10237
telemt_handshake_timeouts_total 132474
telemt_me_keepalive_timeout_total 290
telemt_me_reconnect_attempts_total 7250
telemt_me_reconnect_success_total 7865
telemt_me_route_drop_no_conn_total 483737
telemt_desync_total 4240
telemt_desync_full_logged_total 1346
telemt_desync_suppressed_total 2894
telemt_desync_frames_bucket_total{bucket="1_2"} 918
telemt_desync_frames_bucket_total{bucket="3_10"} 1778
telemt_desync_frames_bucket_total{bucket="gt_10"} 1544
telemt_pool_force_close_total 3411
telemt_pool_stale_pick_total 50710
telemt_me_writer_removed_unexpected_total 7628
telemt_me_writer_restored_same_endpoint_total 6730
telemt_me_writer_removed_unexpected_minus_restored_total 898
telemt_user_connections_total{user="hello"} 1333084
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 30427414504 (28.34 GB)
telemt_user_octets_to_client{user="hello"} 574933558044 (535.45 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 6120.1 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50539
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 463
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1000
telemt_me_reconnect_success_total 1009
telemt_me_reader_eof_total 1003
telemt_me_route_drop_no_conn_total 19134
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1234
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_desync_total 201
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_me_writer_removed_unexpected_total 1005
telemt_me_writer_restored_same_endpoint_total 988
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 46207
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 1822939664 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 17660022264 (16.45 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 6080.8 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49555
telemt_connections_bad_total 15855
telemt_handshake_timeouts_total 4079
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 956
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 963
telemt_me_route_drop_no_conn_total 12674
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1255
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_desync_total 87
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 964
telemt_me_writer_restored_same_endpoint_total 944
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 28102
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 255290772 (243.46 MB)
telemt_user_octets_to_client{user="hello"} 10976797808 (10.22 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 193279.2 (53h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2769545
telemt_connections_bad_total 38610
telemt_handshake_timeouts_total 270778
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6592
telemt_me_reconnect_success_total 7087
telemt_me_route_drop_no_conn_total 1025352
telemt_me_route_drop_channel_closed_total 45
telemt_desync_total 4531
telemt_desync_full_logged_total 1302
telemt_desync_suppressed_total 3229
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 1812
telemt_desync_frames_bucket_total{bucket="gt_10"} 1473
telemt_pool_force_close_total 3487
telemt_pool_stale_pick_total 114652
telemt_me_writer_removed_unexpected_total 6930
telemt_me_writer_restored_same_endpoint_total 6193
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 2310974
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 36870593116 (34.34 GB)
telemt_user_octets_to_client{user="hello"} 814216422368 (758.30 GB)
telemt_user_unique_ips_current{user="hello"} 44
```