# Server Metrics 2026-03-14 14:20:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 3772.6 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152637
telemt_connections_bad_total 2402
telemt_handshake_timeouts_total 2228
telemt_upstream_connect_attempt_total 776
telemt_upstream_connect_success_total 771
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 1294
telemt_me_reconnect_success_total 515
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 57340
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141504
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 238
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 547
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 141496
telemt_user_connections_current{user="hello"} 1841
telemt_user_octets_from_client{user="hello"} 2262096312 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 36984465752 (34.44 GB)
telemt_user_unique_ips_current{user="hello"} 494
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 3778.0 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60213
telemt_connections_bad_total 3802
telemt_handshake_timeouts_total 2297
telemt_upstream_connect_attempt_total 814
telemt_upstream_connect_success_total 809
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 566
telemt_me_reconnect_success_total 555
telemt_me_reader_eof_total 546
telemt_me_idle_close_by_peer_total 546
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 19723
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49213
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 276
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 562
telemt_me_writer_restored_same_endpoint_total 544
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 49174
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 722482388 (689.01 MB)
telemt_user_octets_to_client{user="hello"} 23962790856 (22.32 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 3640.8 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102983
telemt_connections_bad_total 356
telemt_handshake_timeouts_total 14034
telemt_upstream_connect_attempt_total 697
telemt_upstream_connect_success_total 693
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 483
telemt_me_reconnect_success_total 477
telemt_me_reader_eof_total 457
telemt_me_idle_close_by_peer_total 457
telemt_me_route_drop_no_conn_total 30245
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82816
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_restored_same_endpoint_total 444
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 82784
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 1155487932 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 23478991932 (21.87 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 3495.3 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55795
telemt_connections_bad_total 16499
telemt_handshake_timeouts_total 9247
telemt_upstream_connect_attempt_total 1016
telemt_upstream_connect_success_total 1016
telemt_upstream_connect_attempts_per_request{bucket="1"} 1016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 815
telemt_me_reconnect_success_total 810
telemt_me_reader_eof_total 793
telemt_me_idle_close_by_peer_total 793
telemt_me_route_drop_no_conn_total 11915
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29479
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 803
telemt_me_writer_restored_same_endpoint_total 809
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 29447
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 797701280 (760.75 MB)
telemt_user_octets_to_client{user="hello"} 8501343888 (7.92 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 3790.6 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60112
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 926
telemt_upstream_connect_success_total 908
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 1306
telemt_me_reconnect_success_total 659
telemt_me_reader_eof_total 683
telemt_me_idle_close_by_peer_total 683
telemt_me_route_drop_no_conn_total 20757
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55163
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 214
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 693
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 641
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 55166
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 756875576 (721.81 MB)
telemt_user_octets_to_client{user="hello"} 19386454224 (18.06 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 97
```