# Server Metrics 2026-03-15 02:56:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 16927.5 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205851
telemt_connections_bad_total 2746
telemt_handshake_timeouts_total 626
telemt_upstream_connect_attempt_total 3594
telemt_upstream_connect_success_total 3582
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 2744
telemt_me_reconnect_success_total 2731
telemt_me_reader_eof_total 2879
telemt_me_idle_close_by_peer_total 2879
telemt_me_route_drop_no_conn_total 63555
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182051
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 504
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2760
telemt_me_writer_restored_same_endpoint_total 2720
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 182030
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 1964972052 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 65872393260 (61.35 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 16928.0 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84396
telemt_connections_bad_total 14572
telemt_handshake_timeouts_total 3688
telemt_upstream_connect_attempt_total 4968
telemt_upstream_connect_success_total 4946
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 3803
telemt_me_reconnect_success_total 3783
telemt_me_reader_eof_total 3972
telemt_me_idle_close_by_peer_total 3972
telemt_me_route_drop_no_conn_total 16286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64012
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3769
telemt_me_writer_restored_same_endpoint_total 3775
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 64308
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 1586051675 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 19669564732 (18.32 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 16928.3 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141548
telemt_connections_bad_total 2841
telemt_handshake_timeouts_total 13170
telemt_upstream_connect_attempt_total 3959
telemt_upstream_connect_success_total 3941
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3100
telemt_me_reconnect_success_total 3088
telemt_me_reader_eof_total 3260
telemt_me_idle_close_by_peer_total 3260
telemt_me_route_drop_no_conn_total 30619
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122830
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3120
telemt_me_writer_restored_same_endpoint_total 3069
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 122740
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 1100820016 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 38254685396 (35.63 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 16928.0 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117086
telemt_connections_bad_total 29000
telemt_handshake_timeouts_total 3173
telemt_upstream_connect_attempt_total 6097
telemt_upstream_connect_success_total 5969
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 6097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8661
telemt_me_reconnect_success_total 5111
telemt_me_reader_eof_total 5379
telemt_me_idle_close_by_peer_total 5379
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 22553
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83144
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 132
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5266
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5092
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 83156
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 483630084 (461.23 MB)
telemt_user_octets_to_client{user="hello"} 22166406416 (20.64 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 16928.8 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70498
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 963
telemt_upstream_connect_attempt_total 3882
telemt_upstream_connect_success_total 3865
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 3022
telemt_me_reconnect_success_total 3010
telemt_me_reader_eof_total 3198
telemt_me_idle_close_by_peer_total 3198
telemt_me_route_drop_no_conn_total 18231
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67374
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3036
telemt_me_writer_restored_same_endpoint_total 3002
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 67374
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 581636732 (554.69 MB)
telemt_user_octets_to_client{user="hello"} 22012581452 (20.50 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 31
```