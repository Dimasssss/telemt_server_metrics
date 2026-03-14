# Server Metrics 2026-03-14 23:27:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 4405.8 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65999
telemt_connections_bad_total 721
telemt_handshake_timeouts_total 303
telemt_upstream_connect_attempt_total 921
telemt_upstream_connect_success_total 919
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 684
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 696
telemt_me_idle_close_by_peer_total 696
telemt_me_route_drop_no_conn_total 20870
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60440
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 210
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 692
telemt_me_writer_restored_same_endpoint_total 670
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 60433
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 779093140 (743.00 MB)
telemt_user_octets_to_client{user="hello"} 24006360700 (22.36 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 4406.4 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26690
telemt_connections_bad_total 3845
telemt_handshake_timeouts_total 1753
telemt_upstream_connect_attempt_total 1565
telemt_upstream_connect_success_total 1554
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1014
telemt_me_reconnect_success_total 1004
telemt_me_reader_eof_total 1004
telemt_me_idle_close_by_peer_total 1004
telemt_me_route_drop_no_conn_total 5019
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20070
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 968
telemt_me_writer_restored_same_endpoint_total 996
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 20366
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 1241275411 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 5050503968 (4.70 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 4406.6 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42523
telemt_connections_bad_total 978
telemt_handshake_timeouts_total 2516
telemt_upstream_connect_attempt_total 927
telemt_upstream_connect_success_total 920
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 681
telemt_me_reconnect_success_total 679
telemt_me_reader_eof_total 690
telemt_me_idle_close_by_peer_total 690
telemt_me_route_drop_no_conn_total 10630
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38486
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 38408
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 621609448 (592.81 MB)
telemt_user_octets_to_client{user="hello"} 13143746084 (12.24 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 4406.6 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29462
telemt_connections_bad_total 3826
telemt_handshake_timeouts_total 773
telemt_upstream_connect_attempt_total 1377
telemt_upstream_connect_success_total 1328
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 1377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1104
telemt_me_reconnect_success_total 1083
telemt_me_reader_eof_total 1088
telemt_me_idle_close_by_peer_total 1088
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 6334
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24382
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1090
telemt_me_writer_restored_same_endpoint_total 1070
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 24384
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 192646372 (183.72 MB)
telemt_user_octets_to_client{user="hello"} 6534050484 (6.09 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 4407.2 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23444
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 517
telemt_upstream_connect_attempt_total 844
telemt_upstream_connect_success_total 840
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 604
telemt_me_reconnect_success_total 600
telemt_me_reader_eof_total 609
telemt_me_idle_close_by_peer_total 609
telemt_me_route_drop_no_conn_total 5337
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22359
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 607
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 22359
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 178321776 (170.06 MB)
telemt_user_octets_to_client{user="hello"} 12340053528 (11.49 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 30
```