# Server Metrics 2026-03-06 06:46:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 30283.2 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278254
telemt_connections_bad_total 16102
telemt_handshake_timeouts_total 3786
telemt_upstream_connect_attempt_total 30126
telemt_upstream_connect_success_total 29860
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 29860
telemt_upstream_connect_attempts_per_request{bucket="2"} 120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 307
telemt_me_reconnect_attempts_total 10507
telemt_me_reconnect_success_total 10465
telemt_me_reader_eof_total 10817
telemt_me_idle_close_by_peer_total 10817
telemt_me_route_drop_no_conn_total 96475
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 925
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10819
telemt_me_writer_restored_same_endpoint_total 10459
telemt_me_writer_removed_unexpected_minus_restored_total 360
telemt_user_connections_total{user="hello"} 246571
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 8801078180 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 90069364732 (83.88 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 30278.7 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118100
telemt_connections_bad_total 166
telemt_handshake_timeouts_total 11982
telemt_upstream_connect_attempt_total 25258
telemt_upstream_connect_success_total 25256
telemt_upstream_connect_attempts_per_request{bucket="1"} 25256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 301
telemt_me_reconnect_attempts_total 6777
telemt_me_reconnect_success_total 6750
telemt_me_reader_eof_total 6901
telemt_me_idle_close_by_peer_total 6901
telemt_me_route_drop_no_conn_total 33616
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 387
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 10
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6902
telemt_me_writer_restored_same_endpoint_total 6743
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 103845
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 1144514612 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 34360863736 (32.00 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 30276.1 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199057
telemt_connections_bad_total 1765
telemt_handshake_timeouts_total 4873
telemt_upstream_connect_attempt_total 35217
telemt_upstream_connect_success_total 34964
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 34964
telemt_upstream_connect_attempts_per_request{bucket="2"} 115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 490
telemt_me_reconnect_attempts_total 13388
telemt_me_reconnect_success_total 13347
telemt_me_reader_eof_total 13973
telemt_me_idle_close_by_peer_total 13971
telemt_me_route_drop_no_conn_total 60271
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 373
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 251
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 14000
telemt_me_writer_restored_same_endpoint_total 13325
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 176991
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 1816938196 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 58583292236 (54.56 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 30272.6 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159983
telemt_connections_bad_total 16335
telemt_handshake_timeouts_total 6465
telemt_upstream_connect_attempt_total 21726
telemt_upstream_connect_success_total 21653
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 21653
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 233
telemt_me_reconnect_attempts_total 4883
telemt_me_reconnect_success_total 4851
telemt_me_reader_eof_total 5021
telemt_me_idle_close_by_peer_total 5021
telemt_me_route_drop_no_conn_total 51974
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 391
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 10
telemt_pool_force_close_total 244
telemt_me_writer_removed_unexpected_total 5022
telemt_me_writer_restored_same_endpoint_total 4844
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 130849
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 1916503568 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 44176796908 (41.14 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 30271.6 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173032
telemt_connections_bad_total 3278
telemt_handshake_timeouts_total 989
telemt_upstream_connect_attempt_total 20684
telemt_upstream_connect_success_total 20637
telemt_upstream_connect_attempts_per_request{bucket="1"} 20637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 317
telemt_me_reconnect_attempts_total 3701
telemt_me_reconnect_success_total 3685
telemt_me_reader_eof_total 3803
telemt_me_idle_close_by_peer_total 3802
telemt_me_route_drop_no_conn_total 66031
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 379
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3818
telemt_me_writer_restored_same_endpoint_total 3678
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 165531
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 24284557236 (22.62 GB)
telemt_user_octets_to_client{user="hello"} 101301851548 (94.34 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 93
```