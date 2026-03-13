# Server Metrics 2026-03-13 10:49:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 103878.9 (28h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3024838
telemt_connections_bad_total 36457
telemt_handshake_timeouts_total 54335
telemt_upstream_connect_attempt_total 20521
telemt_upstream_connect_success_total 20410
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1452
telemt_me_reconnect_attempts_total 25306
telemt_me_reconnect_success_total 15234
telemt_me_reader_eof_total 16397
telemt_me_idle_close_by_peer_total 16396
telemt_me_route_drop_no_conn_total 1115727
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2761576
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11984
telemt_desync_full_logged_total 3088
telemt_desync_suppressed_total 8896
telemt_desync_frames_bucket_total{bucket="1_2"} 3062
telemt_desync_frames_bucket_total{bucket="3_10"} 4495
telemt_desync_frames_bucket_total{bucket="gt_10"} 4427
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 15757
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15221
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 2761512
telemt_user_connections_current{user="hello"} 1679
telemt_user_octets_from_client{user="hello"} 37828977540 (35.23 GB)
telemt_user_octets_to_client{user="hello"} 895917735044 (834.39 GB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 329
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 3542.4 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39450
telemt_connections_bad_total 3260
telemt_handshake_timeouts_total 923
telemt_upstream_connect_attempt_total 874
telemt_upstream_connect_success_total 806
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 667
telemt_me_reconnect_success_total 600
telemt_me_reader_eof_total 588
telemt_me_idle_close_by_peer_total 588
telemt_me_route_drop_no_conn_total 13222
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34304
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 109
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 595
telemt_me_writer_restored_same_endpoint_total 593
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 34303
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 408986012 (390.04 MB)
telemt_user_octets_to_client{user="hello"} 7841402836 (7.30 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 133499.2 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2336253
telemt_connections_bad_total 25111
telemt_handshake_timeouts_total 158131
telemt_upstream_connect_attempt_total 30444
telemt_upstream_connect_success_total 30434
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1902
telemt_me_reconnect_attempts_total 24723
telemt_me_reconnect_success_total 23433
telemt_me_reader_eof_total 24828
telemt_me_idle_close_by_peer_total 24827
telemt_me_route_drop_no_conn_total 766993
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1879621
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6186
telemt_desync_full_logged_total 1973
telemt_desync_suppressed_total 4213
telemt_desync_frames_bucket_total{bucket="1_2"} 1001
telemt_desync_frames_bucket_total{bucket="3_10"} 2255
telemt_desync_frames_bucket_total{bucket="gt_10"} 2930
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 23667
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23392
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 1879047
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 32178915632 (29.97 GB)
telemt_user_octets_to_client{user="hello"} 675025690049 (628.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 133499.6 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1476544
telemt_connections_bad_total 14245
telemt_handshake_timeouts_total 93626
telemt_upstream_connect_attempt_total 43465
telemt_upstream_connect_success_total 41152
telemt_upstream_connect_fail_total 2176
telemt_upstream_connect_attempts_per_request{bucket="1"} 43191
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2175
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11511
telemt_me_reconnect_attempts_total 37594
telemt_me_reconnect_success_total 28642
telemt_me_reader_eof_total 30827
telemt_me_idle_close_by_peer_total 30820
telemt_me_route_drop_no_conn_total 523304
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1235124
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2311
telemt_desync_full_logged_total 769
telemt_desync_suppressed_total 1542
telemt_desync_frames_bucket_total{bucket="1_2"} 644
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 790
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 29130
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28618
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 1239860
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 18792078997 (17.50 GB)
telemt_user_octets_to_client{user="hello"} 490016910966 (456.36 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2935.2 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34578
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 834
telemt_upstream_connect_success_total 809
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 454
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1825
telemt_me_reconnect_success_total 602
telemt_me_reader_eof_total 610
telemt_me_idle_close_by_peer_total 610
telemt_me_route_drop_no_conn_total 11388
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33082
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 154
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 631
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 33075
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 304238232 (290.14 MB)
telemt_user_octets_to_client{user="hello"} 11833239756 (11.02 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 160
```