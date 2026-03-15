# Server Metrics 2026-03-15 01:29:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 11730.7 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146883
telemt_connections_bad_total 1668
telemt_handshake_timeouts_total 514
telemt_upstream_connect_attempt_total 2456
telemt_upstream_connect_success_total 2447
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1863
telemt_me_reconnect_success_total 1852
telemt_me_reader_eof_total 1943
telemt_me_idle_close_by_peer_total 1943
telemt_me_route_drop_no_conn_total 45911
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128512
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 324
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1876
telemt_me_writer_restored_same_endpoint_total 1841
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 128498
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 1458021492 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 43642058100 (40.64 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 11731.1 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60545
telemt_connections_bad_total 10930
telemt_handshake_timeouts_total 2382
telemt_upstream_connect_attempt_total 3506
telemt_upstream_connect_success_total 3487
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2595
telemt_me_reconnect_success_total 2579
telemt_me_reader_eof_total 2684
telemt_me_idle_close_by_peer_total 2684
telemt_me_route_drop_no_conn_total 11975
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45561
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2553
telemt_me_writer_restored_same_endpoint_total 2571
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 45857
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 1484735879 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 12657450340 (11.79 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 11731.3 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97875
telemt_connections_bad_total 2117
telemt_handshake_timeouts_total 8263
telemt_upstream_connect_attempt_total 2663
telemt_upstream_connect_success_total 2652
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 2063
telemt_me_reconnect_success_total 2055
telemt_me_reader_eof_total 2156
telemt_me_idle_close_by_peer_total 2156
telemt_me_route_drop_no_conn_total 21843
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85756
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2076
telemt_me_writer_restored_same_endpoint_total 2036
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 85673
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 872971984 (832.53 MB)
telemt_user_octets_to_client{user="hello"} 29944122600 (27.89 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 11731.2 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89146
telemt_connections_bad_total 25000
telemt_handshake_timeouts_total 2161
telemt_upstream_connect_attempt_total 4350
telemt_upstream_connect_success_total 4255
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 4350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4962
telemt_me_reconnect_success_total 3656
telemt_me_reader_eof_total 3776
telemt_me_idle_close_by_peer_total 3776
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 16316
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60501
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 97
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3728
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 3638
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 60503
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 347505556 (331.41 MB)
telemt_user_octets_to_client{user="hello"} 11854246516 (11.04 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 11731.7 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52185
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 695
telemt_upstream_connect_attempt_total 2538
telemt_upstream_connect_success_total 2526
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1937
telemt_me_reconnect_success_total 1928
telemt_me_reader_eof_total 2030
telemt_me_idle_close_by_peer_total 2030
telemt_me_route_drop_no_conn_total 12846
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50008
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1946
telemt_me_writer_restored_same_endpoint_total 1920
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 50008
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 411298832 (392.25 MB)
telemt_user_octets_to_client{user="hello"} 18279493296 (17.02 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 31
```