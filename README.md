# Server Metrics 2026-03-13 16:01:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 122582.5 (34h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3847616
telemt_connections_bad_total 37436
telemt_handshake_timeouts_total 89615
telemt_upstream_connect_attempt_total 23826
telemt_upstream_connect_success_total 23689
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 23826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 2209
telemt_me_reconnect_attempts_total 27674
telemt_me_reconnect_success_total 17584
telemt_me_reader_eof_total 18898
telemt_me_idle_close_by_peer_total 18897
telemt_me_route_drop_no_conn_total 1425548
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3517628
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14057
telemt_desync_full_logged_total 3717
telemt_desync_suppressed_total 10340
telemt_desync_frames_bucket_total{bucket="1_2"} 3520
telemt_desync_frames_bucket_total{bucket="3_10"} 5315
telemt_desync_frames_bucket_total{bucket="gt_10"} 5222
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18138
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17571
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3517438
telemt_user_connections_current{user="hello"} 1944
telemt_user_octets_from_client{user="hello"} 47797455800 (44.51 GB)
telemt_user_octets_to_client{user="hello"} 1102717580196 (1.00 TB)
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22246.0 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322751
telemt_connections_bad_total 18548
telemt_handshake_timeouts_total 8826
telemt_upstream_connect_attempt_total 5150
telemt_upstream_connect_success_total 5064
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 5150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 6208
telemt_me_reconnect_success_total 3917
telemt_me_reader_eof_total 4163
telemt_me_idle_close_by_peer_total 4163
telemt_me_route_drop_no_conn_total 116967
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287181
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1081
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 801
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4041
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3910
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 287207
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 2877646628 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 80921175588 (75.36 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 152202.7 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2839360
telemt_connections_bad_total 27807
telemt_handshake_timeouts_total 189349
telemt_upstream_connect_attempt_total 34100
telemt_upstream_connect_success_total 34090
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3284
telemt_me_reconnect_attempts_total 28714
telemt_me_reconnect_success_total 26164
telemt_me_reader_eof_total 27746
telemt_me_idle_close_by_peer_total 27745
telemt_me_route_drop_no_conn_total 959823
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2334399
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8254
telemt_desync_full_logged_total 2729
telemt_desync_suppressed_total 5525
telemt_desync_frames_bucket_total{bucket="1_2"} 1326
telemt_desync_frames_bucket_total{bucket="3_10"} 2997
telemt_desync_frames_bucket_total{bucket="gt_10"} 3931
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 26472
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26123
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 2333794
telemt_user_connections_current{user="hello"} 1127
telemt_user_octets_from_client{user="hello"} 38357806768 (35.72 GB)
telemt_user_octets_to_client{user="hello"} 814484534989 (758.55 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 152203.4 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1807077
telemt_connections_bad_total 18156
telemt_handshake_timeouts_total 143652
telemt_upstream_connect_attempt_total 47853
telemt_upstream_connect_success_total 45519
telemt_upstream_connect_fail_total 2197
telemt_upstream_connect_attempts_per_request{bucket="1"} 47579
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2196
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11885
telemt_me_reconnect_attempts_total 41054
telemt_me_reconnect_success_total 32081
telemt_me_reader_eof_total 34464
telemt_me_idle_close_by_peer_total 34457
telemt_me_route_drop_no_conn_total 648405
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1505206
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3013
telemt_desync_full_logged_total 975
telemt_desync_suppressed_total 2038
telemt_desync_frames_bucket_total{bucket="1_2"} 808
telemt_desync_frames_bucket_total{bucket="3_10"} 1243
telemt_desync_frames_bucket_total{bucket="gt_10"} 962
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 32609
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32057
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 528
telemt_user_connections_total{user="hello"} 1509914
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 23429397361 (21.82 GB)
telemt_user_octets_to_client{user="hello"} 576562361182 (536.97 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21638.8 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348633
telemt_connections_bad_total 4083
telemt_handshake_timeouts_total 3169
telemt_upstream_connect_attempt_total 4645
telemt_upstream_connect_success_total 4506
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 4644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 13984
telemt_me_reconnect_success_total 3410
telemt_me_reader_eof_total 3810
telemt_me_idle_close_by_peer_total 3810
telemt_me_route_drop_no_conn_total 137867
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326703
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 768
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3761
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3406
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 351
telemt_user_connections_total{user="hello"} 326678
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 3780513156 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 105316442200 (98.08 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 113
```