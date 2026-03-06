# Server Metrics 2026-03-06 03:16:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 17690.0 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121338
telemt_connections_bad_total 15918
telemt_handshake_timeouts_total 2322
telemt_upstream_connect_attempt_total 17768
telemt_upstream_connect_success_total 17606
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 17606
telemt_upstream_connect_attempts_per_request{bucket="2"} 76
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 5881
telemt_me_reconnect_success_total 5860
telemt_me_reader_eof_total 6046
telemt_me_idle_close_by_peer_total 6046
telemt_me_route_drop_no_conn_total 32810
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 328
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 2
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 6046
telemt_me_writer_restored_same_endpoint_total 5854
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 96395
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 1106879932 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 37829337552 (35.23 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 17685.4 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39918
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 488
telemt_upstream_connect_attempt_total 13304
telemt_upstream_connect_success_total 13301
telemt_upstream_connect_attempts_per_request{bucket="1"} 13301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 2187
telemt_me_reconnect_success_total 2177
telemt_me_reader_eof_total 2204
telemt_me_idle_close_by_peer_total 2204
telemt_me_route_drop_no_conn_total 11901
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 2205
telemt_me_writer_restored_same_endpoint_total 2171
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 38732
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 259098632 (247.10 MB)
telemt_user_octets_to_client{user="hello"} 9417309264 (8.77 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 17682.8 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72514
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 1539
telemt_upstream_connect_attempt_total 16557
telemt_upstream_connect_success_total 16417
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 16417
telemt_upstream_connect_attempts_per_request{bucket="2"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 4846
telemt_me_reconnect_success_total 4828
telemt_me_reader_eof_total 5050
telemt_me_idle_close_by_peer_total 5050
telemt_me_route_drop_no_conn_total 20165
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 5054
telemt_me_writer_restored_same_endpoint_total 4821
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 67697
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 668650580 (637.67 MB)
telemt_user_octets_to_client{user="hello"} 23372487144 (21.77 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 17679.4 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58322
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 3909
telemt_upstream_connect_attempt_total 12001
telemt_upstream_connect_success_total 11964
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 11964
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 130
telemt_me_reconnect_attempts_total 2467
telemt_me_reconnect_success_total 2451
telemt_me_reader_eof_total 2551
telemt_me_idle_close_by_peer_total 2551
telemt_me_route_drop_no_conn_total 22096
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2551
telemt_me_writer_restored_same_endpoint_total 2444
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 50910
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 447283444 (426.56 MB)
telemt_user_octets_to_client{user="hello"} 23970504048 (22.32 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 17678.4 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71046
telemt_connections_bad_total 869
telemt_handshake_timeouts_total 484
telemt_upstream_connect_attempt_total 10769
telemt_upstream_connect_success_total 10745
telemt_upstream_connect_attempts_per_request{bucket="1"} 10745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 1218
telemt_me_reconnect_success_total 1213
telemt_me_reader_eof_total 1240
telemt_me_idle_close_by_peer_total 1240
telemt_me_route_drop_no_conn_total 22374
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 75
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1240
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 68637
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 12110928744 (11.28 GB)
telemt_user_octets_to_client{user="hello"} 37912444960 (35.31 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 36
```