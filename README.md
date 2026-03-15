# Server Metrics 2026-03-15 03:06:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 17537.7 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213871
telemt_connections_bad_total 2913
telemt_handshake_timeouts_total 652
telemt_upstream_connect_attempt_total 3733
telemt_upstream_connect_success_total 3719
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2838
telemt_me_reconnect_success_total 2825
telemt_me_reader_eof_total 2983
telemt_me_idle_close_by_peer_total 2983
telemt_me_route_drop_no_conn_total 66001
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189317
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 519
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 205
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2856
telemt_me_writer_restored_same_endpoint_total 2814
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 189296
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 2017266188 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 68504302284 (63.80 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 17538.4 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86687
telemt_connections_bad_total 14572
telemt_handshake_timeouts_total 3703
telemt_upstream_connect_attempt_total 5177
telemt_upstream_connect_success_total 5154
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 3968
telemt_me_reconnect_success_total 3948
telemt_me_reader_eof_total 4149
telemt_me_idle_close_by_peer_total 4149
telemt_me_route_drop_no_conn_total 17025
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66231
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3936
telemt_me_writer_restored_same_endpoint_total 3940
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 66527
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1605186855 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 20782866984 (19.36 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 17538.5 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147177
telemt_connections_bad_total 3081
telemt_handshake_timeouts_total 13473
telemt_upstream_connect_attempt_total 4107
telemt_upstream_connect_success_total 4089
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3204
telemt_me_reconnect_success_total 3191
telemt_me_reader_eof_total 3367
telemt_me_idle_close_by_peer_total 3367
telemt_me_route_drop_no_conn_total 32013
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127853
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3223
telemt_me_writer_restored_same_endpoint_total 3172
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 127762
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 1129057268 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 39811315612 (37.08 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 17538.3 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120605
telemt_connections_bad_total 29503
telemt_handshake_timeouts_total 3455
telemt_upstream_connect_attempt_total 6254
telemt_upstream_connect_success_total 6124
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 6254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8773
telemt_me_reconnect_success_total 5222
telemt_me_reader_eof_total 5501
telemt_me_idle_close_by_peer_total 5501
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 23970
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85838
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5379
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5203
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 85850
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 518611896 (494.59 MB)
telemt_user_octets_to_client{user="hello"} 23655112580 (22.03 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 17539.0 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73299
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 969
telemt_upstream_connect_attempt_total 4043
telemt_upstream_connect_success_total 4025
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3139
telemt_me_reconnect_success_total 3126
telemt_me_reader_eof_total 3327
telemt_me_idle_close_by_peer_total 3327
telemt_me_route_drop_no_conn_total 18937
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70071
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 237
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 170
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3153
telemt_me_writer_restored_same_endpoint_total 3118
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 70071
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 595424124 (567.84 MB)
telemt_user_octets_to_client{user="hello"} 22592060620 (21.04 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 35
```