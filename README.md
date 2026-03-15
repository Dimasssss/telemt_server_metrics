# Server Metrics 2026-03-15 15:11:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 61010.0 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1943523
telemt_connections_bad_total 104997
telemt_handshake_timeouts_total 22231
telemt_upstream_connect_attempt_total 12169
telemt_upstream_connect_success_total 12117
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13953
telemt_me_reconnect_success_total 9061
telemt_me_reader_eof_total 9684
telemt_me_idle_close_by_peer_total 9684
telemt_me_route_drop_no_conn_total 668179
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1646019
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6293
telemt_desync_full_logged_total 1739
telemt_desync_suppressed_total 4554
telemt_desync_frames_bucket_total{bucket="1_2"} 1557
telemt_desync_frames_bucket_total{bucket="3_10"} 2419
telemt_desync_frames_bucket_total{bucket="gt_10"} 2317
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9360
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9050
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 1645529
telemt_user_connections_current{user="hello"} 2526
telemt_user_octets_from_client{user="hello"} 24009256016 (22.36 GB)
telemt_user_octets_to_client{user="hello"} 638728004748 (594.86 GB)
telemt_user_unique_ips_current{user="hello"} 702
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 61010.8 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779107
telemt_connections_bad_total 41810
telemt_handshake_timeouts_total 58848
telemt_upstream_connect_attempt_total 15443
telemt_upstream_connect_success_total 15368
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 15443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12068
telemt_me_reconnect_success_total 11972
telemt_me_reader_eof_total 12644
telemt_me_idle_close_by_peer_total 12644
telemt_me_route_drop_no_conn_total 195124
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 591079
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1996
telemt_desync_full_logged_total 691
telemt_desync_suppressed_total 1305
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12126
telemt_me_writer_restored_same_endpoint_total 11960
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 591325
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 8262854139 (7.70 GB)
telemt_user_octets_to_client{user="hello"} 221625559588 (206.40 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 61010.7 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1724668
telemt_connections_bad_total 47214
telemt_handshake_timeouts_total 172924
telemt_upstream_connect_attempt_total 13403
telemt_upstream_connect_success_total 13339
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 13403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11518
telemt_me_reconnect_success_total 10257
telemt_me_reader_eof_total 10870
telemt_me_idle_close_by_peer_total 10870
telemt_me_route_drop_no_conn_total 455995
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1046118
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2601
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 1644
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 985
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10440
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10238
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 1042118
telemt_user_connections_current{user="hello"} 1496
telemt_user_octets_from_client{user="hello"} 15083559232 (14.05 GB)
telemt_user_octets_to_client{user="hello"} 375139145436 (349.38 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 61010.6 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 821804
telemt_connections_bad_total 74737
telemt_handshake_timeouts_total 41773
telemt_upstream_connect_attempt_total 167656
telemt_upstream_connect_success_total 167153
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 167655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52471
telemt_me_reconnect_success_total 12031
telemt_me_reader_eof_total 13629
telemt_me_idle_close_by_peer_total 13629
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 179492
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478350
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1306
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 968
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 526
telemt_desync_frames_bucket_total{bucket="gt_10"} 428
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13413
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 11998
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1382
telemt_user_connections_total{user="hello"} 630251
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 12620902138 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 214141776365 (199.44 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 61011.5 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832610
telemt_connections_bad_total 9428
telemt_handshake_timeouts_total 17793
telemt_upstream_connect_attempt_total 13472
telemt_upstream_connect_success_total 13398
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 13472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14023
telemt_me_reconnect_success_total 10341
telemt_me_reader_eof_total 11045
telemt_me_idle_close_by_peer_total 11045
telemt_me_route_drop_no_conn_total 206990
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682797
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2399
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 1586
telemt_desync_frames_bucket_total{bucket="1_2"} 724
telemt_desync_frames_bucket_total{bucket="3_10"} 925
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10578
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10333
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 682839
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 8551941364 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 250264156340 (233.08 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 133
```