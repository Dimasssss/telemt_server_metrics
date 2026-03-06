# Server Metrics 2026-03-06 22:26:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 15510.8 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254247
telemt_connections_bad_total 2242
telemt_handshake_timeouts_total 9119
telemt_upstream_connect_attempt_total 24963
telemt_upstream_connect_success_total 24768
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 24840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 1072
telemt_me_reconnect_attempts_total 7533
telemt_me_reconnect_success_total 7494
telemt_me_reader_eof_total 9864
telemt_me_idle_close_by_peer_total 9864
telemt_me_route_drop_no_conn_total 97054
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 821
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 581
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 167
telemt_me_writer_removed_unexpected_total 9972
telemt_me_writer_restored_same_endpoint_total 7488
telemt_me_writer_removed_unexpected_minus_restored_total 2484
telemt_user_connections_total{user="hello"} 229096
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 3479920728 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 93005451372 (86.62 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 15510.9 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102682
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 8561
telemt_upstream_connect_attempt_total 30901
telemt_upstream_connect_success_total 30900
telemt_upstream_connect_attempts_per_request{bucket="1"} 30900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 512
telemt_me_reconnect_attempts_total 10828
telemt_me_reconnect_success_total 10813
telemt_me_reader_eof_total 15187
telemt_me_idle_close_by_peer_total 15184
telemt_me_route_drop_no_conn_total 36930
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 657
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 483
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 7
telemt_pool_force_close_total 299
telemt_pool_stale_pick_total 37
telemt_me_writer_removed_unexpected_total 15187
telemt_me_writer_restored_same_endpoint_total 10811
telemt_me_writer_removed_unexpected_minus_restored_total 4376
telemt_user_connections_total{user="hello"} 88561
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 1337878816 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 29303751792 (27.29 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 15510.9 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197199
telemt_connections_bad_total 833
telemt_handshake_timeouts_total 3225
telemt_upstream_connect_attempt_total 24560
telemt_upstream_connect_success_total 24411
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 24454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1077
telemt_me_reconnect_attempts_total 7158
telemt_me_reconnect_success_total 7127
telemt_me_reader_eof_total 9589
telemt_me_idle_close_by_peer_total 9586
telemt_me_route_drop_no_conn_total 74260
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 890
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 670
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 8
telemt_pool_force_close_total 253
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 9694
telemt_me_writer_restored_same_endpoint_total 7120
telemt_me_writer_removed_unexpected_minus_restored_total 2574
telemt_user_connections_total{user="hello"} 182746
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 12611510536 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 55637920812 (51.82 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 15511.1 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196642
telemt_connections_bad_total 53917
telemt_handshake_timeouts_total 15935
telemt_upstream_connect_attempt_total 26487
telemt_upstream_connect_success_total 26414
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 26440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 516
telemt_me_reconnect_attempts_total 8752
telemt_me_reconnect_success_total 8734
telemt_me_reader_eof_total 11736
telemt_me_idle_close_by_peer_total 11735
telemt_me_route_drop_no_conn_total 50314
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 8
telemt_pool_force_close_total 271
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 11741
telemt_me_writer_restored_same_endpoint_total 8729
telemt_me_writer_removed_unexpected_minus_restored_total 3012
telemt_user_connections_total{user="hello"} 123416
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 1611968872 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 38032511392 (35.42 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 15509.6 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169266
telemt_connections_bad_total 458
telemt_handshake_timeouts_total 1258
telemt_upstream_connect_attempt_total 23775
telemt_upstream_connect_success_total 23643
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 23662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 812
telemt_me_reconnect_attempts_total 7078
telemt_me_reconnect_success_total 7049
telemt_me_reader_eof_total 9541
telemt_me_idle_close_by_peer_total 9540
telemt_me_route_drop_no_conn_total 59021
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 128
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 731
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 8
telemt_pool_force_close_total 295
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 9604
telemt_me_writer_restored_same_endpoint_total 7047
telemt_me_writer_removed_unexpected_minus_restored_total 2557
telemt_user_connections_total{user="hello"} 154866
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 9451210152 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 52068524900 (48.49 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 32
```