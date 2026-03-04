# Server Metrics 2026-03-04 01:48:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 16662.5 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108844
telemt_connections_bad_total 1367
telemt_handshake_timeouts_total 769
telemt_upstream_connect_attempt_total 13966
telemt_upstream_connect_success_total 13904
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 13904
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 3748
telemt_me_reconnect_success_total 3746
telemt_me_reader_eof_total 3829
telemt_me_idle_close_by_peer_total 3829
telemt_me_route_drop_no_conn_total 39935
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 155
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 3829
telemt_me_writer_restored_same_endpoint_total 3726
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 104212
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 813296124 (775.62 MB)
telemt_user_octets_to_client{user="hello"} 32013582168 (29.81 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 16659.3 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51170
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 12811
telemt_upstream_connect_attempt_total 36283
telemt_upstream_connect_success_total 35868
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 35862
telemt_upstream_connect_attempts_per_request{bucket="2"} 197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 709
telemt_me_reconnect_attempts_total 21390
telemt_me_reconnect_success_total 21375
telemt_me_reader_eof_total 21943
telemt_me_idle_close_by_peer_total 21942
telemt_me_route_drop_no_conn_total 17512
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 22004
telemt_me_writer_restored_same_endpoint_total 21355
telemt_me_writer_removed_unexpected_minus_restored_total 649
telemt_user_connections_total{user="hello"} 37604
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 289310488 (275.91 MB)
telemt_user_octets_to_client{user="hello"} 22235583488 (20.71 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 16657.9 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119368
telemt_connections_bad_total 41962
telemt_handshake_timeouts_total 2029
telemt_upstream_connect_attempt_total 18665
telemt_upstream_connect_success_total 18552
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 18552
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 6284
telemt_me_reconnect_success_total 6275
telemt_me_reader_eof_total 6537
telemt_me_idle_close_by_peer_total 6535
telemt_me_route_drop_no_conn_total 22463
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 252
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 6538
telemt_me_writer_restored_same_endpoint_total 6254
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 73120
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 444136764 (423.56 MB)
telemt_user_octets_to_client{user="hello"} 18343572784 (17.08 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 16657.0 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53762
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 539
telemt_upstream_connect_attempt_total 10497
telemt_upstream_connect_success_total 10448
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 10448
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1467
telemt_me_reconnect_success_total 1475
telemt_me_reader_eof_total 1480
telemt_me_idle_close_by_peer_total 1480
telemt_me_route_drop_no_conn_total 18656
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 5
telemt_pool_force_close_total 119
telemt_me_writer_removed_unexpected_total 1480
telemt_me_writer_restored_same_endpoint_total 1455
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 52103
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 434638776 (414.50 MB)
telemt_user_octets_to_client{user="hello"} 17038503932 (15.87 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 16655.4 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129848
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 57235
telemt_upstream_connect_attempt_total 25123
telemt_upstream_connect_success_total 24964
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 24964
telemt_upstream_connect_attempts_per_request{bucket="2"} 76
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 339
telemt_me_reconnect_attempts_total 13239
telemt_me_reconnect_success_total 13239
telemt_me_reader_eof_total 14093
telemt_me_idle_close_by_peer_total 14092
telemt_me_route_drop_no_conn_total 38935
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 98
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1250
telemt_me_writer_removed_unexpected_total 14098
telemt_me_writer_restored_same_endpoint_total 13215
telemt_me_writer_removed_unexpected_minus_restored_total 883
telemt_user_connections_total{user="hello"} 70139
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 330938608 (315.61 MB)
telemt_user_octets_to_client{user="hello"} 16194182748 (15.08 GB)
telemt_user_unique_ips_current{user="hello"} 15
```