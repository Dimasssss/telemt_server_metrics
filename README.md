# Server Metrics 2026-03-12 08:22:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8637.3 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263407
telemt_connections_bad_total 1314
telemt_handshake_timeouts_total 1878
telemt_upstream_connect_attempt_total 1706
telemt_upstream_connect_success_total 1695
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 764
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1238
telemt_me_reconnect_success_total 1230
telemt_me_reader_eof_total 1265
telemt_me_idle_close_by_peer_total 1265
telemt_me_route_drop_no_conn_total 89080
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254528
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1216
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 912
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1234
telemt_me_writer_restored_same_endpoint_total 1217
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 254443
telemt_user_connections_current{user="hello"} 1167
telemt_user_octets_from_client{user="hello"} 4018732788 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 72763085900 (67.77 GB)
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 38257.6 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203847
telemt_connections_bad_total 2659
telemt_handshake_timeouts_total 7311
telemt_upstream_connect_attempt_total 9931
telemt_upstream_connect_success_total 9925
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 596
telemt_me_reconnect_attempts_total 7863
telemt_me_reconnect_success_total 7822
telemt_me_reader_eof_total 8308
telemt_me_idle_close_by_peer_total 8308
telemt_me_route_drop_no_conn_total 58961
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177802
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7884
telemt_me_writer_restored_same_endpoint_total 7813
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 178096
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 2633183479 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 69654737542 (64.87 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 38257.5 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590779
telemt_connections_bad_total 2701
telemt_handshake_timeouts_total 44030
telemt_upstream_connect_attempt_total 10031
telemt_upstream_connect_success_total 10026
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 7819
telemt_me_reconnect_success_total 7750
telemt_me_reader_eof_total 8133
telemt_me_idle_close_by_peer_total 8133
telemt_me_route_drop_no_conn_total 115566
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334745
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1581
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 546
telemt_desync_frames_bucket_total{bucket="gt_10"} 824
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7744
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7709
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 335023
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 3734049892 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 116671809821 (108.66 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 38257.9 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278966
telemt_connections_bad_total 1796
telemt_handshake_timeouts_total 18870
telemt_upstream_connect_attempt_total 10620
telemt_upstream_connect_success_total 10578
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 10620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 8689
telemt_me_reconnect_success_total 8658
telemt_me_reader_eof_total 9195
telemt_me_idle_close_by_peer_total 9195
telemt_me_route_drop_no_conn_total 92533
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231808
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 413
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8713
telemt_me_writer_restored_same_endpoint_total 8637
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 231633
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 2629455928 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 80065929116 (74.57 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 38257.7 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307124
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 2422
telemt_upstream_connect_attempt_total 12767
telemt_upstream_connect_success_total 12615
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 12767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 559
telemt_me_reconnect_attempts_total 12199
telemt_me_reconnect_success_total 10685
telemt_me_reader_eof_total 11122
telemt_me_idle_close_by_peer_total 11122
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 97690
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289151
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1168
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 779
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 10829
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10664
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 289094
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 3121039504 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 69586634804 (64.81 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 107
```