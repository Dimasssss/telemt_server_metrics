# Server Metrics 2026-03-12 05:49:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 29073.4 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329064
telemt_connections_bad_total 1488
telemt_handshake_timeouts_total 5686
telemt_upstream_connect_attempt_total 6448
telemt_upstream_connect_success_total 6448
telemt_upstream_connect_attempts_per_request{bucket="1"} 6448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 130
telemt_me_reconnect_attempts_total 4998
telemt_me_reconnect_success_total 4980
telemt_me_reader_eof_total 5272
telemt_me_idle_close_by_peer_total 5272
telemt_me_route_drop_no_conn_total 116492
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313510
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 818
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 589
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5034
telemt_me_writer_restored_same_endpoint_total 4964
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 313202
telemt_user_connections_current{user="hello"} 1188
telemt_user_octets_from_client{user="hello"} 3276487028 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 95257884812 (88.72 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29074.0 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106643
telemt_connections_bad_total 764
telemt_handshake_timeouts_total 2535
telemt_upstream_connect_attempt_total 7820
telemt_upstream_connect_success_total 7815
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 6184
telemt_me_reconnect_success_total 6147
telemt_me_reader_eof_total 6540
telemt_me_idle_close_by_peer_total 6540
telemt_me_route_drop_no_conn_total 31950
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96733
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 305
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6199
telemt_me_writer_restored_same_endpoint_total 6138
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 96920
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 1501268867 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 40924318642 (38.11 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 29073.9 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420253
telemt_connections_bad_total 2084
telemt_handshake_timeouts_total 29898
telemt_upstream_connect_attempt_total 8121
telemt_upstream_connect_success_total 8119
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 6343
telemt_me_reconnect_success_total 6281
telemt_me_reader_eof_total 6578
telemt_me_idle_close_by_peer_total 6578
telemt_me_route_drop_no_conn_total 59694
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182072
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 710
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6258
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6240
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 182383
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 1923339228 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 55635989037 (51.82 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 29074.1 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153047
telemt_connections_bad_total 1694
telemt_handshake_timeouts_total 10904
telemt_upstream_connect_attempt_total 8447
telemt_upstream_connect_success_total 8410
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 6955
telemt_me_reconnect_success_total 6931
telemt_me_reader_eof_total 7362
telemt_me_idle_close_by_peer_total 7362
telemt_me_route_drop_no_conn_total 52458
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138223
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6973
telemt_me_writer_restored_same_endpoint_total 6910
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 138103
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 1485080240 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 41040561880 (38.22 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29074.0 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176050
telemt_connections_bad_total 304
telemt_handshake_timeouts_total 1115
telemt_upstream_connect_attempt_total 10375
telemt_upstream_connect_success_total 10259
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 10375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 10276
telemt_me_reconnect_success_total 8769
telemt_me_reader_eof_total 9134
telemt_me_idle_close_by_peer_total 9134
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 52105
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168365
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 613
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 398
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 8892
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8750
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 168343
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 1506461184 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 37876810648 (35.28 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 69
```