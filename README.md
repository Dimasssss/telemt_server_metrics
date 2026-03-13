# Server Metrics 2026-03-13 09:53:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 100480.0 (27h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2884648
telemt_connections_bad_total 36439
telemt_handshake_timeouts_total 47674
telemt_upstream_connect_attempt_total 19832
telemt_upstream_connect_success_total 19723
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 19832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 24797
telemt_me_reconnect_success_total 14730
telemt_me_reader_eof_total 15862
telemt_me_idle_close_by_peer_total 15861
telemt_me_route_drop_no_conn_total 1067681
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2632478
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11500
telemt_desync_full_logged_total 2973
telemt_desync_suppressed_total 8527
telemt_desync_frames_bucket_total{bucket="1_2"} 2951
telemt_desync_frames_bucket_total{bucket="3_10"} 4302
telemt_desync_frames_bucket_total{bucket="gt_10"} 4247
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15249
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14717
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 2632304
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 36501062912 (33.99 GB)
telemt_user_octets_to_client{user="hello"} 856885940084 (798.04 GB)
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 130100.1 (36h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1171020
telemt_connections_bad_total 14670
telemt_handshake_timeouts_total 106824
telemt_upstream_connect_attempt_total 32233
telemt_upstream_connect_success_total 32202
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3734
telemt_me_reconnect_attempts_total 24226
telemt_me_reconnect_success_total 24100
telemt_me_reader_eof_total 25688
telemt_me_idle_close_by_peer_total 25688
telemt_me_route_drop_no_conn_total 360982
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007645
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4436
telemt_desync_full_logged_total 1343
telemt_desync_suppressed_total 3093
telemt_desync_frames_bucket_total{bucket="1_2"} 1607
telemt_desync_frames_bucket_total{bucket="3_10"} 1465
telemt_desync_frames_bucket_total{bucket="gt_10"} 1364
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 24336
telemt_me_writer_restored_same_endpoint_total 24091
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 1009580
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 15387196040 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 368610024087 (343.29 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 130100.2 (36h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2250022
telemt_connections_bad_total 24685
telemt_handshake_timeouts_total 152634
telemt_upstream_connect_attempt_total 29802
telemt_upstream_connect_success_total 29792
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14059
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1851
telemt_me_reconnect_attempts_total 24256
telemt_me_reconnect_success_total 22968
telemt_me_reader_eof_total 24332
telemt_me_idle_close_by_peer_total 24331
telemt_me_route_drop_no_conn_total 734798
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1801602
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5948
telemt_desync_full_logged_total 1896
telemt_desync_suppressed_total 4052
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 2176
telemt_desync_frames_bucket_total{bucket="gt_10"} 2804
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 23198
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22927
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 1801055
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 31348506500 (29.20 GB)
telemt_user_octets_to_client{user="hello"} 648626592009 (604.08 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 130100.7 (36h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1425494
telemt_connections_bad_total 14235
telemt_handshake_timeouts_total 88824
telemt_upstream_connect_attempt_total 42743
telemt_upstream_connect_success_total 40436
telemt_upstream_connect_fail_total 2170
telemt_upstream_connect_attempts_per_request{bucket="1"} 42469
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2169
telemt_me_keepalive_timeout_total 11473
telemt_me_reconnect_attempts_total 37053
telemt_me_reconnect_success_total 28108
telemt_me_reader_eof_total 30265
telemt_me_idle_close_by_peer_total 30258
telemt_me_route_drop_no_conn_total 502393
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1189596
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2230
telemt_desync_full_logged_total 736
telemt_desync_suppressed_total 1494
telemt_desync_frames_bucket_total{bucket="1_2"} 616
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 759
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 28590
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28084
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 1194363
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 18143613425 (16.90 GB)
telemt_user_octets_to_client{user="hello"} 475318581298 (442.67 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 130100.5 (36h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1591524
telemt_connections_bad_total 36068
telemt_handshake_timeouts_total 12905
telemt_upstream_connect_attempt_total 41717
telemt_upstream_connect_success_total 41222
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 41717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20260
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_timeout_total 2249
telemt_me_reconnect_attempts_total 52722
telemt_me_reconnect_success_total 34746
telemt_me_reader_eof_total 36501
telemt_me_idle_close_by_peer_total 36501
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 582988
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1450213
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 5039
telemt_desync_full_logged_total 1799
telemt_desync_suppressed_total 3240
telemt_desync_frames_bucket_total{bucket="1_2"} 1540
telemt_desync_frames_bucket_total{bucket="3_10"} 1628
telemt_desync_frames_bucket_total{bucket="gt_10"} 1871
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 35685
telemt_me_refill_failed_total 557
telemt_me_writer_restored_same_endpoint_total 34685
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 939
telemt_user_connections_total{user="hello"} 1450013
telemt_user_connections_current{user="hello"} 927
telemt_user_octets_from_client{user="hello"} 18554154240 (17.28 GB)
telemt_user_octets_to_client{user="hello"} 502077853428 (467.60 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 98
```