# Server Metrics 2026-03-03 20:41:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.5

telemt_uptime_seconds 51546.6 (14h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1303193
telemt_connections_bad_total 10292
telemt_handshake_timeouts_total 14895
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4287
telemt_me_reconnect_success_total 4264
telemt_me_reader_eof_total 4283
telemt_me_route_drop_no_conn_total 503566
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 3210
telemt_desync_full_logged_total 1024
telemt_desync_suppressed_total 2186
telemt_desync_frames_bucket_total{bucket="1_2"} 884
telemt_desync_frames_bucket_total{bucket="3_10"} 1090
telemt_desync_frames_bucket_total{bucket="gt_10"} 1236
telemt_pool_swap_total 16
telemt_pool_force_close_total 809
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4285
telemt_me_writer_restored_same_endpoint_total 4223
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1077401
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 18512286948 (17.24 GB)
telemt_user_octets_to_client{user="hello"} 418196947460 (389.48 GB)
telemt_user_unique_ips_current{user="hello"} 90
```

## server2

```
telemt 3.1.5

telemt_uptime_seconds 51543.9 (14h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584387
telemt_connections_bad_total 5292
telemt_handshake_timeouts_total 35607
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 3920
telemt_me_reconnect_success_total 3917
telemt_me_reader_eof_total 3914
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 267713
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 212
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 678
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 451
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 20
telemt_pool_force_close_total 765
telemt_pool_stale_pick_total 318
telemt_me_writer_removed_unexpected_total 3987
telemt_me_writer_restored_same_endpoint_total 3857
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 528796
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 8562668424 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 209954030832 (195.53 GB)
telemt_user_unique_ips_current{user="hello"} 72
```

## server3

```
telemt 3.1.5

telemt_uptime_seconds 4460.2 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55248
telemt_connections_bad_total 10102
telemt_handshake_timeouts_total 744
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 917
telemt_me_reconnect_success_total 931
telemt_me_reader_eof_total 922
telemt_me_route_drop_no_conn_total 38052
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 208
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 145
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_me_writer_removed_unexpected_total 925
telemt_me_writer_restored_same_endpoint_total 905
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 41033
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 303963872 (289.88 MB)
telemt_user_octets_to_client{user="hello"} 11773386512 (10.96 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server4

```
telemt 3.1.5

telemt_uptime_seconds 4192.3 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23009
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 2462
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 407
telemt_me_reconnect_success_total 438
telemt_me_reader_eof_total 420
telemt_me_route_drop_no_conn_total 8092
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="static"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 3
telemt_pool_force_close_total 46
telemt_me_writer_removed_unexpected_total 420
telemt_me_writer_restored_same_endpoint_total 400
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 20038
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 590013324 (562.68 MB)
telemt_user_octets_to_client{user="hello"} 9615849336 (8.96 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server5

```
telemt 3.1.5

telemt_uptime_seconds 49096.7 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 791720
telemt_connections_bad_total 7232
telemt_handshake_timeouts_total 197193
telemt_me_keepalive_timeout_total 198
telemt_me_reconnect_attempts_total 8220
telemt_me_reconnect_success_total 8192
telemt_me_reader_eof_total 8254
telemt_me_route_drop_no_conn_total 316874
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 195
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
telemt_me_writer_removed_unexpected_total 8259
telemt_me_writer_restored_same_endpoint_total 8155
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 566865
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 9693290808 (9.03 GB)
telemt_user_octets_to_client{user="hello"} 190710688980 (177.61 GB)
telemt_user_connections_total{user="hello2"} 6
telemt_user_octets_from_client{user="hello2"} 4260 (4.16 KB)
telemt_user_octets_to_client{user="hello2"} 5848 (5.71 KB)
telemt_user_unique_ips_current{user="hello"} 36
```