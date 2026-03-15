# Server Metrics 2026-03-15 05:08:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 24867.9 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322571
telemt_connections_bad_total 4834
telemt_handshake_timeouts_total 1499
telemt_upstream_connect_attempt_total 5358
telemt_upstream_connect_success_total 5338
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 5358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 4111
telemt_me_reconnect_success_total 4091
telemt_me_reader_eof_total 4324
telemt_me_idle_close_by_peer_total 4324
telemt_me_route_drop_no_conn_total 102706
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287144
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 704
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4137
telemt_me_writer_restored_same_endpoint_total 4080
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 287162
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 3183872132 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 103725970764 (96.60 GB)
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 24868.9 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125739
telemt_connections_bad_total 18263
telemt_handshake_timeouts_total 4435
telemt_upstream_connect_attempt_total 7464
telemt_upstream_connect_success_total 7430
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 5895
telemt_me_reconnect_success_total 5866
telemt_me_reader_eof_total 6197
telemt_me_idle_close_by_peer_total 6197
telemt_me_route_drop_no_conn_total 27869
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99918
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 259
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5874
telemt_me_writer_restored_same_endpoint_total 5858
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 100214
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 1872826995 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 31567731704 (29.40 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 24869.2 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232768
telemt_connections_bad_total 4114
telemt_handshake_timeouts_total 25549
telemt_upstream_connect_attempt_total 5797
telemt_upstream_connect_success_total 5772
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 4540
telemt_me_reconnect_success_total 4518
telemt_me_reader_eof_total 4783
telemt_me_idle_close_by_peer_total 4783
telemt_me_route_drop_no_conn_total 54751
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194447
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 325
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4565
telemt_me_writer_restored_same_endpoint_total 4499
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 194268
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 2296640892 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 67896597968 (63.23 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 24868.9 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172957
telemt_connections_bad_total 35182
telemt_handshake_timeouts_total 12188
telemt_upstream_connect_attempt_total 8626
telemt_upstream_connect_success_total 8446
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 8626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11965
telemt_me_reconnect_success_total 7194
telemt_me_reader_eof_total 7593
telemt_me_idle_close_by_peer_total 7593
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 37256
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122466
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 190
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 7402
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7171
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 122469
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 1013746008 (966.78 MB)
telemt_user_octets_to_client{user="hello"} 43136465744 (40.17 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 24869.8 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110485
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 1264
telemt_upstream_connect_attempt_total 5736
telemt_upstream_connect_success_total 5712
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4480
telemt_me_reconnect_success_total 4461
telemt_me_reader_eof_total 4758
telemt_me_idle_close_by_peer_total 4758
telemt_me_route_drop_no_conn_total 30144
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105561
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4504
telemt_me_writer_restored_same_endpoint_total 4453
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 105557
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 993172128 (947.16 MB)
telemt_user_octets_to_client{user="hello"} 35670362880 (33.22 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 68
```