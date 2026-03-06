# Server Metrics 2026-03-06 20:53:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 9954.9 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207310
telemt_connections_bad_total 2199
telemt_handshake_timeouts_total 8676
telemt_upstream_connect_attempt_total 15872
telemt_upstream_connect_success_total 15721
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 15775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 913
telemt_me_reconnect_attempts_total 4960
telemt_me_reconnect_success_total 4931
telemt_me_reader_eof_total 6387
telemt_me_idle_close_by_peer_total 6387
telemt_me_route_drop_no_conn_total 81332
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 720
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 513
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 2
telemt_pool_force_close_total 185
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 6494
telemt_me_writer_restored_same_endpoint_total 4925
telemt_me_writer_removed_unexpected_minus_restored_total 1569
telemt_user_connections_total{user="hello"} 183345
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 2790912824 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 65676907864 (61.17 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 9954.6 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78178
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 4204
telemt_upstream_connect_attempt_total 18649
telemt_upstream_connect_success_total 18648
telemt_upstream_connect_attempts_per_request{bucket="1"} 18648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 312
telemt_me_reconnect_attempts_total 6704
telemt_me_reconnect_success_total 6695
telemt_me_reader_eof_total 9429
telemt_me_idle_close_by_peer_total 9427
telemt_me_route_drop_no_conn_total 27849
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 410
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 35
telemt_me_writer_removed_unexpected_total 9429
telemt_me_writer_restored_same_endpoint_total 6693
telemt_me_writer_removed_unexpected_minus_restored_total 2736
telemt_user_connections_total{user="hello"} 69014
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 1156539524 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 23829788504 (22.19 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 9954.4 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149901
telemt_connections_bad_total 360
telemt_handshake_timeouts_total 1884
telemt_upstream_connect_attempt_total 15200
telemt_upstream_connect_success_total 15077
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 15109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 904
telemt_me_reconnect_attempts_total 4190
telemt_me_reconnect_success_total 4165
telemt_me_reader_eof_total 5681
telemt_me_idle_close_by_peer_total 5678
telemt_me_route_drop_no_conn_total 61791
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 712
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 542
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 5781
telemt_me_writer_restored_same_endpoint_total 4158
telemt_me_writer_removed_unexpected_minus_restored_total 1623
telemt_user_connections_total{user="hello"} 138239
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 7492740592 (6.98 GB)
telemt_user_octets_to_client{user="hello"} 39427409804 (36.72 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 9954.9 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158816
telemt_connections_bad_total 48805
telemt_handshake_timeouts_total 12429
telemt_upstream_connect_attempt_total 14504
telemt_upstream_connect_success_total 14465
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 14482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 4314
telemt_me_reconnect_success_total 4303
telemt_me_reader_eof_total 5468
telemt_me_idle_close_by_peer_total 5468
telemt_me_route_drop_no_conn_total 38701
telemt_me_single_endpoint_shadow_rotate_total 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 123
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 5
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 5474
telemt_me_writer_restored_same_endpoint_total 4298
telemt_me_writer_removed_unexpected_minus_restored_total 1176
telemt_user_connections_total{user="hello"} 94658
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 1250258880 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 30259216924 (28.18 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 9953.4 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126720
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 820
telemt_upstream_connect_attempt_total 15074
telemt_upstream_connect_success_total 14973
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 14989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 646
telemt_me_reconnect_attempts_total 4498
telemt_me_reconnect_success_total 4478
telemt_me_reader_eof_total 6154
telemt_me_idle_close_by_peer_total 6153
telemt_me_route_drop_no_conn_total 47045
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 630
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 478
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 202
telemt_me_writer_removed_unexpected_total 6213
telemt_me_writer_restored_same_endpoint_total 4476
telemt_me_writer_removed_unexpected_minus_restored_total 1737
telemt_user_connections_total{user="hello"} 120162
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 8825447912 (8.22 GB)
telemt_user_octets_to_client{user="hello"} 41274844044 (38.44 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 52
```