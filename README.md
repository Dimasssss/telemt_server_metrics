# Server Metrics 2026-03-15 07:52:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 34650.2 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645966
telemt_connections_bad_total 24296
telemt_handshake_timeouts_total 4436
telemt_upstream_connect_attempt_total 7212
telemt_upstream_connect_success_total 7185
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5477
telemt_me_reconnect_success_total 5449
telemt_me_reader_eof_total 5767
telemt_me_idle_close_by_peer_total 5767
telemt_me_route_drop_no_conn_total 202315
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544127
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1505
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 1028
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 534
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5522
telemt_me_writer_restored_same_endpoint_total 5438
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 544128
telemt_user_connections_current{user="hello"} 1707
telemt_user_octets_from_client{user="hello"} 6869861236 (6.40 GB)
telemt_user_octets_to_client{user="hello"} 199213865672 (185.53 GB)
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 34651.1 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241206
telemt_connections_bad_total 18360
telemt_handshake_timeouts_total 9732
telemt_upstream_connect_attempt_total 9533
telemt_upstream_connect_success_total 9486
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 9533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7469
telemt_me_reconnect_success_total 7423
telemt_me_reader_eof_total 7857
telemt_me_idle_close_by_peer_total 7857
telemt_me_route_drop_no_conn_total 62678
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198356
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 740
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 494
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 291
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7467
telemt_me_writer_restored_same_endpoint_total 7415
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 198637
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 3044839115 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 72545769852 (67.56 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 34651.1 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437776
telemt_connections_bad_total 12663
telemt_handshake_timeouts_total 40879
telemt_upstream_connect_attempt_total 7777
telemt_upstream_connect_success_total 7743
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 6032
telemt_me_reconnect_success_total 5998
telemt_me_reader_eof_total 6355
telemt_me_idle_close_by_peer_total 6355
telemt_me_route_drop_no_conn_total 114066
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354666
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 677
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6069
telemt_me_writer_restored_same_endpoint_total 5979
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 354448
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 5464110768 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 147916125888 (137.76 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 34650.9 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281669
telemt_connections_bad_total 46125
telemt_handshake_timeouts_total 19514
telemt_upstream_connect_attempt_total 11179
telemt_upstream_connect_success_total 10919
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 11179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21818
telemt_me_reconnect_success_total 9181
telemt_me_reader_eof_total 9856
telemt_me_idle_close_by_peer_total 9856
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 70988
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209702
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 384
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 9650
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9155
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 209703
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 1810080012 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 69770305732 (64.98 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 34651.6 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221063
telemt_connections_bad_total 476
telemt_handshake_timeouts_total 2220
telemt_upstream_connect_attempt_total 7668
telemt_upstream_connect_success_total 7635
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5928
telemt_me_reconnect_success_total 5899
telemt_me_reader_eof_total 6295
telemt_me_idle_close_by_peer_total 6295
telemt_me_route_drop_no_conn_total 67142
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206362
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 880
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 370
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5961
telemt_me_writer_restored_same_endpoint_total 5891
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 206371
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 2144383468 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 84761073272 (78.94 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 91
```