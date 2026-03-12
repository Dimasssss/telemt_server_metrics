# Server Metrics 2026-03-12 05:44:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28767.0 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321660
telemt_connections_bad_total 1488
telemt_handshake_timeouts_total 5653
telemt_upstream_connect_attempt_total 6349
telemt_upstream_connect_success_total 6349
telemt_upstream_connect_attempts_per_request{bucket="1"} 6349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2954
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 4942
telemt_me_reconnect_success_total 4924
telemt_me_reader_eof_total 5210
telemt_me_idle_close_by_peer_total 5210
telemt_me_route_drop_no_conn_total 113911
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306290
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 796
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 575
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4976
telemt_me_writer_restored_same_endpoint_total 4908
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 305986
telemt_user_connections_current{user="hello"} 1295
telemt_user_octets_from_client{user="hello"} 3197624744 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 93607059000 (87.18 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28767.6 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104367
telemt_connections_bad_total 751
telemt_handshake_timeouts_total 2446
telemt_upstream_connect_attempt_total 7705
telemt_upstream_connect_success_total 7700
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 6113
telemt_me_reconnect_success_total 6076
telemt_me_reader_eof_total 6462
telemt_me_idle_close_by_peer_total 6462
telemt_me_route_drop_no_conn_total 31214
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 297
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6128
telemt_me_writer_restored_same_endpoint_total 6067
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 94781
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 1476528539 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 39768919726 (37.04 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 28767.6 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415842
telemt_connections_bad_total 2083
telemt_handshake_timeouts_total 29270
telemt_upstream_connect_attempt_total 8006
telemt_upstream_connect_success_total 8004
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3447
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 6271
telemt_me_reconnect_success_total 6209
telemt_me_reader_eof_total 6498
telemt_me_idle_close_by_peer_total 6498
telemt_me_route_drop_no_conn_total 58494
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178334
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 699
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6186
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6168
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 178646
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 1875039624 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 54607692177 (50.86 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 28767.9 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150032
telemt_connections_bad_total 1692
telemt_handshake_timeouts_total 10534
telemt_upstream_connect_attempt_total 8327
telemt_upstream_connect_success_total 8292
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 236
telemt_me_reconnect_attempts_total 6880
telemt_me_reconnect_success_total 6856
telemt_me_reader_eof_total 7277
telemt_me_idle_close_by_peer_total 7277
telemt_me_route_drop_no_conn_total 50492
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135526
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6898
telemt_me_writer_restored_same_endpoint_total 6835
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 135492
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 1387081936 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 39976867032 (37.23 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28767.6 (7h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172731
telemt_connections_bad_total 304
telemt_handshake_timeouts_total 1097
telemt_upstream_connect_attempt_total 10272
telemt_upstream_connect_success_total 10160
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 10272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 10220
telemt_me_reconnect_success_total 8713
telemt_me_reader_eof_total 9073
telemt_me_idle_close_by_peer_total 9073
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 49821
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165057
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 610
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 398
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 8836
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8694
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 165082
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 1471662192 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 37441045656 (34.87 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 85
```