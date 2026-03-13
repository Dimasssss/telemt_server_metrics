# Server Metrics 2026-03-13 03:50:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 78739.0 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2159044
telemt_connections_bad_total 28006
telemt_handshake_timeouts_total 22984
telemt_upstream_connect_attempt_total 15610
telemt_upstream_connect_success_total 15523
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 15610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 1298
telemt_me_reconnect_attempts_total 20456
telemt_me_reconnect_success_total 11593
telemt_me_reader_eof_total 12519
telemt_me_idle_close_by_peer_total 12518
telemt_me_route_drop_no_conn_total 826955
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1986110
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8823
telemt_desync_full_logged_total 2294
telemt_desync_suppressed_total 6529
telemt_desync_frames_bucket_total{bucket="1_2"} 2318
telemt_desync_frames_bucket_total{bucket="3_10"} 3181
telemt_desync_frames_bucket_total{bucket="gt_10"} 3324
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12030
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11580
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 1985552
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 28814056848 (26.84 GB)
telemt_user_octets_to_client{user="hello"} 684486872772 (637.48 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 108359.5 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 879454
telemt_connections_bad_total 11846
telemt_handshake_timeouts_total 39203
telemt_upstream_connect_attempt_total 27627
telemt_upstream_connect_success_total 27598
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3466
telemt_me_reconnect_attempts_total 20663
telemt_me_reconnect_success_total 20551
telemt_me_reader_eof_total 21901
telemt_me_idle_close_by_peer_total 21901
telemt_me_route_drop_no_conn_total 280847
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 792406
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3132
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 2147
telemt_desync_frames_bucket_total{bucket="1_2"} 1269
telemt_desync_frames_bucket_total{bucket="3_10"} 1016
telemt_desync_frames_bucket_total{bucket="gt_10"} 847
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 20750
telemt_me_writer_restored_same_endpoint_total 20542
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 794309
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 12676455892 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 307371580287 (286.26 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 108359.4 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1816876
telemt_connections_bad_total 13034
telemt_handshake_timeouts_total 120103
telemt_upstream_connect_attempt_total 25262
telemt_upstream_connect_success_total 25252
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11897
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1622
telemt_me_reconnect_attempts_total 20764
telemt_me_reconnect_success_total 19498
telemt_me_reader_eof_total 20659
telemt_me_idle_close_by_peer_total 20658
telemt_me_route_drop_no_conn_total 589096
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1433264
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5095
telemt_desync_full_logged_total 1554
telemt_desync_suppressed_total 3541
telemt_desync_frames_bucket_total{bucket="1_2"} 815
telemt_desync_frames_bucket_total{bucket="3_10"} 1841
telemt_desync_frames_bucket_total{bucket="gt_10"} 2439
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19681
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19457
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 1432858
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 24862055508 (23.15 GB)
telemt_user_octets_to_client{user="hello"} 512281441033 (477.10 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 108359.7 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1129855
telemt_connections_bad_total 13158
telemt_handshake_timeouts_total 74497
telemt_upstream_connect_attempt_total 37600
telemt_upstream_connect_success_total 35319
telemt_upstream_connect_fail_total 2144
telemt_upstream_connect_attempts_per_request{bucket="1"} 37326
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2143
telemt_me_keepalive_timeout_total 11380
telemt_me_reconnect_attempts_total 32979
telemt_me_reconnect_success_total 24048
telemt_me_reader_eof_total 25966
telemt_me_idle_close_by_peer_total 25959
telemt_me_route_drop_no_conn_total 401120
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 970198
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1912
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 531
telemt_desync_frames_bucket_total{bucket="3_10"} 747
telemt_desync_frames_bucket_total{bucket="gt_10"} 634
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 24486
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24024
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 438
telemt_user_connections_total{user="hello"} 975378
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 14881460069 (13.86 GB)
telemt_user_octets_to_client{user="hello"} 385102155698 (358.65 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 108359.4 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1252784
telemt_connections_bad_total 12864
telemt_handshake_timeouts_total 10056
telemt_upstream_connect_attempt_total 34121
telemt_upstream_connect_success_total 33703
telemt_upstream_connect_fail_total 418
telemt_upstream_connect_attempts_per_request{bucket="1"} 34121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 418
telemt_me_keepalive_timeout_total 1913
telemt_me_reconnect_attempts_total 42034
telemt_me_reconnect_success_total 28303
telemt_me_reader_eof_total 29769
telemt_me_idle_close_by_peer_total 29769
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 466192
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1158431
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4279
telemt_desync_full_logged_total 1530
telemt_desync_suppressed_total 2749
telemt_desync_frames_bucket_total{bucket="1_2"} 1295
telemt_desync_frames_bucket_total{bucket="3_10"} 1400
telemt_desync_frames_bucket_total{bucket="gt_10"} 1584
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 29058
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28253
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 755
telemt_user_connections_total{user="hello"} 1158285
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 14256520436 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 398554297252 (371.18 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 49
```