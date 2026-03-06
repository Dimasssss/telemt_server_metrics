# Server Metrics 2026-03-06 18:50:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 2547.9 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64491
telemt_connections_bad_total 771
telemt_handshake_timeouts_total 1726
telemt_upstream_connect_attempt_total 3168
telemt_upstream_connect_success_total 3119
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 846
telemt_me_reconnect_success_total 839
telemt_me_reader_eof_total 1038
telemt_me_idle_close_by_peer_total 1038
telemt_me_route_drop_no_conn_total 20797
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 321
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_restored_same_endpoint_total 833
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 58927
telemt_user_connections_current{user="hello"} 1008
telemt_user_octets_from_client{user="hello"} 1337101992 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 20396306236 (19.00 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 2548.0 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24221
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 1245
telemt_upstream_connect_attempt_total 3653
telemt_upstream_connect_success_total 3652
telemt_upstream_connect_attempts_per_request{bucket="1"} 3652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2999
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 1204
telemt_me_reconnect_success_total 1202
telemt_me_reader_eof_total 1530
telemt_me_idle_close_by_peer_total 1530
telemt_me_route_drop_no_conn_total 8650
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 81
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 1
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 1530
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 22223
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 263526176 (251.32 MB)
telemt_user_octets_to_client{user="hello"} 5821202612 (5.42 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 2547.9 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45240
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 702
telemt_upstream_connect_attempt_total 2810
telemt_upstream_connect_success_total 2796
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 535
telemt_me_reconnect_success_total 536
telemt_me_reader_eof_total 659
telemt_me_idle_close_by_peer_total 659
telemt_me_route_drop_no_conn_total 14919
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 213
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_restored_same_endpoint_total 529
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 41924
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 1423632344 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 9598442140 (8.94 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 2548.4 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58786
telemt_connections_bad_total 25945
telemt_handshake_timeouts_total 1962
telemt_upstream_connect_attempt_total 2662
telemt_upstream_connect_success_total 2649
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 569
telemt_me_reconnect_success_total 565
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 658
telemt_me_route_drop_no_conn_total 9779
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 237
telemt_me_writer_removed_unexpected_total 658
telemt_me_writer_restored_same_endpoint_total 561
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 29771
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 209022716 (199.34 MB)
telemt_user_octets_to_client{user="hello"} 11907101804 (11.09 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 2546.8 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40415
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 3257
telemt_upstream_connect_success_total 3240
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 970
telemt_me_reconnect_success_total 966
telemt_me_reader_eof_total 1314
telemt_me_idle_close_by_peer_total 1314
telemt_me_route_drop_no_conn_total 13939
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 219
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 1317
telemt_me_writer_restored_same_endpoint_total 964
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 38109
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 786724120 (750.28 MB)
telemt_user_octets_to_client{user="hello"} 17664657224 (16.45 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 74
```