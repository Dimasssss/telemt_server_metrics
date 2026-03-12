# Server Metrics 2026-03-12 15:00:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 32500.0 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164118
telemt_connections_bad_total 20161
telemt_handshake_timeouts_total 11993
telemt_upstream_connect_attempt_total 6406
telemt_upstream_connect_success_total 6370
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 407
telemt_me_reconnect_attempts_total 8604
telemt_me_reconnect_success_total 4701
telemt_me_reader_eof_total 5019
telemt_me_idle_close_by_peer_total 5018
telemt_me_route_drop_no_conn_total 411529
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1094927
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5817
telemt_desync_full_logged_total 1464
telemt_desync_suppressed_total 4353
telemt_desync_frames_bucket_total{bucket="1_2"} 1493
telemt_desync_frames_bucket_total{bucket="3_10"} 2086
telemt_desync_frames_bucket_total{bucket="gt_10"} 2238
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4878
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4688
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 1094662
telemt_user_connections_current{user="hello"} 1776
telemt_user_octets_from_client{user="hello"} 17318469728 (16.13 GB)
telemt_user_octets_to_client{user="hello"} 319844201212 (297.88 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62120.6 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531737
telemt_connections_bad_total 6089
telemt_handshake_timeouts_total 26713
telemt_upstream_connect_attempt_total 14945
telemt_upstream_connect_success_total 14938
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1177
telemt_me_reconnect_attempts_total 11733
telemt_me_reconnect_success_total 11668
telemt_me_reader_eof_total 12382
telemt_me_idle_close_by_peer_total 12382
telemt_me_route_drop_no_conn_total 154942
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473851
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1815
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1243
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 588
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11776
telemt_me_writer_restored_same_endpoint_total 11659
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 474350
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 7315416231 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 166763065330 (155.31 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 62120.6 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1139563
telemt_connections_bad_total 6060
telemt_handshake_timeouts_total 80687
telemt_upstream_connect_attempt_total 14862
telemt_upstream_connect_success_total 14857
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 973
telemt_me_reconnect_attempts_total 12634
telemt_me_reconnect_success_total 11413
telemt_me_reader_eof_total 12046
telemt_me_idle_close_by_peer_total 12046
telemt_me_route_drop_no_conn_total 301553
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 829886
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3438
telemt_desync_full_logged_total 1059
telemt_desync_suppressed_total 2379
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 1253
telemt_desync_frames_bucket_total{bucket="gt_10"} 1679
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11494
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11372
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 830075
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 11001914488 (10.25 GB)
telemt_user_octets_to_client{user="hello"} 261454901149 (243.50 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 62121.0 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 671861
telemt_connections_bad_total 7696
telemt_handshake_timeouts_total 57110
telemt_upstream_connect_attempt_total 16528
telemt_upstream_connect_success_total 16460
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1352
telemt_me_reconnect_attempts_total 15892
telemt_me_reconnect_success_total 13375
telemt_me_reader_eof_total 14188
telemt_me_idle_close_by_peer_total 14188
telemt_me_route_drop_no_conn_total 226587
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573681
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1141
telemt_desync_full_logged_total 395
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13554
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 13354
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 573182
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 6904002728 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 229686453064 (213.91 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62120.9 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755585
telemt_connections_bad_total 6026
telemt_handshake_timeouts_total 6072
telemt_upstream_connect_attempt_total 19406
telemt_upstream_connect_success_total 19172
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 19406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 1087
telemt_me_reconnect_attempts_total 23317
telemt_me_reconnect_success_total 16087
telemt_me_reader_eof_total 16850
telemt_me_idle_close_by_peer_total 16850
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 262157
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 698687
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2819
telemt_desync_full_logged_total 945
telemt_desync_suppressed_total 1874
telemt_desync_frames_bucket_total{bucket="1_2"} 795
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 1054
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16478
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16053
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 698587
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 8296850532 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 192998548652 (179.74 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 141
```