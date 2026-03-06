# Server Metrics 2026-03-06 05:14:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 24755.2 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191415
telemt_connections_bad_total 16005
telemt_handshake_timeouts_total 3167
telemt_upstream_connect_attempt_total 26193
telemt_upstream_connect_success_total 25980
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 25980
telemt_upstream_connect_attempts_per_request{bucket="2"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10024
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 268
telemt_me_reconnect_attempts_total 9515
telemt_me_reconnect_success_total 9480
telemt_me_reader_eof_total 9811
telemt_me_idle_close_by_peer_total 9811
telemt_me_route_drop_no_conn_total 59251
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 585
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 9812
telemt_me_writer_restored_same_endpoint_total 9474
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 163678
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 3600152856 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 63425625868 (59.07 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 24750.6 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71357
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 1013
telemt_upstream_connect_attempt_total 23766
telemt_upstream_connect_success_total 23764
telemt_upstream_connect_attempts_per_request{bucket="1"} 23764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 288
telemt_me_reconnect_attempts_total 6755
telemt_me_reconnect_success_total 6733
telemt_me_reader_eof_total 6883
telemt_me_idle_close_by_peer_total 6883
telemt_me_route_drop_no_conn_total 21416
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 279
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_pool_stale_pick_total 1700
telemt_me_writer_removed_unexpected_total 6884
telemt_me_writer_restored_same_endpoint_total 6727
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 68860
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 650696988 (620.55 MB)
telemt_user_octets_to_client{user="hello"} 18580156040 (17.30 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 24748.1 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124466
telemt_connections_bad_total 1385
telemt_handshake_timeouts_total 3094
telemt_upstream_connect_attempt_total 24301
telemt_upstream_connect_success_total 24112
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 24112
telemt_upstream_connect_attempts_per_request{bucket="2"} 85
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 7690
telemt_me_reconnect_success_total 7662
telemt_me_reader_eof_total 8001
telemt_me_idle_close_by_peer_total 8001
telemt_me_route_drop_no_conn_total 36036
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 236
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 8006
telemt_me_writer_restored_same_endpoint_total 7654
telemt_me_writer_removed_unexpected_minus_restored_total 352
telemt_user_connections_total{user="hello"} 116355
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 1097503744 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 39467364212 (36.76 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 24744.7 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101050
telemt_connections_bad_total 5795
telemt_handshake_timeouts_total 5585
telemt_upstream_connect_attempt_total 17235
telemt_upstream_connect_success_total 17176
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 17176
telemt_upstream_connect_attempts_per_request{bucket="2"} 29
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 186
telemt_me_reconnect_attempts_total 3418
telemt_me_reconnect_success_total 3391
telemt_me_reader_eof_total 3505
telemt_me_idle_close_by_peer_total 3505
telemt_me_route_drop_no_conn_total 34830
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 8
telemt_pool_force_close_total 169
telemt_me_writer_removed_unexpected_total 3505
telemt_me_writer_restored_same_endpoint_total 3384
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 85089
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 1481050452 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 32357325564 (30.14 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 24743.6 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115238
telemt_connections_bad_total 1014
telemt_handshake_timeouts_total 660
telemt_upstream_connect_attempt_total 16649
telemt_upstream_connect_success_total 16610
telemt_upstream_connect_attempts_per_request{bucket="1"} 16610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 2853
telemt_me_reconnect_success_total 2840
telemt_me_reader_eof_total 2940
telemt_me_idle_close_by_peer_total 2939
telemt_me_route_drop_no_conn_total 39919
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 156
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 2944
telemt_me_writer_restored_same_endpoint_total 2833
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 111562
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 23635414864 (22.01 GB)
telemt_user_octets_to_client{user="hello"} 66839956096 (62.25 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 56
```