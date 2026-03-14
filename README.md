# Server Metrics 2026-03-14 23:17:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 3795.4 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58489
telemt_connections_bad_total 566
telemt_handshake_timeouts_total 267
telemt_upstream_connect_attempt_total 822
telemt_upstream_connect_success_total 820
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 585
telemt_me_reconnect_success_total 583
telemt_me_reader_eof_total 596
telemt_me_idle_close_by_peer_total 596
telemt_me_route_drop_no_conn_total 18543
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53665
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 195
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 592
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 53658
telemt_user_connections_current{user="hello"} 813
telemt_user_octets_from_client{user="hello"} 736044704 (701.95 MB)
telemt_user_octets_to_client{user="hello"} 20934675000 (19.50 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 3796.0 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24320
telemt_connections_bad_total 3819
telemt_handshake_timeouts_total 1588
telemt_upstream_connect_attempt_total 1426
telemt_upstream_connect_success_total 1415
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 875
telemt_me_reconnect_success_total 865
telemt_me_reader_eof_total 861
telemt_me_idle_close_by_peer_total 861
telemt_me_route_drop_no_conn_total 4655
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17934
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
telemt_me_writer_removed_unexpected_total 825
telemt_me_writer_restored_same_endpoint_total 857
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 18230
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 1220751751 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 4699982896 (4.38 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 3796.2 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37848
telemt_connections_bad_total 978
telemt_handshake_timeouts_total 2186
telemt_upstream_connect_attempt_total 787
telemt_upstream_connect_success_total 780
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 541
telemt_me_reconnect_success_total 539
telemt_me_reader_eof_total 548
telemt_me_idle_close_by_peer_total 548
telemt_me_route_drop_no_conn_total 9554
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34170
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
telemt_me_writer_removed_unexpected_total 543
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 34093
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 531756448 (507.12 MB)
telemt_user_octets_to_client{user="hello"} 11909498212 (11.09 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 3796.1 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25628
telemt_connections_bad_total 3279
telemt_handshake_timeouts_total 763
telemt_upstream_connect_attempt_total 1161
telemt_upstream_connect_success_total 1112
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 1161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 888
telemt_me_reconnect_success_total 866
telemt_me_reader_eof_total 872
telemt_me_idle_close_by_peer_total 872
telemt_me_route_drop_no_conn_total 5470
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21195
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 873
telemt_me_writer_restored_same_endpoint_total 855
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 21197
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 167391936 (159.64 MB)
telemt_user_octets_to_client{user="hello"} 5485270196 (5.11 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 3796.8 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20762
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 503
telemt_upstream_connect_attempt_total 739
telemt_upstream_connect_success_total 735
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 499
telemt_me_reconnect_success_total 496
telemt_me_reader_eof_total 505
telemt_me_idle_close_by_peer_total 505
telemt_me_route_drop_no_conn_total 4654
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19747
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
telemt_me_writer_removed_unexpected_total 503
telemt_me_writer_restored_same_endpoint_total 488
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 19747
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 161706732 (154.22 MB)
telemt_user_octets_to_client{user="hello"} 11749593128 (10.94 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 35
```