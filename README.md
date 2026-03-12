# Server Metrics 2026-03-12 16:22:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 37403.4 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1351099
telemt_connections_bad_total 20241
telemt_handshake_timeouts_total 12980
telemt_upstream_connect_attempt_total 7514
telemt_upstream_connect_success_total 7474
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 458
telemt_me_reconnect_attempts_total 9479
telemt_me_reconnect_success_total 5566
telemt_me_reader_eof_total 5921
telemt_me_idle_close_by_peer_total 5920
telemt_me_route_drop_no_conn_total 485990
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1266272
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6557
telemt_desync_full_logged_total 1640
telemt_desync_suppressed_total 4917
telemt_desync_frames_bucket_total{bucket="1_2"} 1687
telemt_desync_frames_bucket_total{bucket="3_10"} 2370
telemt_desync_frames_bucket_total{bucket="gt_10"} 2500
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5761
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5553
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 1265948
telemt_user_connections_current{user="hello"} 1529
telemt_user_octets_from_client{user="hello"} 19489653524 (18.15 GB)
telemt_user_octets_to_client{user="hello"} 366488452944 (341.32 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 67024.0 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597163
telemt_connections_bad_total 7873
telemt_handshake_timeouts_total 28039
telemt_upstream_connect_attempt_total 16008
telemt_upstream_connect_success_total 16001
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1258
telemt_me_reconnect_attempts_total 12537
telemt_me_reconnect_success_total 12466
telemt_me_reader_eof_total 13254
telemt_me_idle_close_by_peer_total 13254
telemt_me_route_drop_no_conn_total 179051
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534604
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2107
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 932
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 506
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12591
telemt_me_writer_restored_same_endpoint_total 12457
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 535100
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 8254651091 (7.69 GB)
telemt_user_octets_to_client{user="hello"} 188804397910 (175.84 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 67023.8 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1259181
telemt_connections_bad_total 6364
telemt_handshake_timeouts_total 89828
telemt_upstream_connect_attempt_total 16100
telemt_upstream_connect_success_total 16095
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1062
telemt_me_reconnect_attempts_total 13608
telemt_me_reconnect_success_total 12377
telemt_me_reader_eof_total 13054
telemt_me_idle_close_by_peer_total 13053
telemt_me_route_drop_no_conn_total 346378
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 936698
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3999
telemt_desync_full_logged_total 1224
telemt_desync_suppressed_total 2775
telemt_desync_frames_bucket_total{bucket="1_2"} 620
telemt_desync_frames_bucket_total{bucket="3_10"} 1441
telemt_desync_frames_bucket_total{bucket="gt_10"} 1938
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 12467
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12336
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 936859
telemt_user_connections_current{user="hello"} 1012
telemt_user_octets_from_client{user="hello"} 12204876064 (11.37 GB)
telemt_user_octets_to_client{user="hello"} 294347814841 (274.13 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 67024.4 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752543
telemt_connections_bad_total 7727
telemt_handshake_timeouts_total 59897
telemt_upstream_connect_attempt_total 17637
telemt_upstream_connect_success_total 17567
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 17637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1484
telemt_me_reconnect_attempts_total 19453
telemt_me_reconnect_success_total 14208
telemt_me_reader_eof_total 15143
telemt_me_idle_close_by_peer_total 15143
telemt_me_route_drop_no_conn_total 257306
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 649544
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1278
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 846
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 427
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 14478
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14187
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 648996
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 8079701800 (7.52 GB)
telemt_user_octets_to_client{user="hello"} 252669312532 (235.32 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 67024.2 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850729
telemt_connections_bad_total 10264
telemt_handshake_timeouts_total 7002
telemt_upstream_connect_attempt_total 21086
telemt_upstream_connect_success_total 20828
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 21086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_keepalive_timeout_total 1203
telemt_me_reconnect_attempts_total 24706
telemt_me_reconnect_success_total 17463
telemt_me_reader_eof_total 18280
telemt_me_idle_close_by_peer_total 18280
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 299936
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 782079
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3065
telemt_desync_full_logged_total 1036
telemt_desync_suppressed_total 2029
telemt_desync_frames_bucket_total{bucket="1_2"} 851
telemt_desync_frames_bucket_total{bucket="3_10"} 1044
telemt_desync_frames_bucket_total{bucket="gt_10"} 1170
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 17873
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17423
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 781974
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 9576704360 (8.92 GB)
telemt_user_octets_to_client{user="hello"} 219676209180 (204.59 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 114
```