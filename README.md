# Server Metrics 2026-03-13 17:33:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 128086.3 (35h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4085031
telemt_connections_bad_total 37525
telemt_handshake_timeouts_total 101120
telemt_upstream_connect_attempt_total 27208
telemt_upstream_connect_success_total 27030
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 27208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 5684
telemt_me_reconnect_attempts_total 28389
telemt_me_reconnect_success_total 18284
telemt_me_reader_eof_total 19644
telemt_me_idle_close_by_peer_total 19643
telemt_me_route_drop_no_conn_total 1518639
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3730616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14612
telemt_desync_full_logged_total 3879
telemt_desync_suppressed_total 10733
telemt_desync_frames_bucket_total{bucket="1_2"} 3633
telemt_desync_frames_bucket_total{bucket="3_10"} 5541
telemt_desync_frames_bucket_total{bucket="gt_10"} 5438
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 18854
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18271
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 3732785
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 52658662492 (49.04 GB)
telemt_user_octets_to_client{user="hello"} 1161256794049 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 439
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 27750.3 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414755
telemt_connections_bad_total 31032
telemt_handshake_timeouts_total 10408
telemt_upstream_connect_attempt_total 7952
telemt_upstream_connect_success_total 7778
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 7952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 1582
telemt_me_reconnect_attempts_total 8348
telemt_me_reconnect_success_total 4952
telemt_me_reader_eof_total 5246
telemt_me_idle_close_by_peer_total 5245
telemt_me_route_drop_no_conn_total 157067
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361579
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1255
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 935
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5120
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4944
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 362917
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 3733110023 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 107025325232 (99.68 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 157706.9 (43h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2987824
telemt_connections_bad_total 28473
telemt_handshake_timeouts_total 200278
telemt_upstream_connect_attempt_total 35245
telemt_upstream_connect_success_total 35235
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3414
telemt_me_reconnect_attempts_total 29594
telemt_me_reconnect_success_total 27040
telemt_me_reader_eof_total 28671
telemt_me_idle_close_by_peer_total 28670
telemt_me_route_drop_no_conn_total 1017879
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2466940
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8507
telemt_desync_full_logged_total 2818
telemt_desync_suppressed_total 5689
telemt_desync_frames_bucket_total{bucket="1_2"} 1366
telemt_desync_frames_bucket_total{bucket="3_10"} 3115
telemt_desync_frames_bucket_total{bucket="gt_10"} 4026
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 27355
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26999
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 2466294
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 40538399260 (37.75 GB)
telemt_user_octets_to_client{user="hello"} 860736725133 (801.62 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 157707.4 (43h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1926791
telemt_connections_bad_total 18256
telemt_handshake_timeouts_total 178553
telemt_upstream_connect_attempt_total 49102
telemt_upstream_connect_success_total 46763
telemt_upstream_connect_fail_total 2202
telemt_upstream_connect_attempts_per_request{bucket="1"} 48828
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2201
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11967
telemt_me_reconnect_attempts_total 42026
telemt_me_reconnect_success_total 33043
telemt_me_reader_eof_total 35488
telemt_me_idle_close_by_peer_total 35481
telemt_me_route_drop_no_conn_total 683539
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1588037
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3117
telemt_desync_full_logged_total 1012
telemt_desync_suppressed_total 2105
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 1283
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 33587
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33019
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 1592728
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 24554385017 (22.87 GB)
telemt_user_octets_to_client{user="hello"} 602919583270 (561.51 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 27143.1 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444457
telemt_connections_bad_total 4546
telemt_handshake_timeouts_total 4661
telemt_upstream_connect_attempt_total 6276
telemt_upstream_connect_success_total 6072
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 6276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 854
telemt_me_reconnect_attempts_total 16605
telemt_me_reconnect_success_total 4670
telemt_me_reader_eof_total 5138
telemt_me_idle_close_by_peer_total 5138
telemt_me_route_drop_no_conn_total 171186
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415237
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1278
telemt_desync_full_logged_total 409
telemt_desync_suppressed_total 869
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 510
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5079
telemt_me_refill_failed_total 371
telemt_me_writer_restored_same_endpoint_total 4666
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 409
telemt_user_connections_total{user="hello"} 415210
telemt_user_connections_current{user="hello"} 812
telemt_user_octets_from_client{user="hello"} 4747598548 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 130342275248 (121.39 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 106
```