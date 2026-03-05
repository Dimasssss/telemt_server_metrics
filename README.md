# Server Metrics 2026-03-05 23:51:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 5404.3 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43471
telemt_connections_bad_total 14114
telemt_handshake_timeouts_total 400
telemt_upstream_connect_attempt_total 3535
telemt_upstream_connect_success_total 3504
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3504
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 747
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 759
telemt_me_idle_close_by_peer_total 759
telemt_me_route_drop_no_conn_total 7310
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 73
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 759
telemt_me_writer_restored_same_endpoint_total 741
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 28159
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 435283728 (415.12 MB)
telemt_user_octets_to_client{user="hello"} 11585721156 (10.79 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 5399.7 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12821
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 214
telemt_upstream_connect_attempt_total 4225
telemt_upstream_connect_success_total 4223
telemt_upstream_connect_attempts_per_request{bucket="1"} 4223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 772
telemt_me_reconnect_success_total 773
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 778
telemt_me_route_drop_no_conn_total 4095
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 44
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_pool_force_close_total 9
telemt_me_writer_removed_unexpected_total 779
telemt_me_writer_restored_same_endpoint_total 769
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 12289
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 97607680 (93.09 MB)
telemt_user_octets_to_client{user="hello"} 2828113756 (2.63 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 5396.9 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21477
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 4846
telemt_upstream_connect_success_total 4799
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4799
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1275
telemt_me_reconnect_success_total 1272
telemt_me_reader_eof_total 1319
telemt_me_idle_close_by_peer_total 1319
telemt_me_route_drop_no_conn_total 6275
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 1320
telemt_me_writer_restored_same_endpoint_total 1267
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 20888
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 365781508 (348.84 MB)
telemt_user_octets_to_client{user="hello"} 6240333704 (5.81 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 5393.7 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17484
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 466
telemt_upstream_connect_attempt_total 2676
telemt_upstream_connect_success_total 2665
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2665
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 270
telemt_me_reconnect_success_total 267
telemt_me_reader_eof_total 272
telemt_me_idle_close_by_peer_total 272
telemt_me_route_drop_no_conn_total 7945
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_restored_same_endpoint_total 263
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 15935
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 171500280 (163.56 MB)
telemt_user_octets_to_client{user="hello"} 15149561176 (14.11 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 5392.5 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22805
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 3130
telemt_upstream_connect_success_total 3128
telemt_upstream_connect_attempts_per_request{bucket="1"} 3128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 491
telemt_me_reconnect_success_total 493
telemt_me_reader_eof_total 499
telemt_me_idle_close_by_peer_total 499
telemt_me_route_drop_no_conn_total 8749
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_removed_unexpected_total 499
telemt_me_writer_restored_same_endpoint_total 488
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 22341
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 10935124404 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 16241919912 (15.13 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 26
```