# Server Metrics 2026-03-13 10:22:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 102250.7 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2959506
telemt_connections_bad_total 36442
telemt_handshake_timeouts_total 53841
telemt_upstream_connect_attempt_total 20139
telemt_upstream_connect_success_total 20030
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1429
telemt_me_reconnect_attempts_total 25016
telemt_me_reconnect_success_total 14947
telemt_me_reader_eof_total 16098
telemt_me_idle_close_by_peer_total 16097
telemt_me_route_drop_no_conn_total 1092187
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2698661
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11812
telemt_desync_full_logged_total 3046
telemt_desync_suppressed_total 8766
telemt_desync_frames_bucket_total{bucket="1_2"} 3021
telemt_desync_frames_bucket_total{bucket="3_10"} 4437
telemt_desync_frames_bucket_total{bucket="gt_10"} 4354
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 15469
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14934
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 2698601
telemt_user_connections_current{user="hello"} 1664
telemt_user_octets_from_client{user="hello"} 37124857716 (34.58 GB)
telemt_user_octets_to_client{user="hello"} 876402684316 (816.21 GB)
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 1914.4 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15249
telemt_connections_bad_total 1525
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 470
telemt_upstream_connect_success_total 402
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 310
telemt_me_reconnect_success_total 243
telemt_me_reader_eof_total 225
telemt_me_idle_close_by_peer_total 225
telemt_me_route_drop_no_conn_total 4971
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13096
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 238
telemt_me_writer_restored_same_endpoint_total 236
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 13098
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 193508084 (184.54 MB)
telemt_user_octets_to_client{user="hello"} 2416262940 (2.25 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 131871.1 (36h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2295223
telemt_connections_bad_total 25080
telemt_handshake_timeouts_total 156537
telemt_upstream_connect_attempt_total 30131
telemt_upstream_connect_success_total 30121
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1878
telemt_me_reconnect_attempts_total 24496
telemt_me_reconnect_success_total 23206
telemt_me_reader_eof_total 24586
telemt_me_idle_close_by_peer_total 24585
telemt_me_route_drop_no_conn_total 751446
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1840922
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6039
telemt_desync_full_logged_total 1931
telemt_desync_suppressed_total 4108
telemt_desync_frames_bucket_total{bucket="1_2"} 985
telemt_desync_frames_bucket_total{bucket="3_10"} 2201
telemt_desync_frames_bucket_total{bucket="gt_10"} 2853
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 23440
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23165
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 1840367
telemt_user_connections_current{user="hello"} 1116
telemt_user_octets_from_client{user="hello"} 31794239604 (29.61 GB)
telemt_user_octets_to_client{user="hello"} 662388238601 (616.90 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 131871.5 (36h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1450347
telemt_connections_bad_total 14238
telemt_handshake_timeouts_total 90110
telemt_upstream_connect_attempt_total 43121
telemt_upstream_connect_success_total 40811
telemt_upstream_connect_fail_total 2173
telemt_upstream_connect_attempts_per_request{bucket="1"} 42847
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2172
telemt_me_keepalive_timeout_total 11506
telemt_me_reconnect_attempts_total 37342
telemt_me_reconnect_success_total 28391
telemt_me_reader_eof_total 30566
telemt_me_idle_close_by_peer_total 30559
telemt_me_route_drop_no_conn_total 512728
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1212878
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2285
telemt_desync_full_logged_total 755
telemt_desync_suppressed_total 1530
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 873
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 28877
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28367
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 1217625
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 18444042789 (17.18 GB)
telemt_user_octets_to_client{user="hello"} 484151202362 (450.90 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1307.0 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8637
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 380
telemt_upstream_connect_success_total 375
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 264
telemt_me_reconnect_success_total 258
telemt_me_reader_eof_total 219
telemt_me_idle_close_by_peer_total 219
telemt_me_route_drop_no_conn_total 2211
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8012
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 240
telemt_me_writer_restored_same_endpoint_total 255
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 12
telemt_user_connections_total{user="hello"} 8012
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 118836696 (113.33 MB)
telemt_user_octets_to_client{user="hello"} 4199058752 (3.91 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 72
```