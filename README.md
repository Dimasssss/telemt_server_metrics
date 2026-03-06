# Server Metrics 2026-03-06 18:24:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 1008.8 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28836
telemt_connections_bad_total 425
telemt_handshake_timeouts_total 453
telemt_upstream_connect_attempt_total 403
telemt_upstream_connect_success_total 364
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 19
telemt_me_reconnect_success_total 15
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 9257
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 187
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_me_writer_removed_unexpected_total 27
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 26065
telemt_user_connections_current{user="hello"} 1052
telemt_user_octets_from_client{user="hello"} 847599964 (808.33 MB)
telemt_user_octets_to_client{user="hello"} 8573039712 (7.98 GB)
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 1008.5 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9231
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 1034
telemt_upstream_connect_success_total 1034
telemt_upstream_connect_attempts_per_request{bucket="1"} 1034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 928
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 275
telemt_me_reader_eof_total 337
telemt_me_idle_close_by_peer_total 337
telemt_me_route_drop_no_conn_total 2876
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 337
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 8842
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 149521808 (142.60 MB)
telemt_user_octets_to_client{user="hello"} 2247309392 (2.09 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 1008.4 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18235
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 347
telemt_upstream_connect_attempt_total 912
telemt_upstream_connect_success_total 903
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 93
telemt_me_reconnect_success_total 97
telemt_me_reader_eof_total 105
telemt_me_idle_close_by_peer_total 105
telemt_me_route_drop_no_conn_total 5015
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 93
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_me_writer_removed_unexpected_total 107
telemt_me_writer_restored_same_endpoint_total 90
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 16998
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 270159300 (257.64 MB)
telemt_user_octets_to_client{user="hello"} 3096463520 (2.88 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 1008.9 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19434
telemt_connections_bad_total 6001
telemt_handshake_timeouts_total 484
telemt_upstream_connect_attempt_total 745
telemt_upstream_connect_success_total 733
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 38
telemt_me_reader_eof_total 39
telemt_me_idle_close_by_peer_total 39
telemt_me_route_drop_no_conn_total 3629
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_pool_swap_total 1
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_restored_same_endpoint_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 12426
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 62375504 (59.49 MB)
telemt_user_octets_to_client{user="hello"} 4387558720 (4.09 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 1007.6 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19048
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 449
telemt_upstream_connect_success_total 435
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 12
telemt_me_reconnect_success_total 10
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 4919
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 17565
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 170162700 (162.28 MB)
telemt_user_octets_to_client{user="hello"} 7495913228 (6.98 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 83
```