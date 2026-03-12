# Server Metrics 2026-03-12 23:31:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 63140.2 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1956623
telemt_connections_bad_total 26083
telemt_handshake_timeouts_total 21233
telemt_upstream_connect_attempt_total 12525
telemt_upstream_connect_success_total 12454
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 12525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 619
telemt_me_reconnect_attempts_total 18121
telemt_me_reconnect_success_total 9265
telemt_me_reader_eof_total 10005
telemt_me_idle_close_by_peer_total 10004
telemt_me_route_drop_no_conn_total 761731
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1819235
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8570
telemt_desync_full_logged_total 2236
telemt_desync_suppressed_total 6334
telemt_desync_frames_bucket_total{bucket="1_2"} 2262
telemt_desync_frames_bucket_total{bucket="3_10"} 3082
telemt_desync_frames_bucket_total{bucket="gt_10"} 3226
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9673
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9252
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 1818700
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 27261156288 (25.39 GB)
telemt_user_octets_to_client{user="hello"} 644751661428 (600.47 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 92760.6 (25h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808896
telemt_connections_bad_total 11738
telemt_handshake_timeouts_total 31512
telemt_upstream_connect_attempt_total 23469
telemt_upstream_connect_success_total 23440
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3423
telemt_me_reconnect_attempts_total 17259
telemt_me_reconnect_success_total 17163
telemt_me_reader_eof_total 18264
telemt_me_idle_close_by_peer_total 18264
telemt_me_route_drop_no_conn_total 261494
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 731482
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3017
telemt_desync_full_logged_total 941
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 1200
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 17335
telemt_me_writer_restored_same_endpoint_total 17154
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 733362
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 12135218784 (11.30 GB)
telemt_user_octets_to_client{user="hello"} 283429981571 (263.96 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 92760.6 (25h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1684227
telemt_connections_bad_total 8104
telemt_handshake_timeouts_total 113364
telemt_upstream_connect_attempt_total 21522
telemt_upstream_connect_success_total 21516
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1227
telemt_me_reconnect_attempts_total 17782
telemt_me_reconnect_success_total 16530
telemt_me_reader_eof_total 17476
telemt_me_idle_close_by_peer_total 17475
telemt_me_route_drop_no_conn_total 552225
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1316888
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4974
telemt_desync_full_logged_total 1526
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2383
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16690
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16489
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 1316494
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 19800480444 (18.44 GB)
telemt_user_octets_to_client{user="hello"} 484875531085 (451.58 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 92760.7 (25h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040847
telemt_connections_bad_total 13013
telemt_handshake_timeouts_total 71555
telemt_upstream_connect_attempt_total 32764
telemt_upstream_connect_success_total 30505
telemt_upstream_connect_fail_total 2122
telemt_upstream_connect_attempts_per_request{bucket="1"} 32490
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2121
telemt_me_keepalive_timeout_total 11248
telemt_me_reconnect_attempts_total 27852
telemt_me_reconnect_success_total 20015
telemt_me_reader_eof_total 21667
telemt_me_idle_close_by_peer_total 21660
telemt_me_route_drop_no_conn_total 369482
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901490
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 20377
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 19993
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 906710
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 14300674769 (13.32 GB)
telemt_user_octets_to_client{user="hello"} 361305369058 (336.49 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 92760.6 (25h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1159774
telemt_connections_bad_total 12544
telemt_handshake_timeouts_total 9268
telemt_upstream_connect_attempt_total 28191
telemt_upstream_connect_success_total 27842
telemt_upstream_connect_fail_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 28191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 349
telemt_me_keepalive_timeout_total 1459
telemt_me_reconnect_attempts_total 34252
telemt_me_reconnect_success_total 23212
telemt_me_reader_eof_total 24414
telemt_me_idle_close_by_peer_total 24414
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 433325
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1069059
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4027
telemt_desync_full_logged_total 1407
telemt_desync_suppressed_total 2620
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 1339
telemt_desync_frames_bucket_total{bucket="gt_10"} 1515
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 23828
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23167
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 1068917
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 13523851308 (12.60 GB)
telemt_user_octets_to_client{user="hello"} 376777148272 (350.90 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 38
```