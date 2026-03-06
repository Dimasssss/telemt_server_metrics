# Server Metrics 2026-03-06 06:20:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 28747.7 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250839
telemt_connections_bad_total 16076
telemt_handshake_timeouts_total 3647
telemt_upstream_connect_attempt_total 28815
telemt_upstream_connect_success_total 28567
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 28567
telemt_upstream_connect_attempts_per_request{bucket="2"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 294
telemt_me_reconnect_attempts_total 10207
telemt_me_reconnect_success_total 10168
telemt_me_reader_eof_total 10514
telemt_me_idle_close_by_peer_total 10514
telemt_me_route_drop_no_conn_total 86574
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 743
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 505
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10516
telemt_me_writer_restored_same_endpoint_total 10162
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 220454
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 6422888564 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 80671936176 (75.13 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 28743.0 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104647
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 8871
telemt_upstream_connect_attempt_total 24872
telemt_upstream_connect_success_total 24870
telemt_upstream_connect_attempts_per_request{bucket="1"} 24870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 6775
telemt_me_reconnect_success_total 6747
telemt_me_reader_eof_total 6898
telemt_me_idle_close_by_peer_total 6898
telemt_me_route_drop_no_conn_total 30252
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 339
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 230
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 9
telemt_pool_force_close_total 175
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6899
telemt_me_writer_restored_same_endpoint_total 6741
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 93720
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 935001832 (891.69 MB)
telemt_user_octets_to_client{user="hello"} 31678178724 (29.50 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 28740.5 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179285
telemt_connections_bad_total 1587
telemt_handshake_timeouts_total 4371
telemt_upstream_connect_attempt_total 31793
telemt_upstream_connect_success_total 31580
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 31580
telemt_upstream_connect_attempts_per_request{bucket="2"} 96
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 11476
telemt_me_reconnect_success_total 11441
telemt_me_reader_eof_total 11941
telemt_me_idle_close_by_peer_total 11940
telemt_me_route_drop_no_conn_total 52861
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 332
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 11967
telemt_me_writer_restored_same_endpoint_total 11419
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 159139
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 1568960508 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 52856739196 (49.23 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 28736.9 (7h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142402
telemt_connections_bad_total 11424
telemt_handshake_timeouts_total 6339
telemt_upstream_connect_attempt_total 21010
telemt_upstream_connect_success_total 20939
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 20939
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4836
telemt_me_reconnect_success_total 4805
telemt_me_reader_eof_total 4974
telemt_me_idle_close_by_peer_total 4974
telemt_me_route_drop_no_conn_total 47600
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 331
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 9
telemt_pool_force_close_total 214
telemt_me_writer_removed_unexpected_total 4975
telemt_me_writer_restored_same_endpoint_total 4798
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 118758
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 1818795632 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 41406108048 (38.56 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 28736.0 (7h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156639
telemt_connections_bad_total 3274
telemt_handshake_timeouts_total 888
telemt_upstream_connect_attempt_total 20211
telemt_upstream_connect_success_total 20164
telemt_upstream_connect_attempts_per_request{bucket="1"} 20164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 3636
telemt_me_reconnect_success_total 3620
telemt_me_reader_eof_total 3734
telemt_me_idle_close_by_peer_total 3733
telemt_me_route_drop_no_conn_total 58563
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 322
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3749
telemt_me_writer_restored_same_endpoint_total 3613
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 149614
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 24076281912 (22.42 GB)
telemt_user_octets_to_client{user="hello"} 93137423668 (86.74 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 71
```