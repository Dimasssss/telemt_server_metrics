# Server Metrics 2026-03-13 12:11:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 108801.0 (30h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3227255
telemt_connections_bad_total 36550
telemt_handshake_timeouts_total 56160
telemt_upstream_connect_attempt_total 21529
telemt_upstream_connect_success_total 21412
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 21529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 2075
telemt_me_reconnect_attempts_total 26086
telemt_me_reconnect_success_total 16005
telemt_me_reader_eof_total 17207
telemt_me_idle_close_by_peer_total 17206
telemt_me_route_drop_no_conn_total 1196615
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2955745
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12543
telemt_desync_full_logged_total 3254
telemt_desync_suppressed_total 9289
telemt_desync_frames_bucket_total{bucket="1_2"} 3208
telemt_desync_frames_bucket_total{bucket="3_10"} 4711
telemt_desync_frames_bucket_total{bucket="gt_10"} 4624
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16540
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15992
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 2955679
telemt_user_connections_current{user="hello"} 1932
telemt_user_octets_from_client{user="hello"} 40903430064 (38.09 GB)
telemt_user_octets_to_client{user="hello"} 953834122328 (888.33 GB)
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 8464.9 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113487
telemt_connections_bad_total 6521
telemt_handshake_timeouts_total 2654
telemt_upstream_connect_attempt_total 2184
telemt_upstream_connect_success_total 2113
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 2184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1006
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2853
telemt_me_reconnect_success_total 1627
telemt_me_reader_eof_total 1701
telemt_me_idle_close_by_peer_total 1701
telemt_me_route_drop_no_conn_total 40205
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101491
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 213
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1674
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1620
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 101514
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 973332592 (928.24 MB)
telemt_user_octets_to_client{user="hello"} 26303896560 (24.50 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 138421.6 (38h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2458242
telemt_connections_bad_total 25784
telemt_handshake_timeouts_total 163068
telemt_upstream_connect_attempt_total 31566
telemt_upstream_connect_success_total 31556
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14949
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3150
telemt_me_reconnect_attempts_total 26870
telemt_me_reconnect_success_total 24325
telemt_me_reader_eof_total 25784
telemt_me_idle_close_by_peer_total 25783
telemt_me_route_drop_no_conn_total 818571
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1992130
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6653
telemt_desync_full_logged_total 2147
telemt_desync_suppressed_total 4506
telemt_desync_frames_bucket_total{bucket="1_2"} 1053
telemt_desync_frames_bucket_total{bucket="3_10"} 2427
telemt_desync_frames_bucket_total{bucket="gt_10"} 3173
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 24605
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24284
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 1991542
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 33876208856 (31.55 GB)
telemt_user_octets_to_client{user="hello"} 712166988541 (663.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 138422.0 (38h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1565442
telemt_connections_bad_total 17834
telemt_handshake_timeouts_total 106944
telemt_upstream_connect_attempt_total 44846
telemt_upstream_connect_success_total 42529
telemt_upstream_connect_fail_total 2180
telemt_upstream_connect_attempts_per_request{bucket="1"} 44572
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2179
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11819
telemt_me_reconnect_attempts_total 38750
telemt_me_reconnect_success_total 29786
telemt_me_reader_eof_total 32032
telemt_me_idle_close_by_peer_total 32025
telemt_me_route_drop_no_conn_total 555665
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1305377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2483
telemt_desync_full_logged_total 826
telemt_desync_suppressed_total 1657
telemt_desync_frames_bucket_total{bucket="1_2"} 673
telemt_desync_frames_bucket_total{bucket="3_10"} 958
telemt_desync_frames_bucket_total{bucket="gt_10"} 852
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 30283
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 29762
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 1310099
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 19524224453 (18.18 GB)
telemt_user_octets_to_client{user="hello"} 511714762534 (476.57 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7857.7 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113309
telemt_connections_bad_total 610
telemt_handshake_timeouts_total 805
telemt_upstream_connect_attempt_total 1575
telemt_upstream_connect_success_total 1513
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 1575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 869
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 9150
telemt_me_reconnect_success_total 1080
telemt_me_reader_eof_total 1302
telemt_me_idle_close_by_peer_total 1302
telemt_me_route_drop_no_conn_total 44424
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108193
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 252
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_me_writer_removed_unexpected_total 1324
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1076
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 108188
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 1235100324 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 35460832520 (33.03 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 97
```