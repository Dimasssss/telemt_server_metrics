# Server Metrics 2026-03-14 19:27:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 22211.5 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 884416
telemt_connections_bad_total 40371
telemt_handshake_timeouts_total 13023
telemt_upstream_connect_attempt_total 4132
telemt_upstream_connect_success_total 4115
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3761
telemt_me_reconnect_success_total 2958
telemt_me_reader_eof_total 3113
telemt_me_idle_close_by_peer_total 3113
telemt_me_route_drop_no_conn_total 338720
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 781006
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2689
telemt_desync_full_logged_total 767
telemt_desync_suppressed_total 1922
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 997
telemt_desync_frames_bucket_total{bucket="gt_10"} 1053
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3034
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2949
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 780951
telemt_user_connections_current{user="hello"} 1656
telemt_user_octets_from_client{user="hello"} 13893032668 (12.94 GB)
telemt_user_octets_to_client{user="hello"} 258476244292 (240.72 GB)
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 22216.8 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341194
telemt_connections_bad_total 23387
telemt_handshake_timeouts_total 10179
telemt_upstream_connect_attempt_total 4637
telemt_upstream_connect_success_total 4584
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 4637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 388
telemt_me_reconnect_attempts_total 4222
telemt_me_reconnect_success_total 3429
telemt_me_reader_eof_total 3588
telemt_me_idle_close_by_peer_total 3588
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 106056
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287991
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1221
telemt_desync_full_logged_total 374
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3524
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3412
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 287922
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 3911985312 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 100501346472 (93.60 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 22079.7 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711612
telemt_connections_bad_total 2883
telemt_handshake_timeouts_total 139138
telemt_upstream_connect_attempt_total 4305
telemt_upstream_connect_success_total 4290
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 7055
telemt_me_reconnect_success_total 3146
telemt_me_reader_eof_total 3380
telemt_me_idle_close_by_peer_total 3380
telemt_me_route_drop_no_conn_total 173295
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487582
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1719
telemt_desync_full_logged_total 663
telemt_desync_suppressed_total 1056
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 884
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3299
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3113
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 487409
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 7148694152 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 174005781036 (162.06 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 21934.3 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395520
telemt_connections_bad_total 89731
telemt_handshake_timeouts_total 46805
telemt_upstream_connect_attempt_total 5198
telemt_upstream_connect_success_total 5197
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 186
telemt_me_reconnect_attempts_total 4979
telemt_me_reconnect_success_total 4062
telemt_me_reader_eof_total 4248
telemt_me_idle_close_by_peer_total 4248
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 89839
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252489
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 557
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 365
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4137
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4051
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 252420
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 3695116184 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 80660138980 (75.12 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 22229.8 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337274
telemt_connections_bad_total 1294
telemt_handshake_timeouts_total 3664
telemt_upstream_connect_attempt_total 4613
telemt_upstream_connect_success_total 4520
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 4613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 4054
telemt_me_reconnect_success_total 3383
telemt_me_reader_eof_total 3569
telemt_me_idle_close_by_peer_total 3569
telemt_me_route_drop_no_conn_total 105831
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312468
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 785
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 498
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3468
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3365
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 312452
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 4807297364 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 132595353032 (123.49 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 83
```