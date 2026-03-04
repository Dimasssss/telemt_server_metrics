# Server Metrics 2026-03-04 05:48:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 31096.8 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240972
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 4846
telemt_upstream_connect_attempt_total 21080
telemt_upstream_connect_success_total 20983
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 20983
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 4602
telemt_me_reconnect_success_total 4582
telemt_me_reader_eof_total 4687
telemt_me_idle_close_by_peer_total 4687
telemt_me_route_drop_no_conn_total 83518
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 639
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4687
telemt_me_writer_restored_same_endpoint_total 4562
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 227595
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 2385938464 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 74126007628 (69.04 GB)
telemt_user_unique_ips_current{user="hello"} 75
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 31093.3 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112196
telemt_connections_bad_total 362
telemt_handshake_timeouts_total 21951
telemt_upstream_connect_attempt_total 69849
telemt_upstream_connect_success_total 69028
telemt_upstream_connect_fail_total 393
telemt_upstream_connect_attempts_per_request{bucket="1"} 69022
telemt_upstream_connect_attempts_per_request{bucket="2"} 399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 393
telemt_me_keepalive_timeout_total 1017
telemt_me_reconnect_attempts_total 41965
telemt_me_reconnect_success_total 41936
telemt_me_reader_eof_total 42999
telemt_me_idle_close_by_peer_total 42998
telemt_me_route_drop_no_conn_total 36200
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 238
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 43060
telemt_me_writer_restored_same_endpoint_total 41915
telemt_me_writer_removed_unexpected_minus_restored_total 1145
telemt_user_connections_total{user="hello"} 82715
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 727801588 (694.09 MB)
telemt_user_octets_to_client{user="hello"} 35168566120 (32.75 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 31092.0 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251306
telemt_connections_bad_total 89076
telemt_handshake_timeouts_total 5202
telemt_upstream_connect_attempt_total 41482
telemt_upstream_connect_success_total 41215
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 41215
telemt_upstream_connect_attempts_per_request{bucket="2"} 125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 538
telemt_me_reconnect_attempts_total 16842
telemt_me_reconnect_success_total 16797
telemt_me_reader_eof_total 17686
telemt_me_idle_close_by_peer_total 17683
telemt_me_route_drop_no_conn_total 53427
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 370
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 17694
telemt_me_writer_restored_same_endpoint_total 16776
telemt_me_writer_removed_unexpected_minus_restored_total 918
telemt_user_connections_total{user="hello"} 149617
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 1085263508 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 39144025568 (36.46 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 31090.9 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128362
telemt_connections_bad_total 9414
telemt_handshake_timeouts_total 2303
telemt_upstream_connect_attempt_total 23383
telemt_upstream_connect_success_total 23293
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 23293
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 245
telemt_me_reconnect_attempts_total 4621
telemt_me_reconnect_success_total 4615
telemt_me_reader_eof_total 4692
telemt_me_idle_close_by_peer_total 4692
telemt_me_route_drop_no_conn_total 39095
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 141
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 4692
telemt_me_writer_restored_same_endpoint_total 4594
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 110479
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 964161004 (919.50 MB)
telemt_user_octets_to_client{user="hello"} 41172304112 (38.34 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 31089.8 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266779
telemt_connections_bad_total 5435
telemt_handshake_timeouts_total 120505
telemt_upstream_connect_attempt_total 44876
telemt_upstream_connect_success_total 44561
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 44561
telemt_upstream_connect_attempts_per_request{bucket="2"} 148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 615
telemt_me_reconnect_attempts_total 21398
telemt_me_reconnect_success_total 21387
telemt_me_reader_eof_total 22570
telemt_me_idle_close_by_peer_total 22569
telemt_me_route_drop_no_conn_total 59820
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 197
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22583
telemt_me_writer_restored_same_endpoint_total 21362
telemt_me_writer_removed_unexpected_minus_restored_total 1221
telemt_user_connections_total{user="hello"} 136163
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 1936284256 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 31590547820 (29.42 GB)
telemt_user_unique_ips_current{user="hello"} 34
```