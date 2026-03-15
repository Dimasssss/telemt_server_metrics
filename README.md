# Server Metrics 2026-03-15 01:04:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 10205.0 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131198
telemt_connections_bad_total 1503
telemt_handshake_timeouts_total 469
telemt_upstream_connect_attempt_total 2183
telemt_upstream_connect_success_total 2174
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1638
telemt_me_reconnect_success_total 1630
telemt_me_reader_eof_total 1709
telemt_me_idle_close_by_peer_total 1709
telemt_me_route_drop_no_conn_total 40999
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114399
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 291
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1652
telemt_me_writer_restored_same_endpoint_total 1619
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 114390
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 1344545556 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 39466728708 (36.76 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 10205.5 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53521
telemt_connections_bad_total 9658
telemt_handshake_timeouts_total 2181
telemt_upstream_connect_attempt_total 3140
telemt_upstream_connect_success_total 3121
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2280
telemt_me_reconnect_success_total 2264
telemt_me_reader_eof_total 2354
telemt_me_idle_close_by_peer_total 2354
telemt_me_route_drop_no_conn_total 10766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40091
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
telemt_me_writer_removed_unexpected_total 2235
telemt_me_writer_restored_same_endpoint_total 2256
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 40387
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 1413348931 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 11654809584 (10.85 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 10205.7 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84811
telemt_connections_bad_total 1560
telemt_handshake_timeouts_total 6153
telemt_upstream_connect_attempt_total 2331
telemt_upstream_connect_success_total 2320
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1780
telemt_me_reconnect_success_total 1774
telemt_me_reader_eof_total 1861
telemt_me_idle_close_by_peer_total 1861
telemt_me_route_drop_no_conn_total 19817
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75571
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 139
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1791
telemt_me_writer_restored_same_endpoint_total 1755
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 75489
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 796030404 (759.15 MB)
telemt_user_octets_to_client{user="hello"} 22148996668 (20.63 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 10205.6 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80386
telemt_connections_bad_total 23161
telemt_handshake_timeouts_total 1369
telemt_upstream_connect_attempt_total 3659
telemt_upstream_connect_success_total 3572
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 3659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4327
telemt_me_reconnect_success_total 3022
telemt_me_reader_eof_total 3137
telemt_me_idle_close_by_peer_total 3137
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 14394
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54507
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
telemt_me_writer_removed_unexpected_total 3087
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 3006
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 54510
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 315617240 (301.00 MB)
telemt_user_octets_to_client{user="hello"} 11083573696 (10.32 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 10206.1 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45686
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 657
telemt_upstream_connect_attempt_total 2219
telemt_upstream_connect_success_total 2209
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1671
telemt_me_reconnect_success_total 1664
telemt_me_reader_eof_total 1752
telemt_me_idle_close_by_peer_total 1752
telemt_me_route_drop_no_conn_total 11658
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43886
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 176
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1680
telemt_me_writer_restored_same_endpoint_total 1656
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 43886
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 334694820 (319.19 MB)
telemt_user_octets_to_client{user="hello"} 17003956556 (15.84 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 31
```