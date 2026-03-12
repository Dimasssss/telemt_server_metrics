# Server Metrics 2026-03-12 14:19:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 30049.7 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1066730
telemt_connections_bad_total 13328
telemt_handshake_timeouts_total 11058
telemt_upstream_connect_attempt_total 5938
telemt_upstream_connect_success_total 5904
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 402
telemt_me_reconnect_attempts_total 8261
telemt_me_reconnect_success_total 4362
telemt_me_reader_eof_total 4665
telemt_me_idle_close_by_peer_total 4664
telemt_me_route_drop_no_conn_total 377348
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1008306
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5437
telemt_desync_full_logged_total 1367
telemt_desync_suppressed_total 4070
telemt_desync_frames_bucket_total{bucket="1_2"} 1369
telemt_desync_frames_bucket_total{bucket="3_10"} 1970
telemt_desync_frames_bucket_total{bucket="gt_10"} 2098
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4535
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4349
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 1008058
telemt_user_connections_current{user="hello"} 1526
telemt_user_octets_from_client{user="hello"} 16326053656 (15.20 GB)
telemt_user_octets_to_client{user="hello"} 295331599472 (275.05 GB)
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59670.2 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499755
telemt_connections_bad_total 5356
telemt_handshake_timeouts_total 25647
telemt_upstream_connect_attempt_total 14264
telemt_upstream_connect_success_total 14257
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1141
telemt_me_reconnect_attempts_total 11147
telemt_me_reconnect_success_total 11086
telemt_me_reader_eof_total 11795
telemt_me_idle_close_by_peer_total 11795
telemt_me_route_drop_no_conn_total 145056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444436
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1621
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 1106
telemt_desync_frames_bucket_total{bucket="1_2"} 685
telemt_desync_frames_bucket_total{bucket="3_10"} 540
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11189
telemt_me_writer_restored_same_endpoint_total 11077
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 444896
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 6809038971 (6.34 GB)
telemt_user_octets_to_client{user="hello"} 158969026086 (148.05 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 59670.2 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082448
telemt_connections_bad_total 5727
telemt_handshake_timeouts_total 78815
telemt_upstream_connect_attempt_total 14303
telemt_upstream_connect_success_total 14298
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6461
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 931
telemt_me_reconnect_attempts_total 11045
telemt_me_reconnect_success_total 10945
telemt_me_reader_eof_total 11524
telemt_me_idle_close_by_peer_total 11524
telemt_me_route_drop_no_conn_total 282543
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 776977
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3271
telemt_desync_full_logged_total 1004
telemt_desync_suppressed_total 2267
telemt_desync_frames_bucket_total{bucket="1_2"} 482
telemt_desync_frames_bucket_total{bucket="3_10"} 1177
telemt_desync_frames_bucket_total{bucket="gt_10"} 1612
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10987
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10904
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 777168
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 10220622652 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 248507395073 (231.44 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 59670.6 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627664
telemt_connections_bad_total 7687
telemt_handshake_timeouts_total 55702
telemt_upstream_connect_attempt_total 15807
telemt_upstream_connect_success_total 15742
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 15806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 1327
telemt_me_reconnect_attempts_total 13983
telemt_me_reconnect_success_total 12746
telemt_me_reader_eof_total 13517
telemt_me_idle_close_by_peer_total 13517
telemt_me_route_drop_no_conn_total 212341
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532384
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1082
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 705
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 336
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12883
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12725
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 531887
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 5824064564 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 215026911800 (200.26 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59670.4 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710543
telemt_connections_bad_total 4040
telemt_handshake_timeouts_total 5700
telemt_upstream_connect_attempt_total 18712
telemt_upstream_connect_success_total 18485
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 18712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 1053
telemt_me_reconnect_attempts_total 22717
telemt_me_reconnect_success_total 15489
telemt_me_reader_eof_total 16247
telemt_me_idle_close_by_peer_total 16247
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 244961
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658834
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2692
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 1786
telemt_desync_frames_bucket_total{bucket="1_2"} 760
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 996
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 15873
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15458
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 384
telemt_user_connections_total{user="hello"} 658736
telemt_user_connections_current{user="hello"} 796
telemt_user_octets_from_client{user="hello"} 7697610320 (7.17 GB)
telemt_user_octets_to_client{user="hello"} 179082851868 (166.78 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 122
```