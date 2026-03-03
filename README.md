# Server Metrics 2026-03-03 20:15:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 50010.5 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1281635
telemt_connections_bad_total 10289
telemt_handshake_timeouts_total 14177
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4223
telemt_me_reconnect_success_total 4201
telemt_me_reader_eof_total 4219
telemt_me_route_drop_no_conn_total 491444
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 201
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 3153
telemt_desync_full_logged_total 1004
telemt_desync_suppressed_total 2149
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 1068
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 15
telemt_pool_force_close_total 792
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4221
telemt_me_writer_restored_same_endpoint_total 4162
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 1057501
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 17892507256 (16.66 GB)
telemt_user_octets_to_client{user="hello"} 406729993588 (378.80 GB)
telemt_user_unique_ips_current{user="hello"} 101
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 50007.5 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576024
telemt_connections_bad_total 5292
telemt_handshake_timeouts_total 34743
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 3817
telemt_me_reconnect_success_total 3815
telemt_me_reader_eof_total 3809
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 264174
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 205
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 629
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 19
telemt_pool_force_close_total 731
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 3882
telemt_me_writer_restored_same_endpoint_total 3755
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 521393
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 8462868264 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 202165834792 (188.28 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 2923.8 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36649
telemt_connections_bad_total 7850
telemt_handshake_timeouts_total 619
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 554
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 559
telemt_me_route_drop_no_conn_total 24490
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 119
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_me_writer_removed_unexpected_total 561
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 26481
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 170441024 (162.55 MB)
telemt_user_octets_to_client{user="hello"} 7546774896 (7.03 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 2655.8 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12533
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 1625
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 238
telemt_me_reconnect_success_total 270
telemt_me_reader_eof_total 250
telemt_me_route_drop_no_conn_total 3550
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 2
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 250
telemt_me_writer_restored_same_endpoint_total 233
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 10623
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 199182076 (189.95 MB)
telemt_user_octets_to_client{user="hello"} 5482045912 (5.11 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 47560.5 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 770641
telemt_connections_bad_total 7230
telemt_handshake_timeouts_total 189989
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 7874
telemt_me_reconnect_success_total 7846
telemt_me_reader_eof_total 7907
telemt_me_route_drop_no_conn_total 311500
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 738
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 288
telemt_pool_swap_total 10
telemt_pool_force_close_total 433
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7912
telemt_me_writer_restored_same_endpoint_total 7809
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 553338
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 9132473200 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 186718162392 (173.89 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 38
```