# Server Metrics 2026-03-12 07:41:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 6188.5 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183102
telemt_connections_bad_total 1200
telemt_handshake_timeouts_total 1595
telemt_upstream_connect_attempt_total 1246
telemt_upstream_connect_success_total 1238
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 910
telemt_me_reconnect_success_total 905
telemt_me_reader_eof_total 916
telemt_me_idle_close_by_peer_total 916
telemt_me_route_drop_no_conn_total 61249
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176655
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 904
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 682
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 338
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 905
telemt_me_writer_restored_same_endpoint_total 892
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 176574
telemt_user_connections_current{user="hello"} 1125
telemt_user_octets_from_client{user="hello"} 2822174328 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 52117829864 (48.54 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35809.0 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176679
telemt_connections_bad_total 2462
telemt_handshake_timeouts_total 6812
telemt_upstream_connect_attempt_total 9226
telemt_upstream_connect_success_total 9221
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 7289
telemt_me_reconnect_success_total 7250
telemt_me_reader_eof_total 7710
telemt_me_idle_close_by_peer_total 7710
telemt_me_route_drop_no_conn_total 50947
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152860
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7309
telemt_me_writer_restored_same_endpoint_total 7241
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 153097
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 2318810871 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 61748404334 (57.51 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 35808.8 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540552
telemt_connections_bad_total 2537
telemt_handshake_timeouts_total 40382
telemt_upstream_connect_attempt_total 9473
telemt_upstream_connect_success_total 9471
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 7394
telemt_me_reconnect_success_total 7326
telemt_me_reader_eof_total 7690
telemt_me_idle_close_by_peer_total 7690
telemt_me_route_drop_no_conn_total 98950
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289113
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1308
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 905
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 461
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7315
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7285
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 289402
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 3120963116 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 104875552681 (97.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 35809.3 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247363
telemt_connections_bad_total 1782
telemt_handshake_timeouts_total 15372
telemt_upstream_connect_attempt_total 9996
telemt_upstream_connect_success_total 9956
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 8200
telemt_me_reconnect_success_total 8171
telemt_me_reader_eof_total 8679
telemt_me_idle_close_by_peer_total 8679
telemt_me_route_drop_no_conn_total 81339
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204478
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 352
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8222
telemt_me_writer_restored_same_endpoint_total 8150
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 204334
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 2385249348 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 67863636584 (63.20 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35809.1 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268677
telemt_connections_bad_total 348
telemt_handshake_timeouts_total 2209
telemt_upstream_connect_attempt_total 11988
telemt_upstream_connect_success_total 11846
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 11988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 235
telemt_me_reconnect_attempts_total 11561
telemt_me_reconnect_success_total 10049
telemt_me_reader_eof_total 10460
telemt_me_idle_close_by_peer_total 10460
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 83483
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252257
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1004
telemt_desync_full_logged_total 337
telemt_desync_suppressed_total 667
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 391
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 10189
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10028
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 252207
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 2423101960 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 60384714328 (56.24 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 90
```