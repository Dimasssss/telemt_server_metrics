# Server Metrics 2026-03-06 04:33:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 22297.6 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160939
telemt_connections_bad_total 15966
telemt_handshake_timeouts_total 2897
telemt_upstream_connect_attempt_total 23705
telemt_upstream_connect_success_total 23522
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 23522
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 255
telemt_me_reconnect_attempts_total 8729
telemt_me_reconnect_success_total 8699
telemt_me_reader_eof_total 9013
telemt_me_idle_close_by_peer_total 9013
telemt_me_route_drop_no_conn_total 45700
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 393
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 254
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 9013
telemt_me_writer_restored_same_endpoint_total 8693
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 134129
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 3082238980 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 51812489448 (48.25 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 22293.0 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57859
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 795
telemt_upstream_connect_attempt_total 21000
telemt_upstream_connect_success_total 20998
telemt_upstream_connect_attempts_per_request{bucket="1"} 20998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 5487
telemt_me_reconnect_success_total 5469
telemt_me_reader_eof_total 5581
telemt_me_idle_close_by_peer_total 5581
telemt_me_route_drop_no_conn_total 17338
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 211
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5582
telemt_me_writer_restored_same_endpoint_total 5463
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 55873
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 459397900 (438.12 MB)
telemt_user_octets_to_client{user="hello"} 14142473080 (13.17 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 22290.3 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99370
telemt_connections_bad_total 984
telemt_handshake_timeouts_total 1872
telemt_upstream_connect_attempt_total 20946
telemt_upstream_connect_success_total 20770
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 20770
telemt_upstream_connect_attempts_per_request{bucket="2"} 79
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 6367
telemt_me_reconnect_success_total 6343
telemt_me_reader_eof_total 6632
telemt_me_idle_close_by_peer_total 6632
telemt_me_route_drop_no_conn_total 28309
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 185
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6636
telemt_me_writer_restored_same_endpoint_total 6335
telemt_me_writer_removed_unexpected_minus_restored_total 301
telemt_user_connections_total{user="hello"} 93378
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 933070336 (889.85 MB)
telemt_user_octets_to_client{user="hello"} 31457490384 (29.30 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 22286.9 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83172
telemt_connections_bad_total 3427
telemt_handshake_timeouts_total 4600
telemt_upstream_connect_attempt_total 14714
telemt_upstream_connect_success_total 14667
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 14667
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 2806
telemt_me_reconnect_success_total 2783
telemt_me_reader_eof_total 2888
telemt_me_idle_close_by_peer_total 2888
telemt_me_route_drop_no_conn_total 28423
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 223
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 2888
telemt_me_writer_restored_same_endpoint_total 2776
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 70845
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 1352593856 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 28700493644 (26.73 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 22285.9 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96013
telemt_connections_bad_total 1011
telemt_handshake_timeouts_total 599
telemt_upstream_connect_attempt_total 15578
telemt_upstream_connect_success_total 15543
telemt_upstream_connect_attempts_per_request{bucket="1"} 15543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 2771
telemt_me_reconnect_success_total 2760
telemt_me_reader_eof_total 2858
telemt_me_idle_close_by_peer_total 2857
telemt_me_route_drop_no_conn_total 32201
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 121
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_me_writer_removed_unexpected_total 2862
telemt_me_writer_restored_same_endpoint_total 2753
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 92782
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 23241123112 (21.64 GB)
telemt_user_octets_to_client{user="hello"} 52527901420 (48.92 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 50
```