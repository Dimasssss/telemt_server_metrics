# Server Metrics 2026-03-03 10:49:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 16027.1 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458990
telemt_connections_bad_total 568
telemt_handshake_timeouts_total 8497
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 1288
telemt_me_reconnect_success_total 1295
telemt_me_reader_eof_total 1282
telemt_me_route_drop_no_conn_total 127750
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 795
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 550
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 5
telemt_pool_force_close_total 251
telemt_me_writer_removed_unexpected_total 1282
telemt_me_writer_restored_same_endpoint_total 1268
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 317226
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 6672657928 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 102552316380 (95.51 GB)
telemt_user_unique_ips_current{user="hello"} 98
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 16024.2 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176862
telemt_connections_bad_total 255
telemt_handshake_timeouts_total 12918
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1465
telemt_me_reconnect_success_total 1480
telemt_me_reader_eof_total 1475
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 62468
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 67
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 193
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 156
telemt_me_writer_removed_unexpected_total 1479
telemt_me_writer_restored_same_endpoint_total 1453
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 160658
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 2887360104 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 58068854028 (54.08 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 16023.9 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207680
telemt_connections_bad_total 593
telemt_handshake_timeouts_total 29127
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1997
telemt_me_reconnect_success_total 2013
telemt_me_reader_eof_total 2008
telemt_me_route_drop_no_conn_total 58929
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 67
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 574
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 6
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 2008
telemt_me_writer_restored_same_endpoint_total 1982
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 172172
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 2026600120 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 53140501696 (49.49 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 16020.9 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154909
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 24861
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 5241
telemt_me_reconnect_success_total 5253
telemt_me_reader_eof_total 5288
telemt_me_route_drop_no_conn_total 44634
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 337
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 230
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 5288
telemt_me_writer_restored_same_endpoint_total 5232
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 121405
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 1475028472 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 44006010656 (40.98 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 13576.8 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155070
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 836
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 1603
telemt_me_reconnect_success_total 1619
telemt_me_reader_eof_total 1625
telemt_me_route_drop_no_conn_total 66314
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 302
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 2
telemt_pool_force_close_total 87
telemt_me_writer_removed_unexpected_total 1625
telemt_me_writer_restored_same_endpoint_total 1593
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 149826
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 2684817352 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 43708635704 (40.71 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 39
```