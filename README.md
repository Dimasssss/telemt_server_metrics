# Server Metrics 2026-03-13 19:30:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 135122.6 (37h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4314977
telemt_connections_bad_total 37796
telemt_handshake_timeouts_total 105501
telemt_upstream_connect_attempt_total 28347
telemt_upstream_connect_success_total 28154
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 28347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 6525
telemt_me_reconnect_attempts_total 29171
telemt_me_reconnect_success_total 19055
telemt_me_reader_eof_total 20454
telemt_me_idle_close_by_peer_total 20453
telemt_me_route_drop_no_conn_total 1621074
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3945563
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15514
telemt_desync_full_logged_total 4134
telemt_desync_suppressed_total 11380
telemt_desync_frames_bucket_total{bucket="1_2"} 3863
telemt_desync_frames_bucket_total{bucket="3_10"} 5911
telemt_desync_frames_bucket_total{bucket="gt_10"} 5740
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19645
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19042
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 590
telemt_user_connections_total{user="hello"} 3947733
telemt_user_connections_current{user="hello"} 1369
telemt_user_octets_from_client{user="hello"} 57188268936 (53.26 GB)
telemt_user_octets_to_client{user="hello"} 1241684756381 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 34786.5 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 506099
telemt_connections_bad_total 39330
telemt_handshake_timeouts_total 11095
telemt_upstream_connect_attempt_total 10217
telemt_upstream_connect_success_total 10004
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 10217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 1868
telemt_me_reconnect_attempts_total 9637
telemt_me_reconnect_success_total 6224
telemt_me_reader_eof_total 6579
telemt_me_idle_close_by_peer_total 6578
telemt_me_route_drop_no_conn_total 189509
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439700
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1527
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 1117
telemt_desync_frames_bucket_total{bucket="1_2"} 320
telemt_desync_frames_bucket_total{bucket="3_10"} 679
telemt_desync_frames_bucket_total{bucket="gt_10"} 528
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6416
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6216
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 441631
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 4695523677 (4.37 GB)
telemt_user_octets_to_client{user="hello"} 139891261580 (130.28 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 164743.2 (45h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3153379
telemt_connections_bad_total 29281
telemt_handshake_timeouts_total 212540
telemt_upstream_connect_attempt_total 36579
telemt_upstream_connect_success_total 36564
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10182
telemt_me_reconnect_attempts_total 30609
telemt_me_reconnect_success_total 28046
telemt_me_reader_eof_total 29723
telemt_me_idle_close_by_peer_total 29722
telemt_me_route_drop_no_conn_total 1078391
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2606972
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8718
telemt_desync_full_logged_total 2883
telemt_desync_suppressed_total 5835
telemt_desync_frames_bucket_total{bucket="1_2"} 1433
telemt_desync_frames_bucket_total{bucket="3_10"} 3191
telemt_desync_frames_bucket_total{bucket="gt_10"} 4094
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 28380
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28005
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 2606258
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 43212741088 (40.25 GB)
telemt_user_octets_to_client{user="hello"} 914927088513 (852.09 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 164743.6 (45h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2033511
telemt_connections_bad_total 22092
telemt_handshake_timeouts_total 186708
telemt_upstream_connect_attempt_total 51716
telemt_upstream_connect_success_total 49282
telemt_upstream_connect_fail_total 2297
telemt_upstream_connect_attempts_per_request{bucket="1"} 51442
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2296
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20183
telemt_me_reconnect_attempts_total 43070
telemt_me_reconnect_success_total 34064
telemt_me_reader_eof_total 36572
telemt_me_idle_close_by_peer_total 36565
telemt_me_route_drop_no_conn_total 721783
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1679024
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3602
telemt_desync_full_logged_total 1146
telemt_desync_suppressed_total 2456
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1500
telemt_desync_frames_bucket_total{bucket="gt_10"} 1152
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 34627
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34040
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 563
telemt_user_connections_total{user="hello"} 1684894
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 25793323271 (24.02 GB)
telemt_user_octets_to_client{user="hello"} 636436505406 (592.73 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 34179.5 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546024
telemt_connections_bad_total 5643
telemt_handshake_timeouts_total 5383
telemt_upstream_connect_attempt_total 7322
telemt_upstream_connect_success_total 7084
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 7322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 957
telemt_me_reconnect_attempts_total 26308
telemt_me_reconnect_success_total 5373
telemt_me_reader_eof_total 6123
telemt_me_idle_close_by_peer_total 6122
telemt_me_route_drop_no_conn_total 207302
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511388
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1455
telemt_desync_full_logged_total 452
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 439
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 6069
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5369
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 696
telemt_user_connections_total{user="hello"} 511362
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 5972464936 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 164610091700 (153.31 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 70
```