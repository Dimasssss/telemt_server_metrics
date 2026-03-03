# Server Metrics 2026-03-03 23:14:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 7449.3 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60827
telemt_connections_bad_total 643
telemt_handshake_timeouts_total 198
telemt_upstream_connect_attempt_total 4105
telemt_upstream_connect_success_total 4080
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4080
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1743
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 470
telemt_me_reconnect_success_total 481
telemt_me_reader_eof_total 467
telemt_me_idle_close_by_peer_total 467
telemt_me_route_drop_no_conn_total 23731
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 110
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 467
telemt_me_writer_restored_same_endpoint_total 461
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 58746
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 522117388 (497.93 MB)
telemt_user_octets_to_client{user="hello"} 19123110968 (17.81 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 7445.8 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28325
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 5632
telemt_upstream_connect_attempt_total 9677
telemt_upstream_connect_success_total 9500
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 9500
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 4030
telemt_me_reconnect_success_total 4041
telemt_me_reader_eof_total 4099
telemt_me_idle_close_by_peer_total 4098
telemt_me_route_drop_no_conn_total 10762
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 70
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 4099
telemt_me_writer_restored_same_endpoint_total 4021
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 22320
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 140370348 (133.87 MB)
telemt_user_octets_to_client{user="hello"} 10082186328 (9.39 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 7444.7 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68137
telemt_connections_bad_total 20117
telemt_handshake_timeouts_total 1745
telemt_upstream_connect_attempt_total 8284
telemt_upstream_connect_success_total 8236
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 8236
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 2787
telemt_me_reconnect_success_total 2795
telemt_me_reader_eof_total 2901
telemt_me_idle_close_by_peer_total 2900
telemt_me_route_drop_no_conn_total 14662
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 135
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 2902
telemt_me_writer_restored_same_endpoint_total 2774
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 45136
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 305042796 (290.91 MB)
telemt_user_octets_to_client{user="hello"} 13115937276 (12.22 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 7443.6 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30205
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 477
telemt_upstream_connect_attempt_total 4048
telemt_upstream_connect_success_total 4025
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 4025
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 345
telemt_me_reconnect_success_total 360
telemt_me_reader_eof_total 343
telemt_me_idle_close_by_peer_total 343
telemt_me_route_drop_no_conn_total 11608
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 343
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 29254
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 222355616 (212.05 MB)
telemt_user_octets_to_client{user="hello"} 9296854784 (8.66 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 7442.3 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68491
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 25868
telemt_upstream_connect_attempt_total 4853
telemt_upstream_connect_success_total 4795
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4795
telemt_upstream_connect_attempts_per_request{bucket="2"} 27
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 1061
telemt_me_reconnect_success_total 1076
telemt_me_reader_eof_total 1095
telemt_me_idle_close_by_peer_total 1095
telemt_me_route_drop_no_conn_total 31009
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 34
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 1097
telemt_me_writer_restored_same_endpoint_total 1052
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 41396
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 207609424 (197.99 MB)
telemt_user_octets_to_client{user="hello"} 10450327140 (9.73 GB)
telemt_user_unique_ips_current{user="hello"} 22
```