# Server Metrics 2026-03-14 23:02:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 2879.2 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46000
telemt_connections_bad_total 389
telemt_handshake_timeouts_total 193
telemt_upstream_connect_attempt_total 634
telemt_upstream_connect_success_total 631
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 440
telemt_me_reconnect_success_total 438
telemt_me_reader_eof_total 439
telemt_me_idle_close_by_peer_total 439
telemt_me_route_drop_no_conn_total 13681
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42347
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 446
telemt_me_writer_restored_same_endpoint_total 427
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 42345
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 665114020 (634.30 MB)
telemt_user_octets_to_client{user="hello"} 15276485128 (14.23 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 2879.9 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20009
telemt_connections_bad_total 3067
telemt_handshake_timeouts_total 1517
telemt_upstream_connect_attempt_total 1184
telemt_upstream_connect_success_total 1174
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 677
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 651
telemt_me_idle_close_by_peer_total 651
telemt_me_route_drop_no_conn_total 3977
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14567
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 14863
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 1167847259 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 3730577440 (3.47 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 2880.0 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30038
telemt_connections_bad_total 510
telemt_handshake_timeouts_total 1667
telemt_upstream_connect_attempt_total 586
telemt_upstream_connect_success_total 580
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 384
telemt_me_reconnect_success_total 383
telemt_me_reader_eof_total 379
telemt_me_idle_close_by_peer_total 379
telemt_me_route_drop_no_conn_total 6062
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27345
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
telemt_me_writer_removed_unexpected_total 384
telemt_me_writer_restored_same_endpoint_total 364
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 27345
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 477866916 (455.73 MB)
telemt_user_octets_to_client{user="hello"} 7279357072 (6.78 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 2879.8 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20007
telemt_connections_bad_total 2470
telemt_handshake_timeouts_total 735
telemt_upstream_connect_attempt_total 881
telemt_upstream_connect_success_total 839
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 659
telemt_me_reconnect_success_total 639
telemt_me_reader_eof_total 641
telemt_me_idle_close_by_peer_total 641
telemt_me_route_drop_no_conn_total 4333
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16490
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
telemt_me_writer_removed_unexpected_total 644
telemt_me_writer_restored_same_endpoint_total 628
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 16492
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 135703824 (129.42 MB)
telemt_user_octets_to_client{user="hello"} 4575884112 (4.26 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 2880.9 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16208
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 496
telemt_upstream_connect_attempt_total 522
telemt_upstream_connect_success_total 518
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 325
telemt_me_reconnect_success_total 323
telemt_me_reader_eof_total 320
telemt_me_idle_close_by_peer_total 320
telemt_me_route_drop_no_conn_total 3593
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15286
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 79
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 330
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 15286
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 125469428 (119.66 MB)
telemt_user_octets_to_client{user="hello"} 8546714572 (7.96 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 33
```