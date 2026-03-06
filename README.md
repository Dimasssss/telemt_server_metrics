# Server Metrics 2026-03-06 19:47:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 5940.9 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142847
telemt_connections_bad_total 1425
telemt_handshake_timeouts_total 5230
telemt_upstream_connect_attempt_total 8853
telemt_upstream_connect_success_total 8761
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 8797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 283
telemt_me_reconnect_attempts_total 2817
telemt_me_reconnect_success_total 2802
telemt_me_reader_eof_total 3646
telemt_me_idle_close_by_peer_total 3646
telemt_me_route_drop_no_conn_total 58356
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 561
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 404
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 150
telemt_me_writer_removed_unexpected_total 3670
telemt_me_writer_restored_same_endpoint_total 2796
telemt_me_writer_removed_unexpected_minus_restored_total 874
telemt_user_connections_total{user="hello"} 124665
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 2059486208 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 42057081324 (39.17 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 5940.7 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52308
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 2400
telemt_upstream_connect_attempt_total 10545
telemt_upstream_connect_success_total 10544
telemt_upstream_connect_attempts_per_request{bucket="1"} 10544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 3647
telemt_me_reconnect_success_total 3642
telemt_me_reader_eof_total 4812
telemt_me_idle_close_by_peer_total 4810
telemt_me_route_drop_no_conn_total 18681
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 214
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 4812
telemt_me_writer_restored_same_endpoint_total 3640
telemt_me_writer_removed_unexpected_minus_restored_total 1172
telemt_user_connections_total{user="hello"} 45978
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 949576940 (905.59 MB)
telemt_user_octets_to_client{user="hello"} 13727423096 (12.78 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 5940.7 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94733
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 1132
telemt_upstream_connect_attempt_total 7286
telemt_upstream_connect_success_total 7228
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 7250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 1459
telemt_me_reconnect_success_total 1449
telemt_me_reader_eof_total 1947
telemt_me_idle_close_by_peer_total 1947
telemt_me_route_drop_no_conn_total 29817
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 455
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 3
telemt_pool_force_close_total 88
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 2003
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 88802
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 4143933388 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 25617743812 (23.86 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 5941.0 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113852
telemt_connections_bad_total 42578
telemt_handshake_timeouts_total 6694
telemt_upstream_connect_attempt_total 8509
telemt_upstream_connect_success_total 8476
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 8491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 165
telemt_me_reconnect_attempts_total 2603
telemt_me_reconnect_success_total 2594
telemt_me_reader_eof_total 3319
telemt_me_idle_close_by_peer_total 3319
telemt_me_route_drop_no_conn_total 21467
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 55
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_pool_stale_pick_total 397
telemt_me_writer_removed_unexpected_total 3321
telemt_me_writer_restored_same_endpoint_total 2590
telemt_me_writer_removed_unexpected_minus_restored_total 731
telemt_user_connections_total{user="hello"} 62381
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 822623152 (784.51 MB)
telemt_user_octets_to_client{user="hello"} 21261162812 (19.80 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 5939.6 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85826
telemt_connections_bad_total 441
telemt_handshake_timeouts_total 469
telemt_upstream_connect_attempt_total 8452
telemt_upstream_connect_success_total 8404
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 8416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 386
telemt_me_reconnect_attempts_total 2500
telemt_me_reconnect_success_total 2489
telemt_me_reader_eof_total 3460
telemt_me_idle_close_by_peer_total 3459
telemt_me_route_drop_no_conn_total 32610
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 472
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 2
telemt_pool_force_close_total 106
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 3496
telemt_me_writer_restored_same_endpoint_total 2487
telemt_me_writer_removed_unexpected_minus_restored_total 1009
telemt_user_connections_total{user="hello"} 81395
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 8374471616 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 30752149408 (28.64 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 61
```