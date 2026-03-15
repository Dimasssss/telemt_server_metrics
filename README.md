# Server Metrics 2026-03-15 00:28:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 8069.1 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106657
telemt_connections_bad_total 1239
telemt_handshake_timeouts_total 439
telemt_upstream_connect_attempt_total 1670
telemt_upstream_connect_success_total 1663
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1256
telemt_me_reconnect_success_total 1248
telemt_me_reader_eof_total 1300
telemt_me_idle_close_by_peer_total 1300
telemt_me_route_drop_no_conn_total 34309
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94696
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
telemt_me_writer_removed_unexpected_total 1266
telemt_me_writer_restored_same_endpoint_total 1237
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 94688
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 1026991116 (979.42 MB)
telemt_user_octets_to_client{user="hello"} 33797210668 (31.48 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 8069.5 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41880
telemt_connections_bad_total 6419
telemt_handshake_timeouts_total 2014
telemt_upstream_connect_attempt_total 2575
telemt_upstream_connect_success_total 2561
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1848
telemt_me_reconnect_success_total 1833
telemt_me_reader_eof_total 1886
telemt_me_idle_close_by_peer_total 1886
telemt_me_route_drop_no_conn_total 8642
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32001
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
telemt_me_writer_removed_unexpected_total 1800
telemt_me_writer_restored_same_endpoint_total 1825
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 32297
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 1340364887 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 7456936384 (6.94 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 8069.7 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68898
telemt_connections_bad_total 1432
telemt_handshake_timeouts_total 4747
telemt_upstream_connect_attempt_total 1799
telemt_upstream_connect_success_total 1790
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1379
telemt_me_reconnect_success_total 1375
telemt_me_reader_eof_total 1433
telemt_me_idle_close_by_peer_total 1433
telemt_me_route_drop_no_conn_total 16290
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61430
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1389
telemt_me_writer_restored_same_endpoint_total 1356
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 61349
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 721348424 (687.93 MB)
telemt_user_octets_to_client{user="hello"} 16558384064 (15.42 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 8069.6 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66557
telemt_connections_bad_total 19812
telemt_handshake_timeouts_total 931
telemt_upstream_connect_attempt_total 2771
telemt_upstream_connect_success_total 2696
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 2771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3580
telemt_me_reconnect_success_total 2277
telemt_me_reader_eof_total 2354
telemt_me_idle_close_by_peer_total 2354
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 10978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44649
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 74
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2335
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2263
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 44652
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 285053876 (271.85 MB)
telemt_user_octets_to_client{user="hello"} 10105485824 (9.41 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 8070.1 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37615
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 632
telemt_upstream_connect_attempt_total 1696
telemt_upstream_connect_success_total 1691
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1283
telemt_me_reconnect_success_total 1276
telemt_me_reader_eof_total 1332
telemt_me_idle_close_by_peer_total 1332
telemt_me_route_drop_no_conn_total 9525
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36079
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 161
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1288
telemt_me_writer_restored_same_endpoint_total 1268
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 36079
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 291559084 (278.05 MB)
telemt_user_octets_to_client{user="hello"} 15523272100 (14.46 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 26
```