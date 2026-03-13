# Server Metrics 2026-03-13 10:31:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 102761.7 (28h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2980274
telemt_connections_bad_total 36446
telemt_handshake_timeouts_total 53996
telemt_upstream_connect_attempt_total 20238
telemt_upstream_connect_success_total 20127
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1446
telemt_me_reconnect_attempts_total 25067
telemt_me_reconnect_success_total 14997
telemt_me_reader_eof_total 16149
telemt_me_idle_close_by_peer_total 16148
telemt_me_route_drop_no_conn_total 1099699
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2718603
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11875
telemt_desync_full_logged_total 3058
telemt_desync_suppressed_total 8817
telemt_desync_frames_bucket_total{bucket="1_2"} 3036
telemt_desync_frames_bucket_total{bucket="3_10"} 4462
telemt_desync_frames_bucket_total{bucket="gt_10"} 4377
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 15520
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14984
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 2718542
telemt_user_connections_current{user="hello"} 1667
telemt_user_octets_from_client{user="hello"} 37389823236 (34.82 GB)
telemt_user_octets_to_client{user="hello"} 881393739816 (820.86 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2425.5 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22549
telemt_connections_bad_total 2024
telemt_handshake_timeouts_total 377
telemt_upstream_connect_attempt_total 575
telemt_upstream_connect_success_total 507
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 415
telemt_me_reconnect_success_total 349
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 7574
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19642
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 343
telemt_me_writer_restored_same_endpoint_total 342
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 19643
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 280426160 (267.44 MB)
telemt_user_octets_to_client{user="hello"} 3823821756 (3.56 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 132382.3 (36h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2308115
telemt_connections_bad_total 25093
telemt_handshake_timeouts_total 157099
telemt_upstream_connect_attempt_total 30204
telemt_upstream_connect_success_total 30194
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1882
telemt_me_reconnect_attempts_total 24538
telemt_me_reconnect_success_total 23248
telemt_me_reader_eof_total 24628
telemt_me_idle_close_by_peer_total 24627
telemt_me_route_drop_no_conn_total 756344
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1853103
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6087
telemt_desync_full_logged_total 1946
telemt_desync_suppressed_total 4141
telemt_desync_frames_bucket_total{bucket="1_2"} 989
telemt_desync_frames_bucket_total{bucket="3_10"} 2218
telemt_desync_frames_bucket_total{bucket="gt_10"} 2880
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 23482
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23207
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 1852543
telemt_user_connections_current{user="hello"} 1132
telemt_user_octets_from_client{user="hello"} 31920410656 (29.73 GB)
telemt_user_octets_to_client{user="hello"} 667574742765 (621.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 132382.7 (36h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1457805
telemt_connections_bad_total 14238
telemt_handshake_timeouts_total 90612
telemt_upstream_connect_attempt_total 43211
telemt_upstream_connect_success_total 40901
telemt_upstream_connect_fail_total 2173
telemt_upstream_connect_attempts_per_request{bucket="1"} 42937
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2172
telemt_me_keepalive_timeout_total 11507
telemt_me_reconnect_attempts_total 37401
telemt_me_reconnect_success_total 28450
telemt_me_reader_eof_total 30625
telemt_me_idle_close_by_peer_total 30618
telemt_me_route_drop_no_conn_total 516361
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1219745
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2297
telemt_desync_full_logged_total 761
telemt_desync_suppressed_total 1536
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 783
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 28936
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28426
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 1224481
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 18528072693 (17.26 GB)
telemt_user_octets_to_client{user="hello"} 486008971346 (452.63 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1818.3 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15795
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 468
telemt_upstream_connect_success_total 463
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 352
telemt_me_reconnect_success_total 346
telemt_me_reader_eof_total 307
telemt_me_idle_close_by_peer_total 307
telemt_me_route_drop_no_conn_total 4569
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14942
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 328
telemt_me_writer_restored_same_endpoint_total 343
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 12
telemt_user_connections_total{user="hello"} 14939
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 184328120 (175.79 MB)
telemt_user_octets_to_client{user="hello"} 7111859696 (6.62 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 105
```