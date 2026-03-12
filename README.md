# Server Metrics 2026-03-12 02:45:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18051.3 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150303
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 2780
telemt_upstream_connect_attempt_total 4153
telemt_upstream_connect_success_total 4153
telemt_upstream_connect_attempts_per_request{bucket="1"} 4153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 3246
telemt_me_reconnect_success_total 3233
telemt_me_reader_eof_total 3414
telemt_me_idle_close_by_peer_total 3414
telemt_me_route_drop_no_conn_total 54277
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141676
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 226
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 158
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3270
telemt_me_writer_restored_same_endpoint_total 3217
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 141516
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 1011451952 (964.60 MB)
telemt_user_octets_to_client{user="hello"} 43785213640 (40.78 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18052.1 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51138
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 863
telemt_upstream_connect_attempt_total 5178
telemt_upstream_connect_success_total 5175
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 4082
telemt_me_reconnect_success_total 4055
telemt_me_reader_eof_total 4294
telemt_me_idle_close_by_peer_total 4294
telemt_me_route_drop_no_conn_total 13680
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47687
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 61
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4084
telemt_me_writer_restored_same_endpoint_total 4046
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 47866
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 760275547 (725.06 MB)
telemt_user_octets_to_client{user="hello"} 17596033854 (16.39 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 18051.9 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254212
telemt_connections_bad_total 1327
telemt_handshake_timeouts_total 15746
telemt_upstream_connect_attempt_total 5499
telemt_upstream_connect_success_total 5497
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2353
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 4267
telemt_me_reconnect_success_total 4213
telemt_me_reader_eof_total 4361
telemt_me_idle_close_by_peer_total 4361
telemt_me_route_drop_no_conn_total 27148
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87189
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4169
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4172
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 87527
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 735313728 (701.25 MB)
telemt_user_octets_to_client{user="hello"} 28132609241 (26.20 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 18052.3 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79261
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 2541
telemt_upstream_connect_attempt_total 5366
telemt_upstream_connect_success_total 5338
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 4434
telemt_me_reconnect_success_total 4418
telemt_me_reader_eof_total 4672
telemt_me_idle_close_by_peer_total 4672
telemt_me_route_drop_no_conn_total 27134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75544
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4446
telemt_me_writer_restored_same_endpoint_total 4397
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 75532
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 484528728 (462.08 MB)
telemt_user_octets_to_client{user="hello"} 16976239592 (15.81 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18052.1 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97366
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 642
telemt_upstream_connect_attempt_total 6664
telemt_upstream_connect_success_total 6599
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 6664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 7166
telemt_me_reconnect_success_total 5669
telemt_me_reader_eof_total 5887
telemt_me_idle_close_by_peer_total 5887
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 24891
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92711
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 329
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5755
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5653
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 92688
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 551173836 (525.64 MB)
telemt_user_octets_to_client{user="hello"} 20473336728 (19.07 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 33
```