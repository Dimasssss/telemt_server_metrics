# Server Metrics 2026-03-13 15:15:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 119807.0 (33h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3717103
telemt_connections_bad_total 37420
telemt_handshake_timeouts_total 74982
telemt_upstream_connect_attempt_total 23353
telemt_upstream_connect_success_total 23218
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2191
telemt_me_reconnect_attempts_total 27333
telemt_me_reconnect_success_total 17246
telemt_me_reader_eof_total 18534
telemt_me_idle_close_by_peer_total 18533
telemt_me_route_drop_no_conn_total 1379946
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3405951
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13881
telemt_desync_full_logged_total 3663
telemt_desync_suppressed_total 10218
telemt_desync_frames_bucket_total{bucket="1_2"} 3494
telemt_desync_frames_bucket_total{bucket="3_10"} 5264
telemt_desync_frames_bucket_total{bucket="gt_10"} 5123
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 17800
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17233
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3405730
telemt_user_connections_current{user="hello"} 1653
telemt_user_octets_from_client{user="hello"} 46503308048 (43.31 GB)
telemt_user_octets_to_client{user="hello"} 1073432246740 (999.71 GB)
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 19470.9 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278658
telemt_connections_bad_total 14533
telemt_handshake_timeouts_total 7288
telemt_upstream_connect_attempt_total 4664
telemt_upstream_connect_success_total 4579
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 5852
telemt_me_reconnect_success_total 3561
telemt_me_reader_eof_total 3778
telemt_me_idle_close_by_peer_total 3778
telemt_me_route_drop_no_conn_total 100884
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249595
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 945
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 703
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3672
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3554
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 249619
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 2518141092 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 70724629848 (65.87 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 149427.6 (41h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2755719
telemt_connections_bad_total 27527
telemt_handshake_timeouts_total 183139
telemt_upstream_connect_attempt_total 33568
telemt_upstream_connect_success_total 33558
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3266
telemt_me_reconnect_attempts_total 28352
telemt_me_reconnect_success_total 25804
telemt_me_reader_eof_total 27361
telemt_me_idle_close_by_peer_total 27360
telemt_me_route_drop_no_conn_total 930731
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2260486
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8053
telemt_desync_full_logged_total 2655
telemt_desync_suppressed_total 5398
telemt_desync_frames_bucket_total{bucket="1_2"} 1271
telemt_desync_frames_bucket_total{bucket="3_10"} 2937
telemt_desync_frames_bucket_total{bucket="gt_10"} 3845
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 26104
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25763
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 2259877
telemt_user_connections_current{user="hello"} 1062
telemt_user_octets_from_client{user="hello"} 37401186096 (34.83 GB)
telemt_user_octets_to_client{user="hello"} 795495177101 (740.86 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 149427.9 (41h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1754446
telemt_connections_bad_total 18127
telemt_handshake_timeouts_total 132825
telemt_upstream_connect_attempt_total 47107
telemt_upstream_connect_success_total 44778
telemt_upstream_connect_fail_total 2192
telemt_upstream_connect_attempts_per_request{bucket="1"} 46833
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2191
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11864
telemt_me_reconnect_attempts_total 40480
telemt_me_reconnect_success_total 31509
telemt_me_reader_eof_total 33856
telemt_me_idle_close_by_peer_total 33849
telemt_me_route_drop_no_conn_total 628945
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1465056
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2955
telemt_desync_full_logged_total 956
telemt_desync_suppressed_total 1999
telemt_desync_frames_bucket_total{bucket="1_2"} 792
telemt_desync_frames_bucket_total{bucket="3_10"} 1225
telemt_desync_frames_bucket_total{bucket="gt_10"} 938
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 32029
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31485
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 1469768
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 22933300897 (21.36 GB)
telemt_user_octets_to_client{user="hello"} 562355204022 (523.73 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18863.5 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302362
telemt_connections_bad_total 3971
telemt_handshake_timeouts_total 2795
telemt_upstream_connect_attempt_total 4029
telemt_upstream_connect_success_total 3902
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 4029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 13516
telemt_me_reconnect_success_total 2942
telemt_me_reader_eof_total 3308
telemt_me_idle_close_by_peer_total 3308
telemt_me_route_drop_no_conn_total 120166
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283139
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 876
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3285
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 2938
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 283118
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 3263825484 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 90109682440 (83.92 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 99
```