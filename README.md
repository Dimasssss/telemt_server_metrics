# Server Metrics 2026-03-04 13:50:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 60014.3 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082226
telemt_connections_bad_total 13917
telemt_handshake_timeouts_total 18349
telemt_upstream_connect_attempt_total 35711
telemt_upstream_connect_success_total 35549
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 35549
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 399
telemt_me_reconnect_attempts_total 7600
telemt_me_reconnect_success_total 7543
telemt_me_reader_eof_total 7778
telemt_me_idle_close_by_peer_total 7777
telemt_me_route_drop_no_conn_total 391054
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 236
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 530
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 621
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7778
telemt_me_writer_restored_same_endpoint_total 7521
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 856396
telemt_user_connections_current{user="hello"} 1073
telemt_user_octets_from_client{user="hello"} 9760634240 (9.09 GB)
telemt_user_octets_to_client{user="hello"} 288044993608 (268.26 GB)
telemt_user_unique_ips_current{user="hello"} 90
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 60010.7 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418167
telemt_connections_bad_total 3562
telemt_handshake_timeouts_total 29215
telemt_upstream_connect_attempt_total 107541
telemt_upstream_connect_success_total 105927
telemt_upstream_connect_fail_total 769
telemt_upstream_connect_attempts_per_request{bucket="1"} 105921
telemt_upstream_connect_attempts_per_request{bucket="2"} 775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 769
telemt_me_keepalive_timeout_total 1461
telemt_me_reconnect_attempts_total 59015
telemt_me_reconnect_success_total 58921
telemt_me_reader_eof_total 60436
telemt_me_idle_close_by_peer_total 60435
telemt_me_route_drop_no_conn_total 169228
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 814
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 560
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 60516
telemt_me_writer_restored_same_endpoint_total 58896
telemt_me_writer_removed_unexpected_minus_restored_total 1620
telemt_user_connections_total{user="hello"} 323320
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 4161076600 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 102850160948 (95.79 GB)
telemt_user_unique_ips_current{user="hello"} 53
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 60009.7 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818697
telemt_connections_bad_total 178383
telemt_handshake_timeouts_total 29021
telemt_upstream_connect_attempt_total 83114
telemt_upstream_connect_success_total 82597
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 82596
telemt_upstream_connect_attempts_per_request{bucket="2"} 250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 1086
telemt_me_reconnect_attempts_total 37949
telemt_me_reconnect_success_total 37851
telemt_me_reader_eof_total 39845
telemt_me_idle_close_by_peer_total 39841
telemt_me_route_drop_no_conn_total 299997
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1648
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1090
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 530
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39857
telemt_me_writer_restored_same_endpoint_total 37829
telemt_me_writer_removed_unexpected_minus_restored_total 2028
telemt_user_connections_total{user="hello"} 573912
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 12187668992 (11.35 GB)
telemt_user_octets_to_client{user="hello"} 195115830176 (181.72 GB)
telemt_user_unique_ips_current{user="hello"} 71
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 6686.9 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82236
telemt_connections_bad_total 7885
telemt_handshake_timeouts_total 1563
telemt_upstream_connect_attempt_total 2943
telemt_upstream_connect_success_total 2943
telemt_upstream_connect_attempts_per_request{bucket="1"} 2943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1126
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 358
telemt_me_reconnect_success_total 374
telemt_me_reader_eof_total 363
telemt_me_idle_close_by_peer_total 363
telemt_me_route_drop_no_conn_total 29143
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 363
telemt_me_writer_restored_same_endpoint_total 353
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 71579
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 1227133452 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 45529587332 (42.40 GB)
telemt_user_unique_ips_current{user="hello"} 53
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 7046.0 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124222
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 2069
telemt_upstream_connect_attempt_total 4762
telemt_upstream_connect_success_total 4745
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 4745
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 1203
telemt_me_reconnect_success_total 1214
telemt_me_reader_eof_total 1237
telemt_me_idle_close_by_peer_total 1237
telemt_me_route_drop_no_conn_total 43066
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 339
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 1237
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 107041
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 1198999572 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 29865365144 (27.81 GB)
telemt_user_unique_ips_current{user="hello"} 49
```