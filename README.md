# Server Metrics 2026-03-15 04:58:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 24257.5 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310422
telemt_connections_bad_total 4601
telemt_handshake_timeouts_total 1470
telemt_upstream_connect_attempt_total 5207
telemt_upstream_connect_success_total 5189
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 5207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 4005
telemt_me_reconnect_success_total 3985
telemt_me_reader_eof_total 4202
telemt_me_idle_close_by_peer_total 4202
telemt_me_route_drop_no_conn_total 98017
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275922
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 482
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4031
telemt_me_writer_restored_same_endpoint_total 3974
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 275928
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 3041874524 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 98785858648 (92.00 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 24258.1 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121019
telemt_connections_bad_total 18111
telemt_handshake_timeouts_total 4394
telemt_upstream_connect_attempt_total 7308
telemt_upstream_connect_success_total 7276
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5784
telemt_me_reconnect_success_total 5755
telemt_me_reader_eof_total 6076
telemt_me_idle_close_by_peer_total 6076
telemt_me_route_drop_no_conn_total 26224
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95535
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5762
telemt_me_writer_restored_same_endpoint_total 5747
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 95831
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 1844349491 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 29533786252 (27.51 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 24258.3 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221895
telemt_connections_bad_total 3658
telemt_handshake_timeouts_total 24719
telemt_upstream_connect_attempt_total 5639
telemt_upstream_connect_success_total 5617
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 4428
telemt_me_reconnect_success_total 4409
telemt_me_reader_eof_total 4665
telemt_me_idle_close_by_peer_total 4665
telemt_me_route_drop_no_conn_total 50905
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186563
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 311
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4455
telemt_me_writer_restored_same_endpoint_total 4390
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 186429
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 1960331280 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 64264483044 (59.85 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 24258.0 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167512
telemt_connections_bad_total 34695
telemt_handshake_timeouts_total 11198
telemt_upstream_connect_attempt_total 8446
telemt_upstream_connect_success_total 8269
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 8446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11832
telemt_me_reconnect_success_total 7061
telemt_me_reader_eof_total 7450
telemt_me_idle_close_by_peer_total 7450
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 35998
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118707
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 7269
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7038
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 118710
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 986819132 (941.10 MB)
telemt_user_octets_to_client{user="hello"} 41179760136 (38.35 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 24259.0 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105533
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 1235
telemt_upstream_connect_attempt_total 5574
telemt_upstream_connect_success_total 5550
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4361
telemt_me_reconnect_success_total 4343
telemt_me_reader_eof_total 4629
telemt_me_idle_close_by_peer_total 4629
telemt_me_route_drop_no_conn_total 28471
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100791
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 417
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4385
telemt_me_writer_restored_same_endpoint_total 4335
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 100788
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 943411520 (899.71 MB)
telemt_user_octets_to_client{user="hello"} 33333910244 (31.04 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 58
```