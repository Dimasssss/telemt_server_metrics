# Server Metrics 2026-03-07 07:56:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.7

telemt_uptime_seconds 2927.4 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54734
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 380
telemt_upstream_connect_attempt_total 1094
telemt_upstream_connect_success_total 1094
telemt_upstream_connect_attempts_per_request{bucket="1"} 1094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 28
telemt_me_reconnect_success_total 27
telemt_me_reader_eof_total 32
telemt_me_idle_close_by_peer_total 32
telemt_me_route_drop_no_conn_total 19088
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 314
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 105
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_restored_same_endpoint_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 52246
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 864372048 (824.33 MB)
telemt_user_octets_to_client{user="hello"} 20759538036 (19.33 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server2

```
telemt 3.3.7

telemt_uptime_seconds 2927.3 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20650
telemt_connections_bad_total 1062
telemt_handshake_timeouts_total 1162
telemt_upstream_connect_attempt_total 1320
telemt_upstream_connect_success_total 1314
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 686
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 66
telemt_me_reconnect_success_total 63
telemt_me_reader_eof_total 62
telemt_me_idle_close_by_peer_total 62
telemt_me_route_drop_no_conn_total 7509
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 27
telemt_desync_total 54
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_me_writer_removed_unexpected_total 62
telemt_me_writer_restored_same_endpoint_total 62
telemt_user_connections_total{user="hello"} 17696
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 229165068 (218.55 MB)
telemt_user_octets_to_client{user="hello"} 6122915468 (5.70 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.7

telemt_uptime_seconds 2927.2 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40129
telemt_connections_bad_total 2171
telemt_handshake_timeouts_total 1540
telemt_upstream_connect_attempt_total 1722
telemt_upstream_connect_success_total 1714
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 131
telemt_me_reconnect_success_total 130
telemt_me_reader_eof_total 133
telemt_me_idle_close_by_peer_total 133
telemt_me_route_drop_no_conn_total 12942
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 165
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_me_writer_removed_unexpected_total 133
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 35735
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 2880740488 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 16690314852 (15.54 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.7

telemt_uptime_seconds 2927.7 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26075
telemt_connections_bad_total 2816
telemt_handshake_timeouts_total 499
telemt_upstream_connect_attempt_total 1783
telemt_upstream_connect_success_total 1778
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 619
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 147
telemt_me_reconnect_success_total 147
telemt_me_reader_eof_total 151
telemt_me_idle_close_by_peer_total 151
telemt_me_route_drop_no_conn_total 10638
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 96
telemt_me_adaptive_floor_global_cap_effective 96
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 24
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 151
telemt_me_writer_restored_same_endpoint_total 146
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 21631
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 219815280 (209.63 MB)
telemt_user_octets_to_client{user="hello"} 6536753716 (6.09 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.7

telemt_uptime_seconds 2927.4 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34938
telemt_connections_bad_total 177
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 1337
telemt_upstream_connect_success_total 1308
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 78
telemt_me_reconnect_success_total 81
telemt_me_reader_eof_total 76
telemt_me_idle_close_by_peer_total 76
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 12769
telemt_me_endpoint_quarantine_total 1
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_global_cap_raw 192
telemt_me_adaptive_floor_global_cap_effective 192
telemt_me_adaptive_floor_target_writers_total 25
telemt_desync_total 100
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_me_writer_removed_unexpected_total 77
telemt_me_writer_restored_same_endpoint_total 76
telemt_me_writer_restored_fallback_total 1
telemt_user_connections_total{user="hello"} 30631
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 489686972 (467.00 MB)
telemt_user_octets_to_client{user="hello"} 10227485544 (9.53 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 78
```