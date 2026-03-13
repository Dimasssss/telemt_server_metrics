# Server Metrics 2026-03-13 18:04:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 129922.4 (36h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4149303
telemt_connections_bad_total 37531
telemt_handshake_timeouts_total 101856
telemt_upstream_connect_attempt_total 27477
telemt_upstream_connect_success_total 27298
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 27477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 5755
telemt_me_reconnect_attempts_total 28569
telemt_me_reconnect_success_total 18463
telemt_me_reader_eof_total 19835
telemt_me_idle_close_by_peer_total 19834
telemt_me_route_drop_no_conn_total 1547456
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3790666
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14802
telemt_desync_full_logged_total 3941
telemt_desync_suppressed_total 10861
telemt_desync_frames_bucket_total{bucket="1_2"} 3663
telemt_desync_frames_bucket_total{bucket="3_10"} 5618
telemt_desync_frames_bucket_total{bucket="gt_10"} 5521
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19040
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18450
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 3792828
telemt_user_connections_current{user="hello"} 1733
telemt_user_octets_from_client{user="hello"} 53308187044 (49.65 GB)
telemt_user_octets_to_client{user="hello"} 1177155793069 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29586.1 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441496
telemt_connections_bad_total 33861
telemt_handshake_timeouts_total 10555
telemt_upstream_connect_attempt_total 8382
telemt_upstream_connect_success_total 8205
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 8382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 1602
telemt_me_reconnect_attempts_total 8688
telemt_me_reconnect_success_total 5290
telemt_me_reader_eof_total 5602
telemt_me_idle_close_by_peer_total 5601
telemt_me_route_drop_no_conn_total 166060
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384474
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1329
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 983
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 621
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5465
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5282
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 385812
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 3979125939 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 118883555420 (110.72 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 159543.0 (44h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3033826
telemt_connections_bad_total 28758
telemt_handshake_timeouts_total 202873
telemt_upstream_connect_attempt_total 35597
telemt_upstream_connect_success_total 35587
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3489
telemt_me_reconnect_attempts_total 29857
telemt_me_reconnect_success_total 27302
telemt_me_reader_eof_total 28952
telemt_me_idle_close_by_peer_total 28951
telemt_me_route_drop_no_conn_total 1036057
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2509038
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8530
telemt_desync_full_logged_total 2828
telemt_desync_suppressed_total 5702
telemt_desync_frames_bucket_total{bucket="1_2"} 1379
telemt_desync_frames_bucket_total{bucket="3_10"} 3121
telemt_desync_frames_bucket_total{bucket="gt_10"} 4030
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 27620
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27261
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 2508373
telemt_user_connections_current{user="hello"} 1062
telemt_user_octets_from_client{user="hello"} 41221998412 (38.39 GB)
telemt_user_octets_to_client{user="hello"} 876888812133 (816.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 159543.2 (44h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1954347
telemt_connections_bad_total 18480
telemt_handshake_timeouts_total 180947
telemt_upstream_connect_attempt_total 49480
telemt_upstream_connect_success_total 47138
telemt_upstream_connect_fail_total 2205
telemt_upstream_connect_attempts_per_request{bucket="1"} 49206
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2204
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11972
telemt_me_reconnect_attempts_total 42314
telemt_me_reconnect_success_total 33330
telemt_me_reader_eof_total 35792
telemt_me_idle_close_by_peer_total 35785
telemt_me_route_drop_no_conn_total 694701
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1612257
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3199
telemt_desync_full_logged_total 1038
telemt_desync_suppressed_total 2161
telemt_desync_frames_bucket_total{bucket="1_2"} 884
telemt_desync_frames_bucket_total{bucket="3_10"} 1312
telemt_desync_frames_bucket_total{bucket="gt_10"} 1003
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 33878
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33306
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 548
telemt_user_connections_total{user="hello"} 1616952
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 24934546257 (23.22 GB)
telemt_user_octets_to_client{user="hello"} 610298594690 (568.38 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28978.9 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474273
telemt_connections_bad_total 4646
telemt_handshake_timeouts_total 4918
telemt_upstream_connect_attempt_total 6577
telemt_upstream_connect_success_total 6362
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 6577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 872
telemt_me_reconnect_attempts_total 20009
telemt_me_reconnect_success_total 4873
telemt_me_reader_eof_total 5442
telemt_me_idle_close_by_peer_total 5442
telemt_me_route_drop_no_conn_total 181425
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443623
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1323
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 900
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5386
telemt_me_refill_failed_total 471
telemt_me_writer_restored_same_endpoint_total 4869
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 443599
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 4983288124 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 138644517004 (129.12 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 117
```