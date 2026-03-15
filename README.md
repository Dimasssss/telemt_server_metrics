# Server Metrics 2026-03-15 02:41:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 16004.8 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194798
telemt_connections_bad_total 2609
telemt_handshake_timeouts_total 605
telemt_upstream_connect_attempt_total 3392
telemt_upstream_connect_success_total 3382
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 2587
telemt_me_reconnect_success_total 2573
telemt_me_reader_eof_total 2713
telemt_me_idle_close_by_peer_total 2713
telemt_me_route_drop_no_conn_total 60595
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171912
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 469
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 179
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2603
telemt_me_writer_restored_same_endpoint_total 2562
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 171892
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 1870483776 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 60972834488 (56.79 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 16013.4 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80795
telemt_connections_bad_total 14301
telemt_handshake_timeouts_total 3661
telemt_upstream_connect_attempt_total 4734
telemt_upstream_connect_success_total 4713
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3613
telemt_me_reconnect_success_total 3593
telemt_me_reader_eof_total 3766
telemt_me_idle_close_by_peer_total 3766
telemt_me_route_drop_no_conn_total 15553
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60776
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
telemt_me_writer_removed_unexpected_total 3575
telemt_me_writer_restored_same_endpoint_total 3585
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 61072
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 1570007227 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 17053374060 (15.88 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 16005.4 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133891
telemt_connections_bad_total 2821
telemt_handshake_timeouts_total 12597
telemt_upstream_connect_attempt_total 3750
telemt_upstream_connect_success_total 3733
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 2935
telemt_me_reconnect_success_total 2924
telemt_me_reader_eof_total 3084
telemt_me_idle_close_by_peer_total 3084
telemt_me_route_drop_no_conn_total 28545
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115842
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 257
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2954
telemt_me_writer_restored_same_endpoint_total 2905
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 115752
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 1071862292 (1022.21 MB)
telemt_user_octets_to_client{user="hello"} 37271678348 (34.71 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 16005.3 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111104
telemt_connections_bad_total 28294
telemt_handshake_timeouts_total 2736
telemt_upstream_connect_attempt_total 5875
telemt_upstream_connect_success_total 5753
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 5875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8490
telemt_me_reconnect_success_total 4940
telemt_me_reader_eof_total 5198
telemt_me_idle_close_by_peer_total 5198
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 21290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78370
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 132
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 5093
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4921
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 78377
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 460872176 (439.52 MB)
telemt_user_octets_to_client{user="hello"} 19082587004 (17.77 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 16006.0 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66806
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 730
telemt_upstream_connect_attempt_total 3647
telemt_upstream_connect_success_total 3631
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2831
telemt_me_reconnect_success_total 2820
telemt_me_reader_eof_total 2991
telemt_me_idle_close_by_peer_total 2991
telemt_me_route_drop_no_conn_total 17219
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64102
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2842
telemt_me_writer_restored_same_endpoint_total 2812
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 64101
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 564822812 (538.66 MB)
telemt_user_octets_to_client{user="hello"} 21179424440 (19.72 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 35
```