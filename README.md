# Server Metrics 2026-03-14 02:19:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 159636.4 (44h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4664189
telemt_connections_bad_total 39816
telemt_handshake_timeouts_total 108382
telemt_upstream_connect_attempt_total 33759
telemt_upstream_connect_success_total 33533
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 33759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 6713
telemt_me_reconnect_attempts_total 33374
telemt_me_reconnect_success_total 23233
telemt_me_reader_eof_total 24920
telemt_me_idle_close_by_peer_total 24919
telemt_me_route_drop_no_conn_total 1765386
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4276312
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16755
telemt_desync_full_logged_total 4518
telemt_desync_suppressed_total 12237
telemt_desync_frames_bucket_total{bucket="1_2"} 4186
telemt_desync_frames_bucket_total{bucket="3_10"} 6393
telemt_desync_frames_bucket_total{bucket="gt_10"} 6176
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 23884
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23220
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 651
telemt_user_connections_total{user="hello"} 4278166
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 62872095224 (58.55 GB)
telemt_user_octets_to_client{user="hello"} 1352073268129 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59300.0 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694548
telemt_connections_bad_total 50961
telemt_handshake_timeouts_total 13101
telemt_upstream_connect_attempt_total 16578
telemt_upstream_connect_success_total 16328
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 16578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 2058
telemt_me_reconnect_attempts_total 14792
telemt_me_reconnect_success_total 11348
telemt_me_reader_eof_total 12026
telemt_me_idle_close_by_peer_total 12025
telemt_me_route_drop_no_conn_total 233616
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555531
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1669
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 1213
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 723
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11611
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11340
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 557482
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 5962421849 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 179005804864 (166.71 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 189257.0 (52h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3372160
telemt_connections_bad_total 34965
telemt_handshake_timeouts_total 223270
telemt_upstream_connect_attempt_total 42595
telemt_upstream_connect_success_total 42574
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10416
telemt_me_reconnect_attempts_total 37790
telemt_me_reconnect_success_total 32829
telemt_me_reader_eof_total 34867
telemt_me_idle_close_by_peer_total 34866
telemt_me_route_drop_no_conn_total 1156330
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2805681
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9295
telemt_desync_full_logged_total 3113
telemt_desync_suppressed_total 6182
telemt_desync_frames_bucket_total{bucket="1_2"} 1586
telemt_desync_frames_bucket_total{bucket="3_10"} 3368
telemt_desync_frames_bucket_total{bucket="gt_10"} 4341
telemt_pool_swap_total 178
telemt_me_writer_removed_unexpected_total 33292
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32788
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 2804906
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 45136641912 (42.04 GB)
telemt_user_octets_to_client{user="hello"} 1004263393977 (935.29 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 189259.5 (52h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2250876
telemt_connections_bad_total 22956
telemt_handshake_timeouts_total 245490
telemt_upstream_connect_attempt_total 59289
telemt_upstream_connect_success_total 56827
telemt_upstream_connect_fail_total 2325
telemt_upstream_connect_attempts_per_request{bucket="1"} 59015
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2324
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20414
telemt_me_reconnect_attempts_total 49404
telemt_me_reconnect_success_total 40373
telemt_me_reader_eof_total 43300
telemt_me_idle_close_by_peer_total 43293
telemt_me_route_drop_no_conn_total 770830
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1797451
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 41003
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40349
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 1803375
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 27579933151 (25.69 GB)
telemt_user_octets_to_client{user="hello"} 665952666714 (620.22 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58693.0 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694511
telemt_connections_bad_total 7906
telemt_handshake_timeouts_total 8656
telemt_upstream_connect_attempt_total 14790
telemt_upstream_connect_success_total 14378
telemt_upstream_connect_fail_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 14790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 412
telemt_me_keepalive_timeout_total 1498
telemt_me_reconnect_attempts_total 43585
telemt_me_reconnect_success_total 11422
telemt_me_reader_eof_total 12732
telemt_me_idle_close_by_peer_total 12731
telemt_me_route_drop_no_conn_total 263664
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646673
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1668
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 1146
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 12530
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11417
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1108
telemt_user_connections_total{user="hello"} 646559
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 11686885616 (10.88 GB)
telemt_user_octets_to_client{user="hello"} 210455235024 (196.00 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 36
```