# Server Metrics 2026-03-15 17:49:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 70513.9 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2485155
telemt_connections_bad_total 149387
telemt_handshake_timeouts_total 32368
telemt_upstream_connect_attempt_total 13706
telemt_upstream_connect_success_total 13647
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 13706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15006
telemt_me_reconnect_success_total 10108
telemt_me_reader_eof_total 10806
telemt_me_idle_close_by_peer_total 10806
telemt_me_route_drop_no_conn_total 858568
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2075297
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8070
telemt_desync_full_logged_total 2190
telemt_desync_suppressed_total 5880
telemt_desync_frames_bucket_total{bucket="1_2"} 1969
telemt_desync_frames_bucket_total{bucket="3_10"} 3095
telemt_desync_frames_bucket_total{bucket="gt_10"} 3006
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10432
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10097
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 2074779
telemt_user_connections_current{user="hello"} 2374
telemt_user_octets_from_client{user="hello"} 30769216860 (28.66 GB)
telemt_user_octets_to_client{user="hello"} 789926062112 (735.68 GB)
telemt_user_unique_ips_current{user="hello"} 681
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 70514.6 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 962780
telemt_connections_bad_total 53085
telemt_handshake_timeouts_total 62735
telemt_upstream_connect_attempt_total 17622
telemt_upstream_connect_success_total 17527
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14838
telemt_me_reconnect_success_total 13629
telemt_me_reader_eof_total 14420
telemt_me_idle_close_by_peer_total 14420
telemt_me_route_drop_no_conn_total 248802
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744209
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2203
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 830
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13843
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13617
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 744440
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 10800897923 (10.06 GB)
telemt_user_octets_to_client{user="hello"} 279561674008 (260.36 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 70514.7 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2134166
telemt_connections_bad_total 50303
telemt_handshake_timeouts_total 214494
telemt_upstream_connect_attempt_total 15237
telemt_upstream_connect_success_total 15162
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 15237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12861
telemt_me_reconnect_success_total 11592
telemt_me_reader_eof_total 12283
telemt_me_idle_close_by_peer_total 12283
telemt_me_route_drop_no_conn_total 553002
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1324681
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3403
telemt_desync_full_logged_total 1228
telemt_desync_suppressed_total 2175
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 1325
telemt_desync_frames_bucket_total{bucket="gt_10"} 1303
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11796
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11573
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 1320573
telemt_user_connections_current{user="hello"} 1450
telemt_user_octets_from_client{user="hello"} 23734617112 (22.10 GB)
telemt_user_octets_to_client{user="hello"} 484692514588 (451.41 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 70514.5 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028267
telemt_connections_bad_total 82050
telemt_handshake_timeouts_total 50230
telemt_upstream_connect_attempt_total 170586
telemt_upstream_connect_success_total 169999
telemt_upstream_connect_fail_total 587
telemt_upstream_connect_attempts_per_request{bucket="1"} 170586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 587
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61553
telemt_me_reconnect_success_total 13489
telemt_me_reader_eof_total 15355
telemt_me_idle_close_by_peer_total 15355
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 242265
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645276
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1824
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 1328
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 708
telemt_desync_frames_bucket_total{bucket="gt_10"} 653
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15135
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13453
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 797792
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 14896452685 (13.87 GB)
telemt_user_octets_to_client{user="hello"} 284891994672 (265.33 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 70515.7 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1041350
telemt_connections_bad_total 12563
telemt_handshake_timeouts_total 23147
telemt_upstream_connect_attempt_total 15529
telemt_upstream_connect_success_total 15446
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15592
telemt_me_reconnect_success_total 11897
telemt_me_reader_eof_total 12692
telemt_me_idle_close_by_peer_total 12692
telemt_me_route_drop_no_conn_total 259734
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 862320
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2929
telemt_desync_full_logged_total 982
telemt_desync_suppressed_total 1947
telemt_desync_frames_bucket_total{bucket="1_2"} 897
telemt_desync_frames_bucket_total{bucket="3_10"} 1091
telemt_desync_frames_bucket_total{bucket="gt_10"} 941
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12156
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11889
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 862345
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 10744298668 (10.01 GB)
telemt_user_octets_to_client{user="hello"} 302441378660 (281.67 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 115
```