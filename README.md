# Server Metrics 2026-03-11 20:59:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 109916.4 (30h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2783928
telemt_connections_bad_total 61085
telemt_handshake_timeouts_total 62528
telemt_upstream_connect_attempt_total 23469
telemt_upstream_connect_success_total 23457
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5438
telemt_me_reconnect_attempts_total 35764
telemt_me_reconnect_success_total 17870
telemt_me_reader_eof_total 19265
telemt_me_idle_close_by_peer_total 19265
telemt_me_route_drop_no_conn_total 1045274
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2527782
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12701
telemt_desync_full_logged_total 3530
telemt_desync_suppressed_total 9171
telemt_desync_frames_bucket_total{bucket="1_2"} 3134
telemt_desync_frames_bucket_total{bucket="3_10"} 4881
telemt_desync_frames_bucket_total{bucket="gt_10"} 4686
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 18635
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17864
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 765
telemt_user_connections_total{user="hello"} 2526115
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 38300517728 (35.67 GB)
telemt_user_octets_to_client{user="hello"} 728909684580 (678.85 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 109973.2 (30h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1017517
telemt_connections_bad_total 17048
telemt_handshake_timeouts_total 90432
telemt_upstream_connect_attempt_total 33549
telemt_upstream_connect_success_total 30572
telemt_upstream_connect_fail_total 2977
telemt_upstream_connect_attempts_per_request{bucket="1"} 33549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13797
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2977
telemt_me_keepalive_timeout_total 2908
telemt_me_reconnect_attempts_total 24201
telemt_me_reconnect_success_total 22071
telemt_me_reader_eof_total 23393
telemt_me_idle_close_by_peer_total 23390
telemt_me_route_drop_no_conn_total 385109
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 850422
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3377
telemt_desync_full_logged_total 1100
telemt_desync_suppressed_total 2277
telemt_desync_frames_bucket_total{bucket="1_2"} 1101
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 22398
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22048
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 852858
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 10309004862 (9.60 GB)
telemt_user_octets_to_client{user="hello"} 253634844576 (236.22 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 109973.1 (30h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1773589
telemt_connections_bad_total 11326
telemt_handshake_timeouts_total 136423
telemt_upstream_connect_attempt_total 28270
telemt_upstream_connect_success_total 27913
telemt_upstream_connect_fail_total 355
telemt_upstream_connect_attempts_per_request{bucket="1"} 28268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 355
telemt_me_keepalive_timeout_total 2048
telemt_me_reconnect_attempts_total 60472
telemt_me_reconnect_success_total 20638
telemt_me_reader_eof_total 22742
telemt_me_idle_close_by_peer_total 22742
telemt_me_route_drop_no_conn_total 644548
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1559254
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4209
telemt_desync_full_logged_total 1242
telemt_desync_suppressed_total 2967
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1601
telemt_desync_frames_bucket_total{bucket="gt_10"} 1624
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22165
telemt_me_refill_failed_total 1239
telemt_me_writer_restored_same_endpoint_total 20626
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1527
telemt_user_connections_total{user="hello"} 1559491
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 19940160386 (18.57 GB)
telemt_user_octets_to_client{user="hello"} 477584204992 (444.78 GB)
telemt_user_msgs_from_client{user="hello"} 4355
telemt_user_msgs_to_client{user="hello"} 13375
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 109973.6 (30h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1269068
telemt_connections_bad_total 78257
telemt_handshake_timeouts_total 111633
telemt_upstream_connect_attempt_total 29554
telemt_upstream_connect_success_total 29554
telemt_upstream_connect_attempts_per_request{bucket="1"} 29554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1550
telemt_me_reconnect_attempts_total 28653
telemt_me_reconnect_success_total 24033
telemt_me_reader_eof_total 25528
telemt_me_idle_close_by_peer_total 25527
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 426408
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1043291
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2207
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 1376
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 741
telemt_desync_frames_bucket_total{bucket="gt_10"} 685
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 24434
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24000
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 1042412
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 12284687324 (11.44 GB)
telemt_user_octets_to_client{user="hello"} 315926877692 (294.23 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14649.4 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206795
telemt_connections_bad_total 5176
telemt_handshake_timeouts_total 2373
telemt_upstream_connect_attempt_total 4209
telemt_upstream_connect_success_total 4208
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 3430
telemt_me_reconnect_success_total 3397
telemt_me_reader_eof_total 3517
telemt_me_idle_close_by_peer_total 3517
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 70138
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182668
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 471
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3439
telemt_me_writer_restored_same_endpoint_total 3371
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 182630
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 9645354792 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 64035274204 (59.64 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 59
```