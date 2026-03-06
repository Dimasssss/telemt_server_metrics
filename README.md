# Server Metrics 2026-03-06 06:05:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 27826.4 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236353
telemt_connections_bad_total 16049
telemt_handshake_timeouts_total 3541
telemt_upstream_connect_attempt_total 28055
telemt_upstream_connect_success_total 27812
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 27812
telemt_upstream_connect_attempts_per_request{bucket="2"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 10011
telemt_me_reconnect_success_total 9972
telemt_me_reader_eof_total 10312
telemt_me_idle_close_by_peer_total 10312
telemt_me_route_drop_no_conn_total 76586
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 702
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 479
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10313
telemt_me_writer_restored_same_endpoint_total 9966
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 206654
telemt_user_connections_current{user="hello"} 885
telemt_user_octets_from_client{user="hello"} 5719279888 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 76659415116 (71.39 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 27821.6 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96394
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 6609
telemt_upstream_connect_attempt_total 24536
telemt_upstream_connect_success_total 24534
telemt_upstream_connect_attempts_per_request{bucket="1"} 24534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 6771
telemt_me_reconnect_success_total 6744
telemt_me_reader_eof_total 6895
telemt_me_idle_close_by_peer_total 6895
telemt_me_route_drop_no_conn_total 28029
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
telemt_user_connections_total{user="hello"} 87863
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 870024844 (829.72 MB)
telemt_user_octets_to_client{user="hello"} 29364356348 (27.35 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 27819.1 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169054
telemt_connections_bad_total 1559
telemt_handshake_timeouts_total 4077
telemt_upstream_connect_attempt_total 29918
telemt_upstream_connect_success_total 29710
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 29710
telemt_upstream_connect_attempts_per_request{bucket="2"} 94
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 354
telemt_me_reconnect_attempts_total 10468
telemt_me_reconnect_success_total 10433
telemt_me_reader_eof_total 10893
telemt_me_idle_close_by_peer_total 10893
telemt_me_route_drop_no_conn_total 48307
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 310
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 10906
telemt_me_writer_restored_same_endpoint_total 10411
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 149343
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 1483098568 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 49608041376 (46.20 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 27815.7 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130919
telemt_connections_bad_total 8548
telemt_handshake_timeouts_total 6100
telemt_upstream_connect_attempt_total 20748
telemt_upstream_connect_success_total 20680
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 20680
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 217
telemt_me_reconnect_attempts_total 4833
telemt_me_reconnect_success_total 4803
telemt_me_reader_eof_total 4971
telemt_me_idle_close_by_peer_total 4971
telemt_me_route_drop_no_conn_total 44883
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 327
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 9
telemt_pool_force_close_total 214
telemt_me_writer_removed_unexpected_total 4972
telemt_me_writer_restored_same_endpoint_total 4796
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 110812
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 1687878640 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 39872537900 (37.13 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 27814.6 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146560
telemt_connections_bad_total 2039
telemt_handshake_timeouts_total 861
telemt_upstream_connect_attempt_total 19118
telemt_upstream_connect_success_total 19075
telemt_upstream_connect_attempts_per_request{bucket="1"} 19075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 252
telemt_me_reconnect_attempts_total 3307
telemt_me_reconnect_success_total 3292
telemt_me_reader_eof_total 3402
telemt_me_idle_close_by_peer_total 3401
telemt_me_route_drop_no_conn_total 53785
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 296
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3410
telemt_me_writer_restored_same_endpoint_total 3285
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 141029
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 23986999796 (22.34 GB)
telemt_user_octets_to_client{user="hello"} 87346759224 (81.35 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 83
```