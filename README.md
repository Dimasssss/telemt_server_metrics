# Server Metrics 2026-03-10 15:20:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3215.5 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119443
telemt_connections_bad_total 586
telemt_handshake_timeouts_total 621
telemt_upstream_connect_attempt_total 755
telemt_upstream_connect_success_total 751
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2019
telemt_me_reconnect_success_total 542
telemt_me_reader_eof_total 546
telemt_me_idle_close_by_peer_total 546
telemt_me_route_drop_no_conn_total 51347
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114406
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 297
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_me_writer_removed_unexpected_total 573
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 536
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 114392
telemt_user_connections_current{user="hello"} 1339
telemt_user_octets_from_client{user="hello"} 1581101696 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 31563519952 (29.40 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 3272.2 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50804
telemt_connections_bad_total 1431
telemt_handshake_timeouts_total 6205
telemt_upstream_connect_attempt_total 683
telemt_upstream_connect_success_total 678
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 476
telemt_me_reconnect_success_total 473
telemt_me_reader_eof_total 459
telemt_me_idle_close_by_peer_total 459
telemt_me_route_drop_no_conn_total 12289
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40233
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 258
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 471
telemt_me_writer_restored_same_endpoint_total 452
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 40221
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 534787644 (510.01 MB)
telemt_user_octets_to_client{user="hello"} 12826063044 (11.95 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 3272.1 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83368
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 2508
telemt_upstream_connect_attempt_total 1844
telemt_upstream_connect_success_total 1809
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 1844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 590
telemt_me_reconnect_success_total 570
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 27614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69815
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 168
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 581
telemt_me_writer_restored_same_endpoint_total 559
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 70815
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 759255801 (724.08 MB)
telemt_user_octets_to_client{user="hello"} 21434959109 (19.96 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 3272.6 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55739
telemt_connections_bad_total 3154
telemt_handshake_timeouts_total 5489
telemt_upstream_connect_attempt_total 632
telemt_upstream_connect_success_total 632
telemt_upstream_connect_attempts_per_request{bucket="1"} 632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 253
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 434
telemt_me_reconnect_success_total 432
telemt_me_reader_eof_total 426
telemt_me_idle_close_by_peer_total 426
telemt_me_route_drop_no_conn_total 18424
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44412
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 126
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 428
telemt_me_writer_restored_same_endpoint_total 421
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 44377
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 603032320 (575.10 MB)
telemt_user_octets_to_client{user="hello"} 10914616960 (10.17 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3272.3 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62900
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 450
telemt_upstream_connect_attempt_total 1025
telemt_upstream_connect_success_total 1021
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 819
telemt_me_reconnect_success_total 812
telemt_me_reader_eof_total 789
telemt_me_idle_close_by_peer_total 789
telemt_me_route_drop_no_conn_total 20657
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58129
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 335
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 232
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_me_writer_removed_unexpected_total 811
telemt_me_writer_restored_same_endpoint_total 812
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 58097
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 1191833756 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 14673935748 (13.67 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 98
```