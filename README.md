# Server Metrics 2026-03-06 23:12:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 18283.2 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272150
telemt_connections_bad_total 2687
telemt_handshake_timeouts_total 9260
telemt_upstream_connect_attempt_total 37805
telemt_upstream_connect_success_total 37105
telemt_upstream_connect_fail_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 37667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 562
telemt_me_keepalive_timeout_total 1277
telemt_me_reconnect_attempts_total 16038
telemt_me_reconnect_success_total 15516
telemt_me_reader_eof_total 18256
telemt_me_idle_close_by_peer_total 18256
telemt_me_route_drop_no_conn_total 108095
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 855
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 607
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 341
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 6
telemt_pool_force_close_total 377
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 18366
telemt_me_writer_restored_same_endpoint_total 15481
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 8858
telemt_me_writer_removed_unexpected_minus_restored_total 2856
telemt_user_connections_total{user="hello"} 245890
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 3924949236 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 111934690176 (104.25 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 18283.1 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112657
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 10901
telemt_upstream_connect_attempt_total 55883
telemt_upstream_connect_success_total 55879
telemt_upstream_connect_attempts_per_request{bucket="1"} 55879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 765
telemt_me_reconnect_attempts_total 31513
telemt_me_reconnect_success_total 31387
telemt_me_reader_eof_total 32167
telemt_me_idle_close_by_peer_total 32163
telemt_me_route_drop_no_conn_total 39045
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 699
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 513
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 10
telemt_pool_force_close_total 518
telemt_pool_stale_pick_total 50
telemt_me_writer_removed_unexpected_total 32189
telemt_me_writer_restored_same_endpoint_total 31385
telemt_me_async_recovery_trigger_total 8851
telemt_me_writer_removed_unexpected_minus_restored_total 804
telemt_user_connections_total{user="hello"} 95888
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 1462541248 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 35234268464 (32.81 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 18282.9 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210712
telemt_connections_bad_total 915
telemt_handshake_timeouts_total 3498
telemt_upstream_connect_attempt_total 43355
telemt_upstream_connect_success_total 43202
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 43248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1390
telemt_me_reconnect_attempts_total 22335
telemt_me_reconnect_success_total 22294
telemt_me_reader_eof_total 23541
telemt_me_idle_close_by_peer_total 23538
telemt_me_route_drop_no_conn_total 80780
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 957
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 718
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 380
telemt_desync_frames_bucket_total{bucket="gt_10"} 394
telemt_pool_swap_total 10
telemt_pool_force_close_total 298
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 23687
telemt_me_writer_restored_same_endpoint_total 22287
telemt_me_async_recovery_trigger_total 26415
telemt_me_writer_removed_unexpected_minus_restored_total 1400
telemt_user_connections_total{user="hello"} 195756
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 14608165188 (13.60 GB)
telemt_user_octets_to_client{user="hello"} 58507980312 (54.49 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 18283.4 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209817
telemt_connections_bad_total 56402
telemt_handshake_timeouts_total 16166
telemt_upstream_connect_attempt_total 31085
telemt_upstream_connect_success_total 31007
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 621
telemt_me_reconnect_attempts_total 9939
telemt_me_reconnect_success_total 9919
telemt_me_reader_eof_total 13350
telemt_me_idle_close_by_peer_total 13349
telemt_me_route_drop_no_conn_total 55766
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 176
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 10
telemt_pool_force_close_total 366
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 13356
telemt_me_writer_restored_same_endpoint_total 9914
telemt_me_writer_removed_unexpected_minus_restored_total 3442
telemt_user_connections_total{user="hello"} 133714
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 1646247748 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 42282695244 (39.38 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 18281.8 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182607
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 1628
telemt_upstream_connect_attempt_total 28611
telemt_upstream_connect_success_total 28474
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 28493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 920
telemt_me_reconnect_attempts_total 8505
telemt_me_reconnect_success_total 8475
telemt_me_reader_eof_total 11476
telemt_me_idle_close_by_peer_total 11475
telemt_me_route_drop_no_conn_total 62466
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 734
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 10
telemt_pool_force_close_total 351
telemt_pool_stale_pick_total 211
telemt_me_writer_removed_unexpected_total 11543
telemt_me_writer_restored_same_endpoint_total 8471
telemt_me_writer_removed_unexpected_minus_restored_total 3072
telemt_user_connections_total{user="hello"} 167137
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 10036063324 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 56028475192 (52.18 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```