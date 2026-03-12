# Server Metrics 2026-03-12 09:44:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13528.0 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432864
telemt_connections_bad_total 1446
telemt_handshake_timeouts_total 2595
telemt_upstream_connect_attempt_total 2633
telemt_upstream_connect_success_total 2618
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 277
telemt_me_reconnect_attempts_total 1935
telemt_me_reconnect_success_total 1923
telemt_me_reader_eof_total 1989
telemt_me_idle_close_by_peer_total 1989
telemt_me_route_drop_no_conn_total 147430
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418932
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1935
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1449
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 738
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1939
telemt_me_writer_restored_same_endpoint_total 1910
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 418807
telemt_user_connections_current{user="hello"} 1227
telemt_user_octets_from_client{user="hello"} 6165678040 (5.74 GB)
telemt_user_octets_to_client{user="hello"} 112440178772 (104.72 GB)
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43148.4 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262378
telemt_connections_bad_total 2975
telemt_handshake_timeouts_total 8206
telemt_upstream_connect_attempt_total 10891
telemt_upstream_connect_success_total 10885
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 659
telemt_me_reconnect_attempts_total 8606
telemt_me_reconnect_success_total 8563
telemt_me_reader_eof_total 9099
telemt_me_idle_close_by_peer_total 9099
telemt_me_route_drop_no_conn_total 75803
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233050
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 496
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8630
telemt_me_writer_restored_same_endpoint_total 8554
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 233483
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 3305270835 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 89349174614 (83.21 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 43148.4 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 693116
telemt_connections_bad_total 3399
telemt_handshake_timeouts_total 51097
telemt_upstream_connect_attempt_total 10936
telemt_upstream_connect_success_total 10931
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 544
telemt_me_reconnect_attempts_total 8508
telemt_me_reconnect_success_total 8436
telemt_me_reader_eof_total 8859
telemt_me_idle_close_by_peer_total 8859
telemt_me_route_drop_no_conn_total 148817
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426476
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1958
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 1370
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 1021
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8440
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8395
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 426736
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 5292298204 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 143016619953 (133.19 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 43148.8 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344394
telemt_connections_bad_total 1829
telemt_handshake_timeouts_total 24965
telemt_upstream_connect_attempt_total 11809
telemt_upstream_connect_success_total 11762
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 11809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 815
telemt_me_reconnect_attempts_total 9652
telemt_me_reconnect_success_total 9616
telemt_me_reader_eof_total 10188
telemt_me_idle_close_by_peer_total 10188
telemt_me_route_drop_no_conn_total 117583
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289769
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 638
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 413
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9678
telemt_me_writer_restored_same_endpoint_total 9595
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 289595
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 3566236736 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 113381712852 (105.59 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43148.5 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387792
telemt_connections_bad_total 403
telemt_handshake_timeouts_total 2956
telemt_upstream_connect_attempt_total 13945
telemt_upstream_connect_success_total 13778
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 13945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6591
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 618
telemt_me_reconnect_attempts_total 13146
telemt_me_reconnect_success_total 11628
telemt_me_reader_eof_total 12110
telemt_me_idle_close_by_peer_total 12110
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 125137
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366435
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1553
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 1051
telemt_desync_frames_bucket_total{bucket="1_2"} 451
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 11779
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11606
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 366368
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 3980614900 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 88241523768 (82.18 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 114
```