# Server Metrics 2026-03-06 20:33:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 8717.8 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190243
telemt_connections_bad_total 2061
telemt_handshake_timeouts_total 8249
telemt_upstream_connect_attempt_total 13022
telemt_upstream_connect_success_total 12906
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 12951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 353
telemt_me_reconnect_attempts_total 3963
telemt_me_reconnect_success_total 3944
telemt_me_reader_eof_total 5096
telemt_me_idle_close_by_peer_total 5096
telemt_me_route_drop_no_conn_total 74777
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 633
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 447
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 2
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 5120
telemt_me_writer_restored_same_endpoint_total 3938
telemt_me_writer_removed_unexpected_minus_restored_total 1182
telemt_user_connections_total{user="hello"} 167089
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 2637996544 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 60098954076 (55.97 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 8717.7 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70280
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 3256
telemt_upstream_connect_attempt_total 17495
telemt_upstream_connect_success_total 17494
telemt_upstream_connect_attempts_per_request{bucket="1"} 17494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 294
telemt_me_reconnect_attempts_total 6539
telemt_me_reconnect_success_total 6532
telemt_me_reader_eof_total 9251
telemt_me_idle_close_by_peer_total 9249
telemt_me_route_drop_no_conn_total 25598
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 297
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 3
telemt_pool_force_close_total 166
telemt_pool_stale_pick_total 28
telemt_me_writer_removed_unexpected_total 9251
telemt_me_writer_restored_same_endpoint_total 6530
telemt_me_writer_removed_unexpected_minus_restored_total 2721
telemt_user_connections_total{user="hello"} 62416
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 1104634692 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 21163029300 (19.71 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 8717.6 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136698
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 1364
telemt_upstream_connect_attempt_total 12293
telemt_upstream_connect_success_total 12220
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 12245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 607
telemt_me_reconnect_attempts_total 3088
telemt_me_reconnect_success_total 3074
telemt_me_reader_eof_total 4140
telemt_me_idle_close_by_peer_total 4137
telemt_me_route_drop_no_conn_total 56480
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 657
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 504
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 4205
telemt_me_writer_restored_same_endpoint_total 3067
telemt_me_writer_removed_unexpected_minus_restored_total 1138
telemt_user_connections_total{user="hello"} 125845
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 6540945180 (6.09 GB)
telemt_user_octets_to_client{user="hello"} 35241238724 (32.82 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 8718.0 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146307
telemt_connections_bad_total 47703
telemt_handshake_timeouts_total 10813
telemt_upstream_connect_attempt_total 12617
telemt_upstream_connect_success_total 12583
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 12599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 3810
telemt_me_reconnect_success_total 3800
telemt_me_reader_eof_total 4837
telemt_me_idle_close_by_peer_total 4837
telemt_me_route_drop_no_conn_total 35306
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 88
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 4
telemt_pool_force_close_total 157
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 4839
telemt_me_writer_restored_same_endpoint_total 3796
telemt_me_writer_removed_unexpected_minus_restored_total 1043
telemt_user_connections_total{user="hello"} 85102
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 1140589296 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 27967348056 (26.05 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 8716.3 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115459
telemt_connections_bad_total 451
telemt_handshake_timeouts_total 705
telemt_upstream_connect_attempt_total 13546
telemt_upstream_connect_success_total 13471
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 13485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 516
telemt_me_reconnect_attempts_total 4108
telemt_me_reconnect_success_total 4091
telemt_me_reader_eof_total 5610
telemt_me_idle_close_by_peer_total 5609
telemt_me_route_drop_no_conn_total 43711
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 538
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 3
telemt_pool_force_close_total 147
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 5658
telemt_me_writer_restored_same_endpoint_total 4089
telemt_me_writer_removed_unexpected_minus_restored_total 1569
telemt_user_connections_total{user="hello"} 109583
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 8744225248 (8.14 GB)
telemt_user_octets_to_client{user="hello"} 38292210760 (35.66 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 41
```