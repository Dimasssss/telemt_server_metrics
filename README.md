# Server Metrics 2026-03-04 03:05:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 21268.8 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134583
telemt_connections_bad_total 1382
telemt_handshake_timeouts_total 1587
telemt_upstream_connect_attempt_total 16910
telemt_upstream_connect_success_total 16839
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 16839
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 4239
telemt_me_reconnect_success_total 4230
telemt_me_reader_eof_total 4328
telemt_me_idle_close_by_peer_total 4328
telemt_me_route_drop_no_conn_total 47455
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 247
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 4
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 4328
telemt_me_writer_restored_same_endpoint_total 4210
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 128631
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 1122539792 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 37966233908 (35.36 GB)
telemt_user_unique_ips_current{user="hello"} 70
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 21265.5 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63101
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 16380
telemt_upstream_connect_attempt_total 52382
telemt_upstream_connect_success_total 51839
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 51833
telemt_upstream_connect_attempts_per_request{bucket="2"} 261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 871
telemt_me_reconnect_attempts_total 32625
telemt_me_reconnect_success_total 32605
telemt_me_reader_eof_total 33430
telemt_me_idle_close_by_peer_total 33429
telemt_me_route_drop_no_conn_total 20692
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 92
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 33491
telemt_me_writer_restored_same_endpoint_total 32585
telemt_me_writer_removed_unexpected_minus_restored_total 906
telemt_user_connections_total{user="hello"} 45697
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 361594996 (344.84 MB)
telemt_user_octets_to_client{user="hello"} 24487506708 (22.81 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 21264.2 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149012
telemt_connections_bad_total 54021
telemt_handshake_timeouts_total 3353
telemt_upstream_connect_attempt_total 26829
telemt_upstream_connect_success_total 26646
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 26646
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 341
telemt_me_reconnect_attempts_total 10049
telemt_me_reconnect_success_total 10026
telemt_me_reader_eof_total 10476
telemt_me_idle_close_by_peer_total 10474
telemt_me_route_drop_no_conn_total 29012
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 289
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 10478
telemt_me_writer_restored_same_endpoint_total 10005
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 88231
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 540914740 (515.86 MB)
telemt_user_octets_to_client{user="hello"} 21770630236 (20.28 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 21263.1 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67246
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 655
telemt_upstream_connect_attempt_total 13689
telemt_upstream_connect_success_total 13620
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 13620
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 1918
telemt_me_reconnect_success_total 1922
telemt_me_reader_eof_total 1930
telemt_me_idle_close_by_peer_total 1930
telemt_me_route_drop_no_conn_total 23254
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 24
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 1930
telemt_me_writer_restored_same_endpoint_total 1901
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 65230
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 529688344 (505.15 MB)
telemt_user_octets_to_client{user="hello"} 22875067552 (21.30 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 21261.8 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161270
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 73126
telemt_upstream_connect_attempt_total 31344
telemt_upstream_connect_success_total 31148
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 31148
telemt_upstream_connect_attempts_per_request{bucket="2"} 94
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 413
telemt_me_reconnect_attempts_total 15513
telemt_me_reconnect_success_total 15510
telemt_me_reader_eof_total 16453
telemt_me_idle_close_by_peer_total 16452
telemt_me_route_drop_no_conn_total 43618
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 120
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 2428
telemt_me_writer_removed_unexpected_total 16458
telemt_me_writer_restored_same_endpoint_total 15486
telemt_me_writer_removed_unexpected_minus_restored_total 972
telemt_user_connections_total{user="hello"} 84954
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 494104752 (471.22 MB)
telemt_user_octets_to_client{user="hello"} 19636070276 (18.29 GB)
telemt_user_unique_ips_current{user="hello"} 21
```