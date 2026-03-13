# Server Metrics 2026-03-13 02:59:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 75678.5 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2113374
telemt_connections_bad_total 27996
telemt_handshake_timeouts_total 22676
telemt_upstream_connect_attempt_total 14980
telemt_upstream_connect_success_total 14896
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1268
telemt_me_reconnect_attempts_total 19972
telemt_me_reconnect_success_total 11110
telemt_me_reader_eof_total 11999
telemt_me_idle_close_by_peer_total 11998
telemt_me_route_drop_no_conn_total 812925
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1946580
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8744
telemt_desync_full_logged_total 2274
telemt_desync_suppressed_total 6470
telemt_desync_frames_bucket_total{bucket="1_2"} 2300
telemt_desync_frames_bucket_total{bucket="3_10"} 3154
telemt_desync_frames_bucket_total{bucket="gt_10"} 3290
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11542
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11097
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 1946034
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 28364784248 (26.42 GB)
telemt_user_octets_to_client{user="hello"} 675291382812 (628.91 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 105299.0 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 861067
telemt_connections_bad_total 11827
telemt_handshake_timeouts_total 34445
telemt_upstream_connect_attempt_total 26817
telemt_upstream_connect_success_total 26788
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3458
telemt_me_reconnect_attempts_total 20025
telemt_me_reconnect_success_total 19915
telemt_me_reader_eof_total 21215
telemt_me_idle_close_by_peer_total 21215
telemt_me_route_drop_no_conn_total 276608
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 779418
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3100
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2126
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 20109
telemt_me_writer_restored_same_endpoint_total 19906
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 781320
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 12409942596 (11.56 GB)
telemt_user_octets_to_client{user="hello"} 296311711299 (275.96 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 105298.9 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1785749
telemt_connections_bad_total 9240
telemt_handshake_timeouts_total 119839
telemt_upstream_connect_attempt_total 24525
telemt_upstream_connect_success_total 24515
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1614
telemt_me_reconnect_attempts_total 20199
telemt_me_reconnect_success_total 18935
telemt_me_reader_eof_total 20053
telemt_me_idle_close_by_peer_total 20052
telemt_me_route_drop_no_conn_total 581417
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1406697
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5033
telemt_desync_full_logged_total 1540
telemt_desync_suppressed_total 3493
telemt_desync_frames_bucket_total{bucket="1_2"} 805
telemt_desync_frames_bucket_total{bucket="3_10"} 1823
telemt_desync_frames_bucket_total{bucket="gt_10"} 2405
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 19112
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18894
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 1406291
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 20301328932 (18.91 GB)
telemt_user_octets_to_client{user="hello"} 505495933617 (470.78 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 105299.2 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1114198
telemt_connections_bad_total 13139
telemt_handshake_timeouts_total 73822
telemt_upstream_connect_attempt_total 36736
telemt_upstream_connect_success_total 34460
telemt_upstream_connect_fail_total 2139
telemt_upstream_connect_attempts_per_request{bucket="1"} 36462
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2138
telemt_me_keepalive_timeout_total 11365
telemt_me_reconnect_attempts_total 32292
telemt_me_reconnect_success_total 23367
telemt_me_reader_eof_total 25227
telemt_me_idle_close_by_peer_total 25220
telemt_me_route_drop_no_conn_total 394872
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 955553
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 23798
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23343
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 960723
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 14627385205 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 376811080518 (350.93 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 105299.0 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1232675
telemt_connections_bad_total 12632
telemt_handshake_timeouts_total 9571
telemt_upstream_connect_attempt_total 33191
telemt_upstream_connect_success_total 32785
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 33191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15811
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_keepalive_timeout_total 1900
telemt_me_reconnect_attempts_total 41288
telemt_me_reconnect_success_total 27558
telemt_me_reader_eof_total 29000
telemt_me_idle_close_by_peer_total 29000
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 460283
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1140360
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4233
telemt_desync_full_logged_total 1505
telemt_desync_suppressed_total 2728
telemt_desync_frames_bucket_total{bucket="1_2"} 1275
telemt_desync_frames_bucket_total{bucket="3_10"} 1393
telemt_desync_frames_bucket_total{bucket="gt_10"} 1565
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 28304
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27509
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 746
telemt_user_connections_total{user="hello"} 1140212
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 14090137972 (13.12 GB)
telemt_user_octets_to_client{user="hello"} 394624353600 (367.52 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 58
```