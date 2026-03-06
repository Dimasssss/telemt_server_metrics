# Server Metrics 2026-03-06 07:06:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 31512.2 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305062
telemt_connections_bad_total 16126
telemt_handshake_timeouts_total 3894
telemt_upstream_connect_attempt_total 31451
telemt_upstream_connect_success_total 31156
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 31156
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 10903
telemt_me_reconnect_success_total 10857
telemt_me_reader_eof_total 11229
telemt_me_idle_close_by_peer_total 11229
telemt_me_route_drop_no_conn_total 105789
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1037
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 720
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 11231
telemt_me_writer_restored_same_endpoint_total 10851
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 268099
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 9273164244 (8.64 GB)
telemt_user_octets_to_client{user="hello"} 97874783412 (91.15 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 31507.6 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130004
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 14038
telemt_upstream_connect_attempt_total 25885
telemt_upstream_connect_success_total 25883
telemt_upstream_connect_attempts_per_request{bucket="1"} 25883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 310
telemt_me_reconnect_attempts_total 6793
telemt_me_reconnect_success_total 6764
telemt_me_reader_eof_total 6915
telemt_me_idle_close_by_peer_total 6915
telemt_me_route_drop_no_conn_total 38429
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 417
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 281
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 10
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6916
telemt_me_writer_restored_same_endpoint_total 6757
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 113491
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 1293275816 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 36663781972 (34.15 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 31505.1 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224081
telemt_connections_bad_total 1790
telemt_handshake_timeouts_total 6149
telemt_upstream_connect_attempt_total 36405
telemt_upstream_connect_success_total 36148
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 36148
telemt_upstream_connect_attempts_per_request{bucket="2"} 116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 515
telemt_me_reconnect_attempts_total 14112
telemt_me_reconnect_success_total 14072
telemt_me_reader_eof_total 14725
telemt_me_idle_close_by_peer_total 14723
telemt_me_route_drop_no_conn_total 67313
telemt_me_route_drop_channel_closed_total 1
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 439
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 157
telemt_me_writer_removed_unexpected_total 14753
telemt_me_writer_restored_same_endpoint_total 14050
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 689
telemt_user_connections_total{user="hello"} 199210
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 1999122676 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 63983642940 (59.59 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 31501.8 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174932
telemt_connections_bad_total 20279
telemt_handshake_timeouts_total 6721
telemt_upstream_connect_attempt_total 22187
telemt_upstream_connect_success_total 22112
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 22112
telemt_upstream_connect_attempts_per_request{bucket="2"} 36
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 240
telemt_me_reconnect_attempts_total 4890
telemt_me_reconnect_success_total 4857
telemt_me_reader_eof_total 5028
telemt_me_idle_close_by_peer_total 5028
telemt_me_route_drop_no_conn_total 55443
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 420
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 10
telemt_pool_force_close_total 244
telemt_me_writer_removed_unexpected_total 5029
telemt_me_writer_restored_same_endpoint_total 4850
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 141087
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 2032273976 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 47713212816 (44.44 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 31500.6 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188784
telemt_connections_bad_total 3279
telemt_handshake_timeouts_total 1075
telemt_upstream_connect_attempt_total 21122
telemt_upstream_connect_success_total 21074
telemt_upstream_connect_attempts_per_request{bucket="1"} 21074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 325
telemt_me_reconnect_attempts_total 3712
telemt_me_reconnect_success_total 3694
telemt_me_reader_eof_total 3812
telemt_me_idle_close_by_peer_total 3811
telemt_me_route_drop_no_conn_total 75120
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 420
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3827
telemt_me_writer_restored_same_endpoint_total 3687
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 180909
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 24422392384 (22.75 GB)
telemt_user_octets_to_client{user="hello"} 109167180404 (101.67 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 124
```