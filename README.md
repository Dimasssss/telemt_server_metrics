# Server Metrics 2026-03-06 19:21:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 4401.3 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110322
telemt_connections_bad_total 1361
telemt_handshake_timeouts_total 3514
telemt_upstream_connect_attempt_total 5144
telemt_upstream_connect_success_total 5077
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 217
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 1340
telemt_me_reader_eof_total 1655
telemt_me_idle_close_by_peer_total 1655
telemt_me_route_drop_no_conn_total 42798
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 468
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 338
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 142
telemt_me_writer_removed_unexpected_total 1675
telemt_me_writer_restored_same_endpoint_total 1334
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 98164
telemt_user_connections_current{user="hello"} 815
telemt_user_octets_from_client{user="hello"} 1703056344 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 32144322332 (29.94 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 4401.2 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39082
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 2286
telemt_upstream_connect_attempt_total 7786
telemt_upstream_connect_success_total 7784
telemt_upstream_connect_attempts_per_request{bucket="1"} 7784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 2745
telemt_me_reconnect_success_total 2741
telemt_me_reader_eof_total 3610
telemt_me_idle_close_by_peer_total 3610
telemt_me_route_drop_no_conn_total 14692
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 3610
telemt_me_writer_restored_same_endpoint_total 2739
telemt_me_writer_removed_unexpected_minus_restored_total 871
telemt_user_connections_total{user="hello"} 35497
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 402973996 (384.31 MB)
telemt_user_octets_to_client{user="hello"} 10273801452 (9.57 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 4401.3 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72521
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 897
telemt_upstream_connect_attempt_total 4796
telemt_upstream_connect_success_total 4779
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 881
telemt_me_reconnect_success_total 880
telemt_me_reader_eof_total 1145
telemt_me_idle_close_by_peer_total 1145
telemt_me_route_drop_no_conn_total 23087
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 372
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 3
telemt_pool_force_close_total 88
telemt_pool_stale_pick_total 92
telemt_me_writer_removed_unexpected_total 1147
telemt_me_writer_restored_same_endpoint_total 873
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 67346
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 2808592364 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 17680663844 (16.47 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 4401.5 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91678
telemt_connections_bad_total 37664
telemt_handshake_timeouts_total 4064
telemt_upstream_connect_attempt_total 5966
telemt_upstream_connect_success_total 5948
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 1683
telemt_me_reconnect_success_total 1677
telemt_me_reader_eof_total 2207
telemt_me_idle_close_by_peer_total 2207
telemt_me_route_drop_no_conn_total 15861
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 55
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 70
telemt_pool_stale_pick_total 308
telemt_me_writer_removed_unexpected_total 2207
telemt_me_writer_restored_same_endpoint_total 1673
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 48170
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 407132476 (388.27 MB)
telemt_user_octets_to_client{user="hello"} 16330097876 (15.21 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 4400.1 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65650
telemt_connections_bad_total 438
telemt_handshake_timeouts_total 346
telemt_upstream_connect_attempt_total 6525
telemt_upstream_connect_success_total 6507
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 6515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 2076
telemt_me_reconnect_success_total 2071
telemt_me_reader_eof_total 2962
telemt_me_idle_close_by_peer_total 2961
telemt_me_route_drop_no_conn_total 22708
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 382
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 1
telemt_pool_force_close_total 81
telemt_pool_stale_pick_total 65
telemt_me_writer_removed_unexpected_total 2966
telemt_me_writer_restored_same_endpoint_total 2069
telemt_me_writer_removed_unexpected_minus_restored_total 897
telemt_user_connections_total{user="hello"} 61955
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 7539089596 (7.02 GB)
telemt_user_octets_to_client{user="hello"} 24898930012 (23.19 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 67
```