# Server Metrics 2026-03-06 19:11:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 3785.4 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96398
telemt_connections_bad_total 1176
telemt_handshake_timeouts_total 2899
telemt_upstream_connect_attempt_total 4284
telemt_upstream_connect_success_total 4220
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 1107
telemt_me_reconnect_success_total 1097
telemt_me_reader_eof_total 1377
telemt_me_idle_close_by_peer_total 1377
telemt_me_route_drop_no_conn_total 36973
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 418
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 127
telemt_me_writer_removed_unexpected_total 1396
telemt_me_writer_restored_same_endpoint_total 1091
telemt_me_writer_removed_unexpected_minus_restored_total 305
telemt_user_connections_total{user="hello"} 86575
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 1588620452 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 28842683560 (26.86 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 3785.2 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34102
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 2183
telemt_upstream_connect_attempt_total 6198
telemt_upstream_connect_success_total 6197
telemt_upstream_connect_attempts_per_request{bucket="1"} 6197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 2108
telemt_me_reconnect_success_total 2105
telemt_me_reader_eof_total 2681
telemt_me_idle_close_by_peer_total 2681
telemt_me_route_drop_no_conn_total 12331
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 97
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 2681
telemt_me_writer_restored_same_endpoint_total 2103
telemt_me_writer_removed_unexpected_minus_restored_total 578
telemt_user_connections_total{user="hello"} 30859
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 354597712 (338.17 MB)
telemt_user_octets_to_client{user="hello"} 8796907332 (8.19 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 3785.1 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63114
telemt_connections_bad_total 224
telemt_handshake_timeouts_total 803
telemt_upstream_connect_attempt_total 4530
telemt_upstream_connect_success_total 4513
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 878
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 1142
telemt_me_idle_close_by_peer_total 1142
telemt_me_route_drop_no_conn_total 20671
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 311
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 3
telemt_pool_force_close_total 62
telemt_pool_stale_pick_total 9
telemt_me_writer_removed_unexpected_total 1144
telemt_me_writer_restored_same_endpoint_total 870
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 58254
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 2517654288 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 13241955252 (12.33 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 3785.6 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81771
telemt_connections_bad_total 34574
telemt_handshake_timeouts_total 3363
telemt_upstream_connect_attempt_total 5461
telemt_upstream_connect_success_total 5443
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 1639
telemt_me_reconnect_success_total 1633
telemt_me_reader_eof_total 2159
telemt_me_idle_close_by_peer_total 2159
telemt_me_route_drop_no_conn_total 14218
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 31
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 2
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 308
telemt_me_writer_removed_unexpected_total 2159
telemt_me_writer_restored_same_endpoint_total 1629
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 42234
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 280286040 (267.30 MB)
telemt_user_octets_to_client{user="hello"} 15031409996 (14.00 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 3784.2 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57665
telemt_connections_bad_total 435
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 6152
telemt_upstream_connect_success_total 6134
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 6142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 2066
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 2950
telemt_me_idle_close_by_peer_total 2949
telemt_me_route_drop_no_conn_total 20127
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 322
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 1
telemt_pool_force_close_total 2
telemt_pool_stale_pick_total 8
telemt_me_writer_removed_unexpected_total 2954
telemt_me_writer_restored_same_endpoint_total 2059
telemt_me_writer_removed_unexpected_minus_restored_total 895
telemt_user_connections_total{user="hello"} 54247
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 3454713684 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 22699115936 (21.14 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 66
```