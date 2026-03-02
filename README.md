# Server Metrics 2026-03-02 21:46:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.4

telemt_uptime_seconds 962.7 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11004
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 89
telemt_me_reconnect_attempts_total 12
telemt_me_reconnect_success_total 31
telemt_me_reader_eof_total 11
telemt_me_route_drop_no_conn_total 3656
telemt_me_kdf_drift_total 50
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_desync_total 7
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 10544
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 398885188 (380.41 MB)
telemt_user_octets_to_client{user="hello"} 1516908336 (1.41 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server2

```
telemt 3.1.4

telemt_uptime_seconds 953.4 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4109
telemt_handshake_timeouts_total 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 40
telemt_me_reader_eof_total 20
telemt_me_route_drop_no_conn_total 1032
telemt_me_kdf_drift_total 65
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_desync_total 12
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 20
telemt_me_writer_restored_same_endpoint_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 4023
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 69007588 (65.81 MB)
telemt_user_octets_to_client{user="hello"} 2631187832 (2.45 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 9207.1 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69034
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 536
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1411
telemt_me_reconnect_success_total 1420
telemt_me_reader_eof_total 1417
telemt_me_route_drop_no_conn_total 25315
telemt_me_route_drop_channel_closed_total 2
telemt_me_kdf_drift_total 1780
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_desync_total 329
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1422
telemt_me_writer_restored_same_endpoint_total 1394
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 63408
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 1897839480 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 21890729600 (20.39 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 9168.0 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59014
telemt_connections_bad_total 15929
telemt_handshake_timeouts_total 4115
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 3122
telemt_me_reconnect_success_total 3144
telemt_me_reader_eof_total 3133
telemt_me_route_drop_no_conn_total 19869
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 3616
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_desync_total 99
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 3155
telemt_me_writer_restored_same_endpoint_total 3110
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 37233
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 334411240 (318.92 MB)
telemt_user_octets_to_client{user="hello"} 13634027564 (12.70 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.4

telemt_uptime_seconds 946.8 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6680
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 52
telemt_me_reconnect_attempts_total 24
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 24
telemt_me_route_drop_no_conn_total 1026
telemt_me_kdf_drift_total 72
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_desync_total 10
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 6471
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 44415552 (42.36 MB)
telemt_user_octets_to_client{user="hello"} 1163613752 (1.08 GB)
telemt_user_unique_ips_current{user="hello"} 41
```