# Server Metrics 2026-03-04 12:28:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 55094.1 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 944907
telemt_connections_bad_total 12159
telemt_handshake_timeouts_total 14721
telemt_upstream_connect_attempt_total 32992
telemt_upstream_connect_success_total 32848
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 32848
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 367
telemt_me_reconnect_attempts_total 7096
telemt_me_reconnect_success_total 7047
telemt_me_reader_eof_total 7266
telemt_me_idle_close_by_peer_total 7266
telemt_me_route_drop_no_conn_total 343962
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1532
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 586
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7266
telemt_me_writer_restored_same_endpoint_total 7025
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 743892
telemt_user_connections_current{user="hello"} 838
telemt_user_octets_from_client{user="hello"} 7992604128 (7.44 GB)
telemt_user_octets_to_client{user="hello"} 230152674220 (214.35 GB)
telemt_user_unique_ips_current{user="hello"} 81
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 55090.4 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371295
telemt_connections_bad_total 3267
telemt_handshake_timeouts_total 28169
telemt_upstream_connect_attempt_total 101968
telemt_upstream_connect_success_total 100396
telemt_upstream_connect_fail_total 748
telemt_upstream_connect_attempts_per_request{bucket="1"} 100390
telemt_upstream_connect_attempts_per_request{bucket="2"} 754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 748
telemt_me_keepalive_timeout_total 1413
telemt_me_reconnect_attempts_total 57047
telemt_me_reconnect_success_total 56958
telemt_me_reader_eof_total 58395
telemt_me_idle_close_by_peer_total 58394
telemt_me_route_drop_no_conn_total 152210
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 689
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58475
telemt_me_writer_restored_same_endpoint_total 56933
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 280538
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 3740147664 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 89235007024 (83.11 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 55089.4 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707850
telemt_connections_bad_total 164602
telemt_handshake_timeouts_total 23075
telemt_upstream_connect_attempt_total 80267
telemt_upstream_connect_success_total 79783
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 79782
telemt_upstream_connect_attempts_per_request{bucket="2"} 233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 1043
telemt_me_reconnect_attempts_total 37330
telemt_me_reconnect_success_total 37237
telemt_me_reader_eof_total 39213
telemt_me_idle_close_by_peer_total 39209
telemt_me_route_drop_no_conn_total 263840
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 230
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1239
telemt_desync_full_logged_total 440
telemt_desync_suppressed_total 799
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 39225
telemt_me_writer_restored_same_endpoint_total 37215
telemt_me_writer_removed_unexpected_minus_restored_total 2010
telemt_user_connections_total{user="hello"} 492018
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 11419378420 (10.64 GB)
telemt_user_octets_to_client{user="hello"} 163104576384 (151.90 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 1766.7 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19713
telemt_connections_bad_total 1919
telemt_handshake_timeouts_total 542
telemt_upstream_connect_attempt_total 594
telemt_upstream_connect_success_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 199
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 24
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 6942
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 16969
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 186134516 (177.51 MB)
telemt_user_octets_to_client{user="hello"} 10454289600 (9.74 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 2125.9 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37045
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 750
telemt_upstream_connect_attempt_total 640
telemt_upstream_connect_success_total 635
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 635
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 37
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 11160
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 100
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_me_writer_removed_unexpected_total 18
telemt_me_writer_restored_same_endpoint_total 17
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 30718
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 334692448 (319.19 MB)
telemt_user_octets_to_client{user="hello"} 9103412392 (8.48 GB)
telemt_user_unique_ips_current{user="hello"} 53
```