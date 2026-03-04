# Server Metrics 2026-03-04 22:45:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 6702.0 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73469
telemt_connections_bad_total 1346
telemt_handshake_timeouts_total 476
telemt_upstream_connect_attempt_total 6211
telemt_upstream_connect_success_total 6143
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 6143
telemt_upstream_connect_attempts_per_request{bucket="2"} 25
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 1870
telemt_me_reconnect_success_total 1879
telemt_me_reader_eof_total 1917
telemt_me_idle_close_by_peer_total 1917
telemt_me_route_drop_no_conn_total 18432
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 1918
telemt_me_writer_restored_same_endpoint_total 1859
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 61743
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 2341339908 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 33075032132 (30.80 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 6696.6 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25853
telemt_connections_bad_total 680
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 6959
telemt_upstream_connect_success_total 6843
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 6840
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 498
telemt_me_reconnect_attempts_total 2390
telemt_me_reconnect_success_total 2386
telemt_me_reader_eof_total 2424
telemt_me_idle_close_by_peer_total 2423
telemt_me_route_drop_no_conn_total 8228
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 2478
telemt_me_writer_restored_same_endpoint_total 2367
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 24255
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 224464544 (214.07 MB)
telemt_user_octets_to_client{user="hello"} 7185378080 (6.69 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 6693.4 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58949
telemt_connections_bad_total 1017
telemt_handshake_timeouts_total 242
telemt_upstream_connect_attempt_total 2608
telemt_upstream_connect_success_total 2584
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2584
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 118
telemt_me_reconnect_success_total 131
telemt_me_reader_eof_total 120
telemt_me_idle_close_by_peer_total 120
telemt_me_route_drop_no_conn_total 18115
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 120
telemt_me_writer_restored_same_endpoint_total 111
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 54112
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 916459636 (874.00 MB)
telemt_user_octets_to_client{user="hello"} 23044044356 (21.46 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 38741.5 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521788
telemt_connections_bad_total 70346
telemt_handshake_timeouts_total 14668
telemt_upstream_connect_attempt_total 16778
telemt_upstream_connect_success_total 16778
telemt_upstream_connect_attempts_per_request{bucket="1"} 16778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 223
telemt_me_reconnect_attempts_total 2184
telemt_me_reconnect_success_total 2169
telemt_me_reader_eof_total 2211
telemt_me_idle_close_by_peer_total 2211
telemt_me_route_drop_no_conn_total 179160
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 697
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 14
telemt_pool_force_close_total 440
telemt_me_writer_removed_unexpected_total 2212
telemt_me_writer_restored_same_endpoint_total 2143
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 408519
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 5712092996 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 154632963568 (144.01 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 39100.8 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520534
telemt_connections_bad_total 3772
telemt_handshake_timeouts_total 5758
telemt_upstream_connect_attempt_total 23458
telemt_upstream_connect_success_total 23332
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 23332
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 4869
telemt_me_reconnect_success_total 4855
telemt_me_reader_eof_total 5031
telemt_me_idle_close_by_peer_total 5031
telemt_me_route_drop_no_conn_total 229392
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 827
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 5033
telemt_me_writer_restored_same_endpoint_total 4834
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 470430
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 7255938504 (6.76 GB)
telemt_user_octets_to_client{user="hello"} 154776740928 (144.15 GB)
telemt_user_unique_ips_current{user="hello"} 35
```