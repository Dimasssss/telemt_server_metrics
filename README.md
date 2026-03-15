# Server Metrics 2026-03-15 10:25:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 43846.5 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1058686
telemt_connections_bad_total 63434
telemt_handshake_timeouts_total 8220
telemt_upstream_connect_attempt_total 8823
telemt_upstream_connect_success_total 8784
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6636
telemt_me_reconnect_success_total 6596
telemt_me_reader_eof_total 6969
telemt_me_idle_close_by_peer_total 6969
telemt_me_route_drop_no_conn_total 349524
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892382
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3263
telemt_desync_full_logged_total 924
telemt_desync_suppressed_total 2339
telemt_desync_frames_bucket_total{bucket="1_2"} 793
telemt_desync_frames_bucket_total{bucket="3_10"} 1278
telemt_desync_frames_bucket_total{bucket="gt_10"} 1192
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6690
telemt_me_writer_restored_same_endpoint_total 6585
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 892379
telemt_user_connections_current{user="hello"} 2152
telemt_user_octets_from_client{user="hello"} 12839234276 (11.96 GB)
telemt_user_octets_to_client{user="hello"} 347574763380 (323.70 GB)
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 43847.2 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416495
telemt_connections_bad_total 23002
telemt_handshake_timeouts_total 17576
telemt_upstream_connect_attempt_total 11594
telemt_upstream_connect_success_total 11533
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9076
telemt_me_reconnect_success_total 9019
telemt_me_reader_eof_total 9547
telemt_me_idle_close_by_peer_total 9547
telemt_me_route_drop_no_conn_total 106302
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329314
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1174
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 435
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9106
telemt_me_writer_restored_same_endpoint_total 9011
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 329600
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 4819157807 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 123906559796 (115.40 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 43847.1 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783052
telemt_connections_bad_total 26183
telemt_handshake_timeouts_total 78329
telemt_upstream_connect_attempt_total 9728
telemt_upstream_connect_success_total 9686
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 7532
telemt_me_reconnect_success_total 7483
telemt_me_reader_eof_total 7917
telemt_me_idle_close_by_peer_total 7917
telemt_me_route_drop_no_conn_total 219382
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577684
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1284
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 813
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7581
telemt_me_writer_restored_same_endpoint_total 7464
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 577107
telemt_user_connections_current{user="hello"} 1119
telemt_user_octets_from_client{user="hello"} 8480941016 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 230671332848 (214.83 GB)
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 43847.1 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434434
telemt_connections_bad_total 55683
telemt_handshake_timeouts_total 25426
telemt_upstream_connect_attempt_total 13215
telemt_upstream_connect_success_total 12890
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 13215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 31059
telemt_me_reconnect_success_total 10698
telemt_me_reader_eof_total 11657
telemt_me_idle_close_by_peer_total 11657
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 121231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326165
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 762
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 310
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11430
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10666
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 326076
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 3957112800 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 105079100820 (97.86 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 43848.2 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436720
telemt_connections_bad_total 6031
telemt_handshake_timeouts_total 6997
telemt_upstream_connect_attempt_total 9718
telemt_upstream_connect_success_total 9673
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7525
telemt_me_reconnect_success_total 7488
telemt_me_reader_eof_total 7964
telemt_me_idle_close_by_peer_total 7964
telemt_me_route_drop_no_conn_total 114777
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360983
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1357
telemt_desync_full_logged_total 437
telemt_desync_suppressed_total 920
telemt_desync_frames_bucket_total{bucket="1_2"} 402
telemt_desync_frames_bucket_total{bucket="3_10"} 549
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7571
telemt_me_writer_restored_same_endpoint_total 7480
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 360987
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 4518667404 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 134560069272 (125.32 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 102
```