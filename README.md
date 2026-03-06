# Server Metrics 2026-03-06 04:22:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 21683.5 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154641
telemt_connections_bad_total 15941
telemt_handshake_timeouts_total 2883
telemt_upstream_connect_attempt_total 23307
telemt_upstream_connect_success_total 23130
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 23130
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 254
telemt_me_reconnect_attempts_total 8687
telemt_me_reconnect_success_total 8657
telemt_me_reader_eof_total 8971
telemt_me_idle_close_by_peer_total 8971
telemt_me_route_drop_no_conn_total 43411
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 369
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 8971
telemt_me_writer_restored_same_endpoint_total 8651
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 127956
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 3032286200 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 49706703360 (46.29 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 21678.8 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55179
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 760
telemt_upstream_connect_attempt_total 19680
telemt_upstream_connect_success_total 19678
telemt_upstream_connect_attempts_per_request{bucket="1"} 19678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 231
telemt_me_reconnect_attempts_total 4741
telemt_me_reconnect_success_total 4725
telemt_me_reader_eof_total 4820
telemt_me_idle_close_by_peer_total 4820
telemt_me_route_drop_no_conn_total 16361
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 192
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4821
telemt_me_writer_restored_same_endpoint_total 4719
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 53264
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 437155808 (416.90 MB)
telemt_user_octets_to_client{user="hello"} 13352245664 (12.44 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 21676.3 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94258
telemt_connections_bad_total 983
telemt_handshake_timeouts_total 1787
telemt_upstream_connect_attempt_total 20270
telemt_upstream_connect_success_total 20102
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 20102
telemt_upstream_connect_attempts_per_request{bucket="2"} 75
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 240
telemt_me_reconnect_attempts_total 6130
telemt_me_reconnect_success_total 6107
telemt_me_reader_eof_total 6384
telemt_me_idle_close_by_peer_total 6384
telemt_me_route_drop_no_conn_total 26468
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 180
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6388
telemt_me_writer_restored_same_endpoint_total 6099
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 88456
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 902458636 (860.65 MB)
telemt_user_octets_to_client{user="hello"} 29694245768 (27.65 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 21672.8 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79310
telemt_connections_bad_total 2885
telemt_handshake_timeouts_total 4559
telemt_upstream_connect_attempt_total 14377
telemt_upstream_connect_success_total 14330
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 14330
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2788
telemt_me_reconnect_success_total 2766
telemt_me_reader_eof_total 2870
telemt_me_idle_close_by_peer_total 2870
telemt_me_route_drop_no_conn_total 27529
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 216
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 2870
telemt_me_writer_restored_same_endpoint_total 2759
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 67786
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1323908396 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 28084756156 (26.16 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 21671.7 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91689
telemt_connections_bad_total 1001
telemt_handshake_timeouts_total 595
telemt_upstream_connect_attempt_total 15307
telemt_upstream_connect_success_total 15277
telemt_upstream_connect_attempts_per_request{bucket="1"} 15277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 2758
telemt_me_reconnect_success_total 2748
telemt_me_reader_eof_total 2847
telemt_me_idle_close_by_peer_total 2847
telemt_me_route_drop_no_conn_total 30311
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 100
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_me_writer_removed_unexpected_total 2849
telemt_me_writer_restored_same_endpoint_total 2741
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 88598
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 23135592876 (21.55 GB)
telemt_user_octets_to_client{user="hello"} 51216889004 (47.70 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 53
```