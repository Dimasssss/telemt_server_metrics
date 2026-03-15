# Server Metrics 2026-03-15 04:38:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 23034.8 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290514
telemt_connections_bad_total 3941
telemt_handshake_timeouts_total 1402
telemt_upstream_connect_attempt_total 4904
telemt_upstream_connect_success_total 4886
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3746
telemt_me_reconnect_success_total 3726
telemt_me_reader_eof_total 3939
telemt_me_idle_close_by_peer_total 3939
telemt_me_route_drop_no_conn_total 91990
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257957
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 661
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3768
telemt_me_writer_restored_same_endpoint_total 3715
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 257928
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 2795947008 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 92187313600 (85.86 GB)
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 23035.6 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114298
telemt_connections_bad_total 18081
telemt_handshake_timeouts_total 4371
telemt_upstream_connect_attempt_total 6948
telemt_upstream_connect_success_total 6920
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5471
telemt_me_reconnect_success_total 5445
telemt_me_reader_eof_total 5739
telemt_me_idle_close_by_peer_total 5739
telemt_me_route_drop_no_conn_total 23941
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89045
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5450
telemt_me_writer_restored_same_endpoint_total 5437
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 89340
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1775450427 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 25711725188 (23.95 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 23035.8 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204857
telemt_connections_bad_total 3629
telemt_handshake_timeouts_total 22858
telemt_upstream_connect_attempt_total 5399
telemt_upstream_connect_success_total 5377
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 4231
telemt_me_reconnect_success_total 4212
telemt_me_reader_eof_total 4454
telemt_me_idle_close_by_peer_total 4454
telemt_me_route_drop_no_conn_total 45781
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174314
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4256
telemt_me_writer_restored_same_endpoint_total 4193
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 174188
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 1419708060 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 54713106676 (50.96 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 23035.6 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157931
telemt_connections_bad_total 33739
telemt_handshake_timeouts_total 9194
telemt_upstream_connect_attempt_total 8182
telemt_upstream_connect_success_total 8011
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 8182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11617
telemt_me_reconnect_success_total 6845
telemt_me_reader_eof_total 7224
telemt_me_idle_close_by_peer_total 7224
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 33366
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112513
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7054
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6825
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 112516
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 939376912 (895.86 MB)
telemt_user_octets_to_client{user="hello"} 37836436760 (35.24 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 23037.2 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97898
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 1157
telemt_upstream_connect_attempt_total 5339
telemt_upstream_connect_success_total 5315
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4169
telemt_me_reconnect_success_total 4152
telemt_me_reader_eof_total 4427
telemt_me_idle_close_by_peer_total 4427
telemt_me_route_drop_no_conn_total 25936
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93596
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 414
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4192
telemt_me_writer_restored_same_endpoint_total 4144
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 93593
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 815230204 (777.46 MB)
telemt_user_octets_to_client{user="hello"} 29464862768 (27.44 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 38
```