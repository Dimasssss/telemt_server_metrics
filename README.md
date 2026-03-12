# Server Metrics 2026-03-12 04:12:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23254.7 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213274
telemt_connections_bad_total 1369
telemt_handshake_timeouts_total 3554
telemt_upstream_connect_attempt_total 5302
telemt_upstream_connect_success_total 5302
telemt_upstream_connect_attempts_per_request{bucket="1"} 5302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 4153
telemt_me_reconnect_success_total 4136
telemt_me_reader_eof_total 4371
telemt_me_idle_close_by_peer_total 4371
telemt_me_route_drop_no_conn_total 76731
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202505
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 434
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4180
telemt_me_writer_restored_same_endpoint_total 4120
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 202274
telemt_user_connections_current{user="hello"} 765
telemt_user_octets_from_client{user="hello"} 1873265132 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 63352497040 (59.00 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 23255.6 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71617
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1379
telemt_upstream_connect_attempt_total 6497
telemt_upstream_connect_success_total 6494
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 5163
telemt_me_reconnect_success_total 5131
telemt_me_reader_eof_total 5445
telemt_me_idle_close_by_peer_total 5445
telemt_me_route_drop_no_conn_total 20879
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66015
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5170
telemt_me_writer_restored_same_endpoint_total 5122
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 66197
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 1079129055 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 22403651994 (20.87 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 23255.3 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345058
telemt_connections_bad_total 1772
telemt_handshake_timeouts_total 21365
telemt_upstream_connect_attempt_total 6833
telemt_upstream_connect_success_total 6831
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 5356
telemt_me_reconnect_success_total 5299
telemt_me_reader_eof_total 5525
telemt_me_idle_close_by_peer_total 5525
telemt_me_route_drop_no_conn_total 38465
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122348
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 396
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 256
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5267
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5258
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 122665
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 1116152192 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 38061846745 (35.45 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 23255.8 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108605
telemt_connections_bad_total 499
telemt_handshake_timeouts_total 6189
telemt_upstream_connect_attempt_total 6905
telemt_upstream_connect_success_total 6874
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 6905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 5722
telemt_me_reconnect_success_total 5701
telemt_me_reader_eof_total 6046
telemt_me_idle_close_by_peer_total 6046
telemt_me_route_drop_no_conn_total 36635
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100461
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 155
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5737
telemt_me_writer_restored_same_endpoint_total 5680
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 100447
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 788119600 (751.61 MB)
telemt_user_octets_to_client{user="hello"} 28481932016 (26.53 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 23255.4 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127974
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 755
telemt_upstream_connect_attempt_total 8731
telemt_upstream_connect_success_total 8642
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 8731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4147
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 8959
telemt_me_reconnect_success_total 7457
telemt_me_reader_eof_total 7727
telemt_me_idle_close_by_peer_total 7727
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 34803
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122325
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 452
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 7564
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7440
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 122300
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 807212016 (769.82 MB)
telemt_user_octets_to_client{user="hello"} 26904584692 (25.06 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 51
```