# Server Metrics 2026-03-12 03:06:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19275.8 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162629
telemt_connections_bad_total 1353
telemt_handshake_timeouts_total 3314
telemt_upstream_connect_attempt_total 4449
telemt_upstream_connect_success_total 4449
telemt_upstream_connect_attempts_per_request{bucket="1"} 4449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 3474
telemt_me_reconnect_success_total 3459
telemt_me_reader_eof_total 3656
telemt_me_idle_close_by_peer_total 3656
telemt_me_route_drop_no_conn_total 59141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153251
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 280
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3498
telemt_me_writer_restored_same_endpoint_total 3443
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 153078
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 1113453904 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 48491885644 (45.16 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 19276.6 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54467
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 923
telemt_upstream_connect_attempt_total 5531
telemt_upstream_connect_success_total 5528
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 4371
telemt_me_reconnect_success_total 4343
telemt_me_reader_eof_total 4609
telemt_me_idle_close_by_peer_total 4609
telemt_me_route_drop_no_conn_total 14930
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50855
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 88
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4376
telemt_me_writer_restored_same_endpoint_total 4334
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 51034
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 778612847 (742.54 MB)
telemt_user_octets_to_client{user="hello"} 18296297946 (17.04 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 19276.5 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288299
telemt_connections_bad_total 1495
telemt_handshake_timeouts_total 16801
telemt_upstream_connect_attempt_total 5864
telemt_upstream_connect_success_total 5862
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 4563
telemt_me_reconnect_success_total 4509
telemt_me_reader_eof_total 4682
telemt_me_idle_close_by_peer_total 4682
telemt_me_route_drop_no_conn_total 28919
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94066
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 219
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4468
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4468
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 94402
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 795453144 (758.60 MB)
telemt_user_octets_to_client{user="hello"} 29339412453 (27.32 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 19276.8 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85938
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 3962
telemt_upstream_connect_attempt_total 5782
telemt_upstream_connect_success_total 5754
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 4777
telemt_me_reconnect_success_total 4760
telemt_me_reader_eof_total 5045
telemt_me_idle_close_by_peer_total 5045
telemt_me_route_drop_no_conn_total 29161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80725
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 134
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4791
telemt_me_writer_restored_same_endpoint_total 4739
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 80712
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 525537004 (501.19 MB)
telemt_user_octets_to_client{user="hello"} 19273108992 (17.95 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 19276.4 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103683
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 669
telemt_upstream_connect_attempt_total 7169
telemt_upstream_connect_success_total 7095
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 7169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 7587
telemt_me_reconnect_success_total 6089
telemt_me_reader_eof_total 6331
telemt_me_idle_close_by_peer_total 6331
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 26552
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98863
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 334
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 6181
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6073
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 98840
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 599230648 (571.47 MB)
telemt_user_octets_to_client{user="hello"} 21591941824 (20.11 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 40
```