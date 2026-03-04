# Server Metrics 2026-03-04 21:59:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 3936.9 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46602
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 397
telemt_upstream_connect_attempt_total 2286
telemt_upstream_connect_success_total 2254
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2254
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 884
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 364
telemt_me_reconnect_success_total 377
telemt_me_reader_eof_total 366
telemt_me_idle_close_by_peer_total 366
telemt_me_route_drop_no_conn_total 10999
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 366
telemt_me_writer_restored_same_endpoint_total 357
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 39632
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 2108890768 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 16472306712 (15.34 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 3931.8 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17729
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 2431
telemt_upstream_connect_success_total 2399
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2399
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1037
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 354
telemt_me_reconnect_success_total 365
telemt_me_reader_eof_total 358
telemt_me_idle_close_by_peer_total 358
telemt_me_route_drop_no_conn_total 4854
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_restored_same_endpoint_total 346
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 16371
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 162572992 (155.04 MB)
telemt_user_octets_to_client{user="hello"} 4645368048 (4.33 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 3928.4 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40219
telemt_connections_bad_total 588
telemt_handshake_timeouts_total 208
telemt_upstream_connect_attempt_total 1232
telemt_upstream_connect_success_total 1216
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1216
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 33
telemt_me_reader_eof_total 14
telemt_me_idle_close_by_peer_total 14
telemt_me_route_drop_no_conn_total 11591
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 113
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 14
telemt_me_writer_restored_same_endpoint_total 13
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 36259
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 564984688 (538.81 MB)
telemt_user_octets_to_client{user="hello"} 14301570572 (13.32 GB)
telemt_user_unique_ips_current{user="hello"} 62
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 35976.6 (9h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502987
telemt_connections_bad_total 65702
telemt_handshake_timeouts_total 14637
telemt_upstream_connect_attempt_total 15680
telemt_upstream_connect_success_total 15680
telemt_upstream_connect_attempts_per_request{bucket="1"} 15680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 211
telemt_me_reconnect_attempts_total 2125
telemt_me_reconnect_success_total 2112
telemt_me_reader_eof_total 2149
telemt_me_idle_close_by_peer_total 2149
telemt_me_route_drop_no_conn_total 174021
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 695
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 12
telemt_pool_force_close_total 397
telemt_me_writer_removed_unexpected_total 2150
telemt_me_writer_restored_same_endpoint_total 2088
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 394611
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 5619624228 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 152358340096 (141.89 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 36335.8 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505139
telemt_connections_bad_total 3758
telemt_handshake_timeouts_total 5591
telemt_upstream_connect_attempt_total 21580
telemt_upstream_connect_success_total 21466
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 21466
telemt_upstream_connect_attempts_per_request{bucket="2"} 47
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 4559
telemt_me_reconnect_success_total 4547
telemt_me_reader_eof_total 4711
telemt_me_idle_close_by_peer_total 4711
telemt_me_route_drop_no_conn_total 224314
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 825
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4714
telemt_me_writer_restored_same_endpoint_total 4526
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 456013
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 7087718332 (6.60 GB)
telemt_user_octets_to_client{user="hello"} 145776967416 (135.77 GB)
telemt_user_unique_ips_current{user="hello"} 31
```