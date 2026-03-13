# Server Metrics 2026-03-13 14:55:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 118584.4 (32h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3662218
telemt_connections_bad_total 37408
telemt_handshake_timeouts_total 73405
telemt_upstream_connect_attempt_total 23117
telemt_upstream_connect_success_total 22987
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 23117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 2175
telemt_me_reconnect_attempts_total 27187
telemt_me_reconnect_success_total 17100
telemt_me_reader_eof_total 18380
telemt_me_idle_close_by_peer_total 18379
telemt_me_route_drop_no_conn_total 1356787
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3354421
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13777
telemt_desync_full_logged_total 3624
telemt_desync_suppressed_total 10153
telemt_desync_frames_bucket_total{bucket="1_2"} 3482
telemt_desync_frames_bucket_total{bucket="3_10"} 5217
telemt_desync_frames_bucket_total{bucket="gt_10"} 5078
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 17652
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17087
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 3354134
telemt_user_connections_current{user="hello"} 1737
telemt_user_octets_from_client{user="hello"} 45933389852 (42.78 GB)
telemt_user_octets_to_client{user="hello"} 1059977876080 (987.18 GB)
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18248.1 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258697
telemt_connections_bad_total 14481
telemt_handshake_timeouts_total 6345
telemt_upstream_connect_attempt_total 4441
telemt_upstream_connect_success_total 4357
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 4441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 5676
telemt_me_reconnect_success_total 3386
telemt_me_reader_eof_total 3593
telemt_me_idle_close_by_peer_total 3593
telemt_me_route_drop_no_conn_total 93543
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231082
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 901
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 676
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 446
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3494
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3379
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 231110
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 2366392724 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 65305789292 (60.82 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 148204.8 (41h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2719378
telemt_connections_bad_total 27398
telemt_handshake_timeouts_total 180726
telemt_upstream_connect_attempt_total 33358
telemt_upstream_connect_success_total 33348
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3248
telemt_me_reconnect_attempts_total 28189
telemt_me_reconnect_success_total 25642
telemt_me_reader_eof_total 27189
telemt_me_idle_close_by_peer_total 27188
telemt_me_route_drop_no_conn_total 916082
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2227420
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7990
telemt_desync_full_logged_total 2615
telemt_desync_suppressed_total 5375
telemt_desync_frames_bucket_total{bucket="1_2"} 1263
telemt_desync_frames_bucket_total{bucket="3_10"} 2915
telemt_desync_frames_bucket_total{bucket="gt_10"} 3812
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 25940
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25601
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 2226787
telemt_user_connections_current{user="hello"} 1004
telemt_user_octets_from_client{user="hello"} 36853775600 (34.32 GB)
telemt_user_octets_to_client{user="hello"} 786740252121 (732.71 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 148205.3 (41h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1734732
telemt_connections_bad_total 18125
telemt_handshake_timeouts_total 130471
telemt_upstream_connect_attempt_total 46791
telemt_upstream_connect_success_total 44463
telemt_upstream_connect_fail_total 2191
telemt_upstream_connect_attempts_per_request{bucket="1"} 46517
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2190
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11850
telemt_me_reconnect_attempts_total 40209
telemt_me_reconnect_success_total 31239
telemt_me_reader_eof_total 33582
telemt_me_idle_close_by_peer_total 33575
telemt_me_route_drop_no_conn_total 619706
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1448065
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2917
telemt_desync_full_logged_total 941
telemt_desync_suppressed_total 1976
telemt_desync_frames_bucket_total{bucket="1_2"} 776
telemt_desync_frames_bucket_total{bucket="3_10"} 1216
telemt_desync_frames_bucket_total{bucket="gt_10"} 925
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 31754
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31215
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 515
telemt_user_connections_total{user="hello"} 1452784
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 22698557653 (21.14 GB)
telemt_user_octets_to_client{user="hello"} 557223173798 (518.95 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17640.7 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279866
telemt_connections_bad_total 3922
telemt_handshake_timeouts_total 2679
telemt_upstream_connect_attempt_total 3793
telemt_upstream_connect_success_total 3674
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 3793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 12019
telemt_me_reconnect_success_total 2756
telemt_me_reader_eof_total 3078
telemt_me_idle_close_by_peer_total 3078
telemt_me_route_drop_no_conn_total 109989
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261448
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 815
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 552
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3055
telemt_me_refill_failed_total 288
telemt_me_writer_restored_same_endpoint_total 2752
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 261427
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 3021213864 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 85419556104 (79.55 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 116
```