# Server Metrics 2026-03-10 20:01:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20061.0 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 610315
telemt_connections_bad_total 8000
telemt_handshake_timeouts_total 5650
telemt_upstream_connect_attempt_total 4079
telemt_upstream_connect_success_total 4070
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 328
telemt_me_reconnect_attempts_total 13445
telemt_me_reconnect_success_total 2980
telemt_me_reader_eof_total 3328
telemt_me_idle_close_by_peer_total 3328
telemt_me_route_drop_no_conn_total 255776
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576080
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3049
telemt_desync_full_logged_total 820
telemt_desync_suppressed_total 2229
telemt_desync_frames_bucket_total{bucket="1_2"} 835
telemt_desync_frames_bucket_total{bucket="3_10"} 1161
telemt_desync_frames_bucket_total{bucket="gt_10"} 1053
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3324
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2974
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 575902
telemt_user_connections_current{user="hello"} 976
telemt_user_octets_from_client{user="hello"} 8321051936 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 167756160592 (156.24 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 20117.7 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261295
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 16673
telemt_upstream_connect_attempt_total 9565
telemt_upstream_connect_success_total 6818
telemt_upstream_connect_fail_total 2747
telemt_upstream_connect_attempts_per_request{bucket="1"} 9565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1887
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2747
telemt_me_keepalive_timeout_total 718
telemt_me_reconnect_attempts_total 4555
telemt_me_reconnect_success_total 3765
telemt_me_reader_eof_total 3936
telemt_me_idle_close_by_peer_total 3934
telemt_me_route_drop_no_conn_total 142326
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224018
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1163
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 845
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 401
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3834
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3744
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 225318
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 2380517906 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 55413200302 (51.61 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 20117.6 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436699
telemt_connections_bad_total 1428
telemt_handshake_timeouts_total 32405
telemt_upstream_connect_attempt_total 6183
telemt_upstream_connect_success_total 6089
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 6183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 155
telemt_me_reconnect_attempts_total 9589
telemt_me_reconnect_success_total 3959
telemt_me_reader_eof_total 4256
telemt_me_idle_close_by_peer_total 4256
telemt_me_route_drop_no_conn_total 150416
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377386
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1229
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 886
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 423
telemt_desync_frames_bucket_total{bucket="gt_10"} 519
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4208
telemt_me_refill_failed_total 174
telemt_me_writer_restored_same_endpoint_total 3948
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 378332
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 5464772845 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 118055758237 (109.95 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 20118.0 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292463
telemt_connections_bad_total 19858
telemt_handshake_timeouts_total 25580
telemt_upstream_connect_attempt_total 5484
telemt_upstream_connect_success_total 5484
telemt_upstream_connect_attempts_per_request{bucket="1"} 5484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 5437
telemt_me_reconnect_success_total 4420
telemt_me_reader_eof_total 4621
telemt_me_idle_close_by_peer_total 4621
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 95477
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235447
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 639
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4493
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4407
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 235149
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 3643308192 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 72439985244 (67.46 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 20117.6 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307567
telemt_connections_bad_total 882
telemt_handshake_timeouts_total 2002
telemt_upstream_connect_attempt_total 6394
telemt_upstream_connect_success_total 6368
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 6343
telemt_me_reconnect_success_total 5280
telemt_me_reader_eof_total 5457
telemt_me_idle_close_by_peer_total 5457
telemt_me_route_drop_no_conn_total 113037
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289987
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1626
telemt_desync_full_logged_total 606
telemt_desync_suppressed_total 1020
telemt_desync_frames_bucket_total{bucket="1_2"} 633
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5394
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5280
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 289904
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 5639516292 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 96466468896 (89.84 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 66
```