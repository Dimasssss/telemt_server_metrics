# Server Metrics 2026-03-13 01:07:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 68950.0 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2020141
telemt_connections_bad_total 26124
telemt_handshake_timeouts_total 21558
telemt_upstream_connect_attempt_total 13703
telemt_upstream_connect_success_total 13624
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1249
telemt_me_reconnect_attempts_total 19032
telemt_me_reconnect_success_total 10173
telemt_me_reader_eof_total 11004
telemt_me_idle_close_by_peer_total 11003
telemt_me_route_drop_no_conn_total 788616
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1879545
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8674
telemt_desync_full_logged_total 2259
telemt_desync_suppressed_total 6415
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3126
telemt_desync_frames_bucket_total{bucket="gt_10"} 3260
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10594
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10160
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 1879002
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 27605429600 (25.71 GB)
telemt_user_octets_to_client{user="hello"} 658553766848 (613.33 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 98570.5 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832311
telemt_connections_bad_total 11757
telemt_handshake_timeouts_total 31955
telemt_upstream_connect_attempt_total 25120
telemt_upstream_connect_success_total 25091
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3443
telemt_me_reconnect_attempts_total 18631
telemt_me_reconnect_success_total 18528
telemt_me_reader_eof_total 19728
telemt_me_idle_close_by_peer_total 19728
telemt_me_route_drop_no_conn_total 268965
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753768
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3056
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 2098
telemt_desync_frames_bucket_total{bucket="1_2"} 1236
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 18708
telemt_me_writer_restored_same_endpoint_total 18519
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 755671
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 12230663636 (11.39 GB)
telemt_user_octets_to_client{user="hello"} 285866012851 (266.23 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 98570.4 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1730880
telemt_connections_bad_total 8958
telemt_handshake_timeouts_total 114071
telemt_upstream_connect_attempt_total 22973
telemt_upstream_connect_success_total 22963
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10708
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1583
telemt_me_reconnect_attempts_total 18951
telemt_me_reconnect_success_total 17689
telemt_me_reader_eof_total 18725
telemt_me_idle_close_by_peer_total 18724
telemt_me_route_drop_no_conn_total 567769
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1359136
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17859
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17648
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 1358733
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 20009947876 (18.64 GB)
telemt_user_octets_to_client{user="hello"} 494949731989 (460.96 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 98570.6 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1085530
telemt_connections_bad_total 13093
telemt_handshake_timeouts_total 72391
telemt_upstream_connect_attempt_total 34338
telemt_upstream_connect_success_total 32073
telemt_upstream_connect_fail_total 2128
telemt_upstream_connect_attempts_per_request{bucket="1"} 34064
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2127
telemt_me_keepalive_timeout_total 11268
telemt_me_reconnect_attempts_total 29136
telemt_me_reconnect_success_total 21295
telemt_me_reader_eof_total 23048
telemt_me_idle_close_by_peer_total 23041
telemt_me_route_drop_no_conn_total 383852
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 929935
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 21674
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21273
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 935123
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 14435663757 (13.44 GB)
telemt_user_octets_to_client{user="hello"} 368464385946 (343.16 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 98570.6 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1195059
telemt_connections_bad_total 12582
telemt_handshake_timeouts_total 9365
telemt_upstream_connect_attempt_total 29884
telemt_upstream_connect_success_total 29509
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 29884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_keepalive_timeout_total 1839
telemt_me_reconnect_attempts_total 35634
telemt_me_reconnect_success_total 24588
telemt_me_reader_eof_total 25877
telemt_me_idle_close_by_peer_total 25877
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 447784
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1103671
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4131
telemt_desync_full_logged_total 1461
telemt_desync_suppressed_total 2670
telemt_desync_frames_bucket_total{bucket="1_2"} 1223
telemt_desync_frames_bucket_total{bucket="3_10"} 1375
telemt_desync_frames_bucket_total{bucket="gt_10"} 1533
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 25222
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24542
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 1103527
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 13693974868 (12.75 GB)
telemt_user_octets_to_client{user="hello"} 381838792156 (355.62 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 33
```