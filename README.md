# Server Metrics 2026-03-03 20:00:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 49087.7 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1265193
telemt_connections_bad_total 10189
telemt_handshake_timeouts_total 13257
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 4195
telemt_me_reconnect_success_total 4173
telemt_me_reader_eof_total 4191
telemt_me_route_drop_no_conn_total 477266
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 197
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 3102
telemt_desync_full_logged_total 989
telemt_desync_suppressed_total 2113
telemt_desync_frames_bucket_total{bucket="1_2"} 858
telemt_desync_frames_bucket_total{bucket="3_10"} 1045
telemt_desync_frames_bucket_total{bucket="gt_10"} 1199
telemt_pool_swap_total 14
telemt_pool_force_close_total 771
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4193
telemt_me_writer_restored_same_endpoint_total 4135
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1042934
telemt_user_connections_current{user="hello"} 900
telemt_user_octets_from_client{user="hello"} 17700512032 (16.48 GB)
telemt_user_octets_to_client{user="hello"} 398403554120 (371.04 GB)
telemt_user_unique_ips_current{user="hello"} 140
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 49084.9 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569927
telemt_connections_bad_total 5292
telemt_handshake_timeouts_total 34274
telemt_me_keepalive_timeout_total 425
telemt_me_reconnect_attempts_total 3755
telemt_me_reconnect_success_total 3753
telemt_me_reader_eof_total 3748
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 261515
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 201
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 621
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 18
telemt_pool_force_close_total 703
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 3821
telemt_me_writer_restored_same_endpoint_total 3696
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 515816
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 8390311600 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 195916591696 (182.46 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 2001.0 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24593
telemt_connections_bad_total 6154
telemt_handshake_timeouts_total 432
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 228
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 229
telemt_me_route_drop_no_conn_total 13855
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 68
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 231
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 17113
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 89418684 (85.28 MB)
telemt_user_octets_to_client{user="hello"} 5473144552 (5.10 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 1733.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6094
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 541
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 168
telemt_me_reconnect_success_total 200
telemt_me_reader_eof_total 180
telemt_me_route_drop_no_conn_total 1372
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 1
telemt_pool_force_close_total 10
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_restored_same_endpoint_total 165
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 5342
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 50543068 (48.20 MB)
telemt_user_octets_to_client{user="hello"} 3099604920 (2.89 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 46637.8 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 747717
telemt_connections_bad_total 7229
telemt_handshake_timeouts_total 174979
telemt_me_keepalive_timeout_total 192
telemt_me_reconnect_attempts_total 7696
telemt_me_reconnect_success_total 7668
telemt_me_reader_eof_total 7729
telemt_me_route_drop_no_conn_total 308514
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 730
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 10
telemt_pool_force_close_total 433
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7734
telemt_me_writer_restored_same_endpoint_total 7631
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 545626
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 8493393264 (7.91 GB)
telemt_user_octets_to_client{user="hello"} 183433244672 (170.84 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 31
```