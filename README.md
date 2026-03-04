# Server Metrics 2026-03-04 17:00:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 71388.6 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1385793
telemt_connections_bad_total 19747
telemt_handshake_timeouts_total 23249
telemt_upstream_connect_attempt_total 41889
telemt_upstream_connect_success_total 41701
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 41701
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 9219
telemt_me_reconnect_success_total 9149
telemt_me_reader_eof_total 9472
telemt_me_idle_close_by_peer_total 9471
telemt_me_route_drop_no_conn_total 548729
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 279
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3035
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 2077
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 1125
telemt_desync_frames_bucket_total{bucket="gt_10"} 1042
telemt_pool_swap_total 18
telemt_pool_force_close_total 792
telemt_pool_stale_pick_total 296
telemt_me_writer_removed_unexpected_total 9473
telemt_me_writer_restored_same_endpoint_total 9127
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 1134056
telemt_user_connections_current{user="hello"} 1096
telemt_user_octets_from_client{user="hello"} 15145449464 (14.11 GB)
telemt_user_octets_to_client{user="hello"} 380764476032 (354.61 GB)
telemt_user_unique_ips_current{user="hello"} 120
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 71384.8 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532676
telemt_connections_bad_total 7083
telemt_handshake_timeouts_total 30871
telemt_upstream_connect_attempt_total 125544
telemt_upstream_connect_success_total 123696
telemt_upstream_connect_fail_total 886
telemt_upstream_connect_attempts_per_request{bucket="1"} 123690
telemt_upstream_connect_attempts_per_request{bucket="2"} 892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 886
telemt_me_keepalive_timeout_total 1646
telemt_me_reconnect_attempts_total 67898
telemt_me_reconnect_success_total 67791
telemt_me_reader_eof_total 69531
telemt_me_idle_close_by_peer_total 69530
telemt_me_route_drop_no_conn_total 226613
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 297
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1340
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 925
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 525
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 195
telemt_me_writer_removed_unexpected_total 69611
telemt_me_writer_restored_same_endpoint_total 67765
telemt_me_writer_removed_unexpected_minus_restored_total 1846
telemt_user_connections_total{user="hello"} 427917
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 6301933240 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 133953881436 (124.75 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 71383.9 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1067875
telemt_connections_bad_total 211339
telemt_handshake_timeouts_total 30586
telemt_upstream_connect_attempt_total 91708
telemt_upstream_connect_success_total 91062
telemt_upstream_connect_fail_total 313
telemt_upstream_connect_attempts_per_request{bucket="1"} 91061
telemt_upstream_connect_attempts_per_request{bucket="2"} 314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 313
telemt_me_keepalive_timeout_total 1187
telemt_me_reconnect_attempts_total 40421
telemt_me_reconnect_success_total 40311
telemt_me_reader_eof_total 42437
telemt_me_idle_close_by_peer_total 42432
telemt_me_route_drop_no_conn_total 395817
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_shadow_rotate_total 294
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2248
telemt_desync_full_logged_total 746
telemt_desync_suppressed_total 1502
telemt_desync_frames_bucket_total{bucket="1_2"} 670
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 842
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42450
telemt_me_writer_restored_same_endpoint_total 40289
telemt_me_writer_removed_unexpected_minus_restored_total 2161
telemt_user_connections_total{user="hello"} 774630
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 14793847728 (13.78 GB)
telemt_user_octets_to_client{user="hello"} 267870606628 (249.47 GB)
telemt_user_unique_ips_current{user="hello"} 73
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 18060.9 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294792
telemt_connections_bad_total 37207
telemt_handshake_timeouts_total 6718
telemt_upstream_connect_attempt_total 7182
telemt_upstream_connect_success_total 7182
telemt_upstream_connect_attempts_per_request{bucket="1"} 7182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3178
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 937
telemt_me_reconnect_success_total 943
telemt_me_reader_eof_total 954
telemt_me_idle_close_by_peer_total 954
telemt_me_route_drop_no_conn_total 101558
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 326
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 5
telemt_pool_force_close_total 189
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_restored_same_endpoint_total 922
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 240781
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 3018883192 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 88911924948 (82.81 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 18420.5 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312803
telemt_connections_bad_total 3079
telemt_handshake_timeouts_total 4210
telemt_upstream_connect_attempt_total 9127
telemt_upstream_connect_success_total 9078
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 9078
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 1507
telemt_me_reconnect_success_total 1508
telemt_me_reader_eof_total 1541
telemt_me_idle_close_by_peer_total 1541
telemt_me_route_drop_no_conn_total 128681
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 577
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1541
telemt_me_writer_restored_same_endpoint_total 1487
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 272411
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 4675799712 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 81871931092 (76.25 GB)
telemt_user_unique_ips_current{user="hello"} 50
```