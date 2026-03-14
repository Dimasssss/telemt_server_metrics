# Server Metrics 2026-03-14 13:44:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 1629.0 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65328
telemt_connections_bad_total 95
telemt_handshake_timeouts_total 845
telemt_upstream_connect_attempt_total 262
telemt_upstream_connect_success_total 260
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 149
telemt_me_reconnect_success_total 145
telemt_me_reader_eof_total 124
telemt_me_idle_close_by_peer_total 124
telemt_me_route_drop_no_conn_total 24484
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62149
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 146
telemt_me_writer_restored_same_endpoint_total 136
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 62144
telemt_user_connections_current{user="hello"} 1663
telemt_user_octets_from_client{user="hello"} 1179095944 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 13475094288 (12.55 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 1634.5 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27731
telemt_connections_bad_total 1387
telemt_handshake_timeouts_total 1213
telemt_upstream_connect_attempt_total 320
telemt_upstream_connect_success_total 318
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 209
telemt_me_reconnect_success_total 207
telemt_me_reader_eof_total 178
telemt_me_idle_close_by_peer_total 178
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 8626
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22687
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 118
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 202
telemt_me_writer_restored_same_endpoint_total 196
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_user_connections_total{user="hello"} 22652
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 442640388 (422.13 MB)
telemt_user_octets_to_client{user="hello"} 9514850140 (8.86 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 1497.2 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42699
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 6928
telemt_upstream_connect_attempt_total 246
telemt_upstream_connect_success_total 243
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 134
telemt_me_reconnect_success_total 129
telemt_me_reader_eof_total 94
telemt_me_idle_close_by_peer_total 94
telemt_me_route_drop_no_conn_total 10494
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33462
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 64
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 115
telemt_me_writer_restored_same_endpoint_total 96
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 33439
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 543783940 (518.59 MB)
telemt_user_octets_to_client{user="hello"} 9637996256 (8.98 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 230389.6 (63h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2705097
telemt_connections_bad_total 23549
telemt_handshake_timeouts_total 363195
telemt_upstream_connect_attempt_total 70669
telemt_upstream_connect_success_total 68157
telemt_upstream_connect_fail_total 2375
telemt_upstream_connect_attempts_per_request{bucket="1"} 70395
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2374
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21051
telemt_me_reconnect_attempts_total 62467
telemt_me_reconnect_success_total 49672
telemt_me_reader_eof_total 53202
telemt_me_idle_close_by_peer_total 53194
telemt_me_route_drop_no_conn_total 890136
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2103206
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4124
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 2768
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 1688
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 50504
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49647
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 832
telemt_user_connections_total{user="hello"} 2109965
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 31040472847 (28.91 GB)
telemt_user_octets_to_client{user="hello"} 748097857958 (696.72 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 1647.4 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26466
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 301
telemt_upstream_connect_success_total 294
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 185
telemt_me_reconnect_success_total 183
telemt_me_reader_eof_total 164
telemt_me_idle_close_by_peer_total 164
telemt_me_route_drop_no_conn_total 9036
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23951
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 187
telemt_me_writer_restored_same_endpoint_total 165
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 23956
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 341034032 (325.24 MB)
telemt_user_octets_to_client{user="hello"} 10499561060 (9.78 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 90
```