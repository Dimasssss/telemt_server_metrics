# Server Metrics 2026-03-02 19:37:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 188827.2 (52h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3728130
telemt_connections_bad_total 56188
telemt_handshake_timeouts_total 311052
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 6536
telemt_me_reconnect_success_total 6537
telemt_me_route_drop_no_conn_total 1187563
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6613
telemt_desync_full_logged_total 2273
telemt_desync_suppressed_total 4340
telemt_desync_frames_bucket_total{bucket="1_2"} 2196
telemt_desync_frames_bucket_total{bucket="3_10"} 2186
telemt_desync_frames_bucket_total{bucket="gt_10"} 2231
telemt_pool_force_close_total 3295
telemt_pool_stale_pick_total 215055
telemt_me_writer_removed_unexpected_total 6471
telemt_me_writer_restored_same_endpoint_total 5841
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 3111605
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 75581045348 (70.39 GB)
telemt_user_octets_to_client{user="hello"} 1167579910684 (1.06 TB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 188601.8 (52h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1685135
telemt_connections_bad_total 10215
telemt_handshake_timeouts_total 131699
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 7060
telemt_me_reconnect_success_total 7677
telemt_me_route_drop_no_conn_total 472210
telemt_desync_total 4000
telemt_desync_full_logged_total 1301
telemt_desync_suppressed_total 2699
telemt_desync_frames_bucket_total{bucket="1_2"} 847
telemt_desync_frames_bucket_total{bucket="3_10"} 1676
telemt_desync_frames_bucket_total{bucket="gt_10"} 1477
telemt_pool_force_close_total 3319
telemt_pool_stale_pick_total 49281
telemt_me_writer_removed_unexpected_total 7438
telemt_me_writer_restored_same_endpoint_total 6567
telemt_me_writer_removed_unexpected_minus_restored_total 871
telemt_user_connections_total{user="hello"} 1301171
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 29638356068 (27.60 GB)
telemt_user_octets_to_client{user="hello"} 560702571936 (522.19 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 1491.7 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14928
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 167
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 111
telemt_me_reconnect_success_total 127
telemt_me_reader_eof_total 107
telemt_me_route_drop_no_conn_total 3228
telemt_me_kdf_drift_total 191
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_desync_total 41
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 108
telemt_me_writer_restored_same_endpoint_total 106
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 13842
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 1559178716 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 2699960008 (2.51 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 1452.6 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21022
telemt_connections_bad_total 9621
telemt_handshake_timeouts_total 1049
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 115
telemt_me_reconnect_success_total 140
telemt_me_reader_eof_total 121
telemt_me_route_drop_no_conn_total 2660
telemt_me_kdf_drift_total 178
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_me_writer_removed_unexpected_total 121
telemt_me_writer_restored_same_endpoint_total 109
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 9658
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 36223924 (34.55 MB)
telemt_user_octets_to_client{user="hello"} 3731674664 (3.48 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 188651.2 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2712796
telemt_connections_bad_total 38558
telemt_handshake_timeouts_total 270268
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 6434
telemt_me_reconnect_success_total 6918
telemt_me_route_drop_no_conn_total 996911
telemt_me_route_drop_channel_closed_total 43
telemt_desync_total 4391
telemt_desync_full_logged_total 1262
telemt_desync_suppressed_total 3129
telemt_desync_frames_bucket_total{bucket="1_2"} 1201
telemt_desync_frames_bucket_total{bucket="3_10"} 1755
telemt_desync_frames_bucket_total{bucket="gt_10"} 1435
telemt_pool_force_close_total 3410
telemt_pool_stale_pick_total 105394
telemt_me_writer_removed_unexpected_total 6761
telemt_me_writer_restored_same_endpoint_total 6044
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 2257365
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 35242363604 (32.82 GB)
telemt_user_octets_to_client{user="hello"} 800626548044 (745.64 GB)
telemt_user_unique_ips_current{user="hello"} 42
```