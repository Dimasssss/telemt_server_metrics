# Server Metrics 2026-03-05 23:56:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 5711.5 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45063
telemt_connections_bad_total 14114
telemt_handshake_timeouts_total 420
telemt_upstream_connect_attempt_total 3683
telemt_upstream_connect_success_total 3650
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3650
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 753
telemt_me_reconnect_success_total 751
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 769
telemt_me_route_drop_no_conn_total 7658
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 77
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 769
telemt_me_writer_restored_same_endpoint_total 746
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 29703
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 446665840 (425.97 MB)
telemt_user_octets_to_client{user="hello"} 12220025544 (11.38 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 5707.0 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13633
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 221
telemt_upstream_connect_attempt_total 4738
telemt_upstream_connect_success_total 4736
telemt_upstream_connect_attempts_per_request{bucket="1"} 4736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 969
telemt_me_reconnect_success_total 969
telemt_me_reader_eof_total 980
telemt_me_idle_close_by_peer_total 980
telemt_me_route_drop_no_conn_total 4214
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 44
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_pool_force_close_total 9
telemt_me_writer_removed_unexpected_total 981
telemt_me_writer_restored_same_endpoint_total 965
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 13061
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 100966196 (96.29 MB)
telemt_user_octets_to_client{user="hello"} 2930148080 (2.73 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 5704.4 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22676
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 5344
telemt_upstream_connect_success_total 5294
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5294
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 1465
telemt_me_reconnect_success_total 1461
telemt_me_reader_eof_total 1522
telemt_me_idle_close_by_peer_total 1522
telemt_me_route_drop_no_conn_total 6585
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 48
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 1523
telemt_me_writer_restored_same_endpoint_total 1456
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 22045
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 369634964 (352.51 MB)
telemt_user_octets_to_client{user="hello"} 6459325472 (6.02 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 5701.1 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18140
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 2864
telemt_upstream_connect_success_total 2851
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2851
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 283
telemt_me_reconnect_success_total 280
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 8655
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 285
telemt_me_writer_restored_same_endpoint_total 276
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 16543
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 173368104 (165.34 MB)
telemt_user_octets_to_client{user="hello"} 15200426048 (14.16 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 5700.1 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24066
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 114
telemt_upstream_connect_attempt_total 3372
telemt_upstream_connect_success_total 3370
telemt_upstream_connect_attempts_per_request{bucket="1"} 3370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 529
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_route_drop_no_conn_total 9125
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_removed_unexpected_total 536
telemt_me_writer_restored_same_endpoint_total 525
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 23588
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 10937853320 (10.19 GB)
telemt_user_octets_to_client{user="hello"} 16419474180 (15.29 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```