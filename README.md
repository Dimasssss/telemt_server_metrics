# Server Metrics 2026-03-06 03:06:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 17075.7 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115899
telemt_connections_bad_total 15911
telemt_handshake_timeouts_total 1859
telemt_upstream_connect_attempt_total 16499
telemt_upstream_connect_success_total 16344
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 16344
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 5171
telemt_me_reconnect_success_total 5152
telemt_me_reader_eof_total 5319
telemt_me_idle_close_by_peer_total 5319
telemt_me_route_drop_no_conn_total 31256
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 323
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 216
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 2
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 5319
telemt_me_writer_restored_same_endpoint_total 5146
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 92083
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 1076944076 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 36478745908 (33.97 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 17071.1 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38297
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 476
telemt_upstream_connect_attempt_total 12525
telemt_upstream_connect_success_total 12522
telemt_upstream_connect_attempts_per_request{bucket="1"} 12522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 161
telemt_me_reconnect_attempts_total 1984
telemt_me_reconnect_success_total 1974
telemt_me_reader_eof_total 1995
telemt_me_idle_close_by_peer_total 1995
telemt_me_route_drop_no_conn_total 11317
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 112
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1996
telemt_me_writer_restored_same_endpoint_total 1968
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 37147
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 252138268 (240.46 MB)
telemt_user_octets_to_client{user="hello"} 9153639020 (8.52 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 17068.5 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69867
telemt_connections_bad_total 735
telemt_handshake_timeouts_total 1522
telemt_upstream_connect_attempt_total 15641
telemt_upstream_connect_success_total 15513
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 15513
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 4498
telemt_me_reconnect_success_total 4481
telemt_me_reader_eof_total 4687
telemt_me_idle_close_by_peer_total 4687
telemt_me_route_drop_no_conn_total 19287
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 164
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4690
telemt_me_writer_restored_same_endpoint_total 4474
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 65106
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 655297216 (624.94 MB)
telemt_user_octets_to_client{user="hello"} 22789791308 (21.22 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 17065.2 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55058
telemt_connections_bad_total 272
telemt_handshake_timeouts_total 3124
telemt_upstream_connect_attempt_total 11294
telemt_upstream_connect_success_total 11259
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 11259
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 2289
telemt_me_reconnect_success_total 2274
telemt_me_reader_eof_total 2370
telemt_me_idle_close_by_peer_total 2370
telemt_me_route_drop_no_conn_total 21570
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2370
telemt_me_writer_restored_same_endpoint_total 2267
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 48752
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 433590752 (413.50 MB)
telemt_user_octets_to_client{user="hello"} 23146230288 (21.56 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 17064.1 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68245
telemt_connections_bad_total 735
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 10192
telemt_upstream_connect_success_total 10168
telemt_upstream_connect_attempts_per_request{bucket="1"} 10168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3820
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 1109
telemt_me_reconnect_success_total 1105
telemt_me_reader_eof_total 1128
telemt_me_idle_close_by_peer_total 1128
telemt_me_route_drop_no_conn_total 21087
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 70
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1128
telemt_me_writer_restored_same_endpoint_total 1099
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 66015
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 12075381504 (11.25 GB)
telemt_user_octets_to_client{user="hello"} 31302111160 (29.15 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 36
```