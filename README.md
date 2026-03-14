# Server Metrics 2026-03-14 19:33:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 22518.6 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 894156
telemt_connections_bad_total 40371
telemt_handshake_timeouts_total 13222
telemt_upstream_connect_attempt_total 4150
telemt_upstream_connect_success_total 4133
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3779
telemt_me_reconnect_success_total 2975
telemt_me_reader_eof_total 3130
telemt_me_idle_close_by_peer_total 3130
telemt_me_route_drop_no_conn_total 342869
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790143
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2703
telemt_desync_full_logged_total 770
telemt_desync_suppressed_total 1933
telemt_desync_frames_bucket_total{bucket="1_2"} 640
telemt_desync_frames_bucket_total{bucket="3_10"} 1002
telemt_desync_frames_bucket_total{bucket="gt_10"} 1061
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3051
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2966
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 790087
telemt_user_connections_current{user="hello"} 1671
telemt_user_octets_from_client{user="hello"} 14002069040 (13.04 GB)
telemt_user_octets_to_client{user="hello"} 260539067228 (242.65 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 22533.5 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344935
telemt_connections_bad_total 23672
telemt_handshake_timeouts_total 10233
telemt_upstream_connect_attempt_total 4694
telemt_upstream_connect_success_total 4641
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 4694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 389
telemt_me_reconnect_attempts_total 4272
telemt_me_reconnect_success_total 3479
telemt_me_reader_eof_total 3638
telemt_me_idle_close_by_peer_total 3638
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 107027
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291335
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1233
telemt_desync_full_logged_total 378
telemt_desync_suppressed_total 855
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 449
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3574
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3462
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 291266
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 3933671188 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 102147610620 (95.13 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 22386.7 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719544
telemt_connections_bad_total 2884
telemt_handshake_timeouts_total 141308
telemt_upstream_connect_attempt_total 4330
telemt_upstream_connect_success_total 4315
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 7080
telemt_me_reconnect_success_total 3171
telemt_me_reader_eof_total 3407
telemt_me_idle_close_by_peer_total 3407
telemt_me_route_drop_no_conn_total 174978
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492390
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1748
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 611
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3326
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3138
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 492222
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 7228749084 (6.73 GB)
telemt_user_octets_to_client{user="hello"} 176270098620 (164.16 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 22241.0 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400043
telemt_connections_bad_total 90499
telemt_handshake_timeouts_total 47215
telemt_upstream_connect_attempt_total 5243
telemt_upstream_connect_success_total 5242
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 5024
telemt_me_reconnect_success_total 4106
telemt_me_reader_eof_total 4293
telemt_me_idle_close_by_peer_total 4293
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 92574
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255733
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 558
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 365
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4182
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4095
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 255652
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 3710838188 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 81827024088 (76.21 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 22536.3 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341149
telemt_connections_bad_total 1298
telemt_handshake_timeouts_total 3702
telemt_upstream_connect_attempt_total 4654
telemt_upstream_connect_success_total 4561
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 4654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 4088
telemt_me_reconnect_success_total 3417
telemt_me_reader_eof_total 3603
telemt_me_idle_close_by_peer_total 3603
telemt_me_route_drop_no_conn_total 108458
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315795
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 501
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3502
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3399
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 315768
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 4835022420 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 133668962532 (124.49 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 80
```