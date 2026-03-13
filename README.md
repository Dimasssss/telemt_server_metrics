# Server Metrics 2026-03-13 09:22:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 98642.9 (27h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2806366
telemt_connections_bad_total 36388
telemt_handshake_timeouts_total 39731
telemt_upstream_connect_attempt_total 19390
telemt_upstream_connect_success_total 19282
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 19390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 1395
telemt_me_reconnect_attempts_total 24446
telemt_me_reconnect_success_total 14385
telemt_me_reader_eof_total 15511
telemt_me_idle_close_by_peer_total 15510
telemt_me_route_drop_no_conn_total 1041548
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2565095
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11309
telemt_desync_full_logged_total 2927
telemt_desync_suppressed_total 8382
telemt_desync_frames_bucket_total{bucket="1_2"} 2902
telemt_desync_frames_bucket_total{bucket="3_10"} 4232
telemt_desync_frames_bucket_total{bucket="gt_10"} 4175
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 14898
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14372
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 2564727
telemt_user_connections_current{user="hello"} 1801
telemt_user_octets_from_client{user="hello"} 35834062352 (33.37 GB)
telemt_user_octets_to_client{user="hello"} 839673041048 (782.01 GB)
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 128263.3 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1148593
telemt_connections_bad_total 14328
telemt_handshake_timeouts_total 105927
telemt_upstream_connect_attempt_total 31844
telemt_upstream_connect_success_total 31813
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3687
telemt_me_reconnect_attempts_total 23923
telemt_me_reconnect_success_total 23798
telemt_me_reader_eof_total 25367
telemt_me_idle_close_by_peer_total 25367
telemt_me_route_drop_no_conn_total 352253
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 986848
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4355
telemt_desync_full_logged_total 1321
telemt_desync_suppressed_total 3034
telemt_desync_frames_bucket_total{bucket="1_2"} 1587
telemt_desync_frames_bucket_total{bucket="3_10"} 1437
telemt_desync_frames_bucket_total{bucket="gt_10"} 1331
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 24032
telemt_me_writer_restored_same_endpoint_total 23789
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 988775
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 15108138136 (14.07 GB)
telemt_user_octets_to_client{user="hello"} 363386408371 (338.43 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 128263.1 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2206183
telemt_connections_bad_total 24641
telemt_handshake_timeouts_total 147319
telemt_upstream_connect_attempt_total 29446
telemt_upstream_connect_success_total 29436
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1808
telemt_me_reconnect_attempts_total 23987
telemt_me_reconnect_success_total 22701
telemt_me_reader_eof_total 24043
telemt_me_idle_close_by_peer_total 24042
telemt_me_route_drop_no_conn_total 717779
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1763842
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5858
telemt_desync_full_logged_total 1865
telemt_desync_suppressed_total 3993
telemt_desync_frames_bucket_total{bucket="1_2"} 958
telemt_desync_frames_bucket_total{bucket="3_10"} 2136
telemt_desync_frames_bucket_total{bucket="gt_10"} 2764
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22928
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22660
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 1763274
telemt_user_connections_current{user="hello"} 976
telemt_user_octets_from_client{user="hello"} 30738826928 (28.63 GB)
telemt_user_octets_to_client{user="hello"} 636981677093 (593.24 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 128263.6 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1399336
telemt_connections_bad_total 14228
telemt_handshake_timeouts_total 85733
telemt_upstream_connect_attempt_total 42377
telemt_upstream_connect_success_total 40072
telemt_upstream_connect_fail_total 2168
telemt_upstream_connect_attempts_per_request{bucket="1"} 42103
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2167
telemt_me_keepalive_timeout_total 11466
telemt_me_reconnect_attempts_total 36776
telemt_me_reconnect_success_total 27834
telemt_me_reader_eof_total 29972
telemt_me_idle_close_by_peer_total 29965
telemt_me_route_drop_no_conn_total 491993
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1167177
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2203
telemt_desync_full_logged_total 722
telemt_desync_suppressed_total 1481
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 748
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 28312
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27810
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 1171938
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 17639000181 (16.43 GB)
telemt_user_octets_to_client{user="hello"} 465400414542 (433.44 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 128263.3 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1556978
telemt_connections_bad_total 34966
telemt_handshake_timeouts_total 12758
telemt_upstream_connect_attempt_total 41048
telemt_upstream_connect_success_total 40557
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 41048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_timeout_total 2204
telemt_me_reconnect_attempts_total 49428
telemt_me_reconnect_success_total 34174
telemt_me_reader_eof_total 35843
telemt_me_idle_close_by_peer_total 35843
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 569539
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1421474
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4968
telemt_desync_full_logged_total 1774
telemt_desync_suppressed_total 3194
telemt_desync_frames_bucket_total{bucket="1_2"} 1520
telemt_desync_frames_bucket_total{bucket="3_10"} 1611
telemt_desync_frames_bucket_total{bucket="gt_10"} 1837
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 35027
telemt_me_refill_failed_total 472
telemt_me_writer_restored_same_endpoint_total 34113
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 853
telemt_user_connections_total{user="hello"} 1421275
telemt_user_connections_current{user="hello"} 879
telemt_user_octets_from_client{user="hello"} 18299878888 (17.04 GB)
telemt_user_octets_to_client{user="hello"} 491925419716 (458.14 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 108
```