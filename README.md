# Server Metrics 2026-03-12 18:14:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 44147.6 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1586898
telemt_connections_bad_total 20489
telemt_handshake_timeouts_total 14817
telemt_upstream_connect_attempt_total 8807
telemt_upstream_connect_success_total 8756
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 533
telemt_me_reconnect_attempts_total 15357
telemt_me_reconnect_success_total 6511
telemt_me_reader_eof_total 7043
telemt_me_idle_close_by_peer_total 7042
telemt_me_route_drop_no_conn_total 619367
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1486255
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7624
telemt_desync_full_logged_total 1933
telemt_desync_suppressed_total 5691
telemt_desync_frames_bucket_total{bucket="1_2"} 1976
telemt_desync_frames_bucket_total{bucket="3_10"} 2773
telemt_desync_frames_bucket_total{bucket="gt_10"} 2875
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6880
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6498
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 369
telemt_user_connections_total{user="hello"} 1485746
telemt_user_connections_current{user="hello"} 1494
telemt_user_octets_from_client{user="hello"} 22533060960 (20.99 GB)
telemt_user_octets_to_client{user="hello"} 489966628428 (456.32 GB)
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 73768.0 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684845
telemt_connections_bad_total 8936
telemt_handshake_timeouts_total 29277
telemt_upstream_connect_attempt_total 18947
telemt_upstream_connect_success_total 18918
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 18947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3344
telemt_me_reconnect_attempts_total 13667
telemt_me_reconnect_success_total 13582
telemt_me_reader_eof_total 14427
telemt_me_idle_close_by_peer_total 14427
telemt_me_route_drop_no_conn_total 218026
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 615964
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2676
telemt_desync_full_logged_total 820
telemt_desync_suppressed_total 1856
telemt_desync_frames_bucket_total{bucket="1_2"} 1089
telemt_desync_frames_bucket_total{bucket="3_10"} 874
telemt_desync_frames_bucket_total{bucket="gt_10"} 713
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13724
telemt_me_writer_restored_same_endpoint_total 13573
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 617844
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 9356647868 (8.71 GB)
telemt_user_octets_to_client{user="hello"} 232298825647 (216.35 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 73767.9 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1421676
telemt_connections_bad_total 6902
telemt_handshake_timeouts_total 99462
telemt_upstream_connect_attempt_total 17495
telemt_upstream_connect_success_total 17490
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1144
telemt_me_reconnect_attempts_total 14686
telemt_me_reconnect_success_total 13444
telemt_me_reader_eof_total 14172
telemt_me_idle_close_by_peer_total 14171
telemt_me_route_drop_no_conn_total 465686
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1083370
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4572
telemt_desync_full_logged_total 1415
telemt_desync_suppressed_total 3157
telemt_desync_frames_bucket_total{bucket="1_2"} 707
telemt_desync_frames_bucket_total{bucket="3_10"} 1661
telemt_desync_frames_bucket_total{bucket="gt_10"} 2204
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13559
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13403
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 1083236
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 16298555388 (15.18 GB)
telemt_user_octets_to_client{user="hello"} 391665534841 (364.77 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 73768.5 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 862623
telemt_connections_bad_total 11326
telemt_handshake_timeouts_total 64746
telemt_upstream_connect_attempt_total 19179
telemt_upstream_connect_success_total 19104
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 19179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1615
telemt_me_reconnect_attempts_total 23142
telemt_me_reconnect_success_total 15422
telemt_me_reader_eof_total 16464
telemt_me_idle_close_by_peer_total 16464
telemt_me_route_drop_no_conn_total 302177
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 746756
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1722
telemt_desync_full_logged_total 574
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 571
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15785
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15401
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 746170
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 9117199320 (8.49 GB)
telemt_user_octets_to_client{user="hello"} 301440526668 (280.74 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 73768.3 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 968766
telemt_connections_bad_total 11403
telemt_handshake_timeouts_total 7947
telemt_upstream_connect_attempt_total 23331
telemt_upstream_connect_success_total 23055
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 23331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_keepalive_timeout_total 1332
telemt_me_reconnect_attempts_total 30386
telemt_me_reconnect_success_total 19354
telemt_me_reader_eof_total 20338
telemt_me_idle_close_by_peer_total 20338
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 359589
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 889610
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3444
telemt_desync_full_logged_total 1191
telemt_desync_suppressed_total 2253
telemt_desync_frames_bucket_total{bucket="1_2"} 963
telemt_desync_frames_bucket_total{bucket="3_10"} 1161
telemt_desync_frames_bucket_total{bucket="gt_10"} 1320
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 19915
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19310
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 889488
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 10947955944 (10.20 GB)
telemt_user_octets_to_client{user="hello"} 286299848932 (266.64 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 95
```