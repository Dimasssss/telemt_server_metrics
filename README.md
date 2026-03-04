# Server Metrics 2026-03-04 03:40:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 23418.0 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150707
telemt_connections_bad_total 1538
telemt_handshake_timeouts_total 2474
telemt_upstream_connect_attempt_total 17913
telemt_upstream_connect_success_total 17838
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 17838
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 191
telemt_me_reconnect_attempts_total 4277
telemt_me_reconnect_success_total 4264
telemt_me_reader_eof_total 4365
telemt_me_idle_close_by_peer_total 4365
telemt_me_route_drop_no_conn_total 51769
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 333
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 212
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 4
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 4365
telemt_me_writer_restored_same_endpoint_total 4244
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 143308
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 1359373880 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 44409124952 (41.36 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 23414.6 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71294
telemt_connections_bad_total 289
telemt_handshake_timeouts_total 18700
telemt_upstream_connect_attempt_total 59987
telemt_upstream_connect_success_total 59397
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 59391
telemt_upstream_connect_attempts_per_request{bucket="2"} 285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 935
telemt_me_reconnect_attempts_total 38040
telemt_me_reconnect_success_total 38016
telemt_me_reader_eof_total 38987
telemt_me_idle_close_by_peer_total 38986
telemt_me_route_drop_no_conn_total 22848
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_me_writer_removed_unexpected_total 39048
telemt_me_writer_restored_same_endpoint_total 37996
telemt_me_writer_removed_unexpected_minus_restored_total 1052
telemt_user_connections_total{user="hello"} 51428
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 425669848 (405.95 MB)
telemt_user_octets_to_client{user="hello"} 25825456180 (24.05 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 23413.4 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163366
telemt_connections_bad_total 59636
telemt_handshake_timeouts_total 3642
telemt_upstream_connect_attempt_total 32426
telemt_upstream_connect_success_total 32215
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 32215
telemt_upstream_connect_attempts_per_request{bucket="2"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 431
telemt_me_reconnect_attempts_total 13602
telemt_me_reconnect_success_total 13570
telemt_me_reader_eof_total 14293
telemt_me_idle_close_by_peer_total 14290
telemt_me_route_drop_no_conn_total 31709
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 296
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 14298
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_removed_unexpected_minus_restored_total 749
telemt_user_connections_total{user="hello"} 96553
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 601074964 (573.23 MB)
telemt_user_octets_to_client{user="hello"} 25572300904 (23.82 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 23412.3 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78655
telemt_connections_bad_total 1904
telemt_handshake_timeouts_total 726
telemt_upstream_connect_attempt_total 15070
telemt_upstream_connect_success_total 14997
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 14997
telemt_upstream_connect_attempts_per_request{bucket="2"} 36
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 2079
telemt_me_reconnect_success_total 2082
telemt_me_reader_eof_total 2093
telemt_me_idle_close_by_peer_total 2093
telemt_me_route_drop_no_conn_total 26054
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 2093
telemt_me_writer_restored_same_endpoint_total 2061
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 72740
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 651180644 (621.01 MB)
telemt_user_octets_to_client{user="hello"} 25239483712 (23.51 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 23411.3 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178708
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 82093
telemt_upstream_connect_attempt_total 36295
telemt_upstream_connect_success_total 36072
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 36072
telemt_upstream_connect_attempts_per_request{bucket="2"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 505
telemt_me_reconnect_attempts_total 18443
telemt_me_reconnect_success_total 18436
telemt_me_reader_eof_total 19521
telemt_me_idle_close_by_peer_total 19520
telemt_me_route_drop_no_conn_total 46290
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 124
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_pool_stale_pick_total 2735
telemt_me_writer_removed_unexpected_total 19531
telemt_me_writer_restored_same_endpoint_total 18412
telemt_me_writer_removed_unexpected_minus_restored_total 1119
telemt_user_connections_total{user="hello"} 93124
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 551219500 (525.68 MB)
telemt_user_octets_to_client{user="hello"} 21462775972 (19.99 GB)
telemt_user_unique_ips_current{user="hello"} 25
```