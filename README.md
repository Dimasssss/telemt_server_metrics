# Server Metrics 2026-03-03 20:30:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 50932.1 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1294576
telemt_connections_bad_total 10289
telemt_handshake_timeouts_total 14873
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4256
telemt_me_reconnect_success_total 4235
telemt_me_reader_eof_total 4253
telemt_me_route_drop_no_conn_total 496631
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 204
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 3192
telemt_desync_full_logged_total 1018
telemt_desync_suppressed_total 2174
telemt_desync_frames_bucket_total{bucket="1_2"} 879
telemt_desync_frames_bucket_total{bucket="3_10"} 1082
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 16
telemt_pool_force_close_total 809
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4255
telemt_me_writer_restored_same_endpoint_total 4195
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1069417
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 18228188688 (16.98 GB)
telemt_user_octets_to_client{user="hello"} 414854835512 (386.36 GB)
telemt_user_unique_ips_current{user="hello"} 97
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 50929.2 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580955
telemt_connections_bad_total 5292
telemt_handshake_timeouts_total 35237
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 3882
telemt_me_reconnect_success_total 3880
telemt_me_reader_eof_total 3875
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 266375
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 647
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 437
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 19
telemt_pool_force_close_total 731
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 3948
telemt_me_writer_restored_same_endpoint_total 3820
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 525761
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 8518264132 (7.93 GB)
telemt_user_octets_to_client{user="hello"} 205543617144 (191.43 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 3845.4 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47819
telemt_connections_bad_total 9313
telemt_handshake_timeouts_total 729
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 777
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 782
telemt_me_route_drop_no_conn_total 33197
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 174
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_me_writer_removed_unexpected_total 784
telemt_me_writer_restored_same_endpoint_total 767
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 35199
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 229492320 (218.86 MB)
telemt_user_octets_to_client{user="hello"} 9619291908 (8.96 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 3577.6 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19159
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 2449
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 358
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 370
telemt_me_route_drop_no_conn_total 6470
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 2
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 370
telemt_me_writer_restored_same_endpoint_total 351
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 16315
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 401456424 (382.86 MB)
telemt_user_octets_to_client{user="hello"} 8511496916 (7.93 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 48482.2 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784287
telemt_connections_bad_total 7232
telemt_handshake_timeouts_total 194630
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 8084
telemt_me_reconnect_success_total 8056
telemt_me_reader_eof_total 8118
telemt_me_route_drop_no_conn_total 314688
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 742
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 10
telemt_pool_force_close_total 433
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 8123
telemt_me_writer_restored_same_endpoint_total 8019
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 562095
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 9597888032 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 189466788600 (176.45 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 33
```