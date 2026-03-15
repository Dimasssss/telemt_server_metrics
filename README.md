# Server Metrics 2026-03-15 00:18:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 7458.0 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98436
telemt_connections_bad_total 1183
telemt_handshake_timeouts_total 414
telemt_upstream_connect_attempt_total 1589
telemt_upstream_connect_success_total 1582
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1175
telemt_me_reconnect_success_total 1168
telemt_me_reader_eof_total 1219
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 31405
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89098
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1185
telemt_me_writer_restored_same_endpoint_total 1157
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 89090
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 1000969504 (954.60 MB)
telemt_user_octets_to_client{user="hello"} 32366768544 (30.14 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 7458.7 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39017
telemt_connections_bad_total 5923
telemt_handshake_timeouts_total 1993
telemt_upstream_connect_attempt_total 2475
telemt_upstream_connect_success_total 2461
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1748
telemt_me_reconnect_success_total 1734
telemt_me_reader_eof_total 1786
telemt_me_idle_close_by_peer_total 1786
telemt_me_route_drop_no_conn_total 8158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29703
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1700
telemt_me_writer_restored_same_endpoint_total 1726
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 29999
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1304968383 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 6960028880 (6.48 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 7458.8 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64581
telemt_connections_bad_total 1211
telemt_handshake_timeouts_total 4440
telemt_upstream_connect_attempt_total 1699
telemt_upstream_connect_success_total 1690
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1279
telemt_me_reconnect_success_total 1275
telemt_me_reader_eof_total 1331
telemt_me_idle_close_by_peer_total 1331
telemt_me_route_drop_no_conn_total 15476
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57682
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 118
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1287
telemt_me_writer_restored_same_endpoint_total 1256
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 57602
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 711891788 (678.91 MB)
telemt_user_octets_to_client{user="hello"} 16229821172 (15.12 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 7458.7 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62596
telemt_connections_bad_total 18902
telemt_handshake_timeouts_total 911
telemt_upstream_connect_attempt_total 2555
telemt_upstream_connect_success_total 2480
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 2555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3364
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 2133
telemt_me_idle_close_by_peer_total 2133
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 10149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41666
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 68
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2114
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2047
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 41669
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 278238816 (265.35 MB)
telemt_user_octets_to_client{user="hello"} 9771051908 (9.10 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 7459.5 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35608
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 600
telemt_upstream_connect_attempt_total 1608
telemt_upstream_connect_success_total 1603
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1195
telemt_me_reconnect_success_total 1189
telemt_me_reader_eof_total 1245
telemt_me_idle_close_by_peer_total 1245
telemt_me_route_drop_no_conn_total 8745
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34164
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1201
telemt_me_writer_restored_same_endpoint_total 1181
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 34164
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 285291008 (272.07 MB)
telemt_user_octets_to_client{user="hello"} 15249573584 (14.20 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 35
```