# Server Metrics 2026-03-06 05:29:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 25676.5 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202620
telemt_connections_bad_total 16016
telemt_handshake_timeouts_total 3255
telemt_upstream_connect_attempt_total 27037
telemt_upstream_connect_success_total 26824
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 26824
telemt_upstream_connect_attempts_per_request{bucket="2"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10357
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 9873
telemt_me_reconnect_success_total 9837
telemt_me_reader_eof_total 10176
telemt_me_idle_close_by_peer_total 10176
telemt_me_route_drop_no_conn_total 62837
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 618
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10177
telemt_me_writer_restored_same_endpoint_total 9831
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 174543
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 4514062224 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 67567293824 (62.93 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 25671.9 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78699
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 2640
telemt_upstream_connect_attempt_total 24059
telemt_upstream_connect_success_total 24057
telemt_upstream_connect_attempts_per_request{bucket="1"} 24057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 290
telemt_me_reconnect_attempts_total 6758
telemt_me_reconnect_success_total 6736
telemt_me_reader_eof_total 6886
telemt_me_idle_close_by_peer_total 6886
telemt_me_route_drop_no_conn_total 23242
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 291
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 8
telemt_pool_force_close_total 150
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6887
telemt_me_writer_restored_same_endpoint_total 6730
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 74431
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 711196020 (678.25 MB)
telemt_user_octets_to_client{user="hello"} 22267388716 (20.74 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 25669.2 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134012
telemt_connections_bad_total 1445
telemt_handshake_timeouts_total 3212
telemt_upstream_connect_attempt_total 25878
telemt_upstream_connect_success_total 25687
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 25687
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 313
telemt_me_reconnect_attempts_total 8430
telemt_me_reconnect_success_total 8401
telemt_me_reader_eof_total 8763
telemt_me_idle_close_by_peer_total 8763
telemt_me_route_drop_no_conn_total 38862
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 262
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 179
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 8768
telemt_me_writer_restored_same_endpoint_total 8393
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 124858
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 1161455588 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 42393770340 (39.48 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 25666.0 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108053
telemt_connections_bad_total 6625
telemt_handshake_timeouts_total 5639
telemt_upstream_connect_attempt_total 18521
telemt_upstream_connect_success_total 18456
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 18456
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 198
telemt_me_reconnect_attempts_total 3881
telemt_me_reconnect_success_total 3853
telemt_me_reader_eof_total 3982
telemt_me_idle_close_by_peer_total 3982
telemt_me_route_drop_no_conn_total 37670
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 269
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 8
telemt_pool_force_close_total 169
telemt_me_writer_removed_unexpected_total 3982
telemt_me_writer_restored_same_endpoint_total 3846
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 91096
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 1525333996 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 34606813028 (32.23 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 25664.9 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123286
telemt_connections_bad_total 1028
telemt_handshake_timeouts_total 696
telemt_upstream_connect_attempt_total 17187
telemt_upstream_connect_success_total 17147
telemt_upstream_connect_attempts_per_request{bucket="1"} 17147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 2904
telemt_me_reconnect_success_total 2889
telemt_me_reader_eof_total 2992
telemt_me_idle_close_by_peer_total 2991
telemt_me_route_drop_no_conn_total 43372
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 182
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 2996
telemt_me_writer_restored_same_endpoint_total 2882
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 119424
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 23746258848 (22.12 GB)
telemt_user_octets_to_client{user="hello"} 72832293308 (67.83 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 57
```