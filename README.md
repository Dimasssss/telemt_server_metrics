# Server Metrics 2026-03-11 23:06:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4894.8 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46071
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 1185
telemt_upstream_connect_success_total 1185
telemt_upstream_connect_attempts_per_request{bucket="1"} 1185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 900
telemt_me_reconnect_success_total 898
telemt_me_reader_eof_total 917
telemt_me_idle_close_by_peer_total 917
telemt_me_route_drop_no_conn_total 17017
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43305
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 910
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 43288
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 266354228 (254.02 MB)
telemt_user_octets_to_client{user="hello"} 11117983800 (10.35 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 4895.6 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17121
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 1406
telemt_upstream_connect_success_total 1406
telemt_upstream_connect_attempts_per_request{bucket="1"} 1406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 726
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1117
telemt_me_reconnect_success_total 1109
telemt_me_reader_eof_total 1149
telemt_me_idle_close_by_peer_total 1149
telemt_me_route_drop_no_conn_total 4483
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16285
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1113
telemt_me_writer_restored_same_endpoint_total 1100
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 16283
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 508664692 (485.10 MB)
telemt_user_octets_to_client{user="hello"} 7972233788 (7.42 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 4895.2 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41412
telemt_connections_bad_total 284
telemt_handshake_timeouts_total 3546
telemt_upstream_connect_attempt_total 1930
telemt_upstream_connect_success_total 1930
telemt_upstream_connect_attempts_per_request{bucket="1"} 1930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 739
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1321
telemt_me_reconnect_success_total 1282
telemt_me_reader_eof_total 1237
telemt_me_idle_close_by_peer_total 1237
telemt_me_route_drop_no_conn_total 7443
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27036
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1201
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1241
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 27390
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 215188108 (205.22 MB)
telemt_user_octets_to_client{user="hello"} 13140654889 (12.24 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 4895.5 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25608
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 1576
telemt_upstream_connect_success_total 1567
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 627
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 1279
telemt_me_reconnect_success_total 1273
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1303
telemt_me_route_drop_no_conn_total 7292
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24850
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1279
telemt_me_writer_restored_same_endpoint_total 1252
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 24850
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 141850948 (135.28 MB)
telemt_user_octets_to_client{user="hello"} 9898099812 (9.22 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4895.5 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31308
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 410
telemt_upstream_connect_attempt_total 2182
telemt_upstream_connect_success_total 2158
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 2253
telemt_me_reconnect_success_total 1858
telemt_me_reader_eof_total 1846
telemt_me_idle_close_by_peer_total 1846
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 7096
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29566
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 31
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_removed_unexpected_total 1871
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 1853
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 29562
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 192876772 (183.94 MB)
telemt_user_octets_to_client{user="hello"} 8366023036 (7.79 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 40
```