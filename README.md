# Server Metrics 2026-03-13 05:53:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 86086.5 (23h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2315733
telemt_connections_bad_total 34933
telemt_handshake_timeouts_total 24436
telemt_upstream_connect_attempt_total 16935
telemt_upstream_connect_success_total 16842
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1316
telemt_me_reconnect_attempts_total 21428
telemt_me_reconnect_success_total 12559
telemt_me_reader_eof_total 13546
telemt_me_idle_close_by_peer_total 13545
telemt_me_route_drop_no_conn_total 879094
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2130058
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9455
telemt_desync_full_logged_total 2441
telemt_desync_suppressed_total 7014
telemt_desync_frames_bucket_total{bucket="1_2"} 2451
telemt_desync_frames_bucket_total{bucket="3_10"} 3460
telemt_desync_frames_bucket_total{bucket="gt_10"} 3544
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 13008
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12546
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 2129413
telemt_user_connections_current{user="hello"} 1223
telemt_user_octets_from_client{user="hello"} 30777810864 (28.66 GB)
telemt_user_octets_to_client{user="hello"} 729782302872 (679.66 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 115707.1 (32h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937525
telemt_connections_bad_total 12449
telemt_handshake_timeouts_total 40578
telemt_upstream_connect_attempt_total 29230
telemt_upstream_connect_success_total 29199
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3558
telemt_me_reconnect_attempts_total 21921
telemt_me_reconnect_success_total 21803
telemt_me_reader_eof_total 23248
telemt_me_idle_close_by_peer_total 23248
telemt_me_route_drop_no_conn_total 298248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 845989
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3423
telemt_desync_full_logged_total 1076
telemt_desync_suppressed_total 2347
telemt_desync_frames_bucket_total{bucket="1_2"} 1336
telemt_desync_frames_bucket_total{bucket="3_10"} 1115
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 22019
telemt_me_writer_restored_same_endpoint_total 21794
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 847895
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 13393709652 (12.47 GB)
telemt_user_octets_to_client{user="hello"} 322343053991 (300.21 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 115707.0 (32h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1938520
telemt_connections_bad_total 22033
telemt_handshake_timeouts_total 127329
telemt_upstream_connect_attempt_total 26889
telemt_upstream_connect_success_total 26879
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1663
telemt_me_reconnect_attempts_total 22043
telemt_me_reconnect_success_total 20772
telemt_me_reader_eof_total 22004
telemt_me_idle_close_by_peer_total 22003
telemt_me_route_drop_no_conn_total 620852
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1525507
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5323
telemt_desync_full_logged_total 1611
telemt_desync_suppressed_total 3712
telemt_desync_frames_bucket_total{bucket="1_2"} 880
telemt_desync_frames_bucket_total{bucket="3_10"} 1936
telemt_desync_frames_bucket_total{bucket="gt_10"} 2507
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 20972
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20731
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 1525001
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 26177976488 (24.38 GB)
telemt_user_octets_to_client{user="hello"} 542619213785 (505.35 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 115707.4 (32h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1182274
telemt_connections_bad_total 13986
telemt_handshake_timeouts_total 77330
telemt_upstream_connect_attempt_total 39489
telemt_upstream_connect_success_total 37201
telemt_upstream_connect_fail_total 2151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39215
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2150
telemt_me_keepalive_timeout_total 11405
telemt_me_reconnect_attempts_total 34515
telemt_me_reconnect_success_total 25580
telemt_me_reader_eof_total 27589
telemt_me_idle_close_by_peer_total 27582
telemt_me_route_drop_no_conn_total 422247
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1018148
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1998
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1342
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 26034
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25556
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 1023188
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 15572676301 (14.50 GB)
telemt_user_octets_to_client{user="hello"} 408411640746 (380.36 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 115707.1 (32h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1330267
telemt_connections_bad_total 15496
telemt_handshake_timeouts_total 10833
telemt_upstream_connect_attempt_total 36579
telemt_upstream_connect_success_total 36137
telemt_upstream_connect_fail_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 36579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 442
telemt_me_keepalive_timeout_total 1985
telemt_me_reconnect_attempts_total 44116
telemt_me_reconnect_success_total 30381
telemt_me_reader_eof_total 31909
telemt_me_idle_close_by_peer_total 31909
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 490568
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1229781
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 45
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4436
telemt_desync_full_logged_total 1595
telemt_desync_suppressed_total 2841
telemt_desync_frames_bucket_total{bucket="1_2"} 1344
telemt_desync_frames_bucket_total{bucket="3_10"} 1441
telemt_desync_frames_bucket_total{bucket="gt_10"} 1651
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 31146
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30328
telemt_me_writer_restored_fallback_total 53
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 765
telemt_user_connections_total{user="hello"} 1229626
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 14816813580 (13.80 GB)
telemt_user_octets_to_client{user="hello"} 416854882436 (388.23 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 108
```