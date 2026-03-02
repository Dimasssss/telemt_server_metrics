# Server Metrics 2026-03-02 20:39:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 192529.5 (53h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3792974
telemt_connections_bad_total 56652
telemt_handshake_timeouts_total 312997
telemt_me_keepalive_timeout_total 323
telemt_me_reconnect_attempts_total 6772
telemt_me_reconnect_success_total 6776
telemt_me_route_drop_no_conn_total 1206889
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6757
telemt_desync_full_logged_total 2323
telemt_desync_suppressed_total 4434
telemt_desync_frames_bucket_total{bucket="1_2"} 2240
telemt_desync_frames_bucket_total{bucket="3_10"} 2237
telemt_desync_frames_bucket_total{bucket="gt_10"} 2280
telemt_pool_force_close_total 3362
telemt_pool_stale_pick_total 220234
telemt_me_writer_removed_unexpected_total 6709
telemt_me_writer_restored_same_endpoint_total 6071
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3170183
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 80140178312 (74.64 GB)
telemt_user_octets_to_client{user="hello"} 1193945149720 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 79
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 192304.1 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1713004
telemt_connections_bad_total 10236
telemt_handshake_timeouts_total 132443
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 7208
telemt_me_reconnect_success_total 7830
telemt_me_route_drop_no_conn_total 481624
telemt_desync_total 4176
telemt_desync_full_logged_total 1334
telemt_desync_suppressed_total 2842
telemt_desync_frames_bucket_total{bucket="1_2"} 902
telemt_desync_frames_bucket_total{bucket="3_10"} 1745
telemt_desync_frames_bucket_total{bucket="gt_10"} 1529
telemt_pool_force_close_total 3391
telemt_pool_stale_pick_total 50561
telemt_me_writer_removed_unexpected_total 7593
telemt_me_writer_restored_same_endpoint_total 6699
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 1327877
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 29878137196 (27.83 GB)
telemt_user_octets_to_client{user="hello"} 573160396812 (533.80 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 5194.1 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44723
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 447
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 752
telemt_me_reconnect_success_total 763
telemt_me_reader_eof_total 752
telemt_me_route_drop_no_conn_total 16503
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 956
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_desync_total 159
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_me_writer_removed_unexpected_total 754
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 40885
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 1776507480 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 15645161764 (14.57 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 5155.0 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46851
telemt_connections_bad_total 15854
telemt_handshake_timeouts_total 3986
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 660
telemt_me_reconnect_success_total 684
telemt_me_reader_eof_total 667
telemt_me_route_drop_no_conn_total 11290
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 922
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_desync_total 62
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 668
telemt_me_writer_restored_same_endpoint_total 650
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 25534
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 214266372 (204.34 MB)
telemt_user_octets_to_client{user="hello"} 10273783484 (9.57 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 192353.5 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2757043
telemt_connections_bad_total 38608
telemt_handshake_timeouts_total 270549
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6582
telemt_me_reconnect_success_total 7077
telemt_me_route_drop_no_conn_total 1021870
telemt_me_route_drop_channel_closed_total 44
telemt_desync_total 4500
telemt_desync_full_logged_total 1294
telemt_desync_suppressed_total 3206
telemt_desync_frames_bucket_total{bucket="1_2"} 1236
telemt_desync_frames_bucket_total{bucket="3_10"} 1798
telemt_desync_frames_bucket_total{bucket="gt_10"} 1466
telemt_pool_force_close_total 3470
telemt_pool_stale_pick_total 114266
telemt_me_writer_removed_unexpected_total 6920
telemt_me_writer_restored_same_endpoint_total 6186
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 2299594
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 35558576728 (33.12 GB)
telemt_user_octets_to_client{user="hello"} 811562581912 (755.83 GB)
telemt_user_unique_ips_current{user="hello"} 41
```