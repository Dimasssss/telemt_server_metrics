# Server Metrics 2026-03-06 04:38:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 22604.7 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164488
telemt_connections_bad_total 15966
telemt_handshake_timeouts_total 2934
telemt_upstream_connect_attempt_total 23923
telemt_upstream_connect_success_total 23738
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 23738
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 256
telemt_me_reconnect_attempts_total 8768
telemt_me_reconnect_success_total 8738
telemt_me_reader_eof_total 9051
telemt_me_idle_close_by_peer_total 9051
telemt_me_route_drop_no_conn_total 47000
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 455
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 9052
telemt_me_writer_restored_same_endpoint_total 8732
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 137563
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 3114980288 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 53163399548 (49.51 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 22600.0 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59595
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 817
telemt_upstream_connect_attempt_total 21614
telemt_upstream_connect_success_total 21612
telemt_upstream_connect_attempts_per_request{bucket="1"} 21612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 258
telemt_me_reconnect_attempts_total 5783
telemt_me_reconnect_success_total 5765
telemt_me_reader_eof_total 5886
telemt_me_idle_close_by_peer_total 5886
telemt_me_route_drop_no_conn_total 17743
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 226
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5887
telemt_me_writer_restored_same_endpoint_total 5759
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 57562
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 473285536 (451.36 MB)
telemt_user_octets_to_client{user="hello"} 14336061692 (13.35 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 22597.4 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102797
telemt_connections_bad_total 1143
telemt_handshake_timeouts_total 2328
telemt_upstream_connect_attempt_total 21273
telemt_upstream_connect_success_total 21096
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 21096
telemt_upstream_connect_attempts_per_request{bucket="2"} 79
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 6479
telemt_me_reconnect_success_total 6455
telemt_me_reader_eof_total 6748
telemt_me_idle_close_by_peer_total 6748
telemt_me_route_drop_no_conn_total 29125
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 189
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6752
telemt_me_writer_restored_same_endpoint_total 6447
telemt_me_writer_removed_unexpected_minus_restored_total 305
telemt_user_connections_total{user="hello"} 96116
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 946418316 (902.57 MB)
telemt_user_octets_to_client{user="hello"} 32043080184 (29.84 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 22594.1 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84984
telemt_connections_bad_total 3702
telemt_handshake_timeouts_total 4641
telemt_upstream_connect_attempt_total 14913
telemt_upstream_connect_success_total 14862
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 14862
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 2821
telemt_me_reconnect_success_total 2797
telemt_me_reader_eof_total 2903
telemt_me_idle_close_by_peer_total 2903
telemt_me_route_drop_no_conn_total 28971
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 223
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 2903
telemt_me_writer_restored_same_endpoint_total 2790
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 72315
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 1359608508 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 29092695956 (27.09 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 22593.0 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98229
telemt_connections_bad_total 1012
telemt_handshake_timeouts_total 599
telemt_upstream_connect_attempt_total 15729
telemt_upstream_connect_success_total 15693
telemt_upstream_connect_attempts_per_request{bucket="1"} 15693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 2771
telemt_me_reconnect_success_total 2760
telemt_me_reader_eof_total 2858
telemt_me_idle_close_by_peer_total 2857
telemt_me_route_drop_no_conn_total 32833
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_me_writer_removed_unexpected_total 2862
telemt_me_writer_restored_same_endpoint_total 2753
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 94957
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 23413453364 (21.81 GB)
telemt_user_octets_to_client{user="hello"} 53741755172 (50.05 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 53
```