# Server Metrics 2026-03-12 21:03:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 54260.3 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1839237
telemt_connections_bad_total 22350
telemt_handshake_timeouts_total 20210
telemt_upstream_connect_attempt_total 10586
telemt_upstream_connect_success_total 10525
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 16623
telemt_me_reconnect_success_total 7770
telemt_me_reader_eof_total 8409
telemt_me_idle_close_by_peer_total 8408
telemt_me_route_drop_no_conn_total 722144
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1715177
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8342
telemt_desync_full_logged_total 2156
telemt_desync_suppressed_total 6186
telemt_desync_frames_bucket_total{bucket="1_2"} 2188
telemt_desync_frames_bucket_total{bucket="3_10"} 3013
telemt_desync_frames_bucket_total{bucket="gt_10"} 3141
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8160
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7757
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 390
telemt_user_connections_total{user="hello"} 1714659
telemt_user_connections_current{user="hello"} 1016
telemt_user_octets_from_client{user="hello"} 26276080524 (24.47 GB)
telemt_user_octets_to_client{user="hello"} 604009305996 (562.53 GB)
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83880.9 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 770717
telemt_connections_bad_total 11584
telemt_handshake_timeouts_total 30549
telemt_upstream_connect_attempt_total 21229
telemt_upstream_connect_success_total 21200
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3391
telemt_me_reconnect_attempts_total 15431
telemt_me_reconnect_success_total 15339
telemt_me_reader_eof_total 16316
telemt_me_idle_close_by_peer_total 16316
telemt_me_route_drop_no_conn_total 248782
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 695230
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2956
telemt_desync_full_logged_total 908
telemt_desync_suppressed_total 2048
telemt_desync_frames_bucket_total{bucket="1_2"} 1155
telemt_desync_frames_bucket_total{bucket="3_10"} 975
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 15494
telemt_me_writer_restored_same_endpoint_total 15330
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 697108
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 11854877724 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 268413658511 (249.98 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 83880.6 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1592481
telemt_connections_bad_total 7549
telemt_handshake_timeouts_total 109668
telemt_upstream_connect_attempt_total 19676
telemt_upstream_connect_success_total 19670
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1210
telemt_me_reconnect_attempts_total 16346
telemt_me_reconnect_success_total 15099
telemt_me_reader_eof_total 15944
telemt_me_idle_close_by_peer_total 15943
telemt_me_route_drop_no_conn_total 526082
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1231006
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4862
telemt_desync_full_logged_total 1494
telemt_desync_suppressed_total 3368
telemt_desync_frames_bucket_total{bucket="1_2"} 771
telemt_desync_frames_bucket_total{bucket="3_10"} 1755
telemt_desync_frames_bucket_total{bucket="gt_10"} 2336
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15242
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15058
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 1230613
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 19311840600 (17.99 GB)
telemt_user_octets_to_client{user="hello"} 458238995193 (426.77 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 83881.3 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979640
telemt_connections_bad_total 12973
telemt_handshake_timeouts_total 70887
telemt_upstream_connect_attempt_total 21399
telemt_upstream_connect_success_total 21311
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 21399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1674
telemt_me_reconnect_attempts_total 24830
telemt_me_reconnect_success_total 17103
telemt_me_reader_eof_total 18273
telemt_me_idle_close_by_peer_total 18273
telemt_me_route_drop_no_conn_total 350181
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851922
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1832
telemt_desync_full_logged_total 607
telemt_desync_suppressed_total 1225
telemt_desync_frames_bucket_total{bucket="1_2"} 508
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17482
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17082
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 851272
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 13367022908 (12.45 GB)
telemt_user_octets_to_client{user="hello"} 346466900020 (322.67 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83881.0 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1099255
telemt_connections_bad_total 12512
telemt_handshake_timeouts_total 9020
telemt_upstream_connect_attempt_total 25942
telemt_upstream_connect_success_total 25621
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 25942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1426
telemt_me_reconnect_attempts_total 32435
telemt_me_reconnect_success_total 21397
telemt_me_reader_eof_total 22485
telemt_me_idle_close_by_peer_total 22485
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 411320
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1009779
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3829
telemt_desync_full_logged_total 1334
telemt_desync_suppressed_total 2495
telemt_desync_frames_bucket_total{bucket="1_2"} 1113
telemt_desync_frames_bucket_total{bucket="3_10"} 1267
telemt_desync_frames_bucket_total{bucket="gt_10"} 1449
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 21987
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21353
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 590
telemt_user_connections_total{user="hello"} 1009640
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 12508653416 (11.65 GB)
telemt_user_octets_to_client{user="hello"} 355306259368 (330.90 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 56
```