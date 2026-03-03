# Server Metrics 2026-03-03 22:28:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 4686.0 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44499
telemt_connections_bad_total 566
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 2055
telemt_upstream_connect_success_total 2039
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2039
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 199
telemt_me_reconnect_success_total 211
telemt_me_reader_eof_total 194
telemt_me_idle_close_by_peer_total 194
telemt_me_route_drop_no_conn_total 16814
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 80
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 194
telemt_me_writer_restored_same_endpoint_total 191
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 42841
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 423033812 (403.44 MB)
telemt_user_octets_to_client{user="hello"} 16225502192 (15.11 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 4682.4 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18692
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 3509
telemt_upstream_connect_attempt_total 4105
telemt_upstream_connect_success_total 3957
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 3957
telemt_upstream_connect_attempts_per_request{bucket="2"} 71
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 1186
telemt_me_reconnect_success_total 1200
telemt_me_reader_eof_total 1200
telemt_me_idle_close_by_peer_total 1199
telemt_me_route_drop_no_conn_total 7180
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 49
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 1200
telemt_me_writer_restored_same_endpoint_total 1180
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 14898
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 88192892 (84.11 MB)
telemt_user_octets_to_client{user="hello"} 4044360684 (3.77 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 4681.2 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47091
telemt_connections_bad_total 12808
telemt_handshake_timeouts_total 1400
telemt_upstream_connect_attempt_total 3493
telemt_upstream_connect_success_total 3460
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3460
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 624
telemt_me_reconnect_success_total 639
telemt_me_reader_eof_total 634
telemt_me_idle_close_by_peer_total 634
telemt_me_route_drop_no_conn_total 9750
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 117
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 634
telemt_me_writer_restored_same_endpoint_total 618
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 31866
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 227906456 (217.35 MB)
telemt_user_octets_to_client{user="hello"} 11645779052 (10.85 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 4680.1 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21308
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 285
telemt_upstream_connect_attempt_total 2504
telemt_upstream_connect_success_total 2485
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2485
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 259
telemt_me_reconnect_success_total 276
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 8499
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 259
telemt_me_writer_restored_same_endpoint_total 257
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 20656
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 176309028 (168.14 MB)
telemt_user_octets_to_client{user="hello"} 7278445724 (6.78 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 4678.8 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43884
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 12502
telemt_upstream_connect_attempt_total 2333
telemt_upstream_connect_success_total 2292
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2292
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 426
telemt_me_reconnect_success_total 443
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 430
telemt_me_route_drop_no_conn_total 26949
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 430
telemt_me_writer_restored_same_endpoint_total 419
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 30666
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 164744228 (157.11 MB)
telemt_user_octets_to_client{user="hello"} 7531621412 (7.01 GB)
telemt_user_unique_ips_current{user="hello"} 21
```