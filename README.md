# Server Metrics 2026-03-03 20:56:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 52468.6 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1312234
telemt_connections_bad_total 10300
telemt_handshake_timeouts_total 14935
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 4381
telemt_me_reconnect_success_total 4356
telemt_me_reader_eof_total 4381
telemt_me_route_drop_no_conn_total 508376
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 211
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 3227
telemt_desync_full_logged_total 1035
telemt_desync_suppressed_total 2192
telemt_desync_frames_bucket_total{bucket="1_2"} 889
telemt_desync_frames_bucket_total{bucket="3_10"} 1098
telemt_desync_frames_bucket_total{bucket="gt_10"} 1240
telemt_pool_swap_total 16
telemt_pool_force_close_total 809
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4383
telemt_me_writer_restored_same_endpoint_total 4315
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1086248
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 18579118864 (17.30 GB)
telemt_user_octets_to_client{user="hello"} 423699713652 (394.60 GB)
telemt_user_unique_ips_current{user="hello"} 83
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 52465.7 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588375
telemt_connections_bad_total 5292
telemt_handshake_timeouts_total 36091
telemt_me_keepalive_timeout_total 431
telemt_me_reconnect_attempts_total 3989
telemt_me_reconnect_success_total 3985
telemt_me_reader_eof_total 3981
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 269589
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 217
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 712
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 469
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 284
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 20
telemt_pool_force_close_total 765
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 4055
telemt_me_writer_restored_same_endpoint_total 3924
telemt_me_writer_restored_fallback_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 532277
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 8588568920 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 213399294296 (198.74 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 5382.0 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65693
telemt_connections_bad_total 12051
telemt_handshake_timeouts_total 839
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 1171
telemt_me_reconnect_success_total 1184
telemt_me_reader_eof_total 1179
telemt_me_route_drop_no_conn_total 41360
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 231
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_me_writer_removed_unexpected_total 1182
telemt_me_writer_restored_same_endpoint_total 1158
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 48618
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 331153572 (315.81 MB)
telemt_user_octets_to_client{user="hello"} 13230460252 (12.32 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 5114.2 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26970
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 2515
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 449
telemt_me_reconnect_success_total 478
telemt_me_reader_eof_total 460
telemt_me_route_drop_no_conn_total 9776
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 4
telemt_pool_force_close_total 66
telemt_me_writer_removed_unexpected_total 460
telemt_me_writer_restored_same_endpoint_total 440
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 23814
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 737875312 (703.69 MB)
telemt_user_octets_to_client{user="hello"} 12604363140 (11.74 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 50018.5 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803236
telemt_connections_bad_total 7232
telemt_handshake_timeouts_total 200757
telemt_me_keepalive_timeout_total 201
telemt_me_reconnect_attempts_total 8464
telemt_me_reconnect_success_total 8434
telemt_me_reader_eof_total 8502
telemt_me_route_drop_no_conn_total 320277
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 744
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 10
telemt_pool_force_close_total 433
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 8507
telemt_me_writer_restored_same_endpoint_total 8397
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 574722
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 9886018788 (9.21 GB)
telemt_user_octets_to_client{user="hello"} 193490631152 (180.20 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 29
```