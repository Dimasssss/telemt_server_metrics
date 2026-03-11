# Server Metrics 2026-03-11 23:11:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5200.3 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48356
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 1260
telemt_upstream_connect_success_total 1260
telemt_upstream_connect_attempts_per_request{bucket="1"} 1260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 975
telemt_me_reconnect_success_total 973
telemt_me_reader_eof_total 995
telemt_me_idle_close_by_peer_total 995
telemt_me_route_drop_no_conn_total 17931
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45538
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 120
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 988
telemt_me_writer_restored_same_endpoint_total 957
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 45519
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 278233808 (265.34 MB)
telemt_user_octets_to_client{user="hello"} 11748039040 (10.94 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 5201.1 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17820
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 174
telemt_upstream_connect_attempt_total 1470
telemt_upstream_connect_success_total 1470
telemt_upstream_connect_attempts_per_request{bucket="1"} 1470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 760
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 1181
telemt_me_reconnect_success_total 1173
telemt_me_reader_eof_total 1214
telemt_me_idle_close_by_peer_total 1214
telemt_me_route_drop_no_conn_total 4635
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16933
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1178
telemt_me_writer_restored_same_endpoint_total 1164
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 16931
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 511099080 (487.42 MB)
telemt_user_octets_to_client{user="hello"} 8098227408 (7.54 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 5200.9 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42858
telemt_connections_bad_total 290
telemt_handshake_timeouts_total 3625
telemt_upstream_connect_attempt_total 1988
telemt_upstream_connect_success_total 1988
telemt_upstream_connect_attempts_per_request{bucket="1"} 1988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1379
telemt_me_reconnect_success_total 1339
telemt_me_reader_eof_total 1294
telemt_me_idle_close_by_peer_total 1294
telemt_me_route_drop_no_conn_total 7922
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28298
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1258
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1298
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 28652
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 223235116 (212.89 MB)
telemt_user_octets_to_client{user="hello"} 14435476293 (13.44 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 5201.3 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26917
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 326
telemt_upstream_connect_attempt_total 1632
telemt_upstream_connect_success_total 1623
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 653
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1335
telemt_me_reconnect_success_total 1328
telemt_me_reader_eof_total 1358
telemt_me_idle_close_by_peer_total 1358
telemt_me_route_drop_no_conn_total 7825
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26144
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
telemt_me_writer_removed_unexpected_total 1334
telemt_me_writer_restored_same_endpoint_total 1307
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 26144
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 147031688 (140.22 MB)
telemt_user_octets_to_client{user="hello"} 10279660800 (9.57 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 5201.1 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33014
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 431
telemt_upstream_connect_attempt_total 2368
telemt_upstream_connect_success_total 2343
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 2368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2439
telemt_me_reconnect_success_total 2043
telemt_me_reader_eof_total 2032
telemt_me_idle_close_by_peer_total 2032
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 7537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31145
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
telemt_me_writer_removed_unexpected_total 2057
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 2038
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 31142
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 197253720 (188.12 MB)
telemt_user_octets_to_client{user="hello"} 8976181316 (8.36 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 28
```