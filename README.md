# Server Metrics 2026-03-06 19:41:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 5632.4 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137082
telemt_connections_bad_total 1382
telemt_handshake_timeouts_total 4817
telemt_upstream_connect_attempt_total 8074
telemt_upstream_connect_success_total 7983
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 8019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 2512
telemt_me_reconnect_success_total 2497
telemt_me_reader_eof_total 3236
telemt_me_idle_close_by_peer_total 3236
telemt_me_route_drop_no_conn_total 55581
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 547
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 394
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 201
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 150
telemt_me_writer_removed_unexpected_total 3259
telemt_me_writer_restored_same_endpoint_total 2491
telemt_me_writer_removed_unexpected_minus_restored_total 768
telemt_user_connections_total{user="hello"} 119571
telemt_user_connections_current{user="hello"} 772
telemt_user_octets_from_client{user="hello"} 2017006744 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 40158360804 (37.40 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 5632.4 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50417
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 2353
telemt_upstream_connect_attempt_total 9776
telemt_upstream_connect_success_total 9775
telemt_upstream_connect_attempts_per_request{bucket="1"} 9775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 3347
telemt_me_reconnect_success_total 3342
telemt_me_reader_eof_total 4384
telemt_me_idle_close_by_peer_total 4382
telemt_me_route_drop_no_conn_total 17731
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 203
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 4384
telemt_me_writer_restored_same_endpoint_total 3340
telemt_me_writer_removed_unexpected_minus_restored_total 1044
telemt_user_connections_total{user="hello"} 44306
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 923871292 (881.07 MB)
telemt_user_octets_to_client{user="hello"} 13309370232 (12.40 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 5632.2 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89847
telemt_connections_bad_total 253
telemt_handshake_timeouts_total 1110
telemt_upstream_connect_attempt_total 6680
telemt_upstream_connect_success_total 6658
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 1271
telemt_me_reconnect_success_total 1269
telemt_me_reader_eof_total 1662
telemt_me_idle_close_by_peer_total 1662
telemt_me_route_drop_no_conn_total 28411
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 444
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 342
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 3
telemt_pool_force_close_total 88
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 1664
telemt_me_writer_restored_same_endpoint_total 1262
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 84149
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 3878981828 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 24488817632 (22.81 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 5633.0 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108987
telemt_connections_bad_total 41603
telemt_handshake_timeouts_total 6051
telemt_upstream_connect_attempt_total 8352
telemt_upstream_connect_success_total 8333
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 8348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 2592
telemt_me_reconnect_success_total 2585
telemt_me_reader_eof_total 3310
telemt_me_idle_close_by_peer_total 3310
telemt_me_route_drop_no_conn_total 19903
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 55
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_pool_stale_pick_total 323
telemt_me_writer_removed_unexpected_total 3310
telemt_me_writer_restored_same_endpoint_total 2581
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 59252
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 618105932 (589.47 MB)
telemt_user_octets_to_client{user="hello"} 19935534096 (18.57 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 5631.2 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82150
telemt_connections_bad_total 441
telemt_handshake_timeouts_total 452
telemt_upstream_connect_attempt_total 7900
telemt_upstream_connect_success_total 7877
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 2316
telemt_me_reconnect_success_total 2311
telemt_me_reader_eof_total 3228
telemt_me_idle_close_by_peer_total 3227
telemt_me_route_drop_no_conn_total 30839
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 462
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 361
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 2
telemt_pool_force_close_total 106
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 3232
telemt_me_writer_restored_same_endpoint_total 2309
telemt_me_writer_removed_unexpected_minus_restored_total 923
telemt_user_connections_total{user="hello"} 77841
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 8360460852 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 29974060652 (27.92 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 112
```