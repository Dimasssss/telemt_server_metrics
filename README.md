# Server Metrics 2026-03-13 15:31:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 120743.9 (33h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3756720
telemt_connections_bad_total 37425
telemt_handshake_timeouts_total 76579
telemt_upstream_connect_attempt_total 23529
telemt_upstream_connect_success_total 23394
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2194
telemt_me_reconnect_attempts_total 27465
telemt_me_reconnect_success_total 17377
telemt_me_reader_eof_total 18676
telemt_me_idle_close_by_peer_total 18675
telemt_me_route_drop_no_conn_total 1395177
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3442974
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13935
telemt_desync_full_logged_total 3677
telemt_desync_suppressed_total 10258
telemt_desync_frames_bucket_total{bucket="1_2"} 3500
telemt_desync_frames_bucket_total{bucket="3_10"} 5280
telemt_desync_frames_bucket_total{bucket="gt_10"} 5155
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 17931
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17364
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3442769
telemt_user_connections_current{user="hello"} 1817
telemt_user_octets_from_client{user="hello"} 47061639484 (43.83 GB)
telemt_user_octets_to_client{user="hello"} 1081505984180 (1007.23 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 273
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 20407.8 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292466
telemt_connections_bad_total 15146
telemt_handshake_timeouts_total 7876
telemt_upstream_connect_attempt_total 4831
telemt_upstream_connect_success_total 4745
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 4831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 5975
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 3913
telemt_me_idle_close_by_peer_total 3913
telemt_me_route_drop_no_conn_total 106160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261933
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 995
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 741
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 482
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3801
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3677
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 261957
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 2642068308 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 75270454560 (70.10 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 150364.5 (41h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2784088
telemt_connections_bad_total 27657
telemt_handshake_timeouts_total 185504
telemt_upstream_connect_attempt_total 33760
telemt_upstream_connect_success_total 33749
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3270
telemt_me_reconnect_attempts_total 28477
telemt_me_reconnect_success_total 25928
telemt_me_reader_eof_total 27497
telemt_me_idle_close_by_peer_total 27496
telemt_me_route_drop_no_conn_total 939944
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2285605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8139
telemt_desync_full_logged_total 2696
telemt_desync_suppressed_total 5443
telemt_desync_frames_bucket_total{bucket="1_2"} 1291
telemt_desync_frames_bucket_total{bucket="3_10"} 2961
telemt_desync_frames_bucket_total{bucket="gt_10"} 3887
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 26232
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25887
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 2285003
telemt_user_connections_current{user="hello"} 1053
telemt_user_octets_from_client{user="hello"} 37866470256 (35.27 GB)
telemt_user_octets_to_client{user="hello"} 800839708145 (745.84 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 150364.9 (41h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1772387
telemt_connections_bad_total 18134
telemt_handshake_timeouts_total 135950
telemt_upstream_connect_attempt_total 47459
telemt_upstream_connect_success_total 45128
telemt_upstream_connect_fail_total 2193
telemt_upstream_connect_attempts_per_request{bucket="1"} 47184
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2192
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11879
telemt_me_reconnect_attempts_total 40766
telemt_me_reconnect_success_total 31793
telemt_me_reader_eof_total 34144
telemt_me_idle_close_by_peer_total 34137
telemt_me_route_drop_no_conn_total 635152
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1479086
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2975
telemt_desync_full_logged_total 963
telemt_desync_suppressed_total 2012
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1229
telemt_desync_frames_bucket_total{bucket="gt_10"} 948
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 32317
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31769
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 1483796
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 23140738925 (21.55 GB)
telemt_user_octets_to_client{user="hello"} 570438718498 (531.26 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 19800.3 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317232
telemt_connections_bad_total 3998
telemt_handshake_timeouts_total 2939
telemt_upstream_connect_attempt_total 4195
telemt_upstream_connect_success_total 4067
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 4195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 13638
telemt_me_reconnect_success_total 3064
telemt_me_reader_eof_total 3443
telemt_me_idle_close_by_peer_total 3443
telemt_me_route_drop_no_conn_total 126009
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297318
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 917
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 623
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3411
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3060
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 297296
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 3437961176 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 93627517708 (87.20 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 119
```