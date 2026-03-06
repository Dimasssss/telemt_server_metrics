# Server Metrics 2026-03-06 01:03:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 9704.5 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67634
telemt_connections_bad_total 15836
telemt_handshake_timeouts_total 606
telemt_upstream_connect_attempt_total 7344
telemt_upstream_connect_success_total 7285
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7285
telemt_upstream_connect_attempts_per_request{bucket="2"} 27
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 1590
telemt_me_reader_eof_total 1641
telemt_me_idle_close_by_peer_total 1641
telemt_me_route_drop_no_conn_total 14282
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 114
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 1641
telemt_me_writer_restored_same_endpoint_total 1585
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 49845
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 589135612 (561.84 MB)
telemt_user_octets_to_client{user="hello"} 17877095096 (16.65 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 9699.9 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21825
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 8000
telemt_upstream_connect_success_total 7998
telemt_upstream_connect_attempts_per_request{bucket="1"} 7998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 1592
telemt_me_reader_eof_total 1608
telemt_me_idle_close_by_peer_total 1608
telemt_me_route_drop_no_conn_total 6330
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 3
telemt_pool_force_close_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1609
telemt_me_writer_restored_same_endpoint_total 1588
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 21083
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 156688888 (149.43 MB)
telemt_user_octets_to_client{user="hello"} 5509846756 (5.13 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 9697.3 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38330
telemt_connections_bad_total 301
telemt_handshake_timeouts_total 213
telemt_upstream_connect_attempt_total 10007
telemt_upstream_connect_success_total 9912
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9912
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 3312
telemt_me_reconnect_success_total 3303
telemt_me_reader_eof_total 3468
telemt_me_idle_close_by_peer_total 3468
telemt_me_route_drop_no_conn_total 9856
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 88
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3469
telemt_me_writer_restored_same_endpoint_total 3297
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 36644
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 475965784 (453.92 MB)
telemt_user_octets_to_client{user="hello"} 16440414712 (15.31 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 9694.1 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29455
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 1025
telemt_upstream_connect_attempt_total 5700
telemt_upstream_connect_success_total 5679
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5679
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 830
telemt_me_reconnect_success_total 824
telemt_me_reader_eof_total 849
telemt_me_idle_close_by_peer_total 849
telemt_me_route_drop_no_conn_total 12490
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 67
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 849
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 26919
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 274048540 (261.35 MB)
telemt_user_octets_to_client{user="hello"} 17254942608 (16.07 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 9692.8 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39063
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 158
telemt_upstream_connect_attempt_total 5439
telemt_upstream_connect_success_total 5428
telemt_upstream_connect_attempts_per_request{bucket="1"} 5428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 691
telemt_me_reconnect_success_total 689
telemt_me_reader_eof_total 701
telemt_me_idle_close_by_peer_total 701
telemt_me_route_drop_no_conn_total 13067
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 4
telemt_pool_force_close_total 57
telemt_me_writer_removed_unexpected_total 701
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 38351
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 11014905008 (10.26 GB)
telemt_user_octets_to_client{user="hello"} 18691148976 (17.41 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 24
```