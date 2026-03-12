# Server Metrics 2026-03-12 10:40:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16890.4 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558328
telemt_connections_bad_total 1468
telemt_handshake_timeouts_total 3216
telemt_upstream_connect_attempt_total 3270
telemt_upstream_connect_success_total 3249
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 6265
telemt_me_reconnect_success_total 2378
telemt_me_reader_eof_total 2581
telemt_me_idle_close_by_peer_total 2581
telemt_me_route_drop_no_conn_total 192389
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2596
telemt_desync_full_logged_total 651
telemt_desync_suppressed_total 1945
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 980
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2523
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2365
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 538344
telemt_user_connections_current{user="hello"} 1554
telemt_user_octets_from_client{user="hello"} 8771962308 (8.17 GB)
telemt_user_octets_to_client{user="hello"} 146584706340 (136.52 GB)
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46510.9 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307331
telemt_connections_bad_total 3436
telemt_handshake_timeouts_total 8939
telemt_upstream_connect_attempt_total 11689
telemt_upstream_connect_success_total 11683
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5939
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 676
telemt_me_reconnect_attempts_total 9226
telemt_me_reconnect_success_total 9175
telemt_me_reader_eof_total 9752
telemt_me_idle_close_by_peer_total 9752
telemt_me_route_drop_no_conn_total 89057
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275696
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 560
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 338
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9253
telemt_me_writer_restored_same_endpoint_total 9166
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 276129
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 3828779679 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 100466295266 (93.57 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 46510.7 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766093
telemt_connections_bad_total 3720
telemt_handshake_timeouts_total 56025
telemt_upstream_connect_attempt_total 11664
telemt_upstream_connect_success_total 11659
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 589
telemt_me_reconnect_attempts_total 9063
telemt_me_reconnect_success_total 8986
telemt_me_reader_eof_total 9446
telemt_me_idle_close_by_peer_total 9446
telemt_me_route_drop_no_conn_total 173168
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492674
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2231
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1574
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 767
telemt_desync_frames_bucket_total{bucket="gt_10"} 1172
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9001
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8945
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 492928
telemt_user_connections_current{user="hello"} 944
telemt_user_octets_from_client{user="hello"} 5878578804 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 158267686333 (147.40 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 46511.3 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395954
telemt_connections_bad_total 2478
telemt_handshake_timeouts_total 30283
telemt_upstream_connect_attempt_total 12515
telemt_upstream_connect_success_total 12465
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 12515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 844
telemt_me_reconnect_attempts_total 10181
telemt_me_reconnect_success_total 10142
telemt_me_reader_eof_total 10762
telemt_me_idle_close_by_peer_total 10762
telemt_me_route_drop_no_conn_total 133330
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334390
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 696
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 451
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 296
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10211
telemt_me_writer_restored_same_endpoint_total 10121
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 334210
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 3981722612 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 129248772764 (120.37 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46511.1 (12h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 447247
telemt_connections_bad_total 473
telemt_handshake_timeouts_total 3328
telemt_upstream_connect_attempt_total 14988
telemt_upstream_connect_success_total 14809
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 14988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 633
telemt_me_reconnect_attempts_total 14002
telemt_me_reconnect_success_total 12478
telemt_me_reader_eof_total 12994
telemt_me_idle_close_by_peer_total 12994
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 144866
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421037
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1778
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1189
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 640
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 12649
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12454
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 420962
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 4691898636 (4.37 GB)
telemt_user_octets_to_client{user="hello"} 101853523008 (94.86 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 112
```