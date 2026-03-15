# Server Metrics 2026-03-15 01:14:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 10815.3 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137104
telemt_connections_bad_total 1564
telemt_handshake_timeouts_total 503
telemt_upstream_connect_attempt_total 2272
telemt_upstream_connect_success_total 2263
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1092
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1727
telemt_me_reconnect_success_total 1718
telemt_me_reader_eof_total 1797
telemt_me_idle_close_by_peer_total 1797
telemt_me_route_drop_no_conn_total 42959
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119716
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 304
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1740
telemt_me_writer_restored_same_endpoint_total 1707
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 119707
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 1390117960 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 41458453952 (38.61 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 10815.8 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56058
telemt_connections_bad_total 10132
telemt_handshake_timeouts_total 2244
telemt_upstream_connect_attempt_total 3247
telemt_upstream_connect_success_total 3229
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2387
telemt_me_reconnect_success_total 2371
telemt_me_reader_eof_total 2461
telemt_me_idle_close_by_peer_total 2461
telemt_me_route_drop_no_conn_total 11270
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42059
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
telemt_me_writer_removed_unexpected_total 2342
telemt_me_writer_restored_same_endpoint_total 2363
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 42355
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 1438955235 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 12117069720 (11.28 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 10816.0 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90535
telemt_connections_bad_total 1784
telemt_handshake_timeouts_total 7628
telemt_upstream_connect_attempt_total 2435
telemt_upstream_connect_success_total 2424
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1884
telemt_me_reconnect_success_total 1877
telemt_me_reader_eof_total 1964
telemt_me_idle_close_by_peer_total 1964
telemt_me_route_drop_no_conn_total 20616
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79489
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 172
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1894
telemt_me_writer_restored_same_endpoint_total 1858
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 79405
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 826577924 (788.29 MB)
telemt_user_octets_to_client{user="hello"} 26955443300 (25.10 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 10815.9 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84415
telemt_connections_bad_total 24119
telemt_handshake_timeouts_total 1666
telemt_upstream_connect_attempt_total 3854
telemt_upstream_connect_success_total 3767
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 3854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4522
telemt_me_reconnect_success_total 3217
telemt_me_reader_eof_total 3334
telemt_me_idle_close_by_peer_total 3334
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 15153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57239
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 22
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
telemt_me_writer_removed_unexpected_total 3285
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 3200
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 57241
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 332282076 (316.89 MB)
telemt_user_octets_to_client{user="hello"} 11516014304 (10.73 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 10816.6 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48462
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 664
telemt_upstream_connect_attempt_total 2319
telemt_upstream_connect_success_total 2309
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1771
telemt_me_reconnect_success_total 1763
telemt_me_reader_eof_total 1852
telemt_me_idle_close_by_peer_total 1852
telemt_me_route_drop_no_conn_total 12090
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46590
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 184
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1780
telemt_me_writer_restored_same_endpoint_total 1755
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 46591
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 345943632 (329.92 MB)
telemt_user_octets_to_client{user="hello"} 17386765276 (16.19 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 31
```