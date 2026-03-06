# Server Metrics 2026-03-06 01:23:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 10932.9 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74206
telemt_connections_bad_total 15858
telemt_handshake_timeouts_total 701
telemt_upstream_connect_attempt_total 9419
telemt_upstream_connect_success_total 9346
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 9346
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 2537
telemt_me_reconnect_success_total 2525
telemt_me_reader_eof_total 2620
telemt_me_idle_close_by_peer_total 2620
telemt_me_route_drop_no_conn_total 17487
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 2620
telemt_me_writer_restored_same_endpoint_total 2520
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 56146
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 651535788 (621.35 MB)
telemt_user_octets_to_client{user="hello"} 21699150052 (20.21 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 10928.5 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24318
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 333
telemt_upstream_connect_attempt_total 8858
telemt_upstream_connect_success_total 8856
telemt_upstream_connect_attempts_per_request{bucket="1"} 8856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 1655
telemt_me_reconnect_success_total 1648
telemt_me_reader_eof_total 1665
telemt_me_idle_close_by_peer_total 1665
telemt_me_route_drop_no_conn_total 6891
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 4
telemt_pool_force_close_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1666
telemt_me_writer_restored_same_endpoint_total 1644
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 23523
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 163570376 (155.99 MB)
telemt_user_octets_to_client{user="hello"} 5638390248 (5.25 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 10925.8 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43058
telemt_connections_bad_total 309
telemt_handshake_timeouts_total 271
telemt_upstream_connect_attempt_total 11518
telemt_upstream_connect_success_total 11408
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 11408
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 3802
telemt_me_reconnect_success_total 3791
telemt_me_reader_eof_total 3978
telemt_me_idle_close_by_peer_total 3978
telemt_me_route_drop_no_conn_total 11294
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3979
telemt_me_writer_restored_same_endpoint_total 3785
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 40875
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 501564380 (478.33 MB)
telemt_user_octets_to_client{user="hello"} 17100571192 (15.93 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 10922.6 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34566
telemt_connections_bad_total 217
telemt_handshake_timeouts_total 2451
telemt_upstream_connect_attempt_total 7371
telemt_upstream_connect_success_total 7346
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 7346
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 1413
telemt_me_reconnect_success_total 1405
telemt_me_reader_eof_total 1455
telemt_me_idle_close_by_peer_total 1455
telemt_me_route_drop_no_conn_total 13981
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 1455
telemt_me_writer_restored_same_endpoint_total 1400
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 30249
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 307944584 (293.68 MB)
telemt_user_octets_to_client{user="hello"} 18302180076 (17.05 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 10921.4 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43610
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 6160
telemt_upstream_connect_success_total 6148
telemt_upstream_connect_attempts_per_request{bucket="1"} 6148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 707
telemt_me_reconnect_success_total 705
telemt_me_reader_eof_total 718
telemt_me_idle_close_by_peer_total 718
telemt_me_route_drop_no_conn_total 14158
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 4
telemt_pool_force_close_total 57
telemt_me_writer_removed_unexpected_total 718
telemt_me_writer_restored_same_endpoint_total 700
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 42739
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 11041353164 (10.28 GB)
telemt_user_octets_to_client{user="hello"} 19564252024 (18.22 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```