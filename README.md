# Server Metrics 2026-03-12 03:36:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 21112.6 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183513
telemt_connections_bad_total 1366
telemt_handshake_timeouts_total 3374
telemt_upstream_connect_attempt_total 4854
telemt_upstream_connect_success_total 4854
telemt_upstream_connect_attempts_per_request{bucket="1"} 4854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 3791
telemt_me_reconnect_success_total 3775
telemt_me_reader_eof_total 3987
telemt_me_idle_close_by_peer_total 3987
telemt_me_route_drop_no_conn_total 66204
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173608
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 356
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3815
telemt_me_writer_restored_same_endpoint_total 3759
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 173402
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 1542312760 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 53587990072 (49.91 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21113.3 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60817
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1076
telemt_upstream_connect_attempt_total 6019
telemt_upstream_connect_success_total 6016
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 4773
telemt_me_reconnect_success_total 4742
telemt_me_reader_eof_total 5033
telemt_me_idle_close_by_peer_total 5033
telemt_me_route_drop_no_conn_total 17286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56834
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4778
telemt_me_writer_restored_same_endpoint_total 4733
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 57013
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 983256963 (937.71 MB)
telemt_user_octets_to_client{user="hello"} 19936398054 (18.57 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 21113.1 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324922
telemt_connections_bad_total 1544
telemt_handshake_timeouts_total 18863
telemt_upstream_connect_attempt_total 6353
telemt_upstream_connect_success_total 6351
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 4965
telemt_me_reconnect_success_total 4910
telemt_me_reader_eof_total 5112
telemt_me_idle_close_by_peer_total 5112
telemt_me_route_drop_no_conn_total 33090
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105778
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 286
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4872
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4869
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 106099
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 897535032 (855.96 MB)
telemt_user_octets_to_client{user="hello"} 32582600497 (30.34 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 21113.5 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95057
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 4857
telemt_upstream_connect_attempt_total 6345
telemt_upstream_connect_success_total 6317
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 5254
telemt_me_reconnect_success_total 5235
telemt_me_reader_eof_total 5551
telemt_me_idle_close_by_peer_total 5551
telemt_me_route_drop_no_conn_total 32248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88735
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5268
telemt_me_writer_restored_same_endpoint_total 5214
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 88720
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 617822000 (589.20 MB)
telemt_user_octets_to_client{user="hello"} 22720567836 (21.16 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21113.2 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113917
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 706
telemt_upstream_connect_attempt_total 7729
telemt_upstream_connect_success_total 7647
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 7729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 8051
telemt_me_reconnect_success_total 6553
telemt_me_reader_eof_total 6811
telemt_me_idle_close_by_peer_total 6811
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 29788
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108766
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 408
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 6647
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6537
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 108742
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 677451860 (646.07 MB)
telemt_user_octets_to_client{user="hello"} 23387742340 (21.78 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 38
```