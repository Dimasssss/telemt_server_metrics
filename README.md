# Server Metrics 2026-03-06 21:50:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 13355.6 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240183
telemt_connections_bad_total 2208
telemt_handshake_timeouts_total 9002
telemt_upstream_connect_attempt_total 21324
telemt_upstream_connect_success_total 21164
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 21224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13909
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1008
telemt_me_reconnect_attempts_total 6523
telemt_me_reconnect_success_total 6490
telemt_me_reader_eof_total 8481
telemt_me_idle_close_by_peer_total 8481
telemt_me_route_drop_no_conn_total 92260
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 807
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 321
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 8588
telemt_me_writer_restored_same_endpoint_total 6484
telemt_me_writer_removed_unexpected_minus_restored_total 2104
telemt_user_connections_total{user="hello"} 215463
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 3223694448 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 83214067008 (77.50 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 13355.6 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94073
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 6851
telemt_upstream_connect_attempt_total 24749
telemt_upstream_connect_success_total 24748
telemt_upstream_connect_attempts_per_request{bucket="1"} 24748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 408
telemt_me_reconnect_attempts_total 8250
telemt_me_reconnect_success_total 8238
telemt_me_reader_eof_total 11577
telemt_me_idle_close_by_peer_total 11575
telemt_me_route_drop_no_conn_total 34255
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 603
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 446
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 11577
telemt_me_writer_restored_same_endpoint_total 8236
telemt_me_writer_removed_unexpected_minus_restored_total 3341
telemt_user_connections_total{user="hello"} 81863
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1292346396 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 26420616448 (24.61 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 13355.5 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181740
telemt_connections_bad_total 461
telemt_handshake_timeouts_total 2904
telemt_upstream_connect_attempt_total 20649
telemt_upstream_connect_success_total 20509
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 20547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 988
telemt_me_reconnect_attempts_total 5916
telemt_me_reconnect_success_total 5890
telemt_me_reader_eof_total 7839
telemt_me_idle_close_by_peer_total 7836
telemt_me_route_drop_no_conn_total 70518
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 834
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 631
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 6
telemt_pool_force_close_total 223
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 7940
telemt_me_writer_restored_same_endpoint_total 5883
telemt_me_writer_removed_unexpected_minus_restored_total 2057
telemt_user_connections_total{user="hello"} 168132
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 10425134756 (9.71 GB)
telemt_user_octets_to_client{user="hello"} 49664408096 (46.25 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 13356.0 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184244
telemt_connections_bad_total 51981
telemt_handshake_timeouts_total 14211
telemt_upstream_connect_attempt_total 20993
telemt_upstream_connect_success_total 20937
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 20956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 407
telemt_me_reconnect_attempts_total 6427
telemt_me_reconnect_success_total 6412
telemt_me_reader_eof_total 8374
telemt_me_idle_close_by_peer_total 8374
telemt_me_route_drop_no_conn_total 46132
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 7
telemt_pool_force_close_total 271
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 8379
telemt_me_writer_restored_same_endpoint_total 6407
telemt_me_writer_removed_unexpected_minus_restored_total 1972
telemt_user_connections_total{user="hello"} 114854
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 1564196572 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 35939772104 (33.47 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 13354.4 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155064
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 1096
telemt_upstream_connect_attempt_total 20396
telemt_upstream_connect_success_total 20273
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 20292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 752
telemt_me_reconnect_attempts_total 6332
telemt_me_reconnect_success_total 6305
telemt_me_reader_eof_total 8578
telemt_me_idle_close_by_peer_total 8577
telemt_me_route_drop_no_conn_total 54656
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 728
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 236
telemt_pool_swap_total 6
telemt_pool_force_close_total 261
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 8640
telemt_me_writer_restored_same_endpoint_total 6303
telemt_me_writer_removed_unexpected_minus_restored_total 2337
telemt_user_connections_total{user="hello"} 143002
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 9229084312 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 48941413152 (45.58 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 35
```