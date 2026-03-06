# Server Metrics 2026-03-06 05:39:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 26290.6 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210500
telemt_connections_bad_total 16022
telemt_handshake_timeouts_total 3345
telemt_upstream_connect_attempt_total 27179
telemt_upstream_connect_success_total 26958
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 26958
telemt_upstream_connect_attempts_per_request{bucket="2"} 105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 9875
telemt_me_reconnect_success_total 9838
telemt_me_reader_eof_total 10178
telemt_me_idle_close_by_peer_total 10178
telemt_me_route_drop_no_conn_total 65400
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 647
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10179
telemt_me_writer_restored_same_endpoint_total 9832
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 182040
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 5270052768 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 69732228040 (64.94 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 26286.0 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83284
telemt_connections_bad_total 149
telemt_handshake_timeouts_total 3752
telemt_upstream_connect_attempt_total 24197
telemt_upstream_connect_success_total 24195
telemt_upstream_connect_attempts_per_request{bucket="1"} 24195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 290
telemt_me_reconnect_attempts_total 6762
telemt_me_reconnect_success_total 6739
telemt_me_reader_eof_total 6889
telemt_me_idle_close_by_peer_total 6889
telemt_me_route_drop_no_conn_total 24334
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 301
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 8
telemt_pool_force_close_total 150
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6890
telemt_me_writer_restored_same_endpoint_total 6733
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 77836
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 762544664 (727.22 MB)
telemt_user_octets_to_client{user="hello"} 25029700688 (23.31 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 26283.4 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145892
telemt_connections_bad_total 1457
telemt_handshake_timeouts_total 3470
telemt_upstream_connect_attempt_total 26978
telemt_upstream_connect_success_total 26783
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 26783
telemt_upstream_connect_attempts_per_request{bucket="2"} 88
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 325
telemt_me_reconnect_attempts_total 8943
telemt_me_reconnect_success_total 8912
telemt_me_reader_eof_total 9289
telemt_me_idle_close_by_peer_total 9289
telemt_me_route_drop_no_conn_total 41385
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 276
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 184
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 9294
telemt_me_writer_restored_same_endpoint_total 8904
telemt_me_writer_removed_unexpected_minus_restored_total 390
telemt_user_connections_total{user="hello"} 131404
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 1209974400 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 44133399160 (41.10 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 26280.1 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112950
telemt_connections_bad_total 7171
telemt_handshake_timeouts_total 5759
telemt_upstream_connect_attempt_total 19449
telemt_upstream_connect_success_total 19382
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 19382
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 4260
telemt_me_reconnect_success_total 4232
telemt_me_reader_eof_total 4377
telemt_me_idle_close_by_peer_total 4377
telemt_me_route_drop_no_conn_total 39385
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 292
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 8
telemt_pool_force_close_total 169
telemt_me_writer_removed_unexpected_total 4377
telemt_me_writer_restored_same_endpoint_total 4225
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 95213
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 1569903300 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 36116140264 (33.64 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 26279.0 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129393
telemt_connections_bad_total 1030
telemt_handshake_timeouts_total 729
telemt_upstream_connect_attempt_total 17637
telemt_upstream_connect_success_total 17597
telemt_upstream_connect_attempts_per_request{bucket="1"} 17597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 2960
telemt_me_reconnect_success_total 2946
telemt_me_reader_eof_total 3048
telemt_me_idle_close_by_peer_total 3047
telemt_me_route_drop_no_conn_total 45918
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 248
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 145
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3052
telemt_me_writer_restored_same_endpoint_total 2939
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 125344
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 23797630272 (22.16 GB)
telemt_user_octets_to_client{user="hello"} 76708211256 (71.44 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 61
```