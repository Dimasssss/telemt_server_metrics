# Server Metrics 2026-03-15 16:33:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 65913.6 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2222315
telemt_connections_bad_total 130480
telemt_handshake_timeouts_total 27375
telemt_upstream_connect_attempt_total 13039
telemt_upstream_connect_success_total 12983
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 13039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14557
telemt_me_reconnect_success_total 9662
telemt_me_reader_eof_total 10328
telemt_me_idle_close_by_peer_total 10328
telemt_me_route_drop_no_conn_total 766548
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1869000
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7266
telemt_desync_full_logged_total 2001
telemt_desync_suppressed_total 5265
telemt_desync_frames_bucket_total{bucket="1_2"} 1760
telemt_desync_frames_bucket_total{bucket="3_10"} 2789
telemt_desync_frames_bucket_total{bucket="gt_10"} 2717
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9974
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9651
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 1868499
telemt_user_connections_current{user="hello"} 2431
telemt_user_octets_from_client{user="hello"} 27387738836 (25.51 GB)
telemt_user_octets_to_client{user="hello"} 712961445932 (664.00 GB)
telemt_user_unique_ips_current{user="hello"} 678
telemt_user_unique_ips_recent_window{user="hello"} 325
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 65914.5 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 870447
telemt_connections_bad_total 47049
telemt_handshake_timeouts_total 60679
telemt_upstream_connect_attempt_total 16672
telemt_upstream_connect_success_total 16591
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 16672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14048
telemt_me_reconnect_success_total 12919
telemt_me_reader_eof_total 13662
telemt_me_idle_close_by_peer_total 13662
telemt_me_route_drop_no_conn_total 222849
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 666921
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2107
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 769
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 560
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13119
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 12907
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 667164
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 9262159803 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 253070468028 (235.69 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 65914.5 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1968750
telemt_connections_bad_total 48373
telemt_handshake_timeouts_total 194150
telemt_upstream_connect_attempt_total 14374
telemt_upstream_connect_success_total 14305
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 14374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12221
telemt_me_reconnect_success_total 10952
telemt_me_reader_eof_total 11596
telemt_me_idle_close_by_peer_total 11596
telemt_me_route_drop_no_conn_total 507663
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1188665
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2966
telemt_desync_full_logged_total 1077
telemt_desync_suppressed_total 1889
telemt_desync_frames_bucket_total{bucket="1_2"} 683
telemt_desync_frames_bucket_total{bucket="3_10"} 1144
telemt_desync_frames_bucket_total{bucket="gt_10"} 1139
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11147
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10933
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 1184624
telemt_user_connections_current{user="hello"} 1376
telemt_user_octets_from_client{user="hello"} 17266939660 (16.08 GB)
telemt_user_octets_to_client{user="hello"} 427305124612 (397.96 GB)
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 65914.4 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 925327
telemt_connections_bad_total 79206
telemt_handshake_timeouts_total 45702
telemt_upstream_connect_attempt_total 168965
telemt_upstream_connect_success_total 168436
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 168965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 55877
telemt_me_reconnect_success_total 13047
telemt_me_reader_eof_total 14742
telemt_me_idle_close_by_peer_total 14742
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 211418
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562310
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1578
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 1168
telemt_desync_frames_bucket_total{bucket="1_2"} 403
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14519
telemt_me_refill_failed_total 1340
telemt_me_writer_restored_same_endpoint_total 13011
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1472
telemt_user_connections_total{user="hello"} 713935
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 13666074798 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 254803211453 (237.30 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 65915.7 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 938100
telemt_connections_bad_total 12049
telemt_handshake_timeouts_total 20475
telemt_upstream_connect_attempt_total 14756
telemt_upstream_connect_success_total 14676
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 15037
telemt_me_reconnect_success_total 11348
telemt_me_reader_eof_total 12104
telemt_me_idle_close_by_peer_total 12104
telemt_me_route_drop_no_conn_total 233786
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 774807
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2642
telemt_desync_full_logged_total 895
telemt_desync_suppressed_total 1747
telemt_desync_frames_bucket_total{bucket="1_2"} 812
telemt_desync_frames_bucket_total{bucket="3_10"} 999
telemt_desync_frames_bucket_total{bucket="gt_10"} 831
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 11598
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11340
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 774850
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 9521912296 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 276496580012 (257.51 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 128
```