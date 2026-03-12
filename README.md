# Server Metrics 2026-03-12 12:47:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24544.4 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 841916
telemt_connections_bad_total 3530
telemt_handshake_timeouts_total 6773
telemt_upstream_connect_attempt_total 4899
telemt_upstream_connect_success_total 4869
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 7487
telemt_me_reconnect_success_total 3592
telemt_me_reader_eof_total 3855
telemt_me_idle_close_by_peer_total 3855
telemt_me_route_drop_no_conn_total 298219
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 807542
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4235
telemt_desync_full_logged_total 1078
telemt_desync_suppressed_total 3157
telemt_desync_frames_bucket_total{bucket="1_2"} 1060
telemt_desync_frames_bucket_total{bucket="3_10"} 1538
telemt_desync_frames_bucket_total{bucket="gt_10"} 1637
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3751
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3579
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 807372
telemt_user_connections_current{user="hello"} 1560
telemt_user_octets_from_client{user="hello"} 13694990996 (12.75 GB)
telemt_user_octets_to_client{user="hello"} 232178481544 (216.23 GB)
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 54164.7 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421665
telemt_connections_bad_total 5222
telemt_handshake_timeouts_total 22357
telemt_upstream_connect_attempt_total 13126
telemt_upstream_connect_success_total 13119
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1056
telemt_me_reconnect_attempts_total 10272
telemt_me_reconnect_success_total 10215
telemt_me_reader_eof_total 10860
telemt_me_idle_close_by_peer_total 10860
telemt_me_route_drop_no_conn_total 121037
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371839
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1233
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 836
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10309
telemt_me_writer_restored_same_endpoint_total 10206
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 372296
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 5009794027 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 132572612086 (123.47 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 54164.7 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 944853
telemt_connections_bad_total 5154
telemt_handshake_timeouts_total 71193
telemt_upstream_connect_attempt_total 13218
telemt_upstream_connect_success_total 13213
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 863
telemt_me_reconnect_attempts_total 10222
telemt_me_reconnect_success_total 10133
telemt_me_reader_eof_total 10675
telemt_me_idle_close_by_peer_total 10675
telemt_me_route_drop_no_conn_total 234073
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651791
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2945
telemt_desync_full_logged_total 885
telemt_desync_suppressed_total 2060
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 1047
telemt_desync_frames_bucket_total{bucket="gt_10"} 1478
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10162
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10092
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 652019
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 8495417868 (7.91 GB)
telemt_user_octets_to_client{user="hello"} 205208008657 (191.11 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 54165.1 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530554
telemt_connections_bad_total 7637
telemt_handshake_timeouts_total 49143
telemt_upstream_connect_attempt_total 14543
telemt_upstream_connect_success_total 14485
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1268
telemt_me_reconnect_attempts_total 12989
telemt_me_reconnect_success_total 11757
telemt_me_reader_eof_total 12475
telemt_me_idle_close_by_peer_total 12475
telemt_me_route_drop_no_conn_total 178871
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443448
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 898
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11881
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11736
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 442960
telemt_user_connections_current{user="hello"} 677
telemt_user_octets_from_client{user="hello"} 5027516740 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 175623221312 (163.56 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 54165.0 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597527
telemt_connections_bad_total 1710
telemt_handshake_timeouts_total 4733
telemt_upstream_connect_attempt_total 17418
telemt_upstream_connect_success_total 17206
telemt_upstream_connect_fail_total 212
telemt_upstream_connect_attempts_per_request{bucket="1"} 17418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 212
telemt_me_keepalive_timeout_total 967
telemt_me_reconnect_attempts_total 21699
telemt_me_reconnect_success_total 14475
telemt_me_reader_eof_total 15180
telemt_me_idle_close_by_peer_total 15180
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 201507
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558181
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2329
telemt_desync_full_logged_total 785
telemt_desync_suppressed_total 1544
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 822
telemt_desync_frames_bucket_total{bucket="gt_10"} 848
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 14841
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14448
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 558094
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 6459814036 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 142930117272 (133.11 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 109
```