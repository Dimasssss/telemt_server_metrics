# Server Metrics 2026-03-06 19:00:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 3162.8 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82243
telemt_connections_bad_total 908
telemt_handshake_timeouts_total 2276
telemt_upstream_connect_attempt_total 3930
telemt_upstream_connect_success_total 3871
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 202
telemt_me_reconnect_attempts_total 1070
telemt_me_reconnect_success_total 1061
telemt_me_reader_eof_total 1338
telemt_me_idle_close_by_peer_total 1338
telemt_me_route_drop_no_conn_total 31231
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 379
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 51
telemt_me_writer_removed_unexpected_total 1357
telemt_me_writer_restored_same_endpoint_total 1055
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 73882
telemt_user_connections_current{user="hello"} 1010
telemt_user_octets_from_client{user="hello"} 1481794240 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 24226545364 (22.56 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 3162.6 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29258
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 1741
telemt_upstream_connect_attempt_total 4689
telemt_upstream_connect_success_total 4688
telemt_upstream_connect_attempts_per_request{bucket="1"} 4688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 1551
telemt_me_reconnect_success_total 1547
telemt_me_reader_eof_total 1935
telemt_me_idle_close_by_peer_total 1935
telemt_me_route_drop_no_conn_total 10209
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 91
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 1
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 1935
telemt_me_writer_restored_same_endpoint_total 1545
telemt_me_writer_removed_unexpected_minus_restored_total 390
telemt_user_connections_total{user="hello"} 26578
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 293279968 (279.69 MB)
telemt_user_octets_to_client{user="hello"} 7966433560 (7.42 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 3162.5 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53862
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 746
telemt_upstream_connect_attempt_total 3791
telemt_upstream_connect_success_total 3775
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 818
telemt_me_reconnect_success_total 818
telemt_me_reader_eof_total 1077
telemt_me_idle_close_by_peer_total 1077
telemt_me_route_drop_no_conn_total 17454
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 276
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 1079
telemt_me_writer_restored_same_endpoint_total 811
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 49527
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 1960821500 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 11350412036 (10.57 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 3163.1 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70527
telemt_connections_bad_total 30246
telemt_handshake_timeouts_total 2685
telemt_upstream_connect_attempt_total 4081
telemt_upstream_connect_success_total 4065
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 1130
telemt_me_reconnect_success_total 1125
telemt_me_reader_eof_total 1436
telemt_me_idle_close_by_peer_total 1436
telemt_me_route_drop_no_conn_total 12179
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 13
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 285
telemt_me_writer_removed_unexpected_total 1436
telemt_me_writer_restored_same_endpoint_total 1121
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 36189
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 246512472 (235.09 MB)
telemt_user_octets_to_client{user="hello"} 13566705868 (12.63 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 3161.6 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48669
telemt_connections_bad_total 113
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 4766
telemt_upstream_connect_success_total 4747
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 4755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3223
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 1527
telemt_me_reconnect_success_total 1522
telemt_me_reader_eof_total 2132
telemt_me_idle_close_by_peer_total 2131
telemt_me_route_drop_no_conn_total 16782
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 273
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 2136
telemt_me_writer_restored_same_endpoint_total 1520
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 46071
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 1774691832 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 20580352948 (19.17 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 78
```