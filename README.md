# Server Metrics 2026-03-06 19:06:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 3475.3 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89882
telemt_connections_bad_total 1021
telemt_handshake_timeouts_total 2595
telemt_upstream_connect_attempt_total 4065
telemt_upstream_connect_success_total 4006
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 1082
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 1350
telemt_me_idle_close_by_peer_total 1350
telemt_me_route_drop_no_conn_total 34373
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 403
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 81
telemt_me_writer_removed_unexpected_total 1369
telemt_me_writer_restored_same_endpoint_total 1067
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 80683
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 1535688692 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 26782825376 (24.94 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 3475.0 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31995
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 1967
telemt_upstream_connect_attempt_total 5388
telemt_upstream_connect_success_total 5388
telemt_upstream_connect_attempts_per_request{bucket="1"} 5388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1798
telemt_me_reconnect_success_total 1794
telemt_me_reader_eof_total 2249
telemt_me_idle_close_by_peer_total 2249
telemt_me_route_drop_no_conn_total 11482
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 97
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 2249
telemt_me_writer_restored_same_endpoint_total 1792
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 29024
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 312945472 (298.45 MB)
telemt_user_octets_to_client{user="hello"} 8450565784 (7.87 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 3474.8 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58920
telemt_connections_bad_total 223
telemt_handshake_timeouts_total 764
telemt_upstream_connect_attempt_total 4118
telemt_upstream_connect_success_total 4102
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 825
telemt_me_reconnect_success_total 825
telemt_me_reader_eof_total 1084
telemt_me_idle_close_by_peer_total 1084
telemt_me_route_drop_no_conn_total 19143
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 296
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 1086
telemt_me_writer_restored_same_endpoint_total 818
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 54237
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 2221247380 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 12159996852 (11.32 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 3475.3 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76095
telemt_connections_bad_total 32420
telemt_handshake_timeouts_total 3008
telemt_upstream_connect_attempt_total 4821
telemt_upstream_connect_success_total 4805
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 1412
telemt_me_reconnect_success_total 1407
telemt_me_reader_eof_total 1820
telemt_me_idle_close_by_peer_total 1820
telemt_me_route_drop_no_conn_total 13236
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 22
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 298
telemt_me_writer_removed_unexpected_total 1820
telemt_me_writer_restored_same_endpoint_total 1403
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 39151
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 266324092 (253.99 MB)
telemt_user_octets_to_client{user="hello"} 14316170788 (13.33 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 3473.9 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53228
telemt_connections_bad_total 115
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 5544
telemt_upstream_connect_success_total 5526
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 5534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 1841
telemt_me_reconnect_success_total 1836
telemt_me_reader_eof_total 2588
telemt_me_idle_close_by_peer_total 2587
telemt_me_route_drop_no_conn_total 18563
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 294
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 2592
telemt_me_writer_restored_same_endpoint_total 1834
telemt_me_writer_removed_unexpected_minus_restored_total 758
telemt_user_connections_total{user="hello"} 50425
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 2633621684 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 21941948600 (20.44 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 69
```