# Server Metrics 2026-03-14 00:26:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 152888.8 (42h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4601123
telemt_connections_bad_total 38410
telemt_handshake_timeouts_total 107857
telemt_upstream_connect_attempt_total 32148
telemt_upstream_connect_success_total 31931
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 32148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 6662
telemt_me_reconnect_attempts_total 32118
telemt_me_reconnect_success_total 21986
telemt_me_reader_eof_total 23582
telemt_me_idle_close_by_peer_total 23581
telemt_me_route_drop_no_conn_total 1741162
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4217710
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16626
telemt_desync_full_logged_total 4480
telemt_desync_suppressed_total 12146
telemt_desync_frames_bucket_total{bucket="1_2"} 4140
telemt_desync_frames_bucket_total{bucket="3_10"} 6360
telemt_desync_frames_bucket_total{bucket="gt_10"} 6126
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 22620
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21973
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 4219587
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 62271528332 (57.99 GB)
telemt_user_octets_to_client{user="hello"} 1333862078185 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52552.4 (14h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 643554
telemt_connections_bad_total 47995
telemt_handshake_timeouts_total 12822
telemt_upstream_connect_attempt_total 14804
telemt_upstream_connect_success_total 14562
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 14804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6072
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 1939
telemt_me_reconnect_attempts_total 13330
telemt_me_reconnect_success_total 9889
telemt_me_reader_eof_total 10493
telemt_me_idle_close_by_peer_total 10492
telemt_me_route_drop_no_conn_total 225412
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534959
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10136
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9881
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 536910
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 5849262053 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 174463433592 (162.48 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 182509.1 (50h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3333613
telemt_connections_bad_total 32597
telemt_handshake_timeouts_total 222318
telemt_upstream_connect_attempt_total 40781
telemt_upstream_connect_success_total 40760
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10351
telemt_me_reconnect_attempts_total 36321
telemt_me_reconnect_success_total 31365
telemt_me_reader_eof_total 33295
telemt_me_idle_close_by_peer_total 33294
telemt_me_route_drop_no_conn_total 1144232
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2771339
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9114
telemt_desync_full_logged_total 3063
telemt_desync_suppressed_total 6051
telemt_desync_frames_bucket_total{bucket="1_2"} 1534
telemt_desync_frames_bucket_total{bucket="3_10"} 3304
telemt_desync_frames_bucket_total{bucket="gt_10"} 4276
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 31819
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31324
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 2770582
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 44863277756 (41.78 GB)
telemt_user_octets_to_client{user="hello"} 983503152285 (915.96 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 182511.6 (50h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2207955
telemt_connections_bad_total 22869
telemt_handshake_timeouts_total 236628
telemt_upstream_connect_attempt_total 56787
telemt_upstream_connect_success_total 54331
telemt_upstream_connect_fail_total 2319
telemt_upstream_connect_attempts_per_request{bucket="1"} 56513
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2318
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20377
telemt_me_reconnect_attempts_total 47256
telemt_me_reconnect_success_total 38229
telemt_me_reader_eof_total 41010
telemt_me_idle_close_by_peer_total 41003
telemt_me_route_drop_no_conn_total 764397
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1778879
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3798
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 38842
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38205
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 1784786
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 27382293071 (25.50 GB)
telemt_user_octets_to_client{user="hello"} 662983815658 (617.45 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51945.0 (14h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672416
telemt_connections_bad_total 7869
telemt_handshake_timeouts_total 8597
telemt_upstream_connect_attempt_total 12530
telemt_upstream_connect_success_total 12169
telemt_upstream_connect_fail_total 361
telemt_upstream_connect_attempts_per_request{bucket="1"} 12530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 361
telemt_me_keepalive_timeout_total 1461
telemt_me_reconnect_attempts_total 41722
telemt_me_reconnect_success_total 9565
telemt_me_reader_eof_total 10767
telemt_me_idle_close_by_peer_total 10766
telemt_me_route_drop_no_conn_total 253668
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625127
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 10656
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9560
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1091
telemt_user_connections_total{user="hello"} 625026
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 10195478028 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 204264487408 (190.24 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 29
```