# Server Metrics 2026-03-11 06:57:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 59404.4 (16h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1180102
telemt_connections_bad_total 13238
telemt_handshake_timeouts_total 38774
telemt_upstream_connect_attempt_total 12459
telemt_upstream_connect_success_total 12450
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6125
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 705
telemt_me_reconnect_attempts_total 21139
telemt_me_reconnect_success_total 9456
telemt_me_reader_eof_total 10276
telemt_me_idle_close_by_peer_total 10276
telemt_me_route_drop_no_conn_total 433489
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1063201
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5118
telemt_desync_full_logged_total 1430
telemt_desync_suppressed_total 3688
telemt_desync_frames_bucket_total{bucket="1_2"} 1373
telemt_desync_frames_bucket_total{bucket="3_10"} 1911
telemt_desync_frames_bucket_total{bucket="gt_10"} 1834
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9913
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9450
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 1062863
telemt_user_connections_current{user="hello"} 1158
telemt_user_octets_from_client{user="hello"} 14116867260 (13.15 GB)
telemt_user_octets_to_client{user="hello"} 311992408592 (290.57 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59461.1 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455594
telemt_connections_bad_total 5651
telemt_handshake_timeouts_total 22149
telemt_upstream_connect_attempt_total 21230
telemt_upstream_connect_success_total 18317
telemt_upstream_connect_fail_total 2913
telemt_upstream_connect_attempts_per_request{bucket="1"} 21230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2913
telemt_me_keepalive_timeout_total 2030
telemt_me_reconnect_attempts_total 13213
telemt_me_reconnect_success_total 12388
telemt_me_reader_eof_total 13094
telemt_me_idle_close_by_peer_total 13092
telemt_me_route_drop_no_conn_total 204474
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389681
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1977
telemt_desync_full_logged_total 603
telemt_desync_suppressed_total 1374
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12532
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12366
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 391950
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 3894938974 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 99722706380 (92.87 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 59461.0 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774251
telemt_connections_bad_total 6730
telemt_handshake_timeouts_total 41933
telemt_upstream_connect_attempt_total 15934
telemt_upstream_connect_success_total 15731
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 709
telemt_me_reconnect_attempts_total 22749
telemt_me_reconnect_success_total 11676
telemt_me_reader_eof_total 12573
telemt_me_idle_close_by_peer_total 12573
telemt_me_route_drop_no_conn_total 261429
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692461
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1963
telemt_desync_full_logged_total 569
telemt_desync_suppressed_total 1394
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 795
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12171
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11665
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 693293
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 8139188809 (7.58 GB)
telemt_user_octets_to_client{user="hello"} 204194340089 (190.17 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 59461.4 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 591133
telemt_connections_bad_total 55732
telemt_handshake_timeouts_total 59616
telemt_upstream_connect_attempt_total 16845
telemt_upstream_connect_success_total 16845
telemt_upstream_connect_attempts_per_request{bucket="1"} 16845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 653
telemt_me_reconnect_attempts_total 14916
telemt_me_reconnect_success_total 13868
telemt_me_reader_eof_total 14720
telemt_me_idle_close_by_peer_total 14720
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 178545
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456775
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 976
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 14029
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13846
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 456293
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 5475878756 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 125043923436 (116.46 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59461.2 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614727
telemt_connections_bad_total 5966
telemt_handshake_timeouts_total 4453
telemt_upstream_connect_attempt_total 16746
telemt_upstream_connect_success_total 16676
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 16746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 679
telemt_me_reconnect_attempts_total 17367
telemt_me_reconnect_success_total 13581
telemt_me_reader_eof_total 14349
telemt_me_idle_close_by_peer_total 14349
telemt_me_route_drop_no_conn_total 203190
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560026
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2625
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 1622
telemt_desync_frames_bucket_total{bucket="1_2"} 935
telemt_desync_frames_bucket_total{bucket="3_10"} 1121
telemt_desync_frames_bucket_total{bucket="gt_10"} 569
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 13874
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13581
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 559754
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 9678588355 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 205048832930 (190.97 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 82
```