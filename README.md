# Server Metrics 2026-03-12 05:59:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 65.3 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3094
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 102
telemt_upstream_connect_success_total 101
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 33
telemt_me_reconnect_success_total 33
telemt_me_route_drop_no_conn_total 453
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2975
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 7
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 20
telemt_me_writer_restored_same_endpoint_total 20
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 2975
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 21951836 (20.93 MB)
telemt_user_octets_to_client{user="hello"} 424398948 (404.74 MB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29685.7 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111187
telemt_connections_bad_total 964
telemt_handshake_timeouts_total 2882
telemt_upstream_connect_attempt_total 7919
telemt_upstream_connect_success_total 7914
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 6283
telemt_me_reconnect_success_total 6246
telemt_me_reader_eof_total 6640
telemt_me_idle_close_by_peer_total 6640
telemt_me_route_drop_no_conn_total 33185
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100563
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
telemt_me_writer_removed_unexpected_total 6299
telemt_me_writer_restored_same_endpoint_total 6237
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 100751
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 1575341659 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 42732281574 (39.80 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 29685.2 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428813
telemt_connections_bad_total 2086
telemt_handshake_timeouts_total 30676
telemt_upstream_connect_attempt_total 8206
telemt_upstream_connect_success_total 8204
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 6428
telemt_me_reconnect_success_total 6366
telemt_me_reader_eof_total 6663
telemt_me_idle_close_by_peer_total 6663
telemt_me_route_drop_no_conn_total 62072
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189720
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 738
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6344
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6325
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 190029
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 1977174644 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 57940243597 (53.96 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 29685.7 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158389
telemt_connections_bad_total 1694
telemt_handshake_timeouts_total 11395
telemt_upstream_connect_attempt_total 8570
telemt_upstream_connect_success_total 8533
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 7078
telemt_me_reconnect_success_total 7053
telemt_me_reader_eof_total 7484
telemt_me_idle_close_by_peer_total 7484
telemt_me_route_drop_no_conn_total 54200
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143028
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 204
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7095
telemt_me_writer_restored_same_endpoint_total 7032
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 142886
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 1715285016 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 43642705756 (40.65 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29685.5 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182607
telemt_connections_bad_total 304
telemt_handshake_timeouts_total 1141
telemt_upstream_connect_attempt_total 10450
telemt_upstream_connect_success_total 10334
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 10450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4903
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 10351
telemt_me_reconnect_success_total 8843
telemt_me_reader_eof_total 9209
telemt_me_idle_close_by_peer_total 9209
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 54650
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174793
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 626
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 160
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 8967
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8824
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 174752
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 1553322472 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 39954198816 (37.21 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 74
```