# Server Metrics 2026-03-02 20:23:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 191604.1 (53h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3780664
telemt_connections_bad_total 56553
telemt_handshake_timeouts_total 312610
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 6687
telemt_me_reconnect_success_total 6692
telemt_me_route_drop_no_conn_total 1203199
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6727
telemt_desync_full_logged_total 2310
telemt_desync_suppressed_total 4417
telemt_desync_frames_bucket_total{bucket="1_2"} 2230
telemt_desync_frames_bucket_total{bucket="3_10"} 2230
telemt_desync_frames_bucket_total{bucket="gt_10"} 2267
telemt_pool_force_close_total 3337
telemt_pool_stale_pick_total 219804
telemt_me_writer_removed_unexpected_total 6625
telemt_me_writer_restored_same_endpoint_total 5987
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3158834
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 80011985124 (74.52 GB)
telemt_user_octets_to_client{user="hello"} 1184563608828 (1.08 TB)
telemt_user_unique_ips_current{user="hello"} 71
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 191378.4 (53h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1707308
telemt_connections_bad_total 10225
telemt_handshake_timeouts_total 132392
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7176
telemt_me_reconnect_success_total 7796
telemt_me_route_drop_no_conn_total 479792
telemt_desync_total 4147
telemt_desync_full_logged_total 1328
telemt_desync_suppressed_total 2819
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 1734
telemt_desync_frames_bucket_total{bucket="gt_10"} 1518
telemt_pool_force_close_total 3372
telemt_pool_stale_pick_total 50336
telemt_me_writer_removed_unexpected_total 7559
telemt_me_writer_restored_same_endpoint_total 6670
telemt_me_writer_removed_unexpected_minus_restored_total 889
telemt_user_connections_total{user="hello"} 1322348
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 29802812620 (27.76 GB)
telemt_user_octets_to_client{user="hello"} 570503238928 (531.32 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 4268.5 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37620
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 415
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 530
telemt_me_reconnect_success_total 543
telemt_me_reader_eof_total 527
telemt_me_route_drop_no_conn_total 12743
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 706
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_desync_total 129
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_me_writer_removed_unexpected_total 529
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 34480
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 1739125700 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 13464537936 (12.54 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 4229.0 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42440
telemt_connections_bad_total 15854
telemt_handshake_timeouts_total 3219
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 437
telemt_me_reconnect_success_total 463
telemt_me_reader_eof_total 444
telemt_me_route_drop_no_conn_total 9036
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 651
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_desync_total 29
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 445
telemt_me_writer_restored_same_endpoint_total 429
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 22018
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 177844580 (169.61 MB)
telemt_user_octets_to_client{user="hello"} 9185554356 (8.55 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 191427.8 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2749055
telemt_connections_bad_total 38607
telemt_handshake_timeouts_total 270543
telemt_me_keepalive_timeout_total 231
telemt_me_reconnect_attempts_total 6538
telemt_me_reconnect_success_total 7026
telemt_me_route_drop_no_conn_total 1017744
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4462
telemt_desync_full_logged_total 1285
telemt_desync_suppressed_total 3177
telemt_desync_frames_bucket_total{bucket="1_2"} 1220
telemt_desync_frames_bucket_total{bucket="3_10"} 1784
telemt_desync_frames_bucket_total{bucket="gt_10"} 1458
telemt_pool_force_close_total 3450
telemt_pool_stale_pick_total 113987
telemt_me_writer_removed_unexpected_total 6869
telemt_me_writer_restored_same_endpoint_total 6142
telemt_me_writer_removed_unexpected_minus_restored_total 727
telemt_user_connections_total{user="hello"} 2291786
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 35485050848 (33.05 GB)
telemt_user_octets_to_client{user="hello"} 808875696576 (753.32 GB)
telemt_user_unique_ips_current{user="hello"} 51
```