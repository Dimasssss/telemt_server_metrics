# Server Metrics 2026-03-06 18:35:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 1625.5 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43122
telemt_connections_bad_total 564
telemt_handshake_timeouts_total 966
telemt_upstream_connect_attempt_total 1165
telemt_upstream_connect_success_total 1122
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 1139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 131
telemt_me_reconnect_success_total 125
telemt_me_reader_eof_total 135
telemt_me_idle_close_by_peer_total 135
telemt_me_route_drop_no_conn_total 13868
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 235
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_me_writer_removed_unexpected_total 154
telemt_me_writer_restored_same_endpoint_total 119
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 39173
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 1150115788 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 14880435404 (13.86 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 1625.3 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15218
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 271
telemt_upstream_connect_attempt_total 2444
telemt_upstream_connect_success_total 2443
telemt_upstream_connect_attempts_per_request{bucket="1"} 2443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2026
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 779
telemt_me_reconnect_success_total 778
telemt_me_reader_eof_total 988
telemt_me_idle_close_by_peer_total 988
telemt_me_route_drop_no_conn_total 5907
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 63
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 988
telemt_me_writer_restored_same_endpoint_total 776
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 14441
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 178010000 (169.76 MB)
telemt_user_octets_to_client{user="hello"} 3601554964 (3.35 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 1625.3 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29361
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 516
telemt_upstream_connect_attempt_total 1309
telemt_upstream_connect_success_total 1298
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 102
telemt_me_reconnect_success_total 105
telemt_me_reader_eof_total 116
telemt_me_idle_close_by_peer_total 116
telemt_me_route_drop_no_conn_total 8584
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 135
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 118
telemt_me_writer_restored_same_endpoint_total 98
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 27569
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 653665028 (623.38 MB)
telemt_user_octets_to_client{user="hello"} 5378533976 (5.01 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 1625.8 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36137
telemt_connections_bad_total 14694
telemt_handshake_timeouts_total 965
telemt_upstream_connect_attempt_total 1141
telemt_upstream_connect_success_total 1129
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 58
telemt_me_reconnect_success_total 54
telemt_me_reader_eof_total 59
telemt_me_idle_close_by_peer_total 59
telemt_me_route_drop_no_conn_total 6063
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 5
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 132
telemt_me_writer_removed_unexpected_total 59
telemt_me_writer_restored_same_endpoint_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 19665
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 105619648 (100.73 MB)
telemt_user_octets_to_client{user="hello"} 7487433876 (6.97 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 1624.4 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28152
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 198
telemt_upstream_connect_attempt_total 1228
telemt_upstream_connect_success_total 1212
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 208
telemt_me_reconnect_success_total 206
telemt_me_reader_eof_total 262
telemt_me_idle_close_by_peer_total 262
telemt_me_route_drop_no_conn_total 8318
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 116
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_writer_removed_unexpected_total 263
telemt_me_writer_restored_same_endpoint_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 26397
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 691227608 (659.21 MB)
telemt_user_octets_to_client{user="hello"} 11258632300 (10.49 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 76
```