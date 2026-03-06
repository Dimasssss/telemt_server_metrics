# Server Metrics 2026-03-06 19:16:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 4092.8 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104316
telemt_connections_bad_total 1265
telemt_handshake_timeouts_total 3200
telemt_upstream_connect_attempt_total 4632
telemt_upstream_connect_success_total 4567
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 1190
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1471
telemt_me_idle_close_by_peer_total 1471
telemt_me_route_drop_no_conn_total 39766
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 452
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 328
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 140
telemt_me_writer_removed_unexpected_total 1490
telemt_me_writer_restored_same_endpoint_total 1174
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 93129
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 1640016568 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 30537859864 (28.44 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 4092.6 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36528
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 2278
telemt_upstream_connect_attempt_total 7013
telemt_upstream_connect_success_total 7011
telemt_upstream_connect_attempts_per_request{bucket="1"} 7011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 2439
telemt_me_reconnect_success_total 2435
telemt_me_reader_eof_total 3177
telemt_me_idle_close_by_peer_total 3177
telemt_me_route_drop_no_conn_total 13832
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 98
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 3177
telemt_me_writer_restored_same_endpoint_total 2433
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 33112
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 384620236 (366.80 MB)
telemt_user_octets_to_client{user="hello"} 9622200040 (8.96 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 4092.5 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68270
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 863
telemt_upstream_connect_attempt_total 4648
telemt_upstream_connect_success_total 4631
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 881
telemt_me_reconnect_success_total 880
telemt_me_reader_eof_total 1145
telemt_me_idle_close_by_peer_total 1145
telemt_me_route_drop_no_conn_total 21938
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 329
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 3
telemt_pool_force_close_total 88
telemt_pool_stale_pick_total 57
telemt_me_writer_removed_unexpected_total 1147
telemt_me_writer_restored_same_endpoint_total 873
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 63192
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 2682771420 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 15137724532 (14.10 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 4093.0 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87438
telemt_connections_bad_total 36684
telemt_handshake_timeouts_total 3673
telemt_upstream_connect_attempt_total 5683
telemt_upstream_connect_success_total 5665
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 1641
telemt_me_reconnect_success_total 1635
telemt_me_reader_eof_total 2161
telemt_me_idle_close_by_peer_total 2161
telemt_me_route_drop_no_conn_total 14980
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 2
telemt_pool_force_close_total 70
telemt_pool_stale_pick_total 308
telemt_me_writer_removed_unexpected_total 2161
telemt_me_writer_restored_same_endpoint_total 1631
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 45361
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 387179644 (369.24 MB)
telemt_user_octets_to_client{user="hello"} 15644226692 (14.57 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 4091.4 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61809
telemt_connections_bad_total 435
telemt_handshake_timeouts_total 330
telemt_upstream_connect_attempt_total 6291
telemt_upstream_connect_success_total 6273
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 6281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 2066
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 2950
telemt_me_idle_close_by_peer_total 2949
telemt_me_route_drop_no_conn_total 21400
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 361
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 1
telemt_pool_force_close_total 81
telemt_pool_stale_pick_total 40
telemt_me_writer_removed_unexpected_total 2954
telemt_me_writer_restored_same_endpoint_total 2059
telemt_me_writer_removed_unexpected_minus_restored_total 895
telemt_user_connections_total{user="hello"} 58243
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 4503376736 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 23942232852 (22.30 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 74
```