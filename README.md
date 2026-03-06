# Server Metrics 2026-03-06 23:07:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 17975.6 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270030
telemt_connections_bad_total 2500
telemt_handshake_timeouts_total 9256
telemt_upstream_connect_attempt_total 36357
telemt_upstream_connect_success_total 35733
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 36221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 83
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_timeout_total 1250
telemt_me_reconnect_attempts_total 14967
telemt_me_reconnect_success_total 14518
telemt_me_reader_eof_total 17605
telemt_me_idle_close_by_peer_total 17605
telemt_me_route_drop_no_conn_total 107176
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 855
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 607
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 341
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 17715
telemt_me_writer_restored_same_endpoint_total 14487
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 7635
telemt_me_writer_removed_unexpected_minus_restored_total 3203
telemt_user_connections_total{user="hello"} 244021
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 3888881004 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 111293683208 (103.65 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 17975.6 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111520
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 10661
telemt_upstream_connect_attempt_total 52793
telemt_upstream_connect_success_total 52791
telemt_upstream_connect_attempts_per_request{bucket="1"} 52791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 742
telemt_me_reconnect_attempts_total 28907
telemt_me_reconnect_success_total 28793
telemt_me_reader_eof_total 30370
telemt_me_idle_close_by_peer_total 30366
telemt_me_route_drop_no_conn_total 38813
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 699
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 513
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 9
telemt_pool_force_close_total 433
telemt_pool_stale_pick_total 37
telemt_me_writer_removed_unexpected_total 30391
telemt_me_writer_restored_same_endpoint_total 28791
telemt_me_async_recovery_trigger_total 7627
telemt_me_writer_removed_unexpected_minus_restored_total 1600
telemt_user_connections_total{user="hello"} 95012
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 1442285996 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 35155389472 (32.74 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 17975.5 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209600
telemt_connections_bad_total 903
telemt_handshake_timeouts_total 3497
telemt_upstream_connect_attempt_total 40503
telemt_upstream_connect_success_total 40351
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 40397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1347
telemt_me_reconnect_attempts_total 19983
telemt_me_reconnect_success_total 19942
telemt_me_reader_eof_total 21087
telemt_me_idle_close_by_peer_total 21084
telemt_me_route_drop_no_conn_total 80329
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 147
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 951
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 379
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 10
telemt_pool_force_close_total 298
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 21227
telemt_me_writer_restored_same_endpoint_total 19935
telemt_me_async_recovery_trigger_total 22749
telemt_me_writer_removed_unexpected_minus_restored_total 1292
telemt_user_connections_total{user="hello"} 194667
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 14351545988 (13.37 GB)
telemt_user_octets_to_client{user="hello"} 58336353488 (54.33 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 17976.0 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208366
telemt_connections_bad_total 56131
telemt_handshake_timeouts_total 16161
telemt_upstream_connect_attempt_total 30592
telemt_upstream_connect_success_total 30515
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 30544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 597
telemt_me_reconnect_attempts_total 9794
telemt_me_reconnect_success_total 9773
telemt_me_reader_eof_total 13144
telemt_me_idle_close_by_peer_total 13143
telemt_me_route_drop_no_conn_total 55174
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 176
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 9
telemt_pool_force_close_total 332
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 13150
telemt_me_writer_restored_same_endpoint_total 9768
telemt_me_writer_removed_unexpected_minus_restored_total 3382
telemt_user_connections_total{user="hello"} 132553
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1641199556 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 42156648428 (39.26 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 17974.4 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181437
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 1581
telemt_upstream_connect_attempt_total 28136
telemt_upstream_connect_success_total 27999
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 28018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 907
telemt_me_reconnect_attempts_total 8382
telemt_me_reconnect_success_total 8352
telemt_me_reader_eof_total 11319
telemt_me_idle_close_by_peer_total 11318
telemt_me_route_drop_no_conn_total 62284
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 733
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 9
telemt_pool_force_close_total 342
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 11386
telemt_me_writer_restored_same_endpoint_total 8348
telemt_me_writer_removed_unexpected_minus_restored_total 3038
telemt_user_connections_total{user="hello"} 166141
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 10032776204 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 55833377764 (52.00 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 17
```