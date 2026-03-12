# Server Metrics 2026-03-12 02:20:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16521.4 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136158
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 2449
telemt_upstream_connect_attempt_total 3848
telemt_upstream_connect_success_total 3848
telemt_upstream_connect_attempts_per_request{bucket="1"} 3848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 3002
telemt_me_reconnect_success_total 2990
telemt_me_reader_eof_total 3158
telemt_me_idle_close_by_peer_total 3158
telemt_me_route_drop_no_conn_total 48868
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128194
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 206
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3025
telemt_me_writer_restored_same_endpoint_total 2974
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 128048
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 901213392 (859.46 MB)
telemt_user_octets_to_client{user="hello"} 38005796112 (35.40 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 16521.9 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46476
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 777
telemt_upstream_connect_attempt_total 4818
telemt_upstream_connect_success_total 4815
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 3788
telemt_me_reconnect_success_total 3762
telemt_me_reader_eof_total 3989
telemt_me_idle_close_by_peer_total 3989
telemt_me_route_drop_no_conn_total 12529
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43248
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 50
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3791
telemt_me_writer_restored_same_endpoint_total 3753
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 43427
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 715378771 (682.24 MB)
telemt_user_octets_to_client{user="hello"} 15102617150 (14.07 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 16521.8 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211120
telemt_connections_bad_total 1145
telemt_handshake_timeouts_total 14449
telemt_upstream_connect_attempt_total 5137
telemt_upstream_connect_success_total 5135
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 3965
telemt_me_reconnect_success_total 3912
telemt_me_reader_eof_total 4048
telemt_me_idle_close_by_peer_total 4048
telemt_me_route_drop_no_conn_total 24635
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79036
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3864
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3871
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 79377
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 688011796 (656.14 MB)
telemt_user_octets_to_client{user="hello"} 26484985629 (24.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 16522.0 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69762
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 1639
telemt_upstream_connect_attempt_total 4963
telemt_upstream_connect_success_total 4936
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 4088
telemt_me_reconnect_success_total 4073
telemt_me_reader_eof_total 4312
telemt_me_idle_close_by_peer_total 4312
telemt_me_route_drop_no_conn_total 24683
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67087
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 107
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4099
telemt_me_writer_restored_same_endpoint_total 4052
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 67078
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 396531332 (378.16 MB)
telemt_user_octets_to_client{user="hello"} 15245784760 (14.20 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16522.0 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89948
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 618
telemt_upstream_connect_attempt_total 6234
telemt_upstream_connect_success_total 6172
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 6794
telemt_me_reconnect_success_total 5299
telemt_me_reader_eof_total 5504
telemt_me_idle_close_by_peer_total 5504
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 22451
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85499
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 305
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5382
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5285
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 85478
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 482515340 (460.16 MB)
telemt_user_octets_to_client{user="hello"} 18104298984 (16.86 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 44
```