# Server Metrics 2026-03-13 14:44:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 117973.1 (32h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3634283
telemt_connections_bad_total 37403
telemt_handshake_timeouts_total 72413
telemt_upstream_connect_attempt_total 23014
telemt_upstream_connect_success_total 22884
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 23014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 2164
telemt_me_reconnect_attempts_total 27101
telemt_me_reconnect_success_total 17015
telemt_me_reader_eof_total 18291
telemt_me_idle_close_by_peer_total 18290
telemt_me_route_drop_no_conn_total 1345790
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3328155
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13651
telemt_desync_full_logged_total 3587
telemt_desync_suppressed_total 10064
telemt_desync_frames_bucket_total{bucket="1_2"} 3461
telemt_desync_frames_bucket_total{bucket="3_10"} 5168
telemt_desync_frames_bucket_total{bucket="gt_10"} 5022
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17567
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17002
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 3327873
telemt_user_connections_current{user="hello"} 1749
telemt_user_octets_from_client{user="hello"} 45602263524 (42.47 GB)
telemt_user_octets_to_client{user="hello"} 1053755069512 (981.39 GB)
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17636.9 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249163
telemt_connections_bad_total 14177
telemt_handshake_timeouts_total 6092
telemt_upstream_connect_attempt_total 4301
telemt_upstream_connect_success_total 4221
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 4301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 5583
telemt_me_reconnect_success_total 3293
telemt_me_reader_eof_total 3492
telemt_me_idle_close_by_peer_total 3492
telemt_me_route_drop_no_conn_total 90108
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222366
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 872
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 658
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3401
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3286
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 222394
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 2293966012 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 63620447012 (59.25 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 147593.7 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2702319
telemt_connections_bad_total 27316
telemt_handshake_timeouts_total 179625
telemt_upstream_connect_attempt_total 33211
telemt_upstream_connect_success_total 33201
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3244
telemt_me_reconnect_attempts_total 28085
telemt_me_reconnect_success_total 25538
telemt_me_reader_eof_total 27076
telemt_me_idle_close_by_peer_total 27075
telemt_me_route_drop_no_conn_total 910287
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2211824
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7966
telemt_desync_full_logged_total 2605
telemt_desync_suppressed_total 5361
telemt_desync_frames_bucket_total{bucket="1_2"} 1256
telemt_desync_frames_bucket_total{bucket="3_10"} 2908
telemt_desync_frames_bucket_total{bucket="gt_10"} 3802
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 25835
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25497
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 2211208
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 36688354000 (34.17 GB)
telemt_user_octets_to_client{user="hello"} 783185735729 (729.40 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 147594.1 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1720419
telemt_connections_bad_total 18077
telemt_handshake_timeouts_total 125328
telemt_upstream_connect_attempt_total 46642
telemt_upstream_connect_success_total 44315
telemt_upstream_connect_fail_total 2190
telemt_upstream_connect_attempts_per_request{bucket="1"} 46368
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2189
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11849
telemt_me_reconnect_attempts_total 40104
telemt_me_reconnect_success_total 31135
telemt_me_reader_eof_total 33472
telemt_me_idle_close_by_peer_total 33465
telemt_me_route_drop_no_conn_total 615388
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1439401
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2903
telemt_desync_full_logged_total 937
telemt_desync_suppressed_total 1966
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 1210
telemt_desync_frames_bucket_total{bucket="gt_10"} 918
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 31650
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31111
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 515
telemt_user_connections_total{user="hello"} 1444116
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 22590005477 (21.04 GB)
telemt_user_octets_to_client{user="hello"} 554993047846 (516.88 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17029.6 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269230
telemt_connections_bad_total 3909
telemt_handshake_timeouts_total 2598
telemt_upstream_connect_attempt_total 3622
telemt_upstream_connect_success_total 3510
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 3622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 10714
telemt_me_reconnect_success_total 2637
telemt_me_reader_eof_total 2919
telemt_me_idle_close_by_peer_total 2919
telemt_me_route_drop_no_conn_total 105805
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251366
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 803
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2896
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2633
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 251348
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 2854644220 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 82399291764 (76.74 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 98
```