# Server Metrics 2026-03-06 18:55:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 2855.6 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72044
telemt_connections_bad_total 839
telemt_handshake_timeouts_total 2007
telemt_upstream_connect_attempt_total 3809
telemt_upstream_connect_success_total 3752
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 1063
telemt_me_reconnect_success_total 1055
telemt_me_reader_eof_total 1331
telemt_me_idle_close_by_peer_total 1331
telemt_me_route_drop_no_conn_total 23109
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 343
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 248
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 1
telemt_pool_force_close_total 1
telemt_pool_stale_pick_total 6
telemt_me_writer_removed_unexpected_total 1350
telemt_me_writer_restored_same_endpoint_total 1049
telemt_me_writer_removed_unexpected_minus_restored_total 301
telemt_user_connections_total{user="hello"} 64969
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 1438570492 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 21995768392 (20.49 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 2855.3 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26891
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 1509
telemt_upstream_connect_attempt_total 4093
telemt_upstream_connect_success_total 4092
telemt_upstream_connect_attempts_per_request{bucket="1"} 4092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3383
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1354
telemt_me_reconnect_success_total 1352
telemt_me_reader_eof_total 1701
telemt_me_idle_close_by_peer_total 1701
telemt_me_route_drop_no_conn_total 9471
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 1
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 1701
telemt_me_writer_restored_same_endpoint_total 1350
telemt_me_writer_removed_unexpected_minus_restored_total 351
telemt_user_connections_total{user="hello"} 24519
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 279864288 (266.90 MB)
telemt_user_octets_to_client{user="hello"} 7338308412 (6.83 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 2855.3 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49721
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 727
telemt_upstream_connect_attempt_total 3577
telemt_upstream_connect_success_total 3562
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 810
telemt_me_reconnect_success_total 812
telemt_me_reader_eof_total 1066
telemt_me_idle_close_by_peer_total 1066
telemt_me_route_drop_no_conn_total 16345
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 245
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 2
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 1068
telemt_me_writer_restored_same_endpoint_total 805
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 45567
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 1710379840 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 10566088460 (9.84 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 2855.6 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64922
telemt_connections_bad_total 28085
telemt_handshake_timeouts_total 2367
telemt_upstream_connect_attempt_total 3354
telemt_upstream_connect_success_total 3338
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 833
telemt_me_reconnect_success_total 828
telemt_me_reader_eof_total 1015
telemt_me_idle_close_by_peer_total 1015
telemt_me_route_drop_no_conn_total 10928
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 7
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 264
telemt_me_writer_removed_unexpected_total 1015
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 33195
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 223739860 (213.37 MB)
telemt_user_octets_to_client{user="hello"} 12800870412 (11.92 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 2854.5 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44444
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 254
telemt_upstream_connect_attempt_total 3995
telemt_upstream_connect_success_total 3977
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1218
telemt_me_reconnect_success_total 1214
telemt_me_reader_eof_total 1667
telemt_me_idle_close_by_peer_total 1667
telemt_me_route_drop_no_conn_total 15452
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 247
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 188
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 1671
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_removed_unexpected_minus_restored_total 459
telemt_user_connections_total{user="hello"} 41981
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 907369120 (865.33 MB)
telemt_user_octets_to_client{user="hello"} 19155199632 (17.84 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 81
```