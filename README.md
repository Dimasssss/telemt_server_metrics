# Server Metrics 2026-03-05 23:15:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 3254.7 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29808
telemt_connections_bad_total 10783
telemt_handshake_timeouts_total 235
telemt_upstream_connect_attempt_total 1830
telemt_upstream_connect_success_total 1805
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1805
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 291
telemt_me_reconnect_success_total 291
telemt_me_reader_eof_total 294
telemt_me_idle_close_by_peer_total 294
telemt_me_route_drop_no_conn_total 4773
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 64
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 294
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 18222
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 376145964 (358.72 MB)
telemt_user_octets_to_client{user="hello"} 7362229920 (6.86 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 3250.3 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8281
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 161
telemt_upstream_connect_attempt_total 1681
telemt_upstream_connect_success_total 1679
telemt_upstream_connect_attempts_per_request{bucket="1"} 1679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 86
telemt_me_reconnect_success_total 88
telemt_me_reader_eof_total 85
telemt_me_idle_close_by_peer_total 85
telemt_me_route_drop_no_conn_total 2779
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 29
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_pool_force_close_total 8
telemt_me_writer_removed_unexpected_total 86
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 7853
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 74073680 (70.64 MB)
telemt_user_octets_to_client{user="hello"} 1148664484 (1.07 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 3247.6 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13239
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 1982
telemt_upstream_connect_success_total 1951
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1951
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 332
telemt_me_reconnect_success_total 333
telemt_me_reader_eof_total 344
telemt_me_idle_close_by_peer_total 344
telemt_me_route_drop_no_conn_total 4075
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 344
telemt_me_writer_restored_same_endpoint_total 328
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 13084
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 302085744 (288.09 MB)
telemt_user_octets_to_client{user="hello"} 4225481540 (3.94 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 3244.3 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11635
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 272
telemt_upstream_connect_attempt_total 1770
telemt_upstream_connect_success_total 1761
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1761
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 707
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 248
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 246
telemt_me_idle_close_by_peer_total 246
telemt_me_route_drop_no_conn_total 5612
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 47
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 246
telemt_me_writer_restored_same_endpoint_total 241
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 10625
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 152370468 (145.31 MB)
telemt_user_octets_to_client{user="hello"} 12629983672 (11.76 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 3243.3 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13515
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 1949
telemt_upstream_connect_success_total 1948
telemt_upstream_connect_attempts_per_request{bucket="1"} 1948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 290
telemt_me_reconnect_success_total 291
telemt_me_reader_eof_total 295
telemt_me_idle_close_by_peer_total 295
telemt_me_route_drop_no_conn_total 6411
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_restored_same_endpoint_total 288
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 13236
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 7264860920 (6.77 GB)
telemt_user_octets_to_client{user="hello"} 13782139496 (12.84 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 31
```