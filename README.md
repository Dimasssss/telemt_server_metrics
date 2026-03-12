# Server Metrics 2026-03-12 10:50:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 17503.5 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583488
telemt_connections_bad_total 1469
telemt_handshake_timeouts_total 3435
telemt_upstream_connect_attempt_total 3390
telemt_upstream_connect_success_total 3368
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 305
telemt_me_reconnect_attempts_total 6341
telemt_me_reconnect_success_total 2453
telemt_me_reader_eof_total 2660
telemt_me_idle_close_by_peer_total 2660
telemt_me_route_drop_no_conn_total 200770
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 561721
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2679
telemt_desync_full_logged_total 675
telemt_desync_suppressed_total 2004
telemt_desync_frames_bucket_total{bucket="1_2"} 681
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 1009
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2598
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2440
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 561582
telemt_user_connections_current{user="hello"} 1611
telemt_user_octets_from_client{user="hello"} 10182462252 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 152549990644 (142.07 GB)
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47123.9 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316161
telemt_connections_bad_total 3483
telemt_handshake_timeouts_total 9643
telemt_upstream_connect_attempt_total 11817
telemt_upstream_connect_success_total 11811
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 678
telemt_me_reconnect_attempts_total 9311
telemt_me_reconnect_success_total 9260
telemt_me_reader_eof_total 9845
telemt_me_idle_close_by_peer_total 9845
telemt_me_route_drop_no_conn_total 91719
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283631
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 620
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9340
telemt_me_writer_restored_same_endpoint_total 9251
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 284065
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 3945063147 (3.67 GB)
telemt_user_octets_to_client{user="hello"} 102979352774 (95.91 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 47123.9 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780401
telemt_connections_bad_total 3974
telemt_handshake_timeouts_total 57006
telemt_upstream_connect_attempt_total 11789
telemt_upstream_connect_success_total 11784
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 591
telemt_me_reconnect_attempts_total 9145
telemt_me_reconnect_success_total 9068
telemt_me_reader_eof_total 9535
telemt_me_idle_close_by_peer_total 9535
telemt_me_route_drop_no_conn_total 177651
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505460
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2276
telemt_desync_full_logged_total 673
telemt_desync_suppressed_total 1603
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 779
telemt_desync_frames_bucket_total{bucket="gt_10"} 1201
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9085
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9027
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 505711
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 6046102300 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 162329558721 (151.18 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 47124.2 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405058
telemt_connections_bad_total 2480
telemt_handshake_timeouts_total 31513
telemt_upstream_connect_attempt_total 12655
telemt_upstream_connect_success_total 12604
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 12655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 846
telemt_me_reconnect_attempts_total 10277
telemt_me_reconnect_success_total 10237
telemt_me_reader_eof_total 10865
telemt_me_idle_close_by_peer_total 10865
telemt_me_route_drop_no_conn_total 136006
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342156
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 298
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10307
telemt_me_writer_restored_same_endpoint_total 10216
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 341976
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 4053629180 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 131411958544 (122.39 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47124.1 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459484
telemt_connections_bad_total 476
telemt_handshake_timeouts_total 3397
telemt_upstream_connect_attempt_total 15177
telemt_upstream_connect_success_total 14997
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 15177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7150
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 636
telemt_me_reconnect_attempts_total 14146
telemt_me_reconnect_success_total 12621
telemt_me_reader_eof_total 13136
telemt_me_idle_close_by_peer_total 13136
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 149597
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 432427
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1811
telemt_desync_full_logged_total 601
telemt_desync_suppressed_total 1210
telemt_desync_frames_bucket_total{bucket="1_2"} 535
telemt_desync_frames_bucket_total{bucket="3_10"} 621
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 12792
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12596
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 432349
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 4878719140 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 104801200692 (97.60 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 149
```