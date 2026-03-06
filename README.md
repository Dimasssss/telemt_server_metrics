# Server Metrics 2026-03-06 01:13:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 10318.7 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70848
telemt_connections_bad_total 15836
telemt_handshake_timeouts_total 657
telemt_upstream_connect_attempt_total 8330
telemt_upstream_connect_success_total 8263
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 8263
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 1991
telemt_me_reconnect_success_total 1980
telemt_me_reader_eof_total 2053
telemt_me_idle_close_by_peer_total 2053
telemt_me_route_drop_no_conn_total 16149
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 114
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 2053
telemt_me_writer_restored_same_endpoint_total 1975
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 52944
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 606768712 (578.66 MB)
telemt_user_octets_to_client{user="hello"} 21037395340 (19.59 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 10314.3 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22997
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 8396
telemt_upstream_connect_success_total 8394
telemt_upstream_connect_attempts_per_request{bucket="1"} 8394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 1616
telemt_me_reconnect_success_total 1609
telemt_me_reader_eof_total 1625
telemt_me_idle_close_by_peer_total 1625
telemt_me_route_drop_no_conn_total 6542
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 47
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
telemt_me_writer_removed_unexpected_total 1626
telemt_me_writer_restored_same_endpoint_total 1605
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 22229
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 160847456 (153.40 MB)
telemt_user_octets_to_client{user="hello"} 5584819312 (5.20 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 10311.7 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40389
telemt_connections_bad_total 307
telemt_handshake_timeouts_total 248
telemt_upstream_connect_attempt_total 10744
telemt_upstream_connect_success_total 10639
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10639
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 3551
telemt_me_reconnect_success_total 3541
telemt_me_reader_eof_total 3717
telemt_me_idle_close_by_peer_total 3717
telemt_me_route_drop_no_conn_total 10523
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3718
telemt_me_writer_restored_same_endpoint_total 3535
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 38571
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 489112408 (466.45 MB)
telemt_user_octets_to_client{user="hello"} 16862790384 (15.70 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 10308.3 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31693
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 1206
telemt_upstream_connect_attempt_total 6512
telemt_upstream_connect_success_total 6489
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 6489
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2663
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 1099
telemt_me_reconnect_success_total 1092
telemt_me_reader_eof_total 1129
telemt_me_idle_close_by_peer_total 1129
telemt_me_route_drop_no_conn_total 13337
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 69
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 1129
telemt_me_writer_restored_same_endpoint_total 1087
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 28645
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 302724944 (288.70 MB)
telemt_user_octets_to_client{user="hello"} 17677028368 (16.46 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 10307.2 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41459
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 5734
telemt_upstream_connect_success_total 5722
telemt_upstream_connect_attempts_per_request{bucket="1"} 5722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 697
telemt_me_reconnect_success_total 695
telemt_me_reader_eof_total 708
telemt_me_idle_close_by_peer_total 708
telemt_me_route_drop_no_conn_total 13618
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 4
telemt_pool_force_close_total 57
telemt_me_writer_removed_unexpected_total 708
telemt_me_writer_restored_same_endpoint_total 690
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 40609
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 11033799744 (10.28 GB)
telemt_user_octets_to_client{user="hello"} 19000986484 (17.70 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 30
```