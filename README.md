# Server Metrics 2026-03-13 08:06:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 94049.2 (26h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2610611
telemt_connections_bad_total 36234
telemt_handshake_timeouts_total 27711
telemt_upstream_connect_attempt_total 18315
telemt_upstream_connect_success_total 18214
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1366
telemt_me_reconnect_attempts_total 22412
telemt_me_reconnect_success_total 13539
telemt_me_reader_eof_total 14595
telemt_me_idle_close_by_peer_total 14594
telemt_me_route_drop_no_conn_total 975071
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2388169
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10792
telemt_desync_full_logged_total 2788
telemt_desync_suppressed_total 8004
telemt_desync_frames_bucket_total{bucket="1_2"} 2751
telemt_desync_frames_bucket_total{bucket="3_10"} 4021
telemt_desync_frames_bucket_total{bucket="gt_10"} 4020
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 14005
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13526
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 2387660
telemt_user_connections_current{user="hello"} 1594
telemt_user_octets_from_client{user="hello"} 33941479176 (31.61 GB)
telemt_user_octets_to_client{user="hello"} 798725420440 (743.87 GB)
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 123669.6 (34h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1065336
telemt_connections_bad_total 13476
telemt_handshake_timeouts_total 81474
telemt_upstream_connect_attempt_total 30948
telemt_upstream_connect_success_total 30917
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3628
telemt_me_reconnect_attempts_total 23247
telemt_me_reconnect_success_total 23126
telemt_me_reader_eof_total 24651
telemt_me_idle_close_by_peer_total 24651
telemt_me_route_drop_no_conn_total 328869
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 930025
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4108
telemt_desync_full_logged_total 1258
telemt_desync_suppressed_total 2850
telemt_desync_frames_bucket_total{bucket="1_2"} 1533
telemt_desync_frames_bucket_total{bucket="3_10"} 1335
telemt_desync_frames_bucket_total{bucket="gt_10"} 1240
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 23353
telemt_me_writer_restored_same_endpoint_total 23117
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 931950
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 14283373780 (13.30 GB)
telemt_user_octets_to_client{user="hello"} 347258879655 (323.41 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 123669.6 (34h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2097952
telemt_connections_bad_total 23645
telemt_handshake_timeouts_total 140833
telemt_upstream_connect_attempt_total 28425
telemt_upstream_connect_success_total 28415
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1742
telemt_me_reconnect_attempts_total 23188
telemt_me_reconnect_success_total 21908
telemt_me_reader_eof_total 23205
telemt_me_idle_close_by_peer_total 23204
telemt_me_route_drop_no_conn_total 677722
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1666739
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5646
telemt_desync_full_logged_total 1776
telemt_desync_suppressed_total 3870
telemt_desync_frames_bucket_total{bucket="1_2"} 929
telemt_desync_frames_bucket_total{bucket="3_10"} 2057
telemt_desync_frames_bucket_total{bucket="gt_10"} 2660
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22123
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21867
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 1666207
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 27703539696 (25.80 GB)
telemt_user_octets_to_client{user="hello"} 605985594433 (564.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 123670.0 (34h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1314288
telemt_connections_bad_total 14214
telemt_handshake_timeouts_total 82354
telemt_upstream_connect_attempt_total 41518
telemt_upstream_connect_success_total 39217
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41244
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11444
telemt_me_reconnect_attempts_total 36139
telemt_me_reconnect_success_total 27201
telemt_me_reader_eof_total 29298
telemt_me_idle_close_by_peer_total 29291
telemt_me_route_drop_no_conn_total 467075
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1109187
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2173
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1467
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 836
telemt_desync_frames_bucket_total{bucket="gt_10"} 742
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 27670
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27177
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 1113931
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 16879251901 (15.72 GB)
telemt_user_octets_to_client{user="hello"} 443927056866 (413.44 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 123669.6 (34h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1464984
telemt_connections_bad_total 27910
telemt_handshake_timeouts_total 12236
telemt_upstream_connect_attempt_total 38973
telemt_upstream_connect_success_total 38498
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 38973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 2129
telemt_me_reconnect_attempts_total 46087
telemt_me_reconnect_success_total 32346
telemt_me_reader_eof_total 33951
telemt_me_idle_close_by_peer_total 33951
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 537270
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1345993
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4749
telemt_desync_full_logged_total 1693
telemt_desync_suppressed_total 3056
telemt_desync_frames_bucket_total{bucket="1_2"} 1446
telemt_desync_frames_bucket_total{bucket="3_10"} 1532
telemt_desync_frames_bucket_total{bucket="gt_10"} 1771
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33131
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32290
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 785
telemt_user_connections_total{user="hello"} 1345801
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 17153860128 (15.98 GB)
telemt_user_octets_to_client{user="hello"} 463733840252 (431.89 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 121
```