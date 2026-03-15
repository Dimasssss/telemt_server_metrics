# Server Metrics 2026-03-15 01:09:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 10510.3 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134126
telemt_connections_bad_total 1527
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 2241
telemt_upstream_connect_success_total 2232
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1696
telemt_me_reconnect_success_total 1687
telemt_me_reader_eof_total 1766
telemt_me_idle_close_by_peer_total 1766
telemt_me_route_drop_no_conn_total 42195
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117021
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 298
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1709
telemt_me_writer_restored_same_endpoint_total 1676
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 117012
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 1374278572 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 40738053104 (37.94 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 10510.8 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54848
telemt_connections_bad_total 9896
telemt_handshake_timeouts_total 2206
telemt_upstream_connect_attempt_total 3204
telemt_upstream_connect_success_total 3186
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2344
telemt_me_reconnect_success_total 2328
telemt_me_reader_eof_total 2418
telemt_me_idle_close_by_peer_total 2418
telemt_me_route_drop_no_conn_total 10921
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41111
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 99
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2299
telemt_me_writer_restored_same_endpoint_total 2320
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 41407
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 1416850679 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 12010590404 (11.19 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 10511.0 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87764
telemt_connections_bad_total 1586
telemt_handshake_timeouts_total 6940
telemt_upstream_connect_attempt_total 2398
telemt_upstream_connect_success_total 2387
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1847
telemt_me_reconnect_success_total 1840
telemt_me_reader_eof_total 1927
telemt_me_idle_close_by_peer_total 1927
telemt_me_route_drop_no_conn_total 20162
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77576
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 148
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1857
telemt_me_writer_restored_same_endpoint_total 1821
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 77492
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 816283912 (778.47 MB)
telemt_user_octets_to_client{user="hello"} 24566392032 (22.88 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 10510.8 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82350
telemt_connections_bad_total 23645
telemt_handshake_timeouts_total 1526
telemt_upstream_connect_attempt_total 3763
telemt_upstream_connect_success_total 3676
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 3763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4431
telemt_me_reconnect_success_total 3126
telemt_me_reader_eof_total 3244
telemt_me_idle_close_by_peer_total 3244
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 14785
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55814
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 86
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3194
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 3110
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 55816
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 319335904 (304.54 MB)
telemt_user_octets_to_client{user="hello"} 11237333976 (10.47 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 10511.5 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46920
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 658
telemt_upstream_connect_attempt_total 2277
telemt_upstream_connect_success_total 2267
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1729
telemt_me_reconnect_success_total 1722
telemt_me_reader_eof_total 1810
telemt_me_idle_close_by_peer_total 1810
telemt_me_route_drop_no_conn_total 11873
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45095
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1738
telemt_me_writer_restored_same_endpoint_total 1714
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 45095
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 340519656 (324.74 MB)
telemt_user_octets_to_client{user="hello"} 17141374008 (15.96 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 33
```