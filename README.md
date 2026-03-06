# Server Metrics 2026-03-06 07:22:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 32433.9 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324441
telemt_connections_bad_total 16192
telemt_handshake_timeouts_total 3925
telemt_upstream_connect_attempt_total 32724
telemt_upstream_connect_success_total 32403
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 32403
telemt_upstream_connect_attempts_per_request{bucket="2"} 143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 337
telemt_me_reconnect_attempts_total 11467
telemt_me_reconnect_success_total 11419
telemt_me_reader_eof_total 11814
telemt_me_idle_close_by_peer_total 11814
telemt_me_route_drop_no_conn_total 113235
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1099
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 757
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 11817
telemt_me_writer_restored_same_endpoint_total 11413
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 285340
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 9671925032 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 103542887772 (96.43 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 32429.2 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139557
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 15396
telemt_upstream_connect_attempt_total 26036
telemt_upstream_connect_success_total 26034
telemt_upstream_connect_attempts_per_request{bucket="1"} 26034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 6795
telemt_me_reconnect_success_total 6765
telemt_me_reader_eof_total 6916
telemt_me_idle_close_by_peer_total 6916
telemt_me_route_drop_no_conn_total 41361
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 429
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6917
telemt_me_writer_restored_same_endpoint_total 6758
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 121453
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 1399497084 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 38824054320 (36.16 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 32426.7 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245516
telemt_connections_bad_total 1805
telemt_handshake_timeouts_total 7690
telemt_upstream_connect_attempt_total 36611
telemt_upstream_connect_success_total 36337
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 36337
telemt_upstream_connect_attempts_per_request{bucket="2"} 124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 516
telemt_me_reconnect_attempts_total 14114
telemt_me_reconnect_success_total 14073
telemt_me_reader_eof_total 14726
telemt_me_idle_close_by_peer_total 14724
telemt_me_route_drop_no_conn_total 72473
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 546
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 376
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14754
telemt_me_writer_restored_same_endpoint_total 14051
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 689
telemt_user_connections_total{user="hello"} 216078
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 2226586280 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 67689666240 (63.04 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 32423.3 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186783
telemt_connections_bad_total 23223
telemt_handshake_timeouts_total 7611
telemt_upstream_connect_attempt_total 22833
telemt_upstream_connect_success_total 22754
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 22754
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 247
telemt_me_reconnect_attempts_total 5012
telemt_me_reconnect_success_total 4979
telemt_me_reader_eof_total 5151
telemt_me_idle_close_by_peer_total 5151
telemt_me_route_drop_no_conn_total 58611
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 430
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 10
telemt_pool_force_close_total 244
telemt_me_writer_removed_unexpected_total 5152
telemt_me_writer_restored_same_endpoint_total 4972
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 148976
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 2085992380 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 52757428236 (49.13 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 32422.2 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199337
telemt_connections_bad_total 3284
telemt_handshake_timeouts_total 1133
telemt_upstream_connect_attempt_total 21593
telemt_upstream_connect_success_total 21543
telemt_upstream_connect_attempts_per_request{bucket="1"} 21543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 3754
telemt_me_reconnect_success_total 3735
telemt_me_reader_eof_total 3854
telemt_me_idle_close_by_peer_total 3853
telemt_me_route_drop_no_conn_total 80613
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 452
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3869
telemt_me_writer_restored_same_endpoint_total 3728
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 191065
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 24509567600 (22.83 GB)
telemt_user_octets_to_client{user="hello"} 114743762764 (106.86 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 82
```