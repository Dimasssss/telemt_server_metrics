# Server Metrics 2026-03-15 14:04:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 57023.4 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1740685
telemt_connections_bad_total 97175
telemt_handshake_timeouts_total 18428
telemt_upstream_connect_attempt_total 11354
telemt_upstream_connect_success_total 11305
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13318
telemt_me_reconnect_success_total 8430
telemt_me_reader_eof_total 9030
telemt_me_idle_close_by_peer_total 9030
telemt_me_route_drop_no_conn_total 594794
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1469367
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5489
telemt_desync_full_logged_total 1525
telemt_desync_suppressed_total 3964
telemt_desync_frames_bucket_total{bucket="1_2"} 1411
telemt_desync_frames_bucket_total{bucket="3_10"} 2141
telemt_desync_frames_bucket_total{bucket="gt_10"} 1937
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8716
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8419
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 1468995
telemt_user_connections_current{user="hello"} 2268
telemt_user_octets_from_client{user="hello"} 20969062188 (19.53 GB)
telemt_user_octets_to_client{user="hello"} 578960804480 (539.20 GB)
telemt_user_unique_ips_current{user="hello"} 657
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 57024.2 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706379
telemt_connections_bad_total 38293
telemt_handshake_timeouts_total 55885
telemt_upstream_connect_attempt_total 14642
telemt_upstream_connect_success_total 14571
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 14642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11448
telemt_me_reconnect_success_total 11358
telemt_me_reader_eof_total 12008
telemt_me_idle_close_by_peer_total 12008
telemt_me_route_drop_no_conn_total 175427
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529628
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1973
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1292
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11498
telemt_me_writer_restored_same_endpoint_total 11346
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 529885
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 7472311459 (6.96 GB)
telemt_user_octets_to_client{user="hello"} 199914867496 (186.19 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 57024.2 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1503663
telemt_connections_bad_total 44594
telemt_handshake_timeouts_total 156860
telemt_upstream_connect_attempt_total 12603
telemt_upstream_connect_success_total 12545
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 12603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 10906
telemt_me_reconnect_success_total 9652
telemt_me_reader_eof_total 10232
telemt_me_idle_close_by_peer_total 10232
telemt_me_route_drop_no_conn_total 416649
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937257
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2374
telemt_desync_full_logged_total 875
telemt_desync_suppressed_total 1499
telemt_desync_frames_bucket_total{bucket="1_2"} 536
telemt_desync_frames_bucket_total{bucket="3_10"} 909
telemt_desync_frames_bucket_total{bucket="gt_10"} 929
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9819
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9633
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 933356
telemt_user_connections_current{user="hello"} 1267
telemt_user_octets_from_client{user="hello"} 13555407604 (12.62 GB)
telemt_user_octets_to_client{user="hello"} 338666368752 (315.41 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 57024.1 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721805
telemt_connections_bad_total 70950
telemt_handshake_timeouts_total 39055
telemt_upstream_connect_attempt_total 114751
telemt_upstream_connect_success_total 114292
telemt_upstream_connect_fail_total 459
telemt_upstream_connect_attempts_per_request{bucket="1"} 114751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 459
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 49507
telemt_me_reconnect_success_total 11794
telemt_me_reader_eof_total 13304
telemt_me_idle_close_by_peer_total 13304
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 170113
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445834
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1172
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13083
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 11762
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1289
telemt_user_connections_total{user="hello"} 545329
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 9994388551 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 185954340386 (173.18 GB)
telemt_user_msgs_from_client{user="hello"} 1917953
telemt_user_msgs_to_client{user="hello"} 7116326
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 57025.4 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 748164
telemt_connections_bad_total 9177
telemt_handshake_timeouts_total 15574
telemt_upstream_connect_attempt_total 12570
telemt_upstream_connect_success_total 12502
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 13304
telemt_me_reconnect_success_total 9631
telemt_me_reader_eof_total 10304
telemt_me_idle_close_by_peer_total 10304
telemt_me_route_drop_no_conn_total 185342
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606481
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2240
telemt_desync_full_logged_total 750
telemt_desync_suppressed_total 1490
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 695
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9859
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9623
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 606521
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 7538155608 (7.02 GB)
telemt_user_octets_to_client{user="hello"} 228194012704 (212.52 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 134
```