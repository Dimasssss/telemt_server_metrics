# Server Metrics 2026-03-13 22:39:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 146448.1 (40h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4537469
telemt_connections_bad_total 38374
telemt_handshake_timeouts_total 107113
telemt_upstream_connect_attempt_total 30547
telemt_upstream_connect_success_total 30338
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 30547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 6641
telemt_me_reconnect_attempts_total 30834
telemt_me_reconnect_success_total 20710
telemt_me_reader_eof_total 22224
telemt_me_idle_close_by_peer_total 22223
telemt_me_route_drop_no_conn_total 1713631
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4157258
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16562
telemt_desync_full_logged_total 4456
telemt_desync_suppressed_total 12106
telemt_desync_frames_bucket_total{bucket="1_2"} 4121
telemt_desync_frames_bucket_total{bucket="3_10"} 6336
telemt_desync_frames_bucket_total{bucket="gt_10"} 6105
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 21327
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20697
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 4159389
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 61081591024 (56.89 GB)
telemt_user_octets_to_client{user="hello"} 1313818465157 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46111.7 (12h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595320
telemt_connections_bad_total 42941
telemt_handshake_timeouts_total 12457
telemt_upstream_connect_attempt_total 12975
telemt_upstream_connect_success_total 12745
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 12975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 1911
telemt_me_reconnect_attempts_total 11815
telemt_me_reconnect_success_total 8383
telemt_me_reader_eof_total 8887
telemt_me_idle_close_by_peer_total 8886
telemt_me_route_drop_no_conn_total 217025
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515012
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
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8611
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8375
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 516941
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 5713325081 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 168312195700 (156.75 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 176068.4 (48h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3296292
telemt_connections_bad_total 31815
telemt_handshake_timeouts_total 220427
telemt_upstream_connect_attempt_total 39029
telemt_upstream_connect_success_total 39008
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10298
telemt_me_reconnect_attempts_total 34875
telemt_me_reconnect_success_total 29923
telemt_me_reader_eof_total 31758
telemt_me_idle_close_by_peer_total 31757
telemt_me_route_drop_no_conn_total 1130141
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2737329
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8993
telemt_desync_full_logged_total 3027
telemt_desync_suppressed_total 5966
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 3258
telemt_desync_frames_bucket_total{bucket="gt_10"} 4223
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 30364
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29882
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 2736588
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 44647167232 (41.58 GB)
telemt_user_octets_to_client{user="hello"} 968160632513 (901.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 176071.1 (48h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2158384
telemt_connections_bad_total 22840
telemt_handshake_timeouts_total 221422
telemt_upstream_connect_attempt_total 54823
telemt_upstream_connect_success_total 52374
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 54549
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20333
telemt_me_reconnect_attempts_total 45600
telemt_me_reconnect_success_total 36582
telemt_me_reader_eof_total 39229
telemt_me_idle_close_by_peer_total 39222
telemt_me_route_drop_no_conn_total 755993
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1758891
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3795
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 37178
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36558
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 1764774
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 27304659519 (25.43 GB)
telemt_user_octets_to_client{user="hello"} 658666109594 (613.43 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 45504.4 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639791
telemt_connections_bad_total 7439
telemt_handshake_timeouts_total 6406
telemt_upstream_connect_attempt_total 10328
telemt_upstream_connect_success_total 9996
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 10328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 1431
telemt_me_reconnect_attempts_total 37422
telemt_me_reconnect_success_total 7706
telemt_me_reader_eof_total 8768
telemt_me_idle_close_by_peer_total 8767
telemt_me_route_drop_no_conn_total 243108
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597244
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1589
telemt_desync_full_logged_total 495
telemt_desync_suppressed_total 1094
telemt_desync_frames_bucket_total{bucket="1_2"} 481
telemt_desync_frames_bucket_total{bucket="3_10"} 621
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8706
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 7701
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1000
telemt_user_connections_total{user="hello"} 597152
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 9027272348 (8.41 GB)
telemt_user_octets_to_client{user="hello"} 195858980068 (182.41 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 36
```