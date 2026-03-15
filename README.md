# Server Metrics 2026-03-15 02:15:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 14478.4 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176980
telemt_connections_bad_total 2017
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 3087
telemt_upstream_connect_success_total 3077
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 2338
telemt_me_reconnect_success_total 2325
telemt_me_reader_eof_total 2443
telemt_me_idle_close_by_peer_total 2443
telemt_me_route_drop_no_conn_total 54754
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155994
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 420
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2352
telemt_me_writer_restored_same_endpoint_total 2314
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 155980
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 1743507540 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 52638942144 (49.02 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 14478.9 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74283
telemt_connections_bad_total 13108
telemt_handshake_timeouts_total 3532
telemt_upstream_connect_attempt_total 4253
telemt_upstream_connect_success_total 4233
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 3186
telemt_me_reconnect_success_total 3166
telemt_me_reader_eof_total 3307
telemt_me_idle_close_by_peer_total 3307
telemt_me_route_drop_no_conn_total 14113
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55689
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3143
telemt_me_writer_restored_same_endpoint_total 3158
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 55985
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 1541163727 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 16314559932 (15.19 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 14479.1 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121250
telemt_connections_bad_total 2346
telemt_handshake_timeouts_total 10997
telemt_upstream_connect_attempt_total 3370
telemt_upstream_connect_success_total 3353
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 2610
telemt_me_reconnect_success_total 2600
telemt_me_reader_eof_total 2735
telemt_me_idle_close_by_peer_total 2735
telemt_me_route_drop_no_conn_total 26418
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105342
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 241
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2627
telemt_me_writer_restored_same_endpoint_total 2581
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 105253
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 1025721412 (978.20 MB)
telemt_user_octets_to_client{user="hello"} 34089256520 (31.75 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 14478.9 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103329
telemt_connections_bad_total 27123
telemt_handshake_timeouts_total 2626
telemt_upstream_connect_attempt_total 5444
telemt_upstream_connect_success_total 5328
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 5443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8122
telemt_me_reconnect_success_total 4574
telemt_me_reader_eof_total 4797
telemt_me_idle_close_by_peer_total 4797
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 19287
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71955
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 4725
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4555
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 71957
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 424752040 (405.08 MB)
telemt_user_octets_to_client{user="hello"} 13420940368 (12.50 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 14479.8 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61382
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 721
telemt_upstream_connect_attempt_total 3280
telemt_upstream_connect_success_total 3264
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2519
telemt_me_reconnect_success_total 2510
telemt_me_reader_eof_total 2651
telemt_me_idle_close_by_peer_total 2651
telemt_me_route_drop_no_conn_total 15442
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58847
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 213
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2529
telemt_me_writer_restored_same_endpoint_total 2502
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 58846
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 524525896 (500.23 MB)
telemt_user_octets_to_client{user="hello"} 20003536468 (18.63 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 49
```