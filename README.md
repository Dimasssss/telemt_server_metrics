# Server Metrics 2026-03-02 19:32:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 188517.5 (52h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3721333
telemt_connections_bad_total 55934
telemt_handshake_timeouts_total 310839
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 6522
telemt_me_reconnect_success_total 6524
telemt_me_route_drop_no_conn_total 1185806
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6601
telemt_desync_full_logged_total 2268
telemt_desync_suppressed_total 4333
telemt_desync_frames_bucket_total{bucket="1_2"} 2190
telemt_desync_frames_bucket_total{bucket="3_10"} 2183
telemt_desync_frames_bucket_total{bucket="gt_10"} 2228
telemt_pool_force_close_total 3277
telemt_pool_stale_pick_total 215055
telemt_me_writer_removed_unexpected_total 6458
telemt_me_writer_restored_same_endpoint_total 5831
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 3105755
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 75244411024 (70.08 GB)
telemt_user_octets_to_client{user="hello"} 1165654202700 (1.06 TB)
telemt_user_unique_ips_current{user="hello"} 73
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 188292.0 (52h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1682820
telemt_connections_bad_total 10214
telemt_handshake_timeouts_total 131591
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 7056
telemt_me_reconnect_success_total 7670
telemt_me_route_drop_no_conn_total 471558
telemt_desync_total 3991
telemt_desync_full_logged_total 1299
telemt_desync_suppressed_total 2692
telemt_desync_frames_bucket_total{bucket="1_2"} 843
telemt_desync_frames_bucket_total{bucket="3_10"} 1672
telemt_desync_frames_bucket_total{bucket="gt_10"} 1476
telemt_pool_force_close_total 3319
telemt_pool_stale_pick_total 49281
telemt_me_writer_removed_unexpected_total 7432
telemt_me_writer_restored_same_endpoint_total 6563
telemt_me_writer_removed_unexpected_minus_restored_total 869
telemt_user_connections_total{user="hello"} 1298974
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 29622831780 (27.59 GB)
telemt_user_octets_to_client{user="hello"} 558689551432 (520.32 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 1182.2 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12431
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 144
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 46
telemt_me_reconnect_success_total 63
telemt_me_reader_eof_total 42
telemt_me_route_drop_no_conn_total 2385
telemt_me_kdf_drift_total 103
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_desync_total 37
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 11462
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 1534697364 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 2089231704 (1.95 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 1143.4 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18665
telemt_connections_bad_total 8956
telemt_handshake_timeouts_total 821
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 71
telemt_me_reconnect_success_total 94
telemt_me_reader_eof_total 75
telemt_me_route_drop_no_conn_total 1833
telemt_me_kdf_drift_total 121
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_me_writer_removed_unexpected_total 75
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 8226
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 24526992 (23.39 MB)
telemt_user_octets_to_client{user="hello"} 2333499224 (2.17 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 188341.1 (52h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2706529
telemt_connections_bad_total 38557
telemt_handshake_timeouts_total 270096
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 6434
telemt_me_reconnect_success_total 6918
telemt_me_route_drop_no_conn_total 995392
telemt_me_route_drop_channel_closed_total 43
telemt_desync_total 4376
telemt_desync_full_logged_total 1258
telemt_desync_suppressed_total 3118
telemt_desync_frames_bucket_total{bucket="1_2"} 1196
telemt_desync_frames_bucket_total{bucket="3_10"} 1750
telemt_desync_frames_bucket_total{bucket="gt_10"} 1430
telemt_pool_force_close_total 3410
telemt_pool_stale_pick_total 105001
telemt_me_writer_removed_unexpected_total 6761
telemt_me_writer_restored_same_endpoint_total 6044
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 2251729
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 35198775272 (32.78 GB)
telemt_user_octets_to_client{user="hello"} 799779972852 (744.85 GB)
telemt_user_unique_ips_current{user="hello"} 58
```