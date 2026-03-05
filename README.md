# Server Metrics 2026-03-05 23:05:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 2640.4 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26243
telemt_connections_bad_total 10577
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 1234
telemt_upstream_connect_success_total 1214
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1214
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 125
telemt_me_reconnect_success_total 126
telemt_me_reader_eof_total 123
telemt_me_idle_close_by_peer_total 123
telemt_me_route_drop_no_conn_total 3919
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 58
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 123
telemt_me_writer_restored_same_endpoint_total 122
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 15023
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 343786816 (327.86 MB)
telemt_user_octets_to_client{user="hello"} 6078964676 (5.66 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 2635.9 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7029
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 140
telemt_upstream_connect_attempt_total 1125
telemt_upstream_connect_success_total 1123
telemt_upstream_connect_attempts_per_request{bucket="1"} 1123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 2326
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 22
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 1
telemt_pool_force_close_total 8
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 6651
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 69656008 (66.43 MB)
telemt_user_octets_to_client{user="hello"} 990260376 (944.39 MB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 2633.4 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10932
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 1302
telemt_upstream_connect_success_total 1272
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1272
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 157
telemt_me_reconnect_success_total 158
telemt_me_reader_eof_total 158
telemt_me_idle_close_by_peer_total 158
telemt_me_route_drop_no_conn_total 3098
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 158
telemt_me_writer_restored_same_endpoint_total 153
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 10816
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 286965644 (273.67 MB)
telemt_user_octets_to_client{user="hello"} 3888112496 (3.62 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 2630.1 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9758
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 223
telemt_upstream_connect_attempt_total 1455
telemt_upstream_connect_success_total 1448
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1448
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 567
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 208
telemt_me_reconnect_success_total 206
telemt_me_reader_eof_total 207
telemt_me_idle_close_by_peer_total 207
telemt_me_route_drop_no_conn_total 4322
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 207
telemt_me_writer_restored_same_endpoint_total 202
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 8981
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 121694028 (116.06 MB)
telemt_user_octets_to_client{user="hello"} 10514734020 (9.79 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 2628.9 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11436
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 1367
telemt_upstream_connect_success_total 1365
telemt_upstream_connect_attempts_per_request{bucket="1"} 1365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 431
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 123
telemt_me_reconnect_success_total 124
telemt_me_reader_eof_total 124
telemt_me_idle_close_by_peer_total 124
telemt_me_route_drop_no_conn_total 5536
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 124
telemt_me_writer_restored_same_endpoint_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 11196
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 2925830872 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 13490327052 (12.56 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```