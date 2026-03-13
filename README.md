# Server Metrics 2026-03-13 13:43:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 114303.7 (31h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3463147
telemt_connections_bad_total 37383
telemt_handshake_timeouts_total 59263
telemt_upstream_connect_attempt_total 22397
telemt_upstream_connect_success_total 22273
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 2123
telemt_me_reconnect_attempts_total 26688
telemt_me_reconnect_success_total 16604
telemt_me_reader_eof_total 17844
telemt_me_idle_close_by_peer_total 17843
telemt_me_route_drop_no_conn_total 1285151
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3178025
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13239
telemt_desync_full_logged_total 3454
telemt_desync_suppressed_total 9785
telemt_desync_frames_bucket_total{bucket="1_2"} 3368
telemt_desync_frames_bucket_total{bucket="3_10"} 5014
telemt_desync_frames_bucket_total{bucket="gt_10"} 4857
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 17149
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16591
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 3177900
telemt_user_connections_current{user="hello"} 1709
telemt_user_octets_from_client{user="hello"} 43767555048 (40.76 GB)
telemt_user_octets_to_client{user="hello"} 1013212091588 (943.63 GB)
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13967.8 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194682
telemt_connections_bad_total 11007
telemt_handshake_timeouts_total 5014
telemt_upstream_connect_attempt_total 3338
telemt_upstream_connect_success_total 3262
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 3338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 3744
telemt_me_reconnect_success_total 2514
telemt_me_reader_eof_total 2643
telemt_me_idle_close_by_peer_total 2643
telemt_me_route_drop_no_conn_total 70842
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173668
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 525
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2574
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2507
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 173692
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 1715795376 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 49323154664 (45.94 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 143924.5 (39h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2601649
telemt_connections_bad_total 26837
telemt_handshake_timeouts_total 173402
telemt_upstream_connect_attempt_total 32540
telemt_upstream_connect_success_total 32530
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3205
telemt_me_reconnect_attempts_total 27586
telemt_me_reconnect_success_total 25040
telemt_me_reader_eof_total 26549
telemt_me_idle_close_by_peer_total 26548
telemt_me_route_drop_no_conn_total 873720
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2121445
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7358
telemt_desync_full_logged_total 2404
telemt_desync_suppressed_total 4954
telemt_desync_frames_bucket_total{bucket="1_2"} 1160
telemt_desync_frames_bucket_total{bucket="3_10"} 2679
telemt_desync_frames_bucket_total{bucket="gt_10"} 3519
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 25332
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24999
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 2120867
telemt_user_connections_current{user="hello"} 1064
telemt_user_octets_from_client{user="hello"} 35434638628 (33.00 GB)
telemt_user_octets_to_client{user="hello"} 757068020977 (705.07 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server4

Не удалось получить метрики для этого сервера.

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13360.2 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209855
telemt_connections_bad_total 3850
telemt_handshake_timeouts_total 1890
telemt_upstream_connect_attempt_total 2689
telemt_upstream_connect_success_total 2603
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 2689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 9982
telemt_me_reconnect_success_total 1906
telemt_me_reader_eof_total 2172
telemt_me_idle_close_by_peer_total 2172
telemt_me_route_drop_no_conn_total 81877
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196257
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 686
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2160
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1902
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 196240
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 2055402876 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 59137755732 (55.08 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 85
```