# Server Metrics 2026-03-06 09:50:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 4737.8 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133886
telemt_connections_bad_total 397
telemt_handshake_timeouts_total 757
telemt_upstream_connect_attempt_total 1474
telemt_upstream_connect_success_total 1467
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 637
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 26
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 55586
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 713
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 295
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 27
telemt_me_writer_restored_same_endpoint_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 107026
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 1623365096 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 43522125060 (40.53 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 4735.1 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73743
telemt_connections_bad_total 344
telemt_handshake_timeouts_total 29756
telemt_upstream_connect_attempt_total 2562
telemt_upstream_connect_success_total 2562
telemt_upstream_connect_attempts_per_request{bucket="1"} 2562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1176
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 171
telemt_me_reconnect_success_total 167
telemt_me_reader_eof_total 171
telemt_me_idle_close_by_peer_total 171
telemt_me_route_drop_no_conn_total 16581
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 191
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_me_writer_removed_unexpected_total 171
telemt_me_writer_restored_same_endpoint_total 167
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 42753
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 672448308 (641.30 MB)
telemt_user_octets_to_client{user="hello"} 12970084992 (12.08 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 4718.4 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96171
telemt_connections_bad_total 288
telemt_handshake_timeouts_total 11379
telemt_upstream_connect_attempt_total 2636
telemt_upstream_connect_success_total 2618
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 281
telemt_me_reconnect_success_total 271
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 272
telemt_me_route_drop_no_conn_total 30214
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 214
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 278
telemt_me_writer_restored_same_endpoint_total 271
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 81243
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 1367014316 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 21501295496 (20.02 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 4702.9 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73415
telemt_connections_bad_total 4273
telemt_handshake_timeouts_total 12286
telemt_upstream_connect_attempt_total 2871
telemt_upstream_connect_success_total 2851
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 510
telemt_me_reconnect_success_total 504
telemt_me_reader_eof_total 511
telemt_me_idle_close_by_peer_total 511
telemt_me_route_drop_no_conn_total 26639
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 511
telemt_me_writer_restored_same_endpoint_total 502
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 54678
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 861743000 (821.82 MB)
telemt_user_octets_to_client{user="hello"} 15833181036 (14.75 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 4644.5 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65970
telemt_connections_bad_total 270
telemt_handshake_timeouts_total 381
telemt_upstream_connect_attempt_total 2773
telemt_upstream_connect_success_total 2741
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 2771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 536
telemt_me_reconnect_success_total 531
telemt_me_reader_eof_total 544
telemt_me_idle_close_by_peer_total 544
telemt_me_route_drop_no_conn_total 30733
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 108
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_me_writer_removed_unexpected_total 547
telemt_me_writer_restored_same_endpoint_total 526
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 61130
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 1008220412 (961.51 MB)
telemt_user_octets_to_client{user="hello"} 28167569796 (26.23 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 91
```