# Server Metrics 2026-03-04 12:39:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 55708.9 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964929
telemt_connections_bad_total 12160
telemt_handshake_timeouts_total 15264
telemt_upstream_connect_attempt_total 33208
telemt_upstream_connect_success_total 33064
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 33064
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14784
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 372
telemt_me_reconnect_attempts_total 7100
telemt_me_reconnect_success_total 7051
telemt_me_reader_eof_total 7270
telemt_me_idle_close_by_peer_total 7270
telemt_me_route_drop_no_conn_total 349249
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 217
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1554
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 1028
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7270
telemt_me_writer_restored_same_endpoint_total 7029
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 756978
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 8115063320 (7.56 GB)
telemt_user_octets_to_client{user="hello"} 235793647240 (219.60 GB)
telemt_user_unique_ips_current{user="hello"} 77
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 55705.3 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377506
telemt_connections_bad_total 3268
telemt_handshake_timeouts_total 28280
telemt_upstream_connect_attempt_total 102342
telemt_upstream_connect_success_total 100770
telemt_upstream_connect_fail_total 748
telemt_upstream_connect_attempts_per_request{bucket="1"} 100764
telemt_upstream_connect_attempts_per_request{bucket="2"} 754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 748
telemt_me_keepalive_timeout_total 1416
telemt_me_reconnect_attempts_total 57113
telemt_me_reconnect_success_total 57023
telemt_me_reader_eof_total 58461
telemt_me_idle_close_by_peer_total 58460
telemt_me_route_drop_no_conn_total 154658
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 234
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 736
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 505
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58541
telemt_me_writer_restored_same_endpoint_total 56998
telemt_me_writer_removed_unexpected_minus_restored_total 1543
telemt_user_connections_total{user="hello"} 286488
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 3836962588 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 91636962444 (85.34 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 55704.1 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722586
telemt_connections_bad_total 166325
telemt_handshake_timeouts_total 23763
telemt_upstream_connect_attempt_total 80881
telemt_upstream_connect_success_total 80388
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 80387
telemt_upstream_connect_attempts_per_request{bucket="2"} 238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 1051
telemt_me_reconnect_attempts_total 37540
telemt_me_reconnect_success_total 37447
telemt_me_reader_eof_total 39434
telemt_me_idle_close_by_peer_total 39430
telemt_me_route_drop_no_conn_total 268499
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1280
telemt_desync_full_logged_total 452
telemt_desync_suppressed_total 828
telemt_desync_frames_bucket_total{bucket="1_2"} 370
telemt_desync_frames_bucket_total{bucket="3_10"} 430
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 39446
telemt_me_writer_restored_same_endpoint_total 37425
telemt_me_writer_removed_unexpected_minus_restored_total 2021
telemt_user_connections_total{user="hello"} 502452
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 11495247764 (10.71 GB)
telemt_user_octets_to_client{user="hello"} 166036684928 (154.63 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 2381.4 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27041
telemt_connections_bad_total 2932
telemt_handshake_timeouts_total 621
telemt_upstream_connect_attempt_total 935
telemt_upstream_connect_success_total 935
telemt_upstream_connect_attempts_per_request{bucket="1"} 935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 347
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 66
telemt_me_reconnect_success_total 86
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 9501
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_restored_same_endpoint_total 65
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 23092
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 240754144 (229.60 MB)
telemt_user_octets_to_client{user="hello"} 16375982724 (15.25 GB)
telemt_user_unique_ips_current{user="hello"} 54
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 2740.9 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49618
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 878
telemt_upstream_connect_attempt_total 913
telemt_upstream_connect_success_total 908
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 908
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 14820
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 150
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_me_writer_removed_unexpected_total 25
telemt_me_writer_restored_same_endpoint_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 41192
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 489047872 (466.39 MB)
telemt_user_octets_to_client{user="hello"} 12603430784 (11.74 GB)
telemt_user_unique_ips_current{user="hello"} 54
```