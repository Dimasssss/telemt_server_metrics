# Server Metrics 2026-03-12 01:14:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 12544.1 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103071
telemt_connections_bad_total 1340
telemt_handshake_timeouts_total 338
telemt_upstream_connect_attempt_total 2925
telemt_upstream_connect_success_total 2925
telemt_upstream_connect_attempts_per_request{bucket="1"} 2925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2295
telemt_me_reconnect_success_total 2287
telemt_me_reader_eof_total 2402
telemt_me_idle_close_by_peer_total 2402
telemt_me_route_drop_no_conn_total 38392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97933
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2316
telemt_me_writer_restored_same_endpoint_total 2271
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 97825
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 691454392 (659.42 MB)
telemt_user_octets_to_client{user="hello"} 28058762056 (26.13 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 12544.7 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35647
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 400
telemt_upstream_connect_attempt_total 3683
telemt_upstream_connect_success_total 3680
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2868
telemt_me_reconnect_success_total 2846
telemt_me_reader_eof_total 3005
telemt_me_idle_close_by_peer_total 3005
telemt_me_route_drop_no_conn_total 9965
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33747
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2866
telemt_me_writer_restored_same_endpoint_total 2837
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 33926
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 614179015 (585.73 MB)
telemt_user_octets_to_client{user="hello"} 12340213174 (11.49 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 12544.6 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117811
telemt_connections_bad_total 857
telemt_handshake_timeouts_total 10039
telemt_upstream_connect_attempt_total 4049
telemt_upstream_connect_success_total 4047
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 3092
telemt_me_reconnect_success_total 3043
telemt_me_reader_eof_total 3109
telemt_me_idle_close_by_peer_total 3109
telemt_me_route_drop_no_conn_total 18880
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59925
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 101
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2982
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3002
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 60270
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 593560092 (566.06 MB)
telemt_user_octets_to_client{user="hello"} 23058413005 (21.47 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 12545.1 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55833
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 1097
telemt_upstream_connect_attempt_total 3807
telemt_upstream_connect_success_total 3789
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 3156
telemt_me_reconnect_success_total 3145
telemt_me_reader_eof_total 3304
telemt_me_idle_close_by_peer_total 3304
telemt_me_route_drop_no_conn_total 19137
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53868
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3164
telemt_me_writer_restored_same_endpoint_total 3124
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 53862
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 302110624 (288.12 MB)
telemt_user_octets_to_client{user="hello"} 12870937636 (11.99 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12544.7 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71133
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 568
telemt_upstream_connect_attempt_total 5031
telemt_upstream_connect_success_total 4990
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 5031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 5827
telemt_me_reconnect_success_total 4335
telemt_me_reader_eof_total 4482
telemt_me_idle_close_by_peer_total 4482
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 17401
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67113
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 168
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4407
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4327
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 67095
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 311645472 (297.21 MB)
telemt_user_octets_to_client{user="hello"} 15106175604 (14.07 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 33
```