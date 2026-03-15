# Server Metrics 2026-03-15 00:59:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 9899.8 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128198
telemt_connections_bad_total 1469
telemt_handshake_timeouts_total 462
telemt_upstream_connect_attempt_total 2068
telemt_upstream_connect_success_total 2059
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1566
telemt_me_reconnect_success_total 1558
telemt_me_reader_eof_total 1629
telemt_me_idle_close_by_peer_total 1629
telemt_me_route_drop_no_conn_total 40167
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111872
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 291
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1580
telemt_me_writer_restored_same_endpoint_total 1547
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 111864
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 1138744936 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 38693366380 (36.04 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 9900.5 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52016
telemt_connections_bad_total 9330
telemt_handshake_timeouts_total 2170
telemt_upstream_connect_attempt_total 3015
telemt_upstream_connect_success_total 2999
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2200
telemt_me_reconnect_success_total 2185
telemt_me_reader_eof_total 2263
telemt_me_idle_close_by_peer_total 2263
telemt_me_route_drop_no_conn_total 10414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38938
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 99
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2155
telemt_me_writer_restored_same_endpoint_total 2177
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 39234
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1406576791 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 10268807888 (9.56 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 9900.8 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82023
telemt_connections_bad_total 1557
telemt_handshake_timeouts_total 5850
telemt_upstream_connect_attempt_total 2223
telemt_upstream_connect_success_total 2213
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1716
telemt_me_reconnect_success_total 1711
telemt_me_reader_eof_total 1789
telemt_me_idle_close_by_peer_total 1789
telemt_me_route_drop_no_conn_total 19287
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73190
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1728
telemt_me_writer_restored_same_endpoint_total 1692
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 73108
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 779288696 (743.19 MB)
telemt_user_octets_to_client{user="hello"} 19301027276 (17.98 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 9900.6 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78287
telemt_connections_bad_total 22666
telemt_handshake_timeouts_total 1220
telemt_upstream_connect_attempt_total 3491
telemt_upstream_connect_success_total 3408
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 3491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4206
telemt_me_reconnect_success_total 2901
telemt_me_reader_eof_total 3017
telemt_me_idle_close_by_peer_total 3017
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 13742
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53073
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 86
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2966
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2886
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 53076
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 305685100 (291.52 MB)
telemt_user_octets_to_client{user="hello"} 10840235500 (10.10 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 9901.2 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44055
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 655
telemt_upstream_connect_attempt_total 2103
telemt_upstream_connect_success_total 2094
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 1592
telemt_me_reader_eof_total 1670
telemt_me_idle_close_by_peer_total 1670
telemt_me_route_drop_no_conn_total 11112
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42307
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 171
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1607
telemt_me_writer_restored_same_endpoint_total 1584
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 42307
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 328317324 (313.11 MB)
telemt_user_octets_to_client{user="hello"} 16681124492 (15.54 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 32
```