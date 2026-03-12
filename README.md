# Server Metrics 2026-03-12 14:29:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 30665.2 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091313
telemt_connections_bad_total 14914
telemt_handshake_timeouts_total 11432
telemt_upstream_connect_attempt_total 6005
telemt_upstream_connect_success_total 5971
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 6005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 8311
telemt_me_reconnect_success_total 4412
telemt_me_reader_eof_total 4715
telemt_me_idle_close_by_peer_total 4714
telemt_me_route_drop_no_conn_total 385484
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1030232
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5556
telemt_desync_full_logged_total 1395
telemt_desync_suppressed_total 4161
telemt_desync_frames_bucket_total{bucket="1_2"} 1412
telemt_desync_frames_bucket_total{bucket="3_10"} 1999
telemt_desync_frames_bucket_total{bucket="gt_10"} 2145
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4585
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4399
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 1029973
telemt_user_connections_current{user="hello"} 1585
telemt_user_octets_from_client{user="hello"} 16528697896 (15.39 GB)
telemt_user_octets_to_client{user="hello"} 300678000252 (280.03 GB)
telemt_user_unique_ips_current{user="hello"} 439
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60285.6 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508218
telemt_connections_bad_total 5356
telemt_handshake_timeouts_total 25932
telemt_upstream_connect_attempt_total 14336
telemt_upstream_connect_success_total 14329
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1143
telemt_me_reconnect_attempts_total 11219
telemt_me_reconnect_success_total 11158
telemt_me_reader_eof_total 11867
telemt_me_idle_close_by_peer_total 11867
telemt_me_route_drop_no_conn_total 147703
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452424
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1700
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 1165
telemt_desync_frames_bucket_total{bucket="1_2"} 711
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11261
telemt_me_writer_restored_same_endpoint_total 11149
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 452900
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 6944678715 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 160844091742 (149.80 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 60285.6 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1097980
telemt_connections_bad_total 5854
telemt_handshake_timeouts_total 79234
telemt_upstream_connect_attempt_total 14455
telemt_upstream_connect_success_total 14450
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 932
telemt_me_reconnect_attempts_total 11197
telemt_me_reconnect_success_total 11097
telemt_me_reader_eof_total 11677
telemt_me_idle_close_by_peer_total 11677
telemt_me_route_drop_no_conn_total 287587
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790779
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3315
telemt_desync_full_logged_total 1017
telemt_desync_suppressed_total 2298
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 1201
telemt_desync_frames_bucket_total{bucket="gt_10"} 1625
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11140
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 11056
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 790967
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 10353444568 (9.64 GB)
telemt_user_octets_to_client{user="hello"} 252311869065 (234.98 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 60285.9 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639613
telemt_connections_bad_total 7689
telemt_handshake_timeouts_total 56377
telemt_upstream_connect_attempt_total 15923
telemt_upstream_connect_success_total 15859
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 15923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 1338
telemt_me_reconnect_attempts_total 14099
telemt_me_reconnect_success_total 12864
telemt_me_reader_eof_total 13634
telemt_me_idle_close_by_peer_total 13634
telemt_me_route_drop_no_conn_total 216266
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543166
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1089
telemt_desync_full_logged_total 380
telemt_desync_suppressed_total 709
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 446
telemt_desync_frames_bucket_total{bucket="gt_10"} 339
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13000
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12843
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 542669
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 5949317848 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 218877789332 (203.85 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60285.9 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721507
telemt_connections_bad_total 4529
telemt_handshake_timeouts_total 5767
telemt_upstream_connect_attempt_total 18799
telemt_upstream_connect_success_total 18572
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 18799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 1056
telemt_me_reconnect_attempts_total 22804
telemt_me_reconnect_success_total 15575
telemt_me_reader_eof_total 16333
telemt_me_idle_close_by_peer_total 16333
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 248649
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668629
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2739
telemt_desync_full_logged_total 921
telemt_desync_suppressed_total 1818
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 949
telemt_desync_frames_bucket_total{bucket="gt_10"} 1012
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 15959
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15544
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 384
telemt_user_connections_total{user="hello"} 668530
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 7776334056 (7.24 GB)
telemt_user_octets_to_client{user="hello"} 182157636112 (169.65 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 115
```