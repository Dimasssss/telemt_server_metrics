# Server Metrics 2026-03-12 04:27:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24173.5 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227757
telemt_connections_bad_total 1387
telemt_handshake_timeouts_total 3686
telemt_upstream_connect_attempt_total 5486
telemt_upstream_connect_success_total 5486
telemt_upstream_connect_attempts_per_request{bucket="1"} 5486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 4294
telemt_me_reconnect_success_total 4277
telemt_me_reader_eof_total 4519
telemt_me_idle_close_by_peer_total 4519
telemt_me_route_drop_no_conn_total 81785
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216545
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 444
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 324
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4322
telemt_me_writer_restored_same_endpoint_total 4261
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 216300
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 1974669256 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 67459027652 (62.83 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24174.2 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77027
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 1422
telemt_upstream_connect_attempt_total 6705
telemt_upstream_connect_success_total 6702
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 5328
telemt_me_reconnect_success_total 5296
telemt_me_reader_eof_total 5623
telemt_me_idle_close_by_peer_total 5623
telemt_me_route_drop_no_conn_total 22175
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69870
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 197
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5338
telemt_me_writer_restored_same_endpoint_total 5287
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 70057
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 1139744543 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 23436429986 (21.83 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 24174.2 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353687
telemt_connections_bad_total 1782
telemt_handshake_timeouts_total 22347
telemt_upstream_connect_attempt_total 7028
telemt_upstream_connect_success_total 7026
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 5508
telemt_me_reconnect_success_total 5450
telemt_me_reader_eof_total 5685
telemt_me_idle_close_by_peer_total 5685
telemt_me_route_drop_no_conn_total 40843
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129548
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 423
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5418
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5409
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 129866
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 1183231764 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 40368144981 (37.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 24174.6 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115213
telemt_connections_bad_total 1358
telemt_handshake_timeouts_total 7151
telemt_upstream_connect_attempt_total 7182
telemt_upstream_connect_success_total 7151
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 7182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 5956
telemt_me_reconnect_success_total 5935
telemt_me_reader_eof_total 6296
telemt_me_idle_close_by_peer_total 6296
telemt_me_route_drop_no_conn_total 38397
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105181
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5971
telemt_me_writer_restored_same_endpoint_total 5914
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 105165
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 828035712 (789.68 MB)
telemt_user_octets_to_client{user="hello"} 29782950044 (27.74 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 24174.2 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134411
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 778
telemt_upstream_connect_attempt_total 8995
telemt_upstream_connect_success_total 8904
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 8995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 9178
telemt_me_reconnect_success_total 7676
telemt_me_reader_eof_total 7977
telemt_me_idle_close_by_peer_total 7977
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 36930
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128581
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 485
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 7784
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7659
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 128558
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 859670732 (819.85 MB)
telemt_user_octets_to_client{user="hello"} 28117318816 (26.19 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 52
```