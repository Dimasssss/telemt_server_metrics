# Server Metrics 2026-03-06 04:58:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 23833.7 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179252
telemt_connections_bad_total 15970
telemt_handshake_timeouts_total 3141
telemt_upstream_connect_attempt_total 25139
telemt_upstream_connect_success_total 24930
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 24930
telemt_upstream_connect_attempts_per_request{bucket="2"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 9126
telemt_me_reconnect_success_total 9094
telemt_me_reader_eof_total 9413
telemt_me_idle_close_by_peer_total 9413
telemt_me_route_drop_no_conn_total 51995
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 515
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 9414
telemt_me_writer_restored_same_endpoint_total 9088
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 151812
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 3254509752 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 59034075316 (54.98 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 23829.1 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66265
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 909
telemt_upstream_connect_attempt_total 23491
telemt_upstream_connect_success_total 23489
telemt_upstream_connect_attempts_per_request{bucket="1"} 23489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 285
telemt_me_reconnect_attempts_total 6745
telemt_me_reconnect_success_total 6725
telemt_me_reader_eof_total 6875
telemt_me_idle_close_by_peer_total 6875
telemt_me_route_drop_no_conn_total 19584
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 271
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_pool_stale_pick_total 549
telemt_me_writer_removed_unexpected_total 6876
telemt_me_writer_restored_same_endpoint_total 6719
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 64048
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 614934408 (586.45 MB)
telemt_user_octets_to_client{user="hello"} 16665113228 (15.52 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 23826.4 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114566
telemt_connections_bad_total 1362
telemt_handshake_timeouts_total 2648
telemt_upstream_connect_attempt_total 22902
telemt_upstream_connect_success_total 22719
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 22719
telemt_upstream_connect_attempts_per_request{bucket="2"} 82
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 7116
telemt_me_reconnect_success_total 7091
telemt_me_reader_eof_total 7404
telemt_me_idle_close_by_peer_total 7404
telemt_me_route_drop_no_conn_total 32491
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 228
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 7409
telemt_me_writer_restored_same_endpoint_total 7083
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 107098
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 1041084316 (992.86 MB)
telemt_user_octets_to_client{user="hello"} 35589459916 (33.15 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 23823.2 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93460
telemt_connections_bad_total 4815
telemt_handshake_timeouts_total 5399
telemt_upstream_connect_attempt_total 16128
telemt_upstream_connect_success_total 16071
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 16071
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 3082
telemt_me_reconnect_success_total 3056
telemt_me_reader_eof_total 3164
telemt_me_idle_close_by_peer_total 3164
telemt_me_route_drop_no_conn_total 31919
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 253
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 3164
telemt_me_writer_restored_same_endpoint_total 3049
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 78732
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 1442625632 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 30512896404 (28.42 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 23822.0 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107303
telemt_connections_bad_total 1014
telemt_handshake_timeouts_total 630
telemt_upstream_connect_attempt_total 16368
telemt_upstream_connect_success_total 16329
telemt_upstream_connect_attempts_per_request{bucket="1"} 16329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 2841
telemt_me_reconnect_success_total 2829
telemt_me_reader_eof_total 2929
telemt_me_idle_close_by_peer_total 2928
telemt_me_route_drop_no_conn_total 36649
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 149
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 2933
telemt_me_writer_restored_same_endpoint_total 2822
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 103827
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 23525771908 (21.91 GB)
telemt_user_octets_to_client{user="hello"} 60440406964 (56.29 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 60
```