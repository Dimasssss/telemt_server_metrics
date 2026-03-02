# Server Metrics 2026-03-02 19:47:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 189444.0 (52h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3741139
telemt_connections_bad_total 56549
telemt_handshake_timeouts_total 311422
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 6556
telemt_me_reconnect_success_total 6557
telemt_me_route_drop_no_conn_total 1191245
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6644
telemt_desync_full_logged_total 2280
telemt_desync_suppressed_total 4364
telemt_desync_frames_bucket_total{bucket="1_2"} 2204
telemt_desync_frames_bucket_total{bucket="3_10"} 2200
telemt_desync_frames_bucket_total{bucket="gt_10"} 2240
telemt_pool_force_close_total 3295
telemt_pool_stale_pick_total 216266
telemt_me_writer_removed_unexpected_total 6490
telemt_me_writer_restored_same_endpoint_total 5860
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 3123180
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 78517682272 (73.13 GB)
telemt_user_octets_to_client{user="hello"} 1171879355076 (1.07 TB)
telemt_user_unique_ips_current{user="hello"} 77
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 189218.3 (52h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1690166
telemt_connections_bad_total 10223
telemt_handshake_timeouts_total 131744
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7080
telemt_me_reconnect_success_total 7697
telemt_me_route_drop_no_conn_total 473603
telemt_desync_total 4051
telemt_desync_full_logged_total 1307
telemt_desync_suppressed_total 2744
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 1695
telemt_desync_frames_bucket_total{bucket="gt_10"} 1494
telemt_pool_force_close_total 3339
telemt_pool_stale_pick_total 49687
telemt_me_writer_removed_unexpected_total 7458
telemt_me_writer_restored_same_endpoint_total 6584
telemt_me_writer_removed_unexpected_minus_restored_total 874
telemt_user_connections_total{user="hello"} 1306068
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 29675494336 (27.64 GB)
telemt_user_octets_to_client{user="hello"} 564165447220 (525.42 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 2109.0 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19728
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 208
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 215
telemt_me_reconnect_success_total 231
telemt_me_reader_eof_total 212
telemt_me_route_drop_no_conn_total 4955
telemt_me_kdf_drift_total 329
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_desync_total 58
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 214
telemt_me_writer_restored_same_endpoint_total 210
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 18350
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 1621057168 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 5323071648 (4.96 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 2069.5 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26231
telemt_connections_bad_total 10859
telemt_handshake_timeouts_total 1511
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 190
telemt_me_reconnect_success_total 215
telemt_me_reader_eof_total 197
telemt_me_route_drop_no_conn_total 4067
telemt_me_kdf_drift_total 290
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_restored_same_endpoint_total 184
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 12890
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 55196180 (52.64 MB)
telemt_user_octets_to_client{user="hello"} 4567282228 (4.25 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 189267.9 (52h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2723995
telemt_connections_bad_total 38594
telemt_handshake_timeouts_total 270495
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 6460
telemt_me_reconnect_success_total 6944
telemt_me_route_drop_no_conn_total 1002709
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4402
telemt_desync_full_logged_total 1266
telemt_desync_suppressed_total 3136
telemt_desync_frames_bucket_total{bucket="1_2"} 1205
telemt_desync_frames_bucket_total{bucket="3_10"} 1760
telemt_desync_frames_bucket_total{bucket="gt_10"} 1437
telemt_pool_force_close_total 3410
telemt_pool_stale_pick_total 110841
telemt_me_writer_removed_unexpected_total 6787
telemt_me_writer_restored_same_endpoint_total 6070
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 2267630
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 35313603196 (32.89 GB)
telemt_user_octets_to_client{user="hello"} 803151393116 (747.99 GB)
telemt_user_unique_ips_current{user="hello"} 54
```