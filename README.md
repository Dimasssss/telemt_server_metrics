# Server Metrics 2026-03-12 03:57:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22337.2 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199660
telemt_connections_bad_total 1368
telemt_handshake_timeouts_total 3514
telemt_upstream_connect_attempt_total 5106
telemt_upstream_connect_success_total 5106
telemt_upstream_connect_attempts_per_request{bucket="1"} 5106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 4000
telemt_me_reconnect_success_total 3984
telemt_me_reader_eof_total 4207
telemt_me_idle_close_by_peer_total 4207
telemt_me_route_drop_no_conn_total 71532
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189204
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 377
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 275
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4026
telemt_me_writer_restored_same_endpoint_total 3968
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 188985
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 1727076012 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 59284951148 (55.21 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22337.8 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66422
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1261
telemt_upstream_connect_attempt_total 6271
telemt_upstream_connect_success_total 6268
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 4980
telemt_me_reconnect_success_total 4948
telemt_me_reader_eof_total 5250
telemt_me_idle_close_by_peer_total 5250
telemt_me_route_drop_no_conn_total 18991
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62032
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4986
telemt_me_writer_restored_same_endpoint_total 4939
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 62210
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 1026383339 (978.84 MB)
telemt_user_octets_to_client{user="hello"} 21148999026 (19.70 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 22337.6 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336265
telemt_connections_bad_total 1754
telemt_handshake_timeouts_total 20315
telemt_upstream_connect_attempt_total 6619
telemt_upstream_connect_success_total 6617
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2843
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 5188
telemt_me_reconnect_success_total 5132
telemt_me_reader_eof_total 5347
telemt_me_idle_close_by_peer_total 5347
telemt_me_route_drop_no_conn_total 36040
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115044
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 348
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 224
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5098
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5091
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 115360
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 1054995624 (1006.12 MB)
telemt_user_octets_to_client{user="hello"} 35158584793 (32.74 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 22338.1 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102244
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 5590
telemt_upstream_connect_attempt_total 6642
telemt_upstream_connect_success_total 6614
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 5506
telemt_me_reconnect_success_total 5486
telemt_me_reader_eof_total 5817
telemt_me_idle_close_by_peer_total 5817
telemt_me_route_drop_no_conn_total 34727
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95089
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5521
telemt_me_writer_restored_same_endpoint_total 5465
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 95081
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 716823572 (683.62 MB)
telemt_user_octets_to_client{user="hello"} 24799683904 (23.10 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22337.7 (6h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121746
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 722
telemt_upstream_connect_attempt_total 8262
telemt_upstream_connect_success_total 8178
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 8262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 8539
telemt_me_reconnect_success_total 7039
telemt_me_reader_eof_total 7301
telemt_me_idle_close_by_peer_total 7301
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 32569
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116418
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 435
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 7138
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7022
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 116393
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 715127180 (682.00 MB)
telemt_user_octets_to_client{user="hello"} 25380159668 (23.64 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 50
```