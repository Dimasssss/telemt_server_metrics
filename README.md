# Server Metrics 2026-03-12 04:32:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24479.7 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232646
telemt_connections_bad_total 1387
telemt_handshake_timeouts_total 3739
telemt_upstream_connect_attempt_total 5581
telemt_upstream_connect_success_total 5581
telemt_upstream_connect_attempts_per_request{bucket="1"} 5581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 4346
telemt_me_reconnect_success_total 4329
telemt_me_reader_eof_total 4580
telemt_me_idle_close_by_peer_total 4580
telemt_me_route_drop_no_conn_total 83505
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221260
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 452
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 328
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4374
telemt_me_writer_restored_same_endpoint_total 4313
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 221008
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 2016424784 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 68682073672 (63.97 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24480.4 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78481
telemt_connections_bad_total 268
telemt_handshake_timeouts_total 1445
telemt_upstream_connect_attempt_total 6805
telemt_upstream_connect_success_total 6802
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 5385
telemt_me_reconnect_success_total 5353
telemt_me_reader_eof_total 5690
telemt_me_idle_close_by_peer_total 5690
telemt_me_route_drop_no_conn_total 22554
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71152
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 201
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5395
telemt_me_writer_restored_same_endpoint_total 5344
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 71339
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 1155437679 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 24566838282 (22.88 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 24480.3 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357149
telemt_connections_bad_total 1783
telemt_handshake_timeouts_total 22667
telemt_upstream_connect_attempt_total 7129
telemt_upstream_connect_success_total 7127
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 5566
telemt_me_reconnect_success_total 5507
telemt_me_reader_eof_total 5755
telemt_me_idle_close_by_peer_total 5755
telemt_me_route_drop_no_conn_total 43084
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132632
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 437
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 275
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5477
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5466
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 132949
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 1214538736 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 41185231961 (38.36 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 24480.6 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117162
telemt_connections_bad_total 1640
telemt_handshake_timeouts_total 7322
telemt_upstream_connect_attempt_total 7289
telemt_upstream_connect_success_total 7256
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 6017
telemt_me_reconnect_success_total 5995
telemt_me_reader_eof_total 6366
telemt_me_idle_close_by_peer_total 6366
telemt_me_route_drop_no_conn_total 38957
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106664
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6033
telemt_me_writer_restored_same_endpoint_total 5974
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 106647
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 842894668 (803.85 MB)
telemt_user_octets_to_client{user="hello"} 30163827260 (28.09 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 24480.5 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136478
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 796
telemt_upstream_connect_attempt_total 9116
telemt_upstream_connect_success_total 9016
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 9116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 9247
telemt_me_reconnect_success_total 7745
telemt_me_reader_eof_total 8048
telemt_me_idle_close_by_peer_total 8048
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 37594
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130516
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 491
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 7855
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7728
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 130493
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 878463648 (837.77 MB)
telemt_user_octets_to_client{user="hello"} 28724899828 (26.75 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 50
```