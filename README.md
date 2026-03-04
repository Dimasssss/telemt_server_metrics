# Server Metrics 2026-03-04 21:48:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 3322.2 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40068
telemt_connections_bad_total 108
telemt_handshake_timeouts_total 389
telemt_upstream_connect_attempt_total 1648
telemt_upstream_connect_success_total 1619
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1619
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 205
telemt_me_reconnect_success_total 221
telemt_me_reader_eof_total 204
telemt_me_idle_close_by_peer_total 204
telemt_me_route_drop_no_conn_total 9471
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 204
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 33877
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 2083203776 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 13771853556 (12.83 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 3316.9 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15468
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 105
telemt_upstream_connect_attempt_total 1731
telemt_upstream_connect_success_total 1701
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1701
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 759
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 163
telemt_me_reconnect_success_total 175
telemt_me_reader_eof_total 159
telemt_me_idle_close_by_peer_total 159
telemt_me_route_drop_no_conn_total 4244
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 159
telemt_me_writer_restored_same_endpoint_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 14167
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 139402096 (132.94 MB)
telemt_user_octets_to_client{user="hello"} 4183212296 (3.90 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 3313.8 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34944
telemt_connections_bad_total 516
telemt_handshake_timeouts_total 208
telemt_upstream_connect_attempt_total 983
telemt_upstream_connect_success_total 968
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 968
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 31
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 9583
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 100
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 31676
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 540777148 (515.73 MB)
telemt_user_octets_to_client{user="hello"} 11846554744 (11.03 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 35362.0 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499136
telemt_connections_bad_total 64667
telemt_handshake_timeouts_total 14635
telemt_upstream_connect_attempt_total 15205
telemt_upstream_connect_success_total 15205
telemt_upstream_connect_attempts_per_request{bucket="1"} 15205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 2061
telemt_me_reconnect_success_total 2049
telemt_me_reader_eof_total 2081
telemt_me_idle_close_by_peer_total 2081
telemt_me_route_drop_no_conn_total 172770
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 669
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 382
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 12
telemt_pool_force_close_total 397
telemt_me_writer_removed_unexpected_total 2082
telemt_me_writer_restored_same_endpoint_total 2025
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 391841
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 5593017856 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 151671020196 (141.25 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 35721.3 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500992
telemt_connections_bad_total 3757
telemt_handshake_timeouts_total 5493
telemt_upstream_connect_attempt_total 21441
telemt_upstream_connect_success_total 21329
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 21329
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 4559
telemt_me_reconnect_success_total 4547
telemt_me_reader_eof_total 4711
telemt_me_idle_close_by_peer_total 4711
telemt_me_route_drop_no_conn_total 223461
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 824
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4714
telemt_me_writer_restored_same_endpoint_total 4526
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 452124
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 7063232312 (6.58 GB)
telemt_user_octets_to_client{user="hello"} 145169835524 (135.20 GB)
telemt_user_unique_ips_current{user="hello"} 36
```