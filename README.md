# Server Metrics 2026-03-04 13:20:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 58169.6 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1033653
telemt_connections_bad_total 13894
telemt_handshake_timeouts_total 16291
telemt_upstream_connect_attempt_total 34369
telemt_upstream_connect_success_total 34217
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 34217
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15298
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 383
telemt_me_reconnect_attempts_total 7173
telemt_me_reconnect_success_total 7120
telemt_me_reader_eof_total 7342
telemt_me_idle_close_by_peer_total 7341
telemt_me_route_drop_no_conn_total 371131
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 229
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1679
telemt_desync_full_logged_total 565
telemt_desync_suppressed_total 1114
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 570
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7342
telemt_me_writer_restored_same_endpoint_total 7098
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 813430
telemt_user_connections_current{user="hello"} 1029
telemt_user_octets_from_client{user="hello"} 9237735460 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 270250161060 (251.69 GB)
telemt_user_unique_ips_current{user="hello"} 105
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 58166.1 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402315
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 28929
telemt_upstream_connect_attempt_total 104940
telemt_upstream_connect_success_total 103338
telemt_upstream_connect_fail_total 763
telemt_upstream_connect_attempts_per_request{bucket="1"} 103332
telemt_upstream_connect_attempts_per_request{bucket="2"} 769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 763
telemt_me_keepalive_timeout_total 1430
telemt_me_reconnect_attempts_total 57877
telemt_me_reconnect_success_total 57786
telemt_me_reader_eof_total 59239
telemt_me_idle_close_by_peer_total 59238
telemt_me_route_drop_no_conn_total 163368
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 245
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 787
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 59319
telemt_me_writer_restored_same_endpoint_total 57761
telemt_me_writer_removed_unexpected_minus_restored_total 1558
telemt_user_connections_total{user="hello"} 308462
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 4037190472 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 97511797148 (90.81 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 58164.9 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 781038
telemt_connections_bad_total 173243
telemt_handshake_timeouts_total 27469
telemt_upstream_connect_attempt_total 82092
telemt_upstream_connect_success_total 81579
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 81578
telemt_upstream_connect_attempts_per_request{bucket="2"} 248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 1067
telemt_me_reconnect_attempts_total 37726
telemt_me_reconnect_success_total 37630
telemt_me_reader_eof_total 39620
telemt_me_idle_close_by_peer_total 39616
telemt_me_route_drop_no_conn_total 287528
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1468
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 961
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 482
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39632
telemt_me_writer_restored_same_endpoint_total 37608
telemt_me_writer_removed_unexpected_minus_restored_total 2024
telemt_user_connections_total{user="hello"} 544035
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 11939395772 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 182136581212 (169.63 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 4842.2 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59479
telemt_connections_bad_total 5603
telemt_handshake_timeouts_total 1037
telemt_upstream_connect_attempt_total 1802
telemt_upstream_connect_success_total 1802
telemt_upstream_connect_attempts_per_request{bucket="1"} 1802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 686
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 122
telemt_me_reconnect_success_total 140
telemt_me_reader_eof_total 122
telemt_me_idle_close_by_peer_total 122
telemt_me_route_drop_no_conn_total 20942
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 63
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 122
telemt_me_writer_restored_same_endpoint_total 119
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 52016
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 1028580212 (980.93 MB)
telemt_user_octets_to_client{user="hello"} 34622983896 (32.25 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 5201.3 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95562
telemt_connections_bad_total 413
telemt_handshake_timeouts_total 1407
telemt_upstream_connect_attempt_total 2886
telemt_upstream_connect_success_total 2871
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2871
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 410
telemt_me_reconnect_success_total 423
telemt_me_reader_eof_total 413
telemt_me_idle_close_by_peer_total 413
telemt_me_route_drop_no_conn_total 29848
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 274
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 413
telemt_me_writer_restored_same_endpoint_total 403
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 81909
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 860162728 (820.32 MB)
telemt_user_octets_to_client{user="hello"} 22063446100 (20.55 GB)
telemt_user_unique_ips_current{user="hello"} 51
```