# Server Metrics 2026-03-12 22:09:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 58239.1 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1904491
telemt_connections_bad_total 26060
telemt_handshake_timeouts_total 20912
telemt_upstream_connect_attempt_total 11458
telemt_upstream_connect_success_total 11392
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 11458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 598
telemt_me_reconnect_attempts_total 17318
telemt_me_reconnect_success_total 8463
telemt_me_reader_eof_total 9144
telemt_me_idle_close_by_peer_total 9143
telemt_me_route_drop_no_conn_total 744596
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1772439
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8477
telemt_desync_full_logged_total 2205
telemt_desync_suppressed_total 6272
telemt_desync_frames_bucket_total{bucket="1_2"} 2235
telemt_desync_frames_bucket_total{bucket="3_10"} 3052
telemt_desync_frames_bucket_total{bucket="gt_10"} 3190
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8860
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8450
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 1771919
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 26849622440 (25.01 GB)
telemt_user_octets_to_client{user="hello"} 626186881884 (583.18 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87859.8 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 791167
telemt_connections_bad_total 11690
telemt_handshake_timeouts_total 31211
telemt_upstream_connect_attempt_total 22203
telemt_upstream_connect_success_total 22174
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3409
telemt_me_reconnect_attempts_total 16231
telemt_me_reconnect_success_total 16136
telemt_me_reader_eof_total 17169
telemt_me_idle_close_by_peer_total 17169
telemt_me_route_drop_no_conn_total 256239
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 714433
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2996
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 2065
telemt_desync_frames_bucket_total{bucket="1_2"} 1185
telemt_desync_frames_bucket_total{bucket="3_10"} 984
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16301
telemt_me_writer_restored_same_endpoint_total 16127
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 716313
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 12032112084 (11.21 GB)
telemt_user_octets_to_client{user="hello"} 276103056251 (257.14 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 87859.7 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1641865
telemt_connections_bad_total 7742
telemt_handshake_timeouts_total 113238
telemt_upstream_connect_attempt_total 20510
telemt_upstream_connect_success_total 20504
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1217
telemt_me_reconnect_attempts_total 17007
telemt_me_reconnect_success_total 15758
telemt_me_reader_eof_total 16651
telemt_me_idle_close_by_peer_total 16650
telemt_me_route_drop_no_conn_total 540837
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1275870
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4968
telemt_desync_full_logged_total 1524
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 15908
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15717
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 1275476
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 19680412516 (18.33 GB)
telemt_user_octets_to_client{user="hello"} 472333598193 (439.89 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 87860.0 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1012170
telemt_connections_bad_total 12997
telemt_handshake_timeouts_total 71209
telemt_upstream_connect_attempt_total 22446
telemt_upstream_connect_success_total 22355
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 22446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1685
telemt_me_reconnect_attempts_total 25701
telemt_me_reconnect_success_total 17972
telemt_me_reader_eof_total 19199
telemt_me_idle_close_by_peer_total 19199
telemt_me_route_drop_no_conn_total 362214
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 881328
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 18356
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17951
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 384
telemt_user_connections_total{user="hello"} 880677
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 14169394928 (13.20 GB)
telemt_user_octets_to_client{user="hello"} 352527226836 (328.32 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87859.9 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1131735
telemt_connections_bad_total 12533
telemt_handshake_timeouts_total 9111
telemt_upstream_connect_attempt_total 26958
telemt_upstream_connect_success_total 26622
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 26958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 1442
telemt_me_reconnect_attempts_total 33264
telemt_me_reconnect_success_total 22225
telemt_me_reader_eof_total 23360
telemt_me_idle_close_by_peer_total 23360
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 424100
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041569
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3902
telemt_desync_full_logged_total 1359
telemt_desync_suppressed_total 2543
telemt_desync_frames_bucket_total{bucket="1_2"} 1147
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 1470
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 22826
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22181
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 601
telemt_user_connections_total{user="hello"} 1041431
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 12817725376 (11.94 GB)
telemt_user_octets_to_client{user="hello"} 369492366544 (344.12 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 45
```