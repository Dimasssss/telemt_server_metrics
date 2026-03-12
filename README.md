# Server Metrics 2026-03-12 00:17:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9179.3 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80624
telemt_connections_bad_total 1322
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 2205
telemt_upstream_connect_success_total 2205
telemt_upstream_connect_attempts_per_request{bucket="1"} 2205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1704
telemt_me_reconnect_success_total 1698
telemt_me_reader_eof_total 1778
telemt_me_idle_close_by_peer_total 1778
telemt_me_route_drop_no_conn_total 29585
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75958
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 183
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1720
telemt_me_writer_restored_same_endpoint_total 1682
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 75904
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 567004272 (540.74 MB)
telemt_user_octets_to_client{user="hello"} 23230402584 (21.63 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9180.1 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28563
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 348
telemt_upstream_connect_attempt_total 2779
telemt_upstream_connect_success_total 2776
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 2093
telemt_me_reconnect_success_total 2073
telemt_me_reader_eof_total 2183
telemt_me_idle_close_by_peer_total 2183
telemt_me_route_drop_no_conn_total 7436
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26997
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2086
telemt_me_writer_restored_same_endpoint_total 2064
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 27176
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 571608067 (545.13 MB)
telemt_user_octets_to_client{user="hello"} 10453060338 (9.74 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 9179.8 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82176
telemt_connections_bad_total 553
telemt_handshake_timeouts_total 6550
telemt_upstream_connect_attempt_total 3166
telemt_upstream_connect_success_total 3164
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 2339
telemt_me_reconnect_success_total 2293
telemt_me_reader_eof_total 2319
telemt_me_idle_close_by_peer_total 2319
telemt_me_route_drop_no_conn_total 13303
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45030
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 84
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2227
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2252
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 45375
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 531996156 (507.35 MB)
telemt_user_octets_to_client{user="hello"} 20773224909 (19.35 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 9180.2 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43004
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 627
telemt_upstream_connect_attempt_total 2769
telemt_upstream_connect_success_total 2755
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2251
telemt_me_reconnect_success_total 2242
telemt_me_reader_eof_total 2338
telemt_me_idle_close_by_peer_total 2338
telemt_me_route_drop_no_conn_total 14368
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41656
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2255
telemt_me_writer_restored_same_endpoint_total 2221
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 41652
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 203380880 (193.96 MB)
telemt_user_octets_to_client{user="hello"} 11770586176 (10.96 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9180.1 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55673
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 512
telemt_upstream_connect_attempt_total 4175
telemt_upstream_connect_success_total 4140
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 5106
telemt_me_reconnect_success_total 3616
telemt_me_reader_eof_total 3715
telemt_me_idle_close_by_peer_total 3715
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 13358
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52066
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 122
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3681
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3610
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 52048
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 258120688 (246.16 MB)
telemt_user_octets_to_client{user="hello"} 13003859820 (12.11 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 29
```