# Server Metrics 2026-03-06 06:00:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 27518.9 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229703
telemt_connections_bad_total 16042
telemt_handshake_timeouts_total 3476
telemt_upstream_connect_attempt_total 27859
telemt_upstream_connect_success_total 27618
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 27618
telemt_upstream_connect_attempts_per_request{bucket="2"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 9961
telemt_me_reconnect_success_total 9923
telemt_me_reader_eof_total 10263
telemt_me_idle_close_by_peer_total 10263
telemt_me_route_drop_no_conn_total 72190
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 684
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10264
telemt_me_writer_restored_same_endpoint_total 9917
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 200408
telemt_user_connections_current{user="hello"} 779
telemt_user_octets_from_client{user="hello"} 5550049000 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 74979799060 (69.83 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 27514.3 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93384
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 6044
telemt_upstream_connect_attempt_total 24512
telemt_upstream_connect_success_total 24510
telemt_upstream_connect_attempts_per_request{bucket="1"} 24510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 6771
telemt_me_reconnect_success_total 6744
telemt_me_reader_eof_total 6895
telemt_me_idle_close_by_peer_total 6895
telemt_me_route_drop_no_conn_total 27154
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 118
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 322
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 9
telemt_pool_force_close_total 175
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6896
telemt_me_writer_restored_same_endpoint_total 6738
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 85467
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 844586316 (805.46 MB)
telemt_user_octets_to_client{user="hello"} 27963916504 (26.04 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 27511.7 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164571
telemt_connections_bad_total 1524
telemt_handshake_timeouts_total 3911
telemt_upstream_connect_attempt_total 29316
telemt_upstream_connect_success_total 29109
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 29109
telemt_upstream_connect_attempts_per_request{bucket="2"} 94
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 347
telemt_me_reconnect_attempts_total 10138
telemt_me_reconnect_success_total 10106
telemt_me_reader_eof_total 10539
telemt_me_idle_close_by_peer_total 10539
telemt_me_route_drop_no_conn_total 46652
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 308
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 10544
telemt_me_writer_restored_same_endpoint_total 10098
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 145100
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 1435530592 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 48395535144 (45.07 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 27508.5 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125651
telemt_connections_bad_total 8270
telemt_handshake_timeouts_total 6004
telemt_upstream_connect_attempt_total 20744
telemt_upstream_connect_success_total 20676
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 20676
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 217
telemt_me_reconnect_attempts_total 4831
telemt_me_reconnect_success_total 4802
telemt_me_reader_eof_total 4971
telemt_me_idle_close_by_peer_total 4971
telemt_me_route_drop_no_conn_total 43444
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 321
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 216
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 9
telemt_pool_force_close_total 214
telemt_me_writer_removed_unexpected_total 4971
telemt_me_writer_restored_same_endpoint_total 4795
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 106218
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 1651890520 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 39176441444 (36.49 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 27507.4 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142217
telemt_connections_bad_total 1577
telemt_handshake_timeouts_total 832
telemt_upstream_connect_attempt_total 18816
telemt_upstream_connect_success_total 18773
telemt_upstream_connect_attempts_per_request{bucket="1"} 18773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 246
telemt_me_reconnect_attempts_total 3226
telemt_me_reconnect_success_total 3211
telemt_me_reader_eof_total 3320
telemt_me_idle_close_by_peer_total 3319
telemt_me_route_drop_no_conn_total 51135
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 287
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 169
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3324
telemt_me_writer_restored_same_endpoint_total 3204
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 137259
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 23921131740 (22.28 GB)
telemt_user_octets_to_client{user="hello"} 84765066816 (78.94 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 88
```