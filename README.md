# Server Metrics 2026-03-06 05:34:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 25983.6 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206487
telemt_connections_bad_total 16022
telemt_handshake_timeouts_total 3310
telemt_upstream_connect_attempt_total 27093
telemt_upstream_connect_success_total 26880
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 26880
telemt_upstream_connect_attempts_per_request{bucket="2"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 9875
telemt_me_reconnect_success_total 9838
telemt_me_reader_eof_total 10178
telemt_me_idle_close_by_peer_total 10178
telemt_me_route_drop_no_conn_total 64167
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 630
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 429
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10179
telemt_me_writer_restored_same_endpoint_total 9832
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 178206
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 4796055820 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 68417936492 (63.72 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 25979.0 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81070
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 3208
telemt_upstream_connect_attempt_total 24098
telemt_upstream_connect_success_total 24096
telemt_upstream_connect_attempts_per_request{bucket="1"} 24096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 290
telemt_me_reconnect_attempts_total 6761
telemt_me_reconnect_success_total 6738
telemt_me_reader_eof_total 6888
telemt_me_idle_close_by_peer_total 6888
telemt_me_route_drop_no_conn_total 23781
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 291
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 8
telemt_pool_force_close_total 150
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6889
telemt_me_writer_restored_same_endpoint_total 6732
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 76200
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 730735036 (696.88 MB)
telemt_user_octets_to_client{user="hello"} 23671088196 (22.05 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 25976.4 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138927
telemt_connections_bad_total 1445
telemt_handshake_timeouts_total 3288
telemt_upstream_connect_attempt_total 26413
telemt_upstream_connect_success_total 26222
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 26222
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 319
telemt_me_reconnect_attempts_total 8692
telemt_me_reconnect_success_total 8661
telemt_me_reader_eof_total 9035
telemt_me_idle_close_by_peer_total 9035
telemt_me_route_drop_no_conn_total 40064
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 271
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 9040
telemt_me_writer_restored_same_endpoint_total 8653
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 128131
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 1188456620 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 43315922132 (40.34 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 25973.1 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110653
telemt_connections_bad_total 6900
telemt_handshake_timeouts_total 5728
telemt_upstream_connect_attempt_total 18970
telemt_upstream_connect_success_total 18905
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 18905
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 201
telemt_me_reconnect_attempts_total 4066
telemt_me_reconnect_success_total 4038
telemt_me_reader_eof_total 4169
telemt_me_idle_close_by_peer_total 4169
telemt_me_route_drop_no_conn_total 38366
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 287
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 192
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 8
telemt_pool_force_close_total 169
telemt_me_writer_removed_unexpected_total 4169
telemt_me_writer_restored_same_endpoint_total 4031
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 93285
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 1548288500 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 35218642044 (32.80 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 25972.0 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126079
telemt_connections_bad_total 1028
telemt_handshake_timeouts_total 719
telemt_upstream_connect_attempt_total 17405
telemt_upstream_connect_success_total 17366
telemt_upstream_connect_attempts_per_request{bucket="1"} 17366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2934
telemt_me_reconnect_success_total 2920
telemt_me_reader_eof_total 3022
telemt_me_idle_close_by_peer_total 3021
telemt_me_route_drop_no_conn_total 44660
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 215
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3026
telemt_me_writer_restored_same_endpoint_total 2913
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 122142
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 23777095792 (22.14 GB)
telemt_user_octets_to_client{user="hello"} 74699509952 (69.57 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 66
```