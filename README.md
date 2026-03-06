# Server Metrics 2026-03-06 10:21:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 6581.3 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189941
telemt_connections_bad_total 402
telemt_handshake_timeouts_total 2073
telemt_upstream_connect_attempt_total 2023
telemt_upstream_connect_success_total 2014
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 62
telemt_me_reconnect_success_total 56
telemt_me_reader_eof_total 63
telemt_me_idle_close_by_peer_total 63
telemt_me_route_drop_no_conn_total 78372
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 995
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 739
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 352
telemt_desync_frames_bucket_total{bucket="gt_10"} 420
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 63
telemt_me_writer_restored_same_endpoint_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 149027
telemt_user_connections_current{user="hello"} 1147
telemt_user_octets_from_client{user="hello"} 2575884736 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 65566808920 (61.06 GB)
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 6579.1 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91866
telemt_connections_bad_total 348
telemt_handshake_timeouts_total 30144
telemt_upstream_connect_attempt_total 4429
telemt_upstream_connect_success_total 4429
telemt_upstream_connect_attempts_per_request{bucket="1"} 4429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2091
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 603
telemt_me_reconnect_success_total 597
telemt_me_reader_eof_total 614
telemt_me_idle_close_by_peer_total 614
telemt_me_route_drop_no_conn_total 26548
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 261
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 188
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 615
telemt_me_writer_restored_same_endpoint_total 597
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 60128
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 856581736 (816.90 MB)
telemt_user_octets_to_client{user="hello"} 19926848848 (18.56 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 6562.4 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135110
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 12364
telemt_upstream_connect_attempt_total 4296
telemt_upstream_connect_success_total 4274
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 721
telemt_me_reconnect_success_total 710
telemt_me_reader_eof_total 722
telemt_me_idle_close_by_peer_total 721
telemt_me_route_drop_no_conn_total 46869
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 323
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 728
telemt_me_writer_restored_same_endpoint_total 710
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 116557
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 1957564380 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 31523327372 (29.36 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 6546.9 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98987
telemt_connections_bad_total 5923
telemt_handshake_timeouts_total 14347
telemt_upstream_connect_attempt_total 3525
telemt_upstream_connect_success_total 3504
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1518
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 532
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 531
telemt_me_idle_close_by_peer_total 531
telemt_me_route_drop_no_conn_total 36377
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 243
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 531
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 75509
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 1105713708 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 21712396556 (20.22 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 6488.7 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94762
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 503
telemt_upstream_connect_attempt_total 4999
telemt_upstream_connect_success_total 4957
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 4995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1924
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 1382
telemt_me_reader_eof_total 1438
telemt_me_idle_close_by_peer_total 1438
telemt_me_route_drop_no_conn_total 61086
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 159
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_me_writer_removed_unexpected_total 1442
telemt_me_writer_restored_same_endpoint_total 1377
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 89136
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 4203985292 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 39670309880 (36.95 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 90
```