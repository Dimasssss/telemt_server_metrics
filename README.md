# Server Metrics 2026-03-03 22:23:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 4378.5 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42660
telemt_connections_bad_total 529
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 1953
telemt_upstream_connect_success_total 1943
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1943
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 197
telemt_me_reconnect_success_total 210
telemt_me_reader_eof_total 193
telemt_me_idle_close_by_peer_total 193
telemt_me_route_drop_no_conn_total 15982
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 77
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 193
telemt_me_writer_restored_same_endpoint_total 190
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 41067
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 413612104 (394.45 MB)
telemt_user_octets_to_client{user="hello"} 15747580800 (14.67 GB)
telemt_user_unique_ips_current{user="hello"} 57
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 4375.2 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17722
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 3256
telemt_upstream_connect_attempt_total 3579
telemt_upstream_connect_success_total 3437
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 3437
telemt_upstream_connect_attempts_per_request{bucket="2"} 68
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 945
telemt_me_reconnect_success_total 959
telemt_me_reader_eof_total 955
telemt_me_idle_close_by_peer_total 954
telemt_me_route_drop_no_conn_total 6850
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 47
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 955
telemt_me_writer_restored_same_endpoint_total 939
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 14183
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 83118172 (79.27 MB)
telemt_user_octets_to_client{user="hello"} 3694462860 (3.44 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 4374.0 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44056
telemt_connections_bad_total 11968
telemt_handshake_timeouts_total 610
telemt_upstream_connect_attempt_total 3094
telemt_upstream_connect_success_total 3066
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 3066
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 512
telemt_me_reconnect_success_total 527
telemt_me_reader_eof_total 520
telemt_me_idle_close_by_peer_total 520
telemt_me_route_drop_no_conn_total 9345
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 110
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 520
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 30475
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 224156164 (213.77 MB)
telemt_user_octets_to_client{user="hello"} 11404413992 (10.62 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 4372.9 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20293
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 283
telemt_upstream_connect_attempt_total 2391
telemt_upstream_connect_success_total 2376
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2376
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 258
telemt_me_reconnect_success_total 275
telemt_me_reader_eof_total 258
telemt_me_idle_close_by_peer_total 258
telemt_me_route_drop_no_conn_total 8119
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_restored_same_endpoint_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 19680
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 170921144 (163.00 MB)
telemt_user_octets_to_client{user="hello"} 7155795820 (6.66 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 4371.6 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40911
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 10914
telemt_upstream_connect_attempt_total 2231
telemt_upstream_connect_success_total 2199
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2199
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 426
telemt_me_reconnect_success_total 443
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 430
telemt_me_route_drop_no_conn_total 26502
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
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
telemt_user_connections_total{user="hello"} 29311
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 162572508 (155.04 MB)
telemt_user_octets_to_client{user="hello"} 7409467980 (6.90 GB)
telemt_user_unique_ips_current{user="hello"} 23
```