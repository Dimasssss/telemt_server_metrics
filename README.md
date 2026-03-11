# Server Metrics 2026-03-11 23:32:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 6425.5 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58936
telemt_connections_bad_total 969
telemt_handshake_timeouts_total 195
telemt_upstream_connect_attempt_total 1568
telemt_upstream_connect_success_total 1568
telemt_upstream_connect_attempts_per_request{bucket="1"} 1568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1197
telemt_me_reconnect_success_total 1193
telemt_me_reader_eof_total 1236
telemt_me_idle_close_by_peer_total 1236
telemt_me_route_drop_no_conn_total 22029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54974
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1212
telemt_me_writer_restored_same_endpoint_total 1177
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 54947
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 332394532 (317.00 MB)
telemt_user_octets_to_client{user="hello"} 13994309924 (13.03 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 6426.2 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21050
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 1842
telemt_upstream_connect_success_total 1842
telemt_upstream_connect_attempts_per_request{bucket="1"} 1842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 957
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 1466
telemt_me_reconnect_success_total 1455
telemt_me_reader_eof_total 1510
telemt_me_idle_close_by_peer_total 1510
telemt_me_route_drop_no_conn_total 5397
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20053
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1460
telemt_me_writer_restored_same_endpoint_total 1446
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 20051
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 530504316 (505.93 MB)
telemt_user_octets_to_client{user="hello"} 9492943608 (8.84 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 6426.0 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50291
telemt_connections_bad_total 540
telemt_handshake_timeouts_total 4028
telemt_upstream_connect_attempt_total 2391
telemt_upstream_connect_success_total 2389
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1693
telemt_me_reconnect_success_total 1651
telemt_me_reader_eof_total 1616
telemt_me_idle_close_by_peer_total 1616
telemt_me_route_drop_no_conn_total 9692
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32633
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1578
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 32981
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 264723308 (252.46 MB)
telemt_user_octets_to_client{user="hello"} 18329388973 (17.07 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 6426.5 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31482
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 1967
telemt_upstream_connect_success_total 1955
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1580
telemt_me_reconnect_success_total 1572
telemt_me_reader_eof_total 1614
telemt_me_idle_close_by_peer_total 1614
telemt_me_route_drop_no_conn_total 9777
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30570
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1578
telemt_me_writer_restored_same_endpoint_total 1551
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 30569
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 167209280 (159.46 MB)
telemt_user_octets_to_client{user="hello"} 10791077776 (10.05 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6426.4 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40244
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 3039
telemt_upstream_connect_success_total 3010
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 4107
telemt_me_reconnect_success_total 2620
telemt_me_reader_eof_total 2657
telemt_me_idle_close_by_peer_total 2657
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 9202
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37545
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 57
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2679
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 2615
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 37542
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 221680544 (211.41 MB)
telemt_user_octets_to_client{user="hello"} 10868981476 (10.12 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 37
```