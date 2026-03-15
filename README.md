# Server Metrics 2026-03-15 03:16:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 18148.3 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221132
telemt_connections_bad_total 2971
telemt_handshake_timeouts_total 801
telemt_upstream_connect_attempt_total 3849
telemt_upstream_connect_success_total 3834
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 2910
telemt_me_reconnect_success_total 2896
telemt_me_reader_eof_total 3058
telemt_me_idle_close_by_peer_total 3058
telemt_me_route_drop_no_conn_total 68428
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195834
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 530
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2929
telemt_me_writer_restored_same_endpoint_total 2885
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 195811
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 2107438840 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 70760857128 (65.90 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 18149.0 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88911
telemt_connections_bad_total 14572
telemt_handshake_timeouts_total 3749
telemt_upstream_connect_attempt_total 5374
telemt_upstream_connect_success_total 5350
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2416
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4120
telemt_me_reconnect_success_total 4099
telemt_me_reader_eof_total 4307
telemt_me_idle_close_by_peer_total 4307
telemt_me_route_drop_no_conn_total 17763
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68363
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 120
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4087
telemt_me_writer_restored_same_endpoint_total 4091
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 68659
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 1613670931 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 21207004692 (19.75 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 18149.1 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152523
telemt_connections_bad_total 3081
telemt_handshake_timeouts_total 13770
telemt_upstream_connect_attempt_total 4243
telemt_upstream_connect_success_total 4224
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3297
telemt_me_reconnect_success_total 3282
telemt_me_reader_eof_total 3464
telemt_me_idle_close_by_peer_total 3464
telemt_me_route_drop_no_conn_total 33108
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132846
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3315
telemt_me_writer_restored_same_endpoint_total 3263
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 132753
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 1182340040 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 40935872028 (38.12 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 18149.0 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123916
telemt_connections_bad_total 29975
telemt_handshake_timeouts_total 3765
telemt_upstream_connect_attempt_total 6409
telemt_upstream_connect_success_total 6276
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 6409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8882
telemt_me_reconnect_success_total 5331
telemt_me_reader_eof_total 5613
telemt_me_idle_close_by_peer_total 5613
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 25019
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88339
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
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5490
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5312
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 88348
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 546182748 (520.88 MB)
telemt_user_octets_to_client{user="hello"} 24249538760 (22.58 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 18149.8 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75764
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 972
telemt_upstream_connect_attempt_total 4193
telemt_upstream_connect_success_total 4175
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3246
telemt_me_reconnect_success_total 3233
telemt_me_reader_eof_total 3438
telemt_me_idle_close_by_peer_total 3438
telemt_me_route_drop_no_conn_total 19723
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72454
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 254
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3262
telemt_me_writer_restored_same_endpoint_total 3225
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 72452
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 613825976 (585.39 MB)
telemt_user_octets_to_client{user="hello"} 23321714188 (21.72 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 37
```