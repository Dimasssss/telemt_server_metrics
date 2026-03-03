# Server Metrics 2026-03-03 23:19:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 7756.4 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62449
telemt_connections_bad_total 645
telemt_handshake_timeouts_total 208
telemt_upstream_connect_attempt_total 4400
telemt_upstream_connect_success_total 4375
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4375
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 531
telemt_me_reconnect_success_total 542
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 24318
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
telemt_me_writer_removed_unexpected_total 530
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 60322
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 527612012 (503.17 MB)
telemt_user_octets_to_client{user="hello"} 19347378096 (18.02 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 7753.1 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29031
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 5836
telemt_upstream_connect_attempt_total 10405
telemt_upstream_connect_success_total 10228
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 10228
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 4467
telemt_me_reconnect_success_total 4478
telemt_me_reader_eof_total 4546
telemt_me_idle_close_by_peer_total 4545
telemt_me_route_drop_no_conn_total 11113
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 70
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 4546
telemt_me_writer_restored_same_endpoint_total 4458
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 22819
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 142829780 (136.21 MB)
telemt_user_octets_to_client{user="hello"} 10449586948 (9.73 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 7751.7 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69084
telemt_connections_bad_total 20136
telemt_handshake_timeouts_total 1748
telemt_upstream_connect_attempt_total 9000
telemt_upstream_connect_success_total 8952
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 8952
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 3220
telemt_me_reconnect_success_total 3228
telemt_me_reader_eof_total 3348
telemt_me_idle_close_by_peer_total 3347
telemt_me_route_drop_no_conn_total 15055
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 3349
telemt_me_writer_restored_same_endpoint_total 3207
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 46060
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 309859276 (295.50 MB)
telemt_user_octets_to_client{user="hello"} 13245306124 (12.34 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 7750.6 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31062
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 4213
telemt_upstream_connect_success_total 4190
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 4190
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 360
telemt_me_reconnect_success_total 374
telemt_me_reader_eof_total 358
telemt_me_idle_close_by_peer_total 358
telemt_me_route_drop_no_conn_total 11851
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
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_restored_same_endpoint_total 355
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 30082
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 225141748 (214.71 MB)
telemt_user_octets_to_client{user="hello"} 9490822584 (8.84 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 7749.3 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70836
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 26983
telemt_upstream_connect_attempt_total 5318
telemt_upstream_connect_success_total 5260
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5260
telemt_upstream_connect_attempts_per_request{bucket="2"} 27
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 1247
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 1284
telemt_me_idle_close_by_peer_total 1284
telemt_me_route_drop_no_conn_total 31544
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 34
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 1286
telemt_me_writer_restored_same_endpoint_total 1238
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 42570
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 213722184 (203.82 MB)
telemt_user_octets_to_client{user="hello"} 11374611008 (10.59 GB)
telemt_user_unique_ips_current{user="hello"} 22
```