# Server Metrics 2026-03-15 03:37:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 19370.5 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236298
telemt_connections_bad_total 3209
telemt_handshake_timeouts_total 1106
telemt_upstream_connect_attempt_total 4108
telemt_upstream_connect_success_total 4093
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 3126
telemt_me_reconnect_success_total 3112
telemt_me_reader_eof_total 3289
telemt_me_idle_close_by_peer_total 3289
telemt_me_route_drop_no_conn_total 72798
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209077
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 546
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 382
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3147
telemt_me_writer_restored_same_endpoint_total 3101
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 209054
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 2250816156 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 74838190500 (69.70 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 19370.9 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94768
telemt_connections_bad_total 16023
telemt_handshake_timeouts_total 3794
telemt_upstream_connect_attempt_total 5790
telemt_upstream_connect_success_total 5766
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4493
telemt_me_reconnect_success_total 4471
telemt_me_reader_eof_total 4711
telemt_me_idle_close_by_peer_total 4711
telemt_me_route_drop_no_conn_total 18910
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72592
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 129
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4461
telemt_me_writer_restored_same_endpoint_total 4463
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 72888
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 1650270015 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 21890948976 (20.39 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 19371.2 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163797
telemt_connections_bad_total 3219
telemt_handshake_timeouts_total 15750
telemt_upstream_connect_attempt_total 4496
telemt_upstream_connect_success_total 4477
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 3505
telemt_me_reconnect_success_total 3489
telemt_me_reader_eof_total 3681
telemt_me_idle_close_by_peer_total 3681
telemt_me_route_drop_no_conn_total 35496
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141899
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 279
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3525
telemt_me_writer_restored_same_endpoint_total 3470
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 141796
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 1214587552 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 42690486704 (39.76 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 19371.0 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131544
telemt_connections_bad_total 30908
telemt_handshake_timeouts_total 4742
telemt_upstream_connect_attempt_total 6736
telemt_upstream_connect_success_total 6599
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 6736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9162
telemt_me_reconnect_success_total 5610
telemt_me_reader_eof_total 5916
telemt_me_idle_close_by_peer_total 5916
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 26431
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93986
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5772
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5591
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 93995
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 693434828 (661.31 MB)
telemt_user_octets_to_client{user="hello"} 25333890444 (23.59 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 19371.7 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80339
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 1024
telemt_upstream_connect_attempt_total 4475
telemt_upstream_connect_success_total 4456
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 3484
telemt_me_reconnect_success_total 3470
telemt_me_reader_eof_total 3699
telemt_me_idle_close_by_peer_total 3699
telemt_me_route_drop_no_conn_total 21232
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76805
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 274
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 195
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3503
telemt_me_writer_restored_same_endpoint_total 3462
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 76803
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 645103628 (615.22 MB)
telemt_user_octets_to_client{user="hello"} 24349338016 (22.68 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 38
```