# Server Metrics 2026-03-03 22:44:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 5606.8 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50053
telemt_connections_bad_total 639
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 2509
telemt_upstream_connect_success_total 2491
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2491
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 210
telemt_me_reconnect_success_total 222
telemt_me_reader_eof_total 205
telemt_me_idle_close_by_peer_total 205
telemt_me_route_drop_no_conn_total 19160
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 94
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 205
telemt_me_writer_restored_same_endpoint_total 202
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 48228
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 457405848 (436.22 MB)
telemt_user_octets_to_client{user="hello"} 17393469148 (16.20 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 5603.4 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21897
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 4250
telemt_upstream_connect_attempt_total 5869
telemt_upstream_connect_success_total 5708
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 5708
telemt_upstream_connect_attempts_per_request{bucket="2"} 77
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2038
telemt_me_reconnect_success_total 2050
telemt_me_reader_eof_total 2070
telemt_me_idle_close_by_peer_total 2069
telemt_me_route_drop_no_conn_total 8280
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 53
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 2070
telemt_me_writer_restored_same_endpoint_total 2030
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 17315
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 101114912 (96.43 MB)
telemt_user_octets_to_client{user="hello"} 6351142704 (5.91 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 5602.2 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54621
telemt_connections_bad_total 15347
telemt_handshake_timeouts_total 1552
telemt_upstream_connect_attempt_total 4835
telemt_upstream_connect_success_total 4798
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4798
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 1083
telemt_me_reconnect_success_total 1097
telemt_me_reader_eof_total 1115
telemt_me_idle_close_by_peer_total 1114
telemt_me_route_drop_no_conn_total 11276
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 120
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 1115
telemt_me_writer_restored_same_endpoint_total 1076
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 36660
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 278013800 (265.13 MB)
telemt_user_octets_to_client{user="hello"} 12153558176 (11.32 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 5601.0 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24245
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 375
telemt_upstream_connect_attempt_total 3023
telemt_upstream_connect_success_total 3002
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3002
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 271
telemt_me_reconnect_success_total 287
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 270
telemt_me_route_drop_no_conn_total 9422
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 270
telemt_me_writer_restored_same_endpoint_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 23478
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 194338616 (185.34 MB)
telemt_user_octets_to_client{user="hello"} 7760894860 (7.23 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 5599.7 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52483
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 17715
telemt_upstream_connect_attempt_total 2895
telemt_upstream_connect_success_total 2847
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2847
telemt_upstream_connect_attempts_per_request{bucket="2"} 22
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 508
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 517
telemt_me_idle_close_by_peer_total 517
telemt_me_route_drop_no_conn_total 28038
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 517
telemt_me_writer_restored_same_endpoint_total 501
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 33920
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 182528108 (174.07 MB)
telemt_user_octets_to_client{user="hello"} 8402029180 (7.82 GB)
telemt_user_unique_ips_current{user="hello"} 22
```