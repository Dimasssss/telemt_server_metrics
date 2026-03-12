# Server Metrics 2026-03-12 02:30:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 17133.0 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142017
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 2464
telemt_upstream_connect_attempt_total 3947
telemt_upstream_connect_success_total 3947
telemt_upstream_connect_attempts_per_request{bucket="1"} 3947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 3093
telemt_me_reconnect_success_total 3080
telemt_me_reader_eof_total 3248
telemt_me_idle_close_by_peer_total 3248
telemt_me_route_drop_no_conn_total 51051
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133907
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 209
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3116
telemt_me_writer_restored_same_endpoint_total 3064
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 133750
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 950188500 (906.17 MB)
telemt_user_octets_to_client{user="hello"} 39746175856 (37.02 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17133.7 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48429
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 816
telemt_upstream_connect_attempt_total 4955
telemt_upstream_connect_success_total 4952
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 3914
telemt_me_reconnect_success_total 3887
telemt_me_reader_eof_total 4113
telemt_me_idle_close_by_peer_total 4113
telemt_me_route_drop_no_conn_total 12973
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45104
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3916
telemt_me_writer_restored_same_endpoint_total 3878
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 45283
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 734851511 (700.81 MB)
telemt_user_octets_to_client{user="hello"} 17012949938 (15.84 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 17133.6 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228514
telemt_connections_bad_total 1163
telemt_handshake_timeouts_total 14818
telemt_upstream_connect_attempt_total 5237
telemt_upstream_connect_success_total 5235
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2234
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 4058
telemt_me_reconnect_success_total 4004
telemt_me_reader_eof_total 4141
telemt_me_idle_close_by_peer_total 4141
telemt_me_route_drop_no_conn_total 25486
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82417
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 157
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3958
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3963
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 82756
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 708156672 (675.35 MB)
telemt_user_octets_to_client{user="hello"} 27144903693 (25.28 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 17133.8 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72555
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 1933
telemt_upstream_connect_attempt_total 5096
telemt_upstream_connect_success_total 5069
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 4218
telemt_me_reconnect_success_total 4202
telemt_me_reader_eof_total 4441
telemt_me_idle_close_by_peer_total 4441
telemt_me_route_drop_no_conn_total 25639
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69505
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4228
telemt_me_writer_restored_same_endpoint_total 4181
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 69495
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 423508736 (403.89 MB)
telemt_user_octets_to_client{user="hello"} 16059892324 (14.96 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17133.6 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92912
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 624
telemt_upstream_connect_attempt_total 6387
telemt_upstream_connect_success_total 6325
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 6944
telemt_me_reconnect_success_total 5448
telemt_me_reader_eof_total 5651
telemt_me_idle_close_by_peer_total 5651
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 23472
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88393
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 311
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5531
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5432
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 88372
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 508442812 (484.89 MB)
telemt_user_octets_to_client{user="hello"} 19003683820 (17.70 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 37
```