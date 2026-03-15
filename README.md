# Server Metrics 2026-03-15 01:40:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 12341.6 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153532
telemt_connections_bad_total 1737
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 2605
telemt_upstream_connect_success_total 2596
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1974
telemt_me_reconnect_success_total 1963
telemt_me_reader_eof_total 2064
telemt_me_idle_close_by_peer_total 2064
telemt_me_route_drop_no_conn_total 47928
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134600
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 338
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1989
telemt_me_writer_restored_same_endpoint_total 1952
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 134586
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 1494089472 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 45887093336 (42.74 GB)
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 12342.0 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63823
telemt_connections_bad_total 11406
telemt_handshake_timeouts_total 2689
telemt_upstream_connect_attempt_total 3686
telemt_upstream_connect_success_total 3668
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2740
telemt_me_reconnect_success_total 2724
telemt_me_reader_eof_total 2840
telemt_me_idle_close_by_peer_total 2840
telemt_me_route_drop_no_conn_total 12502
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47941
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2698
telemt_me_writer_restored_same_endpoint_total 2716
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 48237
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1491870095 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 12927799148 (12.04 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 12342.3 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102809
telemt_connections_bad_total 2189
telemt_handshake_timeouts_total 8547
telemt_upstream_connect_attempt_total 2845
telemt_upstream_connect_success_total 2830
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2205
telemt_me_reconnect_success_total 2196
telemt_me_reader_eof_total 2308
telemt_me_idle_close_by_peer_total 2308
telemt_me_route_drop_no_conn_total 22971
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90252
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 210
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2220
telemt_me_writer_restored_same_endpoint_total 2177
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 90168
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 896546864 (855.01 MB)
telemt_user_octets_to_client{user="hello"} 31247055888 (29.10 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 12342.0 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92571
telemt_connections_bad_total 25480
telemt_handshake_timeouts_total 2477
telemt_upstream_connect_attempt_total 4659
telemt_upstream_connect_success_total 4557
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 4659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6282
telemt_me_reconnect_success_total 3919
telemt_me_reader_eof_total 4076
telemt_me_idle_close_by_peer_total 4076
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 16887
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63100
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 110
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4028
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 3901
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 63102
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 359508068 (342.85 MB)
telemt_user_octets_to_client{user="hello"} 12013002056 (11.19 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 12342.9 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54038
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 696
telemt_upstream_connect_attempt_total 2731
telemt_upstream_connect_success_total 2719
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 2094
telemt_me_reconnect_success_total 2085
telemt_me_reader_eof_total 2198
telemt_me_idle_close_by_peer_total 2198
telemt_me_route_drop_no_conn_total 13452
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51807
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2103
telemt_me_writer_restored_same_endpoint_total 2077
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 51807
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 487709948 (465.12 MB)
telemt_user_octets_to_client{user="hello"} 18944953140 (17.64 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 24
```