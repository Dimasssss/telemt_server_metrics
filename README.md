# Server Metrics 2026-03-14 13:19:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 97.3 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6268
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 90
telemt_upstream_connect_success_total 89
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 90
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 23
telemt_me_reconnect_success_total 23
telemt_me_route_drop_no_conn_total 1341
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5835
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_user_connections_total{user="hello"} 5844
telemt_user_connections_current{user="hello"} 1549
telemt_user_octets_from_client{user="hello"} 41828288 (39.89 MB)
telemt_user_octets_to_client{user="hello"} 659493092 (628.94 MB)
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 102.5 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3261
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 191
telemt_upstream_connect_attempt_total 101
telemt_upstream_connect_success_total 100
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 35
telemt_me_reconnect_success_total 34
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2865
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 20
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_user_connections_total{user="hello"} 2828
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 14852640 (14.16 MB)
telemt_user_octets_to_client{user="hello"} 414013200 (394.83 MB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 43.5 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2616
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 1692
telemt_upstream_connect_success_total 1691
telemt_upstream_connect_attempts_per_request{bucket="1"} 1691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 103240
telemt_me_reconnect_success_total 120
telemt_me_route_drop_no_conn_total 62
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_me_writer_removed_unexpected_total 15
telemt_me_refill_failed_total 4806
telemt_me_writer_restored_same_endpoint_total 28
telemt_me_writer_restored_fallback_total 92
telemt_me_async_recovery_trigger_total 5773
telemt_user_connections_total{user="hello"} 2280
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 6860482 (6.54 MB)
telemt_user_octets_to_client{user="hello"} 116771387 (111.36 MB)
telemt_user_msgs_from_client{user="hello"} 5880
telemt_user_msgs_to_client{user="hello"} 13463
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 228859.8 (63h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2684370
telemt_connections_bad_total 23533
telemt_handshake_timeouts_total 355363
telemt_upstream_connect_attempt_total 70360
telemt_upstream_connect_success_total 67850
telemt_upstream_connect_fail_total 2373
telemt_upstream_connect_attempts_per_request{bucket="1"} 70086
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2372
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21025
telemt_me_reconnect_attempts_total 62203
telemt_me_reconnect_success_total 49411
telemt_me_reader_eof_total 52929
telemt_me_idle_close_by_peer_total 52921
telemt_me_route_drop_no_conn_total 886209
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2091273
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
telemt_pool_swap_total 196
telemt_me_writer_removed_unexpected_total 50242
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49386
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 831
telemt_user_connections_total{user="hello"} 2097953
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 30907213359 (28.78 GB)
telemt_user_octets_to_client{user="hello"} 744739013838 (693.59 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 115.4 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2865
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 100
telemt_upstream_connect_success_total 97
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 34
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 376
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2609
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_user_connections_total{user="hello"} 2609
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 35607180 (33.96 MB)
telemt_user_octets_to_client{user="hello"} 862953968 (822.98 MB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 115
```