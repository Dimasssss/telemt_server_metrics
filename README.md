# Server Metrics 2026-03-05 23:25:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 3868.7 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33652
telemt_connections_bad_total 11570
telemt_handshake_timeouts_total 286
telemt_upstream_connect_attempt_total 2479
telemt_upstream_connect_success_total 2448
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2448
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 478
telemt_me_reconnect_success_total 477
telemt_me_reader_eof_total 486
telemt_me_idle_close_by_peer_total 486
telemt_me_route_drop_no_conn_total 5620
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 486
telemt_me_writer_restored_same_endpoint_total 473
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 21111
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 388717916 (370.71 MB)
telemt_user_octets_to_client{user="hello"} 8200531296 (7.64 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 3864.3 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9765
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 2295
telemt_upstream_connect_success_total 2293
telemt_upstream_connect_attempts_per_request{bucket="1"} 2293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 178
telemt_me_reconnect_success_total 179
telemt_me_reader_eof_total 179
telemt_me_idle_close_by_peer_total 179
telemt_me_route_drop_no_conn_total 3142
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 37
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_pool_force_close_total 9
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_restored_same_endpoint_total 175
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 9305
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 81364932 (77.60 MB)
telemt_user_octets_to_client{user="hello"} 1379466952 (1.28 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 3861.5 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16015
telemt_connections_bad_total 94
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 2711
telemt_upstream_connect_success_total 2668
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2668
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 514
telemt_me_reconnect_success_total 514
telemt_me_reader_eof_total 529
telemt_me_idle_close_by_peer_total 529
telemt_me_route_drop_no_conn_total 5045
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 530
telemt_me_writer_restored_same_endpoint_total 509
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 15625
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 327574852 (312.40 MB)
telemt_user_octets_to_client{user="hello"} 5186642428 (4.83 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 3858.4 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13482
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 327
telemt_upstream_connect_attempt_total 1997
telemt_upstream_connect_success_total 1986
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1986
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 251
telemt_me_reconnect_success_total 248
telemt_me_reader_eof_total 253
telemt_me_idle_close_by_peer_total 253
telemt_me_route_drop_no_conn_total 6128
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 253
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 12307
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 158396344 (151.06 MB)
telemt_user_octets_to_client{user="hello"} 13580961700 (12.65 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 3857.2 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16112
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 2496
telemt_upstream_connect_success_total 2494
telemt_upstream_connect_attempts_per_request{bucket="1"} 2494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 457
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 466
telemt_me_idle_close_by_peer_total 466
telemt_me_route_drop_no_conn_total 7319
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_restored_same_endpoint_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 15779
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 10915457212 (10.17 GB)
telemt_user_octets_to_client{user="hello"} 14298300632 (13.32 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 27
```