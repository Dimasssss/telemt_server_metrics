# Server Metrics 2026-03-12 12:06:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22095.0 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 751216
telemt_connections_bad_total 1523
telemt_handshake_timeouts_total 4458
telemt_upstream_connect_attempt_total 4371
telemt_upstream_connect_success_total 4343
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 7096
telemt_me_reconnect_success_total 3203
telemt_me_reader_eof_total 3445
telemt_me_idle_close_by_peer_total 3445
telemt_me_route_drop_no_conn_total 265044
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724520
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3724
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 2786
telemt_desync_frames_bucket_total{bucket="1_2"} 951
telemt_desync_frames_bucket_total{bucket="3_10"} 1350
telemt_desync_frames_bucket_total{bucket="gt_10"} 1423
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3358
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3190
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 724368
telemt_user_connections_current{user="hello"} 1403
telemt_user_octets_from_client{user="hello"} 12591779128 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 201130671188 (187.32 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51715.5 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387330
telemt_connections_bad_total 4723
telemt_handshake_timeouts_total 20396
telemt_upstream_connect_attempt_total 12646
telemt_upstream_connect_success_total 12639
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 12646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1052
telemt_me_reconnect_attempts_total 9923
telemt_me_reconnect_success_total 9866
telemt_me_reader_eof_total 10490
telemt_me_idle_close_by_peer_total 10490
telemt_me_route_drop_no_conn_total 110327
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340860
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1088
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 412
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 9957
telemt_me_writer_restored_same_endpoint_total 9857
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 341328
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 4658964163 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 120184354782 (111.93 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 51715.3 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 883431
telemt_connections_bad_total 4943
telemt_handshake_timeouts_total 66555
telemt_upstream_connect_attempt_total 12737
telemt_upstream_connect_success_total 12732
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5711
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 858
telemt_me_reconnect_attempts_total 9871
telemt_me_reconnect_success_total 9788
telemt_me_reader_eof_total 10299
telemt_me_idle_close_by_peer_total 10299
telemt_me_route_drop_no_conn_total 213339
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 596187
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2771
telemt_desync_full_logged_total 821
telemt_desync_suppressed_total 1950
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 974
telemt_desync_frames_bucket_total{bucket="gt_10"} 1417
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9811
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9747
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 596421
telemt_user_connections_current{user="hello"} 926
telemt_user_octets_from_client{user="hello"} 7846808088 (7.31 GB)
telemt_user_octets_to_client{user="hello"} 189565770457 (176.55 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 51715.8 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491344
telemt_connections_bad_total 7618
telemt_handshake_timeouts_total 46287
telemt_upstream_connect_attempt_total 13868
telemt_upstream_connect_success_total 13812
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 13868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1263
telemt_me_reconnect_attempts_total 11266
telemt_me_reconnect_success_total 11220
telemt_me_reader_eof_total 11875
telemt_me_idle_close_by_peer_total 11875
telemt_me_route_drop_no_conn_total 160497
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407472
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 828
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 346
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11302
telemt_me_writer_restored_same_endpoint_total 11199
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 407295
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 4636520600 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 153849380860 (143.28 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51715.6 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549821
telemt_connections_bad_total 1694
telemt_handshake_timeouts_total 4257
telemt_upstream_connect_attempt_total 16889
telemt_upstream_connect_success_total 16689
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 16889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 956
telemt_me_reconnect_attempts_total 18656
telemt_me_reconnect_success_total 14090
telemt_me_reader_eof_total 14706
telemt_me_idle_close_by_peer_total 14706
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 182637
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514247
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2153
telemt_desync_full_logged_total 723
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 748
telemt_desync_frames_bucket_total{bucket="gt_10"} 774
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14370
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 14063
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 514167
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 5977611300 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 127728577616 (118.96 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 122
```