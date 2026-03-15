# Server Metrics 2026-03-15 00:54:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 9594.7 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125074
telemt_connections_bad_total 1429
telemt_handshake_timeouts_total 458
telemt_upstream_connect_attempt_total 2037
telemt_upstream_connect_success_total 2028
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1535
telemt_me_reconnect_success_total 1527
telemt_me_reader_eof_total 1596
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 39432
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109208
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 290
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1547
telemt_me_writer_restored_same_endpoint_total 1516
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 109200
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 1101334852 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 38227804612 (35.60 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 9595.2 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50458
telemt_connections_bad_total 8858
telemt_handshake_timeouts_total 2155
telemt_upstream_connect_attempt_total 2976
telemt_upstream_connect_success_total 2960
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2161
telemt_me_reconnect_success_total 2146
telemt_me_reader_eof_total 2223
telemt_me_idle_close_by_peer_total 2223
telemt_me_route_drop_no_conn_total 10286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37878
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
telemt_me_writer_removed_unexpected_total 2115
telemt_me_writer_restored_same_endpoint_total 2138
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 38174
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1400144751 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 9543073560 (8.89 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 9595.5 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79729
telemt_connections_bad_total 1557
telemt_handshake_timeouts_total 5709
telemt_upstream_connect_attempt_total 2184
telemt_upstream_connect_success_total 2174
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1677
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1749
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 18968
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71053
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1688
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 70971
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 769337532 (733.70 MB)
telemt_user_octets_to_client{user="hello"} 19193853180 (17.88 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 9595.3 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76190
telemt_connections_bad_total 22188
telemt_handshake_timeouts_total 1068
telemt_upstream_connect_attempt_total 3438
telemt_upstream_connect_success_total 3355
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 3438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4153
telemt_me_reconnect_success_total 2848
telemt_me_reader_eof_total 2962
telemt_me_idle_close_by_peer_total 2962
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 13346
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51639
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 82
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2911
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2833
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 51642
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 302643192 (288.62 MB)
telemt_user_octets_to_client{user="hello"} 10754534604 (10.02 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 9596.1 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42762
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 653
telemt_upstream_connect_attempt_total 2054
telemt_upstream_connect_success_total 2045
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1550
telemt_me_reconnect_success_total 1543
telemt_me_reader_eof_total 1621
telemt_me_idle_close_by_peer_total 1621
telemt_me_route_drop_no_conn_total 10811
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41046
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1558
telemt_me_writer_restored_same_endpoint_total 1535
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 41046
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 317363828 (302.66 MB)
telemt_user_octets_to_client{user="hello"} 16230578696 (15.12 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 28
```