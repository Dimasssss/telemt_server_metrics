# Server Metrics 2026-03-13 11:00:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 104504.3 (29h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3050575
telemt_connections_bad_total 36459
telemt_handshake_timeouts_total 54550
telemt_upstream_connect_attempt_total 20594
telemt_upstream_connect_success_total 20483
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1454
telemt_me_reconnect_attempts_total 25345
telemt_me_reconnect_success_total 15272
telemt_me_reader_eof_total 16437
telemt_me_idle_close_by_peer_total 16436
telemt_me_route_drop_no_conn_total 1126478
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2786018
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12076
telemt_desync_full_logged_total 3115
telemt_desync_suppressed_total 8961
telemt_desync_frames_bucket_total{bucket="1_2"} 3084
telemt_desync_frames_bucket_total{bucket="3_10"} 4527
telemt_desync_frames_bucket_total{bucket="gt_10"} 4465
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 15797
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15259
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 2785956
telemt_user_connections_current{user="hello"} 1697
telemt_user_octets_from_client{user="hello"} 38388142256 (35.75 GB)
telemt_user_octets_to_client{user="hello"} 904096446088 (842.01 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 4168.0 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48137
telemt_connections_bad_total 4043
telemt_handshake_timeouts_total 1076
telemt_upstream_connect_attempt_total 1192
telemt_upstream_connect_success_total 1124
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 1192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 936
telemt_me_reconnect_success_total 866
telemt_me_reader_eof_total 856
telemt_me_idle_close_by_peer_total 856
telemt_me_route_drop_no_conn_total 16597
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41860
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 127
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 863
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 41859
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 478742224 (456.56 MB)
telemt_user_octets_to_client{user="hello"} 10392922832 (9.68 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 134124.8 (37h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2351608
telemt_connections_bad_total 25123
telemt_handshake_timeouts_total 158497
telemt_upstream_connect_attempt_total 30509
telemt_upstream_connect_success_total 30499
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1903
telemt_me_reconnect_attempts_total 24784
telemt_me_reconnect_success_total 23493
telemt_me_reader_eof_total 24889
telemt_me_idle_close_by_peer_total 24888
telemt_me_route_drop_no_conn_total 773659
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1894131
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6253
telemt_desync_full_logged_total 1993
telemt_desync_suppressed_total 4260
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 2285
telemt_desync_frames_bucket_total{bucket="gt_10"} 2964
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 23728
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23452
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 1893556
telemt_user_connections_current{user="hello"} 1147
telemt_user_octets_from_client{user="hello"} 32425431984 (30.20 GB)
telemt_user_octets_to_client{user="hello"} 680329500229 (633.61 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 134125.3 (37h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1487115
telemt_connections_bad_total 14999
telemt_handshake_timeouts_total 95112
telemt_upstream_connect_attempt_total 43602
telemt_upstream_connect_success_total 41289
telemt_upstream_connect_fail_total 2176
telemt_upstream_connect_attempts_per_request{bucket="1"} 43328
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2175
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11524
telemt_me_reconnect_attempts_total 37731
telemt_me_reconnect_success_total 28778
telemt_me_reader_eof_total 30965
telemt_me_idle_close_by_peer_total 30958
telemt_me_route_drop_no_conn_total 527510
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1243404
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2316
telemt_desync_full_logged_total 773
telemt_desync_suppressed_total 1543
telemt_desync_frames_bucket_total{bucket="1_2"} 648
telemt_desync_frames_bucket_total{bucket="3_10"} 878
telemt_desync_frames_bucket_total{bucket="gt_10"} 790
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 29268
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28754
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 1248130
telemt_user_connections_current{user="hello"} 705
telemt_user_octets_from_client{user="hello"} 18867310909 (17.57 GB)
telemt_user_octets_to_client{user="hello"} 491993370754 (458.20 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3560.9 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45492
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 251
telemt_upstream_connect_attempt_total 920
telemt_upstream_connect_success_total 895
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 519
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 1911
telemt_me_reconnect_success_total 688
telemt_me_reader_eof_total 697
telemt_me_idle_close_by_peer_total 697
telemt_me_route_drop_no_conn_total 15540
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43567
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 718
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 685
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 43558
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 407898944 (389.00 MB)
telemt_user_octets_to_client{user="hello"} 16855609804 (15.70 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 127
```