# Server Metrics 2026-03-12 19:15:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 47827.4 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1696405
telemt_connections_bad_total 20538
telemt_handshake_timeouts_total 16459
telemt_upstream_connect_attempt_total 9434
telemt_upstream_connect_success_total 9380
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 9434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 15779
telemt_me_reconnect_success_total 6933
telemt_me_reader_eof_total 7506
telemt_me_idle_close_by_peer_total 7505
telemt_me_route_drop_no_conn_total 664458
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1585447
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8020
telemt_desync_full_logged_total 2047
telemt_desync_suppressed_total 5973
telemt_desync_frames_bucket_total{bucket="1_2"} 2097
telemt_desync_frames_bucket_total{bucket="3_10"} 2888
telemt_desync_frames_bucket_total{bucket="gt_10"} 3035
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7306
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6920
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 1584931
telemt_user_connections_current{user="hello"} 1342
telemt_user_octets_from_client{user="hello"} 24548636728 (22.86 GB)
telemt_user_octets_to_client{user="hello"} 539490589692 (502.44 GB)
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 77448.0 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723590
telemt_connections_bad_total 9514
telemt_handshake_timeouts_total 29864
telemt_upstream_connect_attempt_total 19686
telemt_upstream_connect_success_total 19657
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3368
telemt_me_reconnect_attempts_total 14216
telemt_me_reconnect_success_total 14130
telemt_me_reader_eof_total 15020
telemt_me_idle_close_by_peer_total 15020
telemt_me_route_drop_no_conn_total 231722
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 652126
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2847
telemt_desync_full_logged_total 873
telemt_desync_suppressed_total 1974
telemt_desync_frames_bucket_total{bucket="1_2"} 1119
telemt_desync_frames_bucket_total{bucket="3_10"} 932
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 14280
telemt_me_writer_restored_same_endpoint_total 14121
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 654002
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 11081222392 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 246034649823 (229.14 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 77448.0 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1497712
telemt_connections_bad_total 7178
telemt_handshake_timeouts_total 102669
telemt_upstream_connect_attempt_total 18306
telemt_upstream_connect_success_total 18301
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1184
telemt_me_reconnect_attempts_total 15305
telemt_me_reconnect_success_total 14061
telemt_me_reader_eof_total 14830
telemt_me_idle_close_by_peer_total 14829
telemt_me_route_drop_no_conn_total 492867
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1145280
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4745
telemt_desync_full_logged_total 1463
telemt_desync_suppressed_total 3282
telemt_desync_frames_bucket_total{bucket="1_2"} 747
telemt_desync_frames_bucket_total{bucket="3_10"} 1718
telemt_desync_frames_bucket_total{bucket="gt_10"} 2280
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14188
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14020
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 1145143
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 17979568880 (16.74 GB)
telemt_user_octets_to_client{user="hello"} 424234821205 (395.10 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 77448.5 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913988
telemt_connections_bad_total 12959
telemt_handshake_timeouts_total 67549
telemt_upstream_connect_attempt_total 19896
telemt_upstream_connect_success_total 19815
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 19896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1639
telemt_me_reconnect_attempts_total 23673
telemt_me_reconnect_success_total 15948
telemt_me_reader_eof_total 17033
telemt_me_idle_close_by_peer_total 17033
telemt_me_route_drop_no_conn_total 323300
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790868
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1745
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 16318
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15927
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 790225
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 11938894212 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 324515961972 (302.23 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 77448.3 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1025390
telemt_connections_bad_total 11811
telemt_handshake_timeouts_total 8415
telemt_upstream_connect_attempt_total 24134
telemt_upstream_connect_success_total 23843
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 24134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 1393
telemt_me_reconnect_attempts_total 30992
telemt_me_reconnect_success_total 19957
telemt_me_reader_eof_total 20974
telemt_me_idle_close_by_peer_total 20974
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 383302
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940461
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3533
telemt_desync_full_logged_total 1237
telemt_desync_suppressed_total 2296
telemt_desync_frames_bucket_total{bucket="1_2"} 998
telemt_desync_frames_bucket_total{bucket="3_10"} 1179
telemt_desync_frames_bucket_total{bucket="gt_10"} 1356
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 20527
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19913
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 940332
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 11655002552 (10.85 GB)
telemt_user_octets_to_client{user="hello"} 318302238660 (296.44 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 78
```