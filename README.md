# Server Metrics 2026-03-04 12:49:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 56323.8 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 980920
telemt_connections_bad_total 12597
telemt_handshake_timeouts_total 15680
telemt_upstream_connect_attempt_total 33473
telemt_upstream_connect_success_total 33329
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 33329
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 375
telemt_me_reconnect_attempts_total 7116
telemt_me_reconnect_success_total 7066
telemt_me_reader_eof_total 7286
telemt_me_idle_close_by_peer_total 7286
telemt_me_route_drop_no_conn_total 354060
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1565
telemt_desync_full_logged_total 531
telemt_desync_suppressed_total 1034
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 518
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7286
telemt_me_writer_restored_same_endpoint_total 7044
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 771066
telemt_user_connections_current{user="hello"} 1000
telemt_user_octets_from_client{user="hello"} 8248229472 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 242379823480 (225.73 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 56320.1 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383895
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 28500
telemt_upstream_connect_attempt_total 102835
telemt_upstream_connect_success_total 101245
telemt_upstream_connect_fail_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 101239
telemt_upstream_connect_attempts_per_request{bucket="2"} 763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 757
telemt_me_keepalive_timeout_total 1418
telemt_me_reconnect_attempts_total 57214
telemt_me_reconnect_success_total 57124
telemt_me_reader_eof_total 58563
telemt_me_idle_close_by_peer_total 58562
telemt_me_route_drop_no_conn_total 156672
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 754
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 519
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 319
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58643
telemt_me_writer_restored_same_endpoint_total 57099
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 292452
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 3895851656 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 93539573256 (87.12 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 56318.9 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737034
telemt_connections_bad_total 168078
telemt_handshake_timeouts_total 24296
telemt_upstream_connect_attempt_total 81238
telemt_upstream_connect_success_total 80745
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 80744
telemt_upstream_connect_attempts_per_request{bucket="2"} 238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 1057
telemt_me_reconnect_attempts_total 37644
telemt_me_reconnect_success_total 37550
telemt_me_reader_eof_total 39539
telemt_me_idle_close_by_peer_total 39535
telemt_me_route_drop_no_conn_total 272284
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 234
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1326
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 860
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 440
telemt_desync_frames_bucket_total{bucket="gt_10"} 495
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39551
telemt_me_writer_restored_same_endpoint_total 37528
telemt_me_writer_removed_unexpected_minus_restored_total 2023
telemt_user_connections_total{user="hello"} 513033
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 11584977072 (10.79 GB)
telemt_user_octets_to_client{user="hello"} 169217306256 (157.60 GB)
telemt_user_unique_ips_current{user="hello"} 72
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 2996.3 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35228
telemt_connections_bad_total 3838
telemt_handshake_timeouts_total 663
telemt_upstream_connect_attempt_total 1191
telemt_upstream_connect_success_total 1191
telemt_upstream_connect_attempts_per_request{bucket="1"} 1191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 454
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 88
telemt_me_reconnect_success_total 108
telemt_me_reader_eof_total 88
telemt_me_idle_close_by_peer_total 88
telemt_me_route_drop_no_conn_total 12128
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 21
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 88
telemt_me_writer_restored_same_endpoint_total 87
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 30200
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 464379568 (442.87 MB)
telemt_user_octets_to_client{user="hello"} 20168790676 (18.78 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 3355.6 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61262
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 1007
telemt_upstream_connect_attempt_total 1327
telemt_upstream_connect_success_total 1318
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1318
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 79
telemt_me_reconnect_success_total 93
telemt_me_reader_eof_total 74
telemt_me_idle_close_by_peer_total 74
telemt_me_route_drop_no_conn_total 18579
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 175
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_me_writer_removed_unexpected_total 74
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 51657
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 603932140 (575.95 MB)
telemt_user_octets_to_client{user="hello"} 15330513180 (14.28 GB)
telemt_user_unique_ips_current{user="hello"} 46
```