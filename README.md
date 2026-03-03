# Server Metrics 2026-03-03 12:42:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 22830.1 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 617601
telemt_connections_bad_total 1374
telemt_handshake_timeouts_total 10047
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1943
telemt_me_reconnect_success_total 1946
telemt_me_reader_eof_total 1941
telemt_me_route_drop_no_conn_total 179873
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 1164
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 797
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 7
telemt_pool_force_close_total 349
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1941
telemt_me_writer_restored_same_endpoint_total 1916
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 459174
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 8302278144 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 156005141888 (145.29 GB)
telemt_user_unique_ips_current{user="hello"} 122
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 22827.2 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265144
telemt_connections_bad_total 695
telemt_handshake_timeouts_total 23545
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1878
telemt_me_reconnect_success_total 1892
telemt_me_reader_eof_total 1895
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 90806
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 310
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 7
telemt_pool_force_close_total 287
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 1899
telemt_me_writer_restored_same_endpoint_total 1862
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 235517
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 4122112616 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 79073399788 (73.64 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 22826.8 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298262
telemt_connections_bad_total 647
telemt_handshake_timeouts_total 32755
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2845
telemt_me_reconnect_success_total 2862
telemt_me_reader_eof_total 2864
telemt_me_route_drop_no_conn_total 98714
telemt_me_route_drop_channel_closed_total 10
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 887
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 613
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 8
telemt_pool_force_close_total 225
telemt_me_writer_removed_unexpected_total 2864
telemt_me_writer_restored_same_endpoint_total 2829
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 253753
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 2811042196 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 78716459000 (73.31 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 22824.3 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238769
telemt_connections_bad_total 245
telemt_handshake_timeouts_total 54095
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 9153
telemt_me_reconnect_success_total 9154
telemt_me_reader_eof_total 9228
telemt_me_route_drop_no_conn_total 69881
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 554
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 9229
telemt_me_writer_restored_same_endpoint_total 9133
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 174152
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 2027283848 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 66764095608 (62.18 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 20380.2 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244977
telemt_connections_bad_total 2271
telemt_handshake_timeouts_total 1157
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 3031
telemt_me_reconnect_success_total 3037
telemt_me_reader_eof_total 3054
telemt_me_route_drop_no_conn_total 114872
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 436
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 3
telemt_pool_force_close_total 143
telemt_me_writer_removed_unexpected_total 3055
telemt_me_writer_restored_same_endpoint_total 3009
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 234819
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 3627242940 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 69964127544 (65.16 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 51
```