# Server Metrics 2026-03-06 02:04:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 13390.1 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88208
telemt_connections_bad_total 15901
telemt_handshake_timeouts_total 870
telemt_upstream_connect_attempt_total 11188
telemt_upstream_connect_success_total 11077
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 11077
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 3045
telemt_me_reconnect_success_total 3029
telemt_me_reader_eof_total 3141
telemt_me_idle_close_by_peer_total 3141
telemt_me_route_drop_no_conn_total 21796
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 176
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 2
telemt_pool_force_close_total 90
telemt_me_writer_removed_unexpected_total 3141
telemt_me_writer_restored_same_endpoint_total 3023
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 69720
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 773671636 (737.83 MB)
telemt_user_octets_to_client{user="hello"} 24072237356 (22.42 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 13385.5 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29979
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 402
telemt_upstream_connect_attempt_total 10019
telemt_upstream_connect_success_total 10017
telemt_upstream_connect_attempts_per_request{bucket="1"} 10017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 1690
telemt_me_reconnect_success_total 1680
telemt_me_reader_eof_total 1697
telemt_me_idle_close_by_peer_total 1697
telemt_me_route_drop_no_conn_total 8541
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 5
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1698
telemt_me_writer_restored_same_endpoint_total 1676
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 29052
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 185815876 (177.21 MB)
telemt_user_octets_to_client{user="hello"} 6446104992 (6.00 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 13382.9 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54364
telemt_connections_bad_total 519
telemt_handshake_timeouts_total 535
telemt_upstream_connect_attempt_total 12886
telemt_upstream_connect_success_total 12769
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 12769
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 3958
telemt_me_reconnect_success_total 3947
telemt_me_reader_eof_total 4137
telemt_me_idle_close_by_peer_total 4137
telemt_me_route_drop_no_conn_total 14283
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 4138
telemt_me_writer_restored_same_endpoint_total 3940
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 50982
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 577955084 (551.18 MB)
telemt_user_octets_to_client{user="hello"} 19372357660 (18.04 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 13379.6 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42775
telemt_connections_bad_total 237
telemt_handshake_timeouts_total 2774
telemt_upstream_connect_attempt_total 9420
telemt_upstream_connect_success_total 9391
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 9391
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 2058
telemt_me_reconnect_success_total 2046
telemt_me_reader_eof_total 2140
telemt_me_idle_close_by_peer_total 2140
telemt_me_route_drop_no_conn_total 18027
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 4
telemt_pool_force_close_total 86
telemt_me_writer_removed_unexpected_total 2140
telemt_me_writer_restored_same_endpoint_total 2041
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 37564
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 346989388 (330.91 MB)
telemt_user_octets_to_client{user="hello"} 20075991776 (18.70 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 13378.4 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53863
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 220
telemt_upstream_connect_attempt_total 7674
telemt_upstream_connect_success_total 7656
telemt_upstream_connect_attempts_per_request{bucket="1"} 7656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 847
telemt_me_reader_eof_total 862
telemt_me_idle_close_by_peer_total 862
telemt_me_route_drop_no_conn_total 16811
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 52
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 5
telemt_pool_force_close_total 79
telemt_me_writer_removed_unexpected_total 862
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 52764
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 11084820608 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 21557870728 (20.08 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```