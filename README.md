# Server Metrics 2026-03-13 07:04:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 90373.3 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2460128
telemt_connections_bad_total 36051
telemt_handshake_timeouts_total 26070
telemt_upstream_connect_attempt_total 17694
telemt_upstream_connect_success_total 17595
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 1340
telemt_me_reconnect_attempts_total 21966
telemt_me_reconnect_success_total 13095
telemt_me_reader_eof_total 14122
telemt_me_idle_close_by_peer_total 14121
telemt_me_route_drop_no_conn_total 927373
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2258564
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10074
telemt_desync_full_logged_total 2599
telemt_desync_suppressed_total 7475
telemt_desync_frames_bucket_total{bucket="1_2"} 2565
telemt_desync_frames_bucket_total{bucket="3_10"} 3710
telemt_desync_frames_bucket_total{bucket="gt_10"} 3799
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 13555
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13082
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 2258091
telemt_user_connections_current{user="hello"} 1558
telemt_user_octets_from_client{user="hello"} 32499760720 (30.27 GB)
telemt_user_octets_to_client{user="hello"} 765000012368 (712.46 GB)
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 119993.8 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 983045
telemt_connections_bad_total 12599
telemt_handshake_timeouts_total 43381
telemt_upstream_connect_attempt_total 30166
telemt_upstream_connect_success_total 30135
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3599
telemt_me_reconnect_attempts_total 22639
telemt_me_reconnect_success_total 22520
telemt_me_reader_eof_total 24005
telemt_me_idle_close_by_peer_total 24005
telemt_me_route_drop_no_conn_total 313423
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 887739
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1172
telemt_desync_suppressed_total 2634
telemt_desync_frames_bucket_total{bucket="1_2"} 1455
telemt_desync_frames_bucket_total{bucket="3_10"} 1232
telemt_desync_frames_bucket_total{bucket="gt_10"} 1119
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22742
telemt_me_writer_restored_same_endpoint_total 22511
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 889664
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 13783604348 (12.84 GB)
telemt_user_octets_to_client{user="hello"} 336700850479 (313.58 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 119993.7 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2022364
telemt_connections_bad_total 23089
telemt_handshake_timeouts_total 135903
telemt_upstream_connect_attempt_total 27723
telemt_upstream_connect_success_total 27713
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1706
telemt_me_reconnect_attempts_total 22659
telemt_me_reconnect_success_total 21384
telemt_me_reader_eof_total 22652
telemt_me_idle_close_by_peer_total 22651
telemt_me_route_drop_no_conn_total 648070
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1598117
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5478
telemt_desync_full_logged_total 1691
telemt_desync_suppressed_total 3787
telemt_desync_frames_bucket_total{bucket="1_2"} 898
telemt_desync_frames_bucket_total{bucket="3_10"} 1992
telemt_desync_frames_bucket_total{bucket="gt_10"} 2588
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 21590
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21343
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 1597605
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 26963814128 (25.11 GB)
telemt_user_octets_to_client{user="hello"} 574025073945 (534.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 119994.1 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1235209
telemt_connections_bad_total 14049
telemt_handshake_timeouts_total 79662
telemt_upstream_connect_attempt_total 40598
telemt_upstream_connect_success_total 38302
telemt_upstream_connect_fail_total 2159
telemt_upstream_connect_attempts_per_request{bucket="1"} 40324
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2158
telemt_me_keepalive_timeout_total 11427
telemt_me_reconnect_attempts_total 35397
telemt_me_reconnect_success_total 26460
telemt_me_reader_eof_total 28509
telemt_me_idle_close_by_peer_total 28502
telemt_me_route_drop_no_conn_total 444952
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1063355
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2089
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1413
telemt_desync_frames_bucket_total{bucket="1_2"} 577
telemt_desync_frames_bucket_total{bucket="3_10"} 805
telemt_desync_frames_bucket_total{bucket="gt_10"} 707
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 26921
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26436
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 1068183
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 16362220453 (15.24 GB)
telemt_user_octets_to_client{user="hello"} 423351650002 (394.28 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 119994.1 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1395975
telemt_connections_bad_total 22224
telemt_handshake_timeouts_total 11500
telemt_upstream_connect_attempt_total 38067
telemt_upstream_connect_success_total 37602
telemt_upstream_connect_fail_total 465
telemt_upstream_connect_attempts_per_request{bucket="1"} 38067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 465
telemt_me_keepalive_timeout_total 2080
telemt_me_reconnect_attempts_total 45365
telemt_me_reconnect_success_total 31628
telemt_me_reader_eof_total 33184
telemt_me_idle_close_by_peer_total 33184
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 512158
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1285699
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4598
telemt_desync_full_logged_total 1644
telemt_desync_suppressed_total 2954
telemt_desync_frames_bucket_total{bucket="1_2"} 1398
telemt_desync_frames_bucket_total{bucket="3_10"} 1484
telemt_desync_frames_bucket_total{bucket="gt_10"} 1716
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 32403
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31572
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 775
telemt_user_connections_total{user="hello"} 1285538
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 16382347704 (15.26 GB)
telemt_user_octets_to_client{user="hello"} 441285242588 (410.98 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 142
```