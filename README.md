# Server Metrics 2026-03-10 15:25:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3521.9 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129662
telemt_connections_bad_total 591
telemt_handshake_timeouts_total 658
telemt_upstream_connect_attempt_total 793
telemt_upstream_connect_success_total 789
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2057
telemt_me_reconnect_success_total 580
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 56835
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124363
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 350
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_me_writer_removed_unexpected_total 611
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 574
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 124316
telemt_user_connections_current{user="hello"} 1356
telemt_user_octets_from_client{user="hello"} 1702169688 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 33894604176 (31.57 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 3578.7 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54266
telemt_connections_bad_total 1436
telemt_handshake_timeouts_total 6218
telemt_upstream_connect_attempt_total 728
telemt_upstream_connect_success_total 723
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 312
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 521
telemt_me_reconnect_success_total 518
telemt_me_reader_eof_total 504
telemt_me_idle_close_by_peer_total 504
telemt_me_route_drop_no_conn_total 13523
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43513
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 264
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 516
telemt_me_writer_restored_same_endpoint_total 497
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 43501
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 573253876 (546.70 MB)
telemt_user_octets_to_client{user="hello"} 13695156832 (12.75 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 3578.5 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90717
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 3144
telemt_upstream_connect_attempt_total 1925
telemt_upstream_connect_success_total 1890
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 1925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 671
telemt_me_reconnect_success_total 651
telemt_me_reader_eof_total 640
telemt_me_idle_close_by_peer_total 640
telemt_me_route_drop_no_conn_total 30131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76358
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 174
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 663
telemt_me_writer_restored_same_endpoint_total 640
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 77358
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 812493541 (774.85 MB)
telemt_user_octets_to_client{user="hello"} 22886547513 (21.31 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 3578.9 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60190
telemt_connections_bad_total 3472
telemt_handshake_timeouts_total 5785
telemt_upstream_connect_attempt_total 669
telemt_upstream_connect_success_total 669
telemt_upstream_connect_attempts_per_request{bucket="1"} 669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 266
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 471
telemt_me_reconnect_success_total 468
telemt_me_reader_eof_total 462
telemt_me_idle_close_by_peer_total 462
telemt_me_route_drop_no_conn_total 20023
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48059
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 464
telemt_me_writer_restored_same_endpoint_total 457
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 48011
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 678257792 (646.84 MB)
telemt_user_octets_to_client{user="hello"} 11699837124 (10.90 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3578.6 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68147
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 1141
telemt_upstream_connect_success_total 1137
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 935
telemt_me_reconnect_success_total 928
telemt_me_reader_eof_total 905
telemt_me_idle_close_by_peer_total 905
telemt_me_route_drop_no_conn_total 22212
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62839
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 354
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_me_writer_removed_unexpected_total 927
telemt_me_writer_restored_same_endpoint_total 928
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 62807
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 1233526056 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 15606081820 (14.53 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 96
```