# Server Metrics 2026-03-13 22:08:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 144607.6 (40h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4514485
telemt_connections_bad_total 38278
telemt_handshake_timeouts_total 106904
telemt_upstream_connect_attempt_total 30198
telemt_upstream_connect_success_total 29990
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 30198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 6624
telemt_me_reconnect_attempts_total 30572
telemt_me_reconnect_success_total 20452
telemt_me_reader_eof_total 21945
telemt_me_idle_close_by_peer_total 21944
telemt_me_route_drop_no_conn_total 1704386
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4136414
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16476
telemt_desync_full_logged_total 4421
telemt_desync_suppressed_total 12055
telemt_desync_frames_bucket_total{bucket="1_2"} 4100
telemt_desync_frames_bucket_total{bucket="3_10"} 6296
telemt_desync_frames_bucket_total{bucket="gt_10"} 6080
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 21063
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20439
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 4138544
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 60897660684 (56.72 GB)
telemt_user_octets_to_client{user="hello"} 1309365267205 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44271.3 (12h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586677
telemt_connections_bad_total 42252
telemt_handshake_timeouts_total 12388
telemt_upstream_connect_attempt_total 12519
telemt_upstream_connect_success_total 12294
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 12519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 1904
telemt_me_reconnect_attempts_total 11450
telemt_me_reconnect_success_total 8021
telemt_me_reader_eof_total 8497
telemt_me_idle_close_by_peer_total 8496
telemt_me_route_drop_no_conn_total 214418
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508334
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 8242
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8013
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 510265
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 5538368637 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 166531807920 (155.09 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 174228.2 (48h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3282413
telemt_connections_bad_total 31413
telemt_handshake_timeouts_total 219622
telemt_upstream_connect_attempt_total 38626
telemt_upstream_connect_success_total 38605
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10273
telemt_me_reconnect_attempts_total 34559
telemt_me_reconnect_success_total 29608
telemt_me_reader_eof_total 31423
telemt_me_idle_close_by_peer_total 31422
telemt_me_route_drop_no_conn_total 1124448
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2724893
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8944
telemt_desync_full_logged_total 3006
telemt_desync_suppressed_total 5938
telemt_desync_frames_bucket_total{bucket="1_2"} 1481
telemt_desync_frames_bucket_total{bucket="3_10"} 3252
telemt_desync_frames_bucket_total{bucket="gt_10"} 4211
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 30045
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29567
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 2724158
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 44537953252 (41.48 GB)
telemt_user_octets_to_client{user="hello"} 963862082337 (897.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 174230.7 (48h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2141072
telemt_connections_bad_total 22815
telemt_handshake_timeouts_total 215351
telemt_upstream_connect_attempt_total 54226
telemt_upstream_connect_success_total 51779
telemt_upstream_connect_fail_total 2310
telemt_upstream_connect_attempts_per_request{bucket="1"} 53952
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2309
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20318
telemt_me_reconnect_attempts_total 45093
telemt_me_reconnect_success_total 36078
telemt_me_reader_eof_total 38709
telemt_me_idle_close_by_peer_total 38702
telemt_me_route_drop_no_conn_total 752371
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1751591
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3791
telemt_desync_full_logged_total 1213
telemt_desync_suppressed_total 2578
telemt_desync_frames_bucket_total{bucket="1_2"} 1000
telemt_desync_frames_bucket_total{bucket="3_10"} 1585
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 36671
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36054
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 593
telemt_user_connections_total{user="hello"} 1757472
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 27267045235 (25.39 GB)
telemt_user_octets_to_client{user="hello"} 657244592746 (612.11 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43664.0 (12h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626890
telemt_connections_bad_total 5846
telemt_handshake_timeouts_total 5800
telemt_upstream_connect_attempt_total 9915
telemt_upstream_connect_success_total 9596
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 9915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_keepalive_timeout_total 981
telemt_me_reconnect_attempts_total 34548
telemt_me_reconnect_success_total 7398
telemt_me_reader_eof_total 8381
telemt_me_idle_close_by_peer_total 8380
telemt_me_route_drop_no_conn_total 239062
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 587215
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1571
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 1083
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8312
telemt_me_refill_failed_total 845
telemt_me_writer_restored_same_endpoint_total 7393
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 914
telemt_user_connections_total{user="hello"} 587127
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 8605648248 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 187105648948 (174.26 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 50
```