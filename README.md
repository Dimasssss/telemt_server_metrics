# Server Metrics 2026-03-06 18:40:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 1933.1 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49560
telemt_connections_bad_total 632
telemt_handshake_timeouts_total 1204
telemt_upstream_connect_attempt_total 1736
telemt_upstream_connect_success_total 1691
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 1708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 286
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 334
telemt_me_route_drop_no_conn_total 15756
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 246
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_me_writer_removed_unexpected_total 353
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 45164
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 1211501564 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 16909957232 (15.75 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 1932.7 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18510
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 632
telemt_upstream_connect_attempt_total 3200
telemt_upstream_connect_success_total 3200
telemt_upstream_connect_attempts_per_request{bucket="1"} 3200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2575
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 1074
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 1385
telemt_me_idle_close_by_peer_total 1385
telemt_me_route_drop_no_conn_total 6860
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 66
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1385
telemt_me_writer_restored_same_endpoint_total 1071
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 17245
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 209685848 (199.97 MB)
telemt_user_octets_to_client{user="hello"} 4155356496 (3.87 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 1932.9 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34409
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 591
telemt_upstream_connect_attempt_total 1621
telemt_upstream_connect_success_total 1608
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 139
telemt_me_reconnect_success_total 142
telemt_me_reader_eof_total 162
telemt_me_idle_close_by_peer_total 162
telemt_me_route_drop_no_conn_total 10289
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 171
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 164
telemt_me_writer_restored_same_endpoint_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 32330
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 972300664 (927.26 MB)
telemt_user_octets_to_client{user="hello"} 6891799708 (6.42 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 1933.2 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44400
telemt_connections_bad_total 19154
telemt_handshake_timeouts_total 1271
telemt_upstream_connect_attempt_total 1546
telemt_upstream_connect_success_total 1533
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 155
telemt_me_reconnect_success_total 151
telemt_me_reader_eof_total 171
telemt_me_idle_close_by_peer_total 171
telemt_me_route_drop_no_conn_total 7173
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 5
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 171
telemt_me_writer_restored_same_endpoint_total 147
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 23078
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 166941628 (159.21 MB)
telemt_user_octets_to_client{user="hello"} 8419213932 (7.84 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 1931.7 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32636
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 209
telemt_upstream_connect_attempt_total 1829
telemt_upstream_connect_success_total 1812
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 407
telemt_me_reconnect_success_total 404
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 9741
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 160
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_me_writer_removed_unexpected_total 532
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 30709
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 715574324 (682.42 MB)
telemt_user_octets_to_client{user="hello"} 12904267440 (12.02 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 79
```