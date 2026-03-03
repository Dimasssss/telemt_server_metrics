# Server Metrics 2026-03-03 20:20:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 50317.7 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1285874
telemt_connections_bad_total 10289
telemt_handshake_timeouts_total 14474
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4233
telemt_me_reconnect_success_total 4212
telemt_me_reader_eof_total 4230
telemt_me_route_drop_no_conn_total 493183
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 201
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 3155
telemt_desync_full_logged_total 1006
telemt_desync_suppressed_total 2149
telemt_desync_frames_bucket_total{bucket="1_2"} 869
telemt_desync_frames_bucket_total{bucket="3_10"} 1069
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 15
telemt_pool_force_close_total 792
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4232
telemt_me_writer_restored_same_endpoint_total 4172
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1061280
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 18027809848 (16.79 GB)
telemt_user_octets_to_client{user="hello"} 409719918708 (381.58 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 50314.8 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577633
telemt_connections_bad_total 5292
telemt_handshake_timeouts_total 34879
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 3821
telemt_me_reconnect_success_total 3819
telemt_me_reader_eof_total 3813
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 264907
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 205
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 631
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 19
telemt_pool_force_close_total 731
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 3886
telemt_me_writer_restored_same_endpoint_total 3759
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 522842
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 8472882928 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 203113200120 (189.16 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 3231.2 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40490
telemt_connections_bad_total 8103
telemt_handshake_timeouts_total 640
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 653
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 657
telemt_me_route_drop_no_conn_total 27881
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 144
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_me_writer_removed_unexpected_total 659
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 29670
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 192721660 (183.79 MB)
telemt_user_octets_to_client{user="hello"} 8357372340 (7.78 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 2963.2 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14797
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 1989
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 284
telemt_me_reconnect_success_total 315
telemt_me_reader_eof_total 296
telemt_me_route_drop_no_conn_total 4456
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 2
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 296
telemt_me_writer_restored_same_endpoint_total 278
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 12479
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 228599272 (218.01 MB)
telemt_user_octets_to_client{user="hello"} 6455474840 (6.01 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 47867.8 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 775001
telemt_connections_bad_total 7232
telemt_handshake_timeouts_total 191654
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 7929
telemt_me_reconnect_success_total 7901
telemt_me_reader_eof_total 7962
telemt_me_route_drop_no_conn_total 312670
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 11
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
telemt_me_writer_removed_unexpected_total 7967
telemt_me_writer_restored_same_endpoint_total 7864
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 556030
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 9173180748 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 187747963196 (174.85 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 33
```