# Server Metrics 2026-03-12 05:54:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 29379.1 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336151
telemt_connections_bad_total 1533
telemt_handshake_timeouts_total 5747
telemt_upstream_connect_attempt_total 6494
telemt_upstream_connect_success_total 6494
telemt_upstream_connect_attempts_per_request{bucket="1"} 6494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 5044
telemt_me_reconnect_success_total 5026
telemt_me_reader_eof_total 5318
telemt_me_idle_close_by_peer_total 5318
telemt_me_route_drop_no_conn_total 119270
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320345
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 858
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5080
telemt_me_writer_restored_same_endpoint_total 5010
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 320036
telemt_user_connections_current{user="hello"} 1076
telemt_user_octets_from_client{user="hello"} 3372706824 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 97537910828 (90.84 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29379.8 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108599
telemt_connections_bad_total 886
telemt_handshake_timeouts_total 2643
telemt_upstream_connect_attempt_total 7882
telemt_upstream_connect_success_total 7877
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 6246
telemt_me_reconnect_success_total 6209
telemt_me_reader_eof_total 6602
telemt_me_idle_close_by_peer_total 6602
telemt_me_route_drop_no_conn_total 32435
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98395
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 306
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6261
telemt_me_writer_restored_same_endpoint_total 6200
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 98583
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 1533115027 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 41704254222 (38.84 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 29379.7 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424314
telemt_connections_bad_total 2086
telemt_handshake_timeouts_total 30296
telemt_upstream_connect_attempt_total 8168
telemt_upstream_connect_success_total 8166
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 6390
telemt_me_reconnect_success_total 6328
telemt_me_reader_eof_total 6626
telemt_me_idle_close_by_peer_total 6626
telemt_me_route_drop_no_conn_total 60678
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185681
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 733
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 481
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 380
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6306
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6287
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 185991
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 1943911236 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 56754241393 (52.86 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 29380.0 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155513
telemt_connections_bad_total 1694
telemt_handshake_timeouts_total 11208
telemt_upstream_connect_attempt_total 8523
telemt_upstream_connect_success_total 8486
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 7031
telemt_me_reconnect_success_total 7006
telemt_me_reader_eof_total 7437
telemt_me_idle_close_by_peer_total 7437
telemt_me_route_drop_no_conn_total 53296
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140397
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7048
telemt_me_writer_restored_same_endpoint_total 6985
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 140257
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 1617718848 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 42462869652 (39.55 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29379.8 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179382
telemt_connections_bad_total 304
telemt_handshake_timeouts_total 1131
telemt_upstream_connect_attempt_total 10427
telemt_upstream_connect_success_total 10311
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 10427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 10328
telemt_me_reconnect_success_total 8820
telemt_me_reader_eof_total 9185
telemt_me_idle_close_by_peer_total 9185
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 53446
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171610
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 616
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 8943
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8801
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 171583
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 1532414100 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 38620483808 (35.97 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 62
```