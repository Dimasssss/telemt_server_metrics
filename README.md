# Server Metrics 2026-03-03 22:54:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 6221.3 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53397
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 2950
telemt_upstream_connect_success_total 2931
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2931
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 291
telemt_me_reconnect_success_total 302
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 20272
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_pool_force_close_total 39
telemt_me_writer_removed_unexpected_total 285
telemt_me_writer_restored_same_endpoint_total 282
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 51492
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 477133472 (455.03 MB)
telemt_user_octets_to_client{user="hello"} 17833281244 (16.61 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 6217.8 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24077
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 4764
telemt_upstream_connect_attempt_total 7081
telemt_upstream_connect_success_total 6920
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 6920
telemt_upstream_connect_attempts_per_request{bucket="2"} 78
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 2659
telemt_me_reconnect_success_total 2671
telemt_me_reader_eof_total 2702
telemt_me_idle_close_by_peer_total 2701
telemt_me_route_drop_no_conn_total 8659
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 55
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 2702
telemt_me_writer_restored_same_endpoint_total 2651
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 18979
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 113554928 (108.29 MB)
telemt_user_octets_to_client{user="hello"} 7979149612 (7.43 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 6216.6 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58965
telemt_connections_bad_total 16930
telemt_handshake_timeouts_total 1624
telemt_upstream_connect_attempt_total 5916
telemt_upstream_connect_success_total 5878
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5878
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 1606
telemt_me_reconnect_success_total 1617
telemt_me_reader_eof_total 1673
telemt_me_idle_close_by_peer_total 1672
telemt_me_route_drop_no_conn_total 12144
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 1674
telemt_me_writer_restored_same_endpoint_total 1596
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 39335
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 288182708 (274.83 MB)
telemt_user_octets_to_client{user="hello"} 12442065004 (11.59 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 6215.6 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25822
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 405
telemt_upstream_connect_attempt_total 3485
telemt_upstream_connect_success_total 3464
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3464
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 317
telemt_me_reconnect_success_total 332
telemt_me_reader_eof_total 315
telemt_me_idle_close_by_peer_total 315
telemt_me_route_drop_no_conn_total 10143
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
telemt_me_writer_removed_unexpected_total 315
telemt_me_writer_restored_same_endpoint_total 313
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 24996
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 206605800 (197.03 MB)
telemt_user_octets_to_client{user="hello"} 8446162624 (7.87 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 6214.2 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57122
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 20147
telemt_upstream_connect_attempt_total 3449
telemt_upstream_connect_success_total 3401
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3401
telemt_upstream_connect_attempts_per_request{bucket="2"} 22
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 658
telemt_me_reconnect_success_total 675
telemt_me_reader_eof_total 670
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 29064
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 11
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 672
telemt_me_writer_restored_same_endpoint_total 651
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 36022
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 188231776 (179.51 MB)
telemt_user_octets_to_client{user="hello"} 8624013948 (8.03 GB)
telemt_user_unique_ips_current{user="hello"} 17
```