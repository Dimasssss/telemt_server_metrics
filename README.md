# Server Metrics 2026-03-13 07:10:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 90679.7 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2472082
telemt_connections_bad_total 36053
telemt_handshake_timeouts_total 26137
telemt_upstream_connect_attempt_total 17719
telemt_upstream_connect_success_total 17620
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 1349
telemt_me_reconnect_attempts_total 21991
telemt_me_reconnect_success_total 13120
telemt_me_reader_eof_total 14149
telemt_me_idle_close_by_peer_total 14148
telemt_me_route_drop_no_conn_total 931820
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2268988
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10122
telemt_desync_full_logged_total 2613
telemt_desync_suppressed_total 7509
telemt_desync_frames_bucket_total{bucket="1_2"} 2580
telemt_desync_frames_bucket_total{bucket="3_10"} 3728
telemt_desync_frames_bucket_total{bucket="gt_10"} 3814
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 13582
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13107
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 2268519
telemt_user_connections_current{user="hello"} 1619
telemt_user_octets_from_client{user="hello"} 32614865072 (30.37 GB)
telemt_user_octets_to_client{user="hello"} 768315841680 (715.55 GB)
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 120300.1 (33h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 986642
telemt_connections_bad_total 12648
telemt_handshake_timeouts_total 43570
telemt_upstream_connect_attempt_total 30256
telemt_upstream_connect_success_total 30225
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3603
telemt_me_reconnect_attempts_total 22729
telemt_me_reconnect_success_total 22610
telemt_me_reader_eof_total 24095
telemt_me_idle_close_by_peer_total 24095
telemt_me_route_drop_no_conn_total 314681
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 890978
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3819
telemt_desync_full_logged_total 1175
telemt_desync_suppressed_total 2644
telemt_desync_frames_bucket_total{bucket="1_2"} 1461
telemt_desync_frames_bucket_total{bucket="3_10"} 1233
telemt_desync_frames_bucket_total{bucket="gt_10"} 1125
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22832
telemt_me_writer_restored_same_endpoint_total 22601
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 892904
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 13800949520 (12.85 GB)
telemt_user_octets_to_client{user="hello"} 337576646999 (314.39 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 120300.2 (33h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2028385
telemt_connections_bad_total 23091
telemt_handshake_timeouts_total 136077
telemt_upstream_connect_attempt_total 27763
telemt_upstream_connect_success_total 27753
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1707
telemt_me_reconnect_attempts_total 22699
telemt_me_reconnect_success_total 21423
telemt_me_reader_eof_total 22693
telemt_me_idle_close_by_peer_total 22692
telemt_me_route_drop_no_conn_total 650532
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1603828
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5494
telemt_desync_full_logged_total 1702
telemt_desync_suppressed_total 3792
telemt_desync_frames_bucket_total{bucket="1_2"} 900
telemt_desync_frames_bucket_total{bucket="3_10"} 1997
telemt_desync_frames_bucket_total{bucket="gt_10"} 2597
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 21631
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21382
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 1603317
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 27025836244 (25.17 GB)
telemt_user_octets_to_client{user="hello"} 576926998517 (537.31 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 120300.4 (33h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1240529
telemt_connections_bad_total 14052
telemt_handshake_timeouts_total 80086
telemt_upstream_connect_attempt_total 40677
telemt_upstream_connect_success_total 38381
telemt_upstream_connect_fail_total 2159
telemt_upstream_connect_attempts_per_request{bucket="1"} 40403
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2158
telemt_me_keepalive_timeout_total 11429
telemt_me_reconnect_attempts_total 35476
telemt_me_reconnect_success_total 26539
telemt_me_reader_eof_total 28588
telemt_me_idle_close_by_peer_total 28581
telemt_me_route_drop_no_conn_total 447041
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1067272
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2093
telemt_desync_full_logged_total 678
telemt_desync_suppressed_total 1415
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 807
telemt_desync_frames_bucket_total{bucket="gt_10"} 708
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 27000
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26515
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 1072099
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 16388378821 (15.26 GB)
telemt_user_octets_to_client{user="hello"} 424705037626 (395.54 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 120300.2 (33h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1401565
telemt_connections_bad_total 22701
telemt_handshake_timeouts_total 11537
telemt_upstream_connect_attempt_total 38197
telemt_upstream_connect_success_total 37732
telemt_upstream_connect_fail_total 465
telemt_upstream_connect_attempts_per_request{bucket="1"} 38197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 465
telemt_me_keepalive_timeout_total 2082
telemt_me_reconnect_attempts_total 45495
telemt_me_reconnect_success_total 31758
telemt_me_reader_eof_total 33314
telemt_me_idle_close_by_peer_total 33314
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 514589
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1290590
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4633
telemt_desync_full_logged_total 1650
telemt_desync_suppressed_total 2983
telemt_desync_frames_bucket_total{bucket="1_2"} 1401
telemt_desync_frames_bucket_total{bucket="3_10"} 1499
telemt_desync_frames_bucket_total{bucket="gt_10"} 1733
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 32533
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31702
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 775
telemt_user_connections_total{user="hello"} 1290432
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 16435914636 (15.31 GB)
telemt_user_octets_to_client{user="hello"} 442483600648 (412.09 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 119
```