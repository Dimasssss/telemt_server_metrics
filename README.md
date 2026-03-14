# Server Metrics 2026-03-14 23:12:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 3490.1 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54731
telemt_connections_bad_total 506
telemt_handshake_timeouts_total 253
telemt_upstream_connect_attempt_total 723
telemt_upstream_connect_success_total 721
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 529
telemt_me_reconnect_success_total 527
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 17075
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50279
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 184
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_restored_same_endpoint_total 516
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 50273
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 710556476 (677.64 MB)
telemt_user_octets_to_client{user="hello"} 19581029284 (18.24 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 3490.8 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22902
telemt_connections_bad_total 3573
telemt_handshake_timeouts_total 1570
telemt_upstream_connect_attempt_total 1324
telemt_upstream_connect_success_total 1314
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 817
telemt_me_reconnect_success_total 807
telemt_me_reader_eof_total 791
telemt_me_idle_close_by_peer_total 791
telemt_me_route_drop_no_conn_total 4433
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16820
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 767
telemt_me_writer_restored_same_endpoint_total 799
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 17116
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 1212501147 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 4432908616 (4.13 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 3490.9 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35522
telemt_connections_bad_total 978
telemt_handshake_timeouts_total 2009
telemt_upstream_connect_attempt_total 687
telemt_upstream_connect_success_total 681
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 485
telemt_me_reconnect_success_total 483
telemt_me_reader_eof_total 483
telemt_me_idle_close_by_peer_total 483
telemt_me_route_drop_no_conn_total 8881
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32033
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 57
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 485
telemt_me_writer_restored_same_endpoint_total 464
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 31963
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 516537664 (492.61 MB)
telemt_user_octets_to_client{user="hello"} 11093819384 (10.33 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 3490.8 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23613
telemt_connections_bad_total 3014
telemt_handshake_timeouts_total 751
telemt_upstream_connect_attempt_total 1026
telemt_upstream_connect_success_total 984
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 1026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 804
telemt_me_reconnect_success_total 783
telemt_me_reader_eof_total 788
telemt_me_idle_close_by_peer_total 788
telemt_me_route_drop_no_conn_total 5130
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19490
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 19492
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 155070304 (147.89 MB)
telemt_user_octets_to_client{user="hello"} 4902912956 (4.57 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 3491.4 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19284
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 501
telemt_upstream_connect_attempt_total 638
telemt_upstream_connect_success_total 634
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 441
telemt_me_reconnect_success_total 438
telemt_me_reader_eof_total 435
telemt_me_idle_close_by_peer_total 435
telemt_me_route_drop_no_conn_total 4382
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18301
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 105
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 445
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 18301
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 150386976 (143.42 MB)
telemt_user_octets_to_client{user="hello"} 11354051140 (10.57 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 27
```