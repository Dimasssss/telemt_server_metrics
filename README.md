# Server Metrics 2026-03-06 18:45:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 2240.8 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57206
telemt_connections_bad_total 701
telemt_handshake_timeouts_total 1457
telemt_upstream_connect_attempt_total 2412
telemt_upstream_connect_success_total 2364
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 540
telemt_me_reconnect_success_total 533
telemt_me_reader_eof_total 641
telemt_me_idle_close_by_peer_total 641
telemt_me_route_drop_no_conn_total 18276
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 286
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 212
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_restored_same_endpoint_total 527
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 52325
telemt_user_connections_current{user="hello"} 1092
telemt_user_octets_from_client{user="hello"} 1259891548 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 18614072052 (17.34 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 2240.5 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21696
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1001
telemt_upstream_connect_attempt_total 3332
telemt_upstream_connect_success_total 3332
telemt_upstream_connect_attempts_per_request{bucket="1"} 3332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2683
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1087
telemt_me_reconnect_success_total 1086
telemt_me_reader_eof_total 1398
telemt_me_idle_close_by_peer_total 1398
telemt_me_route_drop_no_conn_total 8012
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 74
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_swap_total 1
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 1398
telemt_me_writer_restored_same_endpoint_total 1084
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 20045
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 242975760 (231.72 MB)
telemt_user_octets_to_client{user="hello"} 4751823248 (4.43 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 2240.5 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39617
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 682
telemt_upstream_connect_attempt_total 2145
telemt_upstream_connect_success_total 2132
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 294
telemt_me_reconnect_success_total 297
telemt_me_reader_eof_total 342
telemt_me_idle_close_by_peer_total 342
telemt_me_route_drop_no_conn_total 11850
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 192
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 344
telemt_me_writer_restored_same_endpoint_total 290
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 37174
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 1189035612 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 7865225120 (7.33 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 2241.0 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53175
telemt_connections_bad_total 23797
telemt_handshake_timeouts_total 1627
telemt_upstream_connect_attempt_total 2039
telemt_upstream_connect_success_total 2026
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 315
telemt_me_reconnect_success_total 311
telemt_me_reader_eof_total 345
telemt_me_idle_close_by_peer_total 345
telemt_me_route_drop_no_conn_total 8655
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 210
telemt_me_writer_removed_unexpected_total 345
telemt_me_writer_restored_same_endpoint_total 307
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 26762
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 185168780 (176.59 MB)
telemt_user_octets_to_client{user="hello"} 9443792940 (8.80 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 2239.5 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36669
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 225
telemt_upstream_connect_attempt_total 2520
telemt_upstream_connect_success_total 2503
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 684
telemt_me_reconnect_success_total 680
telemt_me_reader_eof_total 914
telemt_me_idle_close_by_peer_total 914
telemt_me_route_drop_no_conn_total 12323
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 180
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 917
telemt_me_writer_restored_same_endpoint_total 678
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 34625
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 743808780 (709.35 MB)
telemt_user_octets_to_client{user="hello"} 15841302324 (14.75 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 80
```