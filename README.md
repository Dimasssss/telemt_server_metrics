# Server Metrics 2026-03-12 08:27:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8942.8 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273318
telemt_connections_bad_total 1314
telemt_handshake_timeouts_total 1931
telemt_upstream_connect_attempt_total 1734
telemt_upstream_connect_success_total 1723
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 782
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1266
telemt_me_reconnect_success_total 1258
telemt_me_reader_eof_total 1295
telemt_me_idle_close_by_peer_total 1295
telemt_me_route_drop_no_conn_total 91955
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264182
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1246
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 934
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 452
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1264
telemt_me_writer_restored_same_endpoint_total 1245
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 264092
telemt_user_connections_current{user="hello"} 1230
telemt_user_octets_from_client{user="hello"} 4144631304 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 74685675668 (69.56 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 38563.5 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207182
telemt_connections_bad_total 2665
telemt_handshake_timeouts_total 7355
telemt_upstream_connect_attempt_total 9965
telemt_upstream_connect_success_total 9959
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 596
telemt_me_reconnect_attempts_total 7897
telemt_me_reconnect_success_total 7856
telemt_me_reader_eof_total 8342
telemt_me_idle_close_by_peer_total 8342
telemt_me_route_drop_no_conn_total 59830
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181005
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 442
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 264
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7918
telemt_me_writer_restored_same_endpoint_total 7847
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 181300
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 2696362187 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 70461239978 (65.62 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 38563.3 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596446
telemt_connections_bad_total 2703
telemt_handshake_timeouts_total 44414
telemt_upstream_connect_attempt_total 10063
telemt_upstream_connect_success_total 10058
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 7851
telemt_me_reconnect_success_total 7781
telemt_me_reader_eof_total 8164
telemt_me_idle_close_by_peer_total 8164
telemt_me_route_drop_no_conn_total 117491
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339967
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1609
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 836
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7775
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7740
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 340237
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 3766194456 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 117736223689 (109.65 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 38563.6 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282742
telemt_connections_bad_total 1797
telemt_handshake_timeouts_total 19103
telemt_upstream_connect_attempt_total 10657
telemt_upstream_connect_success_total 10615
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 10657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 8726
telemt_me_reconnect_success_total 8694
telemt_me_reader_eof_total 9231
telemt_me_idle_close_by_peer_total 9231
telemt_me_route_drop_no_conn_total 93951
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235292
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 430
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 271
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8749
telemt_me_writer_restored_same_endpoint_total 8673
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 235117
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 2775489236 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 80994619236 (75.43 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 38563.5 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312099
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 2460
telemt_upstream_connect_attempt_total 12845
telemt_upstream_connect_success_total 12693
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 12845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 560
telemt_me_reconnect_attempts_total 12277
telemt_me_reconnect_success_total 10763
telemt_me_reader_eof_total 11202
telemt_me_idle_close_by_peer_total 11202
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 99410
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293958
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1194
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 797
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 10909
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10742
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 293900
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 3168670900 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 70558026772 (65.71 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 96
```