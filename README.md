# Server Metrics 2026-03-06 00:01:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 6018.9 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46753
telemt_connections_bad_total 14114
telemt_handshake_timeouts_total 438
telemt_upstream_connect_attempt_total 3814
telemt_upstream_connect_success_total 3781
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3781
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1403
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 753
telemt_me_reconnect_success_total 751
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 769
telemt_me_route_drop_no_conn_total 8116
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 80
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 769
telemt_me_writer_restored_same_endpoint_total 746
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 31355
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 452109008 (431.16 MB)
telemt_user_octets_to_client{user="hello"} 12636690260 (11.77 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 6014.6 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14201
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 225
telemt_upstream_connect_attempt_total 5241
telemt_upstream_connect_success_total 5238
telemt_upstream_connect_attempts_per_request{bucket="1"} 5238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 1184
telemt_me_reconnect_success_total 1184
telemt_me_reader_eof_total 1195
telemt_me_idle_close_by_peer_total 1195
telemt_me_route_drop_no_conn_total 4635
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 44
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_pool_force_close_total 9
telemt_me_writer_removed_unexpected_total 1196
telemt_me_writer_restored_same_endpoint_total 1180
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 13620
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 103459004 (98.67 MB)
telemt_user_octets_to_client{user="hello"} 3037609588 (2.83 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 6011.8 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23929
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 5881
telemt_upstream_connect_success_total 5832
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5832
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 1720
telemt_me_reconnect_success_total 1717
telemt_me_reader_eof_total 1790
telemt_me_idle_close_by_peer_total 1790
telemt_me_route_drop_no_conn_total 6753
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 1791
telemt_me_writer_restored_same_endpoint_total 1712
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 23266
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 381542044 (363.87 MB)
telemt_user_octets_to_client{user="hello"} 6611075840 (6.16 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 6008.3 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18887
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 521
telemt_upstream_connect_attempt_total 3048
telemt_upstream_connect_success_total 3035
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 3035
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 301
telemt_me_reconnect_success_total 298
telemt_me_reader_eof_total 303
telemt_me_idle_close_by_peer_total 303
telemt_me_route_drop_no_conn_total 9197
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 303
telemt_me_writer_restored_same_endpoint_total 294
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 17214
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 175211624 (167.09 MB)
telemt_user_octets_to_client{user="hello"} 15268884596 (14.22 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 6007.2 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25346
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 121
telemt_upstream_connect_attempt_total 3608
telemt_upstream_connect_success_total 3605
telemt_upstream_connect_attempts_per_request{bucket="1"} 3605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 583
telemt_me_reconnect_success_total 584
telemt_me_reader_eof_total 590
telemt_me_idle_close_by_peer_total 590
telemt_me_route_drop_no_conn_total 9602
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_removed_unexpected_total 590
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 24848
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 10947537020 (10.20 GB)
telemt_user_octets_to_client{user="hello"} 16794112388 (15.64 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 26
```