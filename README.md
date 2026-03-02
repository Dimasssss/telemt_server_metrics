# Server Metrics 2026-03-02 21:40:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.4

telemt_uptime_seconds 654.6 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7705
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 75
telemt_me_reconnect_attempts_total 10
telemt_me_reconnect_success_total 29
telemt_me_reader_eof_total 9
telemt_me_route_drop_no_conn_total 3077
telemt_me_kdf_drift_total 47
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_desync_total 3
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 7359
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 261256580 (249.15 MB)
telemt_user_octets_to_client{user="hello"} 928187480 (885.19 MB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server2

```
telemt 3.1.4

telemt_uptime_seconds 645.2 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2699
telemt_handshake_timeouts_total 3
telemt_me_reconnect_attempts_total 14
telemt_me_reconnect_success_total 32
telemt_me_reader_eof_total 13
telemt_me_route_drop_no_conn_total 640
telemt_me_kdf_drift_total 51
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_me_writer_removed_unexpected_total 13
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 2633
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 28385924 (27.07 MB)
telemt_user_octets_to_client{user="hello"} 1708713152 (1.59 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 8899.0 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67596
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 528
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1383
telemt_me_reconnect_success_total 1392
telemt_me_reader_eof_total 1389
telemt_me_route_drop_no_conn_total 24909
telemt_me_route_drop_channel_closed_total 2
telemt_me_kdf_drift_total 1725
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_desync_total 328
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1394
telemt_me_writer_restored_same_endpoint_total 1366
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 62090
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 1893340812 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 21709278836 (20.22 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 8859.7 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58444
telemt_connections_bad_total 15928
telemt_handshake_timeouts_total 4114
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 2855
telemt_me_reconnect_success_total 2877
telemt_me_reader_eof_total 2866
telemt_me_route_drop_no_conn_total 19405
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 3325
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_desync_total 99
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 2887
telemt_me_writer_restored_same_endpoint_total 2843
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 36679
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 329547796 (314.28 MB)
telemt_user_octets_to_client{user="hello"} 13321529948 (12.41 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.4

telemt_uptime_seconds 638.6 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4634
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 33
telemt_me_reconnect_attempts_total 16
telemt_me_reconnect_success_total 36
telemt_me_reader_eof_total 16
telemt_me_route_drop_no_conn_total 619
telemt_me_kdf_drift_total 54
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_desync_total 6
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_restored_same_endpoint_total 15
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 4473
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 32506380 (31.00 MB)
telemt_user_octets_to_client{user="hello"} 640062520 (610.41 MB)
telemt_user_unique_ips_current{user="hello"} 38
```