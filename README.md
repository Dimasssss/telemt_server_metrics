# Server Metrics 2026-03-04 02:03:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 17583.3 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114749
telemt_connections_bad_total 1374
telemt_handshake_timeouts_total 994
telemt_upstream_connect_attempt_total 14827
telemt_upstream_connect_success_total 14766
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 14766
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 4038
telemt_me_reconnect_success_total 4033
telemt_me_reader_eof_total 4125
telemt_me_idle_close_by_peer_total 4125
telemt_me_route_drop_no_conn_total 41486
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 169
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4125
telemt_me_writer_restored_same_endpoint_total 4013
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 109771
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 888655228 (847.49 MB)
telemt_user_octets_to_client{user="hello"} 33217027056 (30.94 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 17580.1 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53278
telemt_connections_bad_total 166
telemt_handshake_timeouts_total 13404
telemt_upstream_connect_attempt_total 39373
telemt_upstream_connect_success_total 38939
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 38933
telemt_upstream_connect_attempts_per_request{bucket="2"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 23515
telemt_me_reconnect_success_total 23500
telemt_me_reader_eof_total 24097
telemt_me_idle_close_by_peer_total 24096
telemt_me_route_drop_no_conn_total 18184
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 24158
telemt_me_writer_restored_same_endpoint_total 23480
telemt_me_writer_removed_unexpected_minus_restored_total 678
telemt_user_connections_total{user="hello"} 39097
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 299475544 (285.60 MB)
telemt_user_octets_to_client{user="hello"} 22730544048 (21.17 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 17578.8 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125912
telemt_connections_bad_total 44393
telemt_handshake_timeouts_total 3142
telemt_upstream_connect_attempt_total 19888
telemt_upstream_connect_success_total 19770
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 19770
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 245
telemt_me_reconnect_attempts_total 6657
telemt_me_reconnect_success_total 6647
telemt_me_reader_eof_total 6929
telemt_me_idle_close_by_peer_total 6927
telemt_me_route_drop_no_conn_total 23968
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 259
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 6930
telemt_me_writer_restored_same_endpoint_total 6626
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 75687
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 457373160 (436.19 MB)
telemt_user_octets_to_client{user="hello"} 19040801604 (17.73 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 17577.8 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56269
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 543
telemt_upstream_connect_attempt_total 10988
telemt_upstream_connect_success_total 10939
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 10939
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 1537
telemt_me_reconnect_success_total 1544
telemt_me_reader_eof_total 1549
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 19315
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 17
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1549
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 54547
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 445174156 (424.55 MB)
telemt_user_octets_to_client{user="hello"} 18137353096 (16.89 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 17576.3 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135614
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 60220
telemt_upstream_connect_attempt_total 25959
telemt_upstream_connect_success_total 25795
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 25795
telemt_upstream_connect_attempts_per_request{bucket="2"} 78
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 347
telemt_me_reconnect_attempts_total 13464
telemt_me_reconnect_success_total 13464
telemt_me_reader_eof_total 14323
telemt_me_idle_close_by_peer_total 14322
telemt_me_route_drop_no_conn_total 39735
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 103
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1606
telemt_me_writer_removed_unexpected_total 14328
telemt_me_writer_restored_same_endpoint_total 13440
telemt_me_writer_removed_unexpected_minus_restored_total 888
telemt_user_connections_total{user="hello"} 72793
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 368488048 (351.42 MB)
telemt_user_octets_to_client{user="hello"} 16750669340 (15.60 GB)
telemt_user_unique_ips_current{user="hello"} 27
```