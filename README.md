# Server Metrics 2026-03-13 04:52:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 82412.1 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2226496
telemt_connections_bad_total 31539
telemt_handshake_timeouts_total 23435
telemt_upstream_connect_attempt_total 16267
telemt_upstream_connect_success_total 16177
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 16267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 20938
telemt_me_reconnect_success_total 12073
telemt_me_reader_eof_total 13029
telemt_me_idle_close_by_peer_total 13028
telemt_me_route_drop_no_conn_total 848901
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2047418
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8987
telemt_desync_full_logged_total 2334
telemt_desync_suppressed_total 6653
telemt_desync_frames_bucket_total{bucket="1_2"} 2359
telemt_desync_frames_bucket_total{bucket="3_10"} 3254
telemt_desync_frames_bucket_total{bucket="gt_10"} 3374
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12518
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12060
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 2046841
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 29780034100 (27.73 GB)
telemt_user_octets_to_client{user="hello"} 706777378052 (658.24 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 112032.5 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 903797
telemt_connections_bad_total 11938
telemt_handshake_timeouts_total 39740
telemt_upstream_connect_attempt_total 28411
telemt_upstream_connect_success_total 28380
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3529
telemt_me_reconnect_attempts_total 21274
telemt_me_reconnect_success_total 21157
telemt_me_reader_eof_total 22554
telemt_me_idle_close_by_peer_total 22554
telemt_me_route_drop_no_conn_total 287987
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 815203
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3239
telemt_desync_full_logged_total 1019
telemt_desync_suppressed_total 2220
telemt_desync_frames_bucket_total{bucket="1_2"} 1293
telemt_desync_frames_bucket_total{bucket="3_10"} 1059
telemt_desync_frames_bucket_total{bucket="gt_10"} 887
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 21367
telemt_me_writer_restored_same_endpoint_total 21148
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 817102
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 13060907552 (12.16 GB)
telemt_user_octets_to_client{user="hello"} 314317257199 (292.73 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 112032.5 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1866687
telemt_connections_bad_total 17401
telemt_handshake_timeouts_total 122758
telemt_upstream_connect_attempt_total 26100
telemt_upstream_connect_success_total 26090
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12298
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1641
telemt_me_reconnect_attempts_total 21428
telemt_me_reconnect_success_total 20160
telemt_me_reader_eof_total 21351
telemt_me_idle_close_by_peer_total 21350
telemt_me_route_drop_no_conn_total 602369
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1474101
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5134
telemt_desync_full_logged_total 1570
telemt_desync_suppressed_total 3564
telemt_desync_frames_bucket_total{bucket="1_2"} 825
telemt_desync_frames_bucket_total{bucket="3_10"} 1852
telemt_desync_frames_bucket_total{bucket="gt_10"} 2457
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 20351
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20119
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 1473638
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 25423847256 (23.68 GB)
telemt_user_octets_to_client{user="hello"} 522081109717 (486.23 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 112032.9 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1153396
telemt_connections_bad_total 13200
telemt_handshake_timeouts_total 74979
telemt_upstream_connect_attempt_total 38511
telemt_upstream_connect_success_total 36227
telemt_upstream_connect_fail_total 2147
telemt_upstream_connect_attempts_per_request{bucket="1"} 38237
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2146
telemt_me_keepalive_timeout_total 11391
telemt_me_reconnect_attempts_total 33715
telemt_me_reconnect_success_total 24781
telemt_me_reader_eof_total 26746
telemt_me_idle_close_by_peer_total 26739
telemt_me_route_drop_no_conn_total 410605
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 992756
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1952
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 25229
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24757
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 997932
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 15259891385 (14.21 GB)
telemt_user_octets_to_client{user="hello"} 393443648154 (366.42 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 112032.7 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284192
telemt_connections_bad_total 12908
telemt_handshake_timeouts_total 10285
telemt_upstream_connect_attempt_total 35314
telemt_upstream_connect_success_total 34888
telemt_upstream_connect_fail_total 426
telemt_upstream_connect_attempts_per_request{bucket="1"} 35314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 426
telemt_me_keepalive_timeout_total 1942
telemt_me_reconnect_attempts_total 43045
telemt_me_reconnect_success_total 29313
telemt_me_reader_eof_total 30812
telemt_me_idle_close_by_peer_total 30812
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 475583
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1188518
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4332
telemt_desync_full_logged_total 1561
telemt_desync_suppressed_total 2771
telemt_desync_frames_bucket_total{bucket="1_2"} 1310
telemt_desync_frames_bucket_total{bucket="3_10"} 1413
telemt_desync_frames_bucket_total{bucket="gt_10"} 1609
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 30075
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29262
telemt_me_writer_restored_fallback_total 51
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 762
telemt_user_connections_total{user="hello"} 1188372
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 14448297696 (13.46 GB)
telemt_user_octets_to_client{user="hello"} 404483677440 (376.70 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 77
```