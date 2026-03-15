# Server Metrics 2026-03-15 02:36:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 15699.4 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191298
telemt_connections_bad_total 2549
telemt_handshake_timeouts_total 596
telemt_upstream_connect_attempt_total 3350
telemt_upstream_connect_success_total 3340
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 2545
telemt_me_reconnect_success_total 2532
telemt_me_reader_eof_total 2671
telemt_me_idle_close_by_peer_total 2671
telemt_me_route_drop_no_conn_total 59394
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168711
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 463
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 334
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2561
telemt_me_writer_restored_same_endpoint_total 2521
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 168698
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 1836473764 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 56787115284 (52.89 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 15699.9 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79322
telemt_connections_bad_total 14068
telemt_handshake_timeouts_total 3621
telemt_upstream_connect_attempt_total 4673
telemt_upstream_connect_success_total 4652
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3552
telemt_me_reconnect_success_total 3532
telemt_me_reader_eof_total 3702
telemt_me_idle_close_by_peer_total 3702
telemt_me_route_drop_no_conn_total 15208
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59602
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
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3511
telemt_me_writer_restored_same_endpoint_total 3524
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 59898
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 1564980711 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 16503555232 (15.37 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 15700.2 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131168
telemt_connections_bad_total 2411
telemt_handshake_timeouts_total 12344
telemt_upstream_connect_attempt_total 3696
telemt_upstream_connect_success_total 3679
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 2881
telemt_me_reconnect_success_total 2870
telemt_me_reader_eof_total 3029
telemt_me_idle_close_by_peer_total 3029
telemt_me_route_drop_no_conn_total 27985
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113801
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2899
telemt_me_writer_restored_same_endpoint_total 2851
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 113712
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 1066401720 (1017.00 MB)
telemt_user_octets_to_client{user="hello"} 36996473108 (34.46 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 15700.0 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109326
telemt_connections_bad_total 28056
telemt_handshake_timeouts_total 2642
telemt_upstream_connect_attempt_total 5826
telemt_upstream_connect_success_total 5704
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 5826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8441
telemt_me_reconnect_success_total 4892
telemt_me_reader_eof_total 5148
telemt_me_idle_close_by_peer_total 5148
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 20963
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76952
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 5043
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4873
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 76959
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 451826452 (430.90 MB)
telemt_user_octets_to_client{user="hello"} 18177292096 (16.93 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 15700.8 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65758
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 727
telemt_upstream_connect_attempt_total 3596
telemt_upstream_connect_success_total 3580
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2780
telemt_me_reconnect_success_total 2769
telemt_me_reader_eof_total 2940
telemt_me_idle_close_by_peer_total 2940
telemt_me_route_drop_no_conn_total 16844
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63093
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2791
telemt_me_writer_restored_same_endpoint_total 2761
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 63092
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 560029972 (534.09 MB)
telemt_user_octets_to_client{user="hello"} 21008411700 (19.57 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 32
```