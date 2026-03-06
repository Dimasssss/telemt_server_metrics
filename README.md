# Server Metrics 2026-03-06 03:36:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 18918.4 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130456
telemt_connections_bad_total 15926
telemt_handshake_timeouts_total 2743
telemt_upstream_connect_attempt_total 20404
telemt_upstream_connect_success_total 20235
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 20235
telemt_upstream_connect_attempts_per_request{bucket="2"} 79
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 7349
telemt_me_reconnect_success_total 7324
telemt_me_reader_eof_total 7565
telemt_me_idle_close_by_peer_total 7565
telemt_me_route_drop_no_conn_total 35568
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 343
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 2
telemt_pool_force_close_total 93
telemt_me_writer_removed_unexpected_total 7565
telemt_me_writer_restored_same_endpoint_total 7318
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 104599
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 1358084336 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 40711747756 (37.92 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 18913.9 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43579
telemt_connections_bad_total 105
telemt_handshake_timeouts_total 575
telemt_upstream_connect_attempt_total 14920
telemt_upstream_connect_success_total 14918
telemt_upstream_connect_attempts_per_request{bucket="1"} 14918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 2640
telemt_me_reconnect_success_total 2629
telemt_me_reader_eof_total 2661
telemt_me_idle_close_by_peer_total 2661
telemt_me_route_drop_no_conn_total 12802
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 2662
telemt_me_writer_restored_same_endpoint_total 2623
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 42129
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 302187936 (288.19 MB)
telemt_user_octets_to_client{user="hello"} 10356257012 (9.65 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 18911.2 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77642
telemt_connections_bad_total 785
telemt_handshake_timeouts_total 1592
telemt_upstream_connect_attempt_total 18600
telemt_upstream_connect_success_total 18452
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 18452
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 218
telemt_me_reconnect_attempts_total 5752
telemt_me_reconnect_success_total 5732
telemt_me_reader_eof_total 5997
telemt_me_idle_close_by_peer_total 5997
telemt_me_route_drop_no_conn_total 21502
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 6001
telemt_me_writer_restored_same_endpoint_total 5725
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 72524
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 725154872 (691.56 MB)
telemt_user_octets_to_client{user="hello"} 24567992120 (22.88 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 18907.9 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63251
telemt_connections_bad_total 404
telemt_handshake_timeouts_total 4077
telemt_upstream_connect_attempt_total 12701
telemt_upstream_connect_success_total 12664
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 12664
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 2602
telemt_me_reconnect_success_total 2584
telemt_me_reader_eof_total 2686
telemt_me_idle_close_by_peer_total 2686
telemt_me_route_drop_no_conn_total 23138
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 7
telemt_pool_force_close_total 148
telemt_me_writer_removed_unexpected_total 2686
telemt_me_writer_restored_same_endpoint_total 2577
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 55408
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 574438332 (547.83 MB)
telemt_user_octets_to_client{user="hello"} 25170036608 (23.44 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 18906.7 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76114
telemt_connections_bad_total 871
telemt_handshake_timeouts_total 523
telemt_upstream_connect_attempt_total 12148
telemt_upstream_connect_success_total 12123
telemt_upstream_connect_attempts_per_request{bucket="1"} 12123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 155
telemt_me_reconnect_attempts_total 1569
telemt_me_reconnect_success_total 1564
telemt_me_reader_eof_total 1600
telemt_me_idle_close_by_peer_total 1600
telemt_me_route_drop_no_conn_total 24341
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 78
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1601
telemt_me_writer_restored_same_endpoint_total 1558
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 73607
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 12148440276 (11.31 GB)
telemt_user_octets_to_client{user="hello"} 43335131104 (40.36 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 38
```