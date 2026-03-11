# Server Metrics 2026-03-11 14:51:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 87865.5 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2136056
telemt_connections_bad_total 34692
telemt_handshake_timeouts_total 52255
telemt_upstream_connect_attempt_total 18554
telemt_upstream_connect_success_total 18542
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4849
telemt_me_reconnect_attempts_total 30648
telemt_me_reconnect_success_total 14094
telemt_me_reader_eof_total 15263
telemt_me_idle_close_by_peer_total 15263
telemt_me_route_drop_no_conn_total 789415
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1953567
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10221
telemt_desync_full_logged_total 2769
telemt_desync_suppressed_total 7452
telemt_desync_frames_bucket_total{bucket="1_2"} 2545
telemt_desync_frames_bucket_total{bucket="3_10"} 3942
telemt_desync_frames_bucket_total{bucket="gt_10"} 3734
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14762
telemt_me_refill_failed_total 514
telemt_me_writer_restored_same_endpoint_total 14088
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 668
telemt_user_connections_total{user="hello"} 1952058
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 26316312168 (24.51 GB)
telemt_user_octets_to_client{user="hello"} 557377335916 (519.10 GB)
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87922.3 (24h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797067
telemt_connections_bad_total 13234
telemt_handshake_timeouts_total 54316
telemt_upstream_connect_attempt_total 27981
telemt_upstream_connect_success_total 25030
telemt_upstream_connect_fail_total 2951
telemt_upstream_connect_attempts_per_request{bucket="1"} 27981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2951
telemt_me_keepalive_timeout_total 2535
telemt_me_reconnect_attempts_total 19765
telemt_me_reconnect_success_total 17674
telemt_me_reader_eof_total 18723
telemt_me_idle_close_by_peer_total 18720
telemt_me_route_drop_no_conn_total 312689
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675832
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2861
telemt_desync_full_logged_total 909
telemt_desync_suppressed_total 1952
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1032
telemt_desync_frames_bucket_total{bucket="gt_10"} 941
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 17935
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17651
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 678309
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 7751510422 (7.22 GB)
telemt_user_octets_to_client{user="hello"} 191426295220 (178.28 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 87922.3 (24h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1382549
telemt_connections_bad_total 8456
telemt_handshake_timeouts_total 122574
telemt_upstream_connect_attempt_total 23352
telemt_upstream_connect_success_total 23073
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 23352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 1566
telemt_me_reconnect_attempts_total 33681
telemt_me_reconnect_success_total 17569
telemt_me_reader_eof_total 18870
telemt_me_idle_close_by_peer_total 18870
telemt_me_route_drop_no_conn_total 500819
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1200280
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3172
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 2234
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 1200
telemt_desync_frames_bucket_total{bucket="gt_10"} 1197
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18311
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17558
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 742
telemt_user_connections_total{user="hello"} 1200049
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 14413580277 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 359245579741 (334.57 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 87922.7 (24h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 990896
telemt_connections_bad_total 77629
telemt_handshake_timeouts_total 94487
telemt_upstream_connect_attempt_total 23654
telemt_upstream_connect_success_total 23654
telemt_upstream_connect_attempts_per_request{bucket="1"} 23654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 966
telemt_me_reconnect_attempts_total 20342
telemt_me_reconnect_success_total 19268
telemt_me_reader_eof_total 20438
telemt_me_idle_close_by_peer_total 20437
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 323026
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791894
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1679
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 596
telemt_desync_frames_bucket_total{bucket="gt_10"} 482
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19506
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19240
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 791218
telemt_user_connections_current{user="hello"} 581
telemt_user_octets_from_client{user="hello"} 9231710992 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 231697769340 (215.79 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87922.5 (24h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091275
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 11080
telemt_upstream_connect_attempt_total 23833
telemt_upstream_connect_success_total 23727
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 23833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1907
telemt_me_reconnect_attempts_total 23290
telemt_me_reconnect_success_total 19205
telemt_me_reader_eof_total 20254
telemt_me_idle_close_by_peer_total 20254
telemt_me_route_drop_no_conn_total 388140
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 991699
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3831
telemt_desync_full_logged_total 1405
telemt_desync_suppressed_total 2426
telemt_desync_frames_bucket_total{bucket="1_2"} 1336
telemt_desync_frames_bucket_total{bucket="3_10"} 1442
telemt_desync_frames_bucket_total{bucket="gt_10"} 1053
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19580
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19205
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 991425
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 14263436839 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 347734149674 (323.85 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 90
```