# Server Metrics 2026-03-15 04:12:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 21508.2 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268048
telemt_connections_bad_total 3629
telemt_handshake_timeouts_total 1317
telemt_upstream_connect_attempt_total 4566
telemt_upstream_connect_success_total 4548
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3494
telemt_me_reconnect_success_total 3476
telemt_me_reader_eof_total 3670
telemt_me_idle_close_by_peer_total 3670
telemt_me_route_drop_no_conn_total 84015
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237528
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 626
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 439
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3515
telemt_me_writer_restored_same_endpoint_total 3465
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 237500
telemt_user_connections_current{user="hello"} 919
telemt_user_octets_from_client{user="hello"} 2533859128 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 84516038828 (78.71 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 21508.8 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107592
telemt_connections_bad_total 18081
telemt_handshake_timeouts_total 4282
telemt_upstream_connect_attempt_total 6395
telemt_upstream_connect_success_total 6368
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2814
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5008
telemt_me_reconnect_success_total 4985
telemt_me_reader_eof_total 5260
telemt_me_idle_close_by_peer_total 5260
telemt_me_route_drop_no_conn_total 21717
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82578
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4983
telemt_me_writer_restored_same_endpoint_total 4977
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 82874
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 1740326999 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 24484736572 (22.80 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 21509.0 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187395
telemt_connections_bad_total 3607
telemt_handshake_timeouts_total 19751
telemt_upstream_connect_attempt_total 5003
telemt_upstream_connect_success_total 4982
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3922
telemt_me_reconnect_success_total 3903
telemt_me_reader_eof_total 4121
telemt_me_idle_close_by_peer_total 4121
telemt_me_route_drop_no_conn_total 40540
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160353
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 291
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3944
telemt_me_writer_restored_same_endpoint_total 3884
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 160231
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 1327766152 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 49561403632 (46.16 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 21508.8 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146995
telemt_connections_bad_total 32547
telemt_handshake_timeouts_total 7169
telemt_upstream_connect_attempt_total 7597
telemt_upstream_connect_success_total 7438
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 7597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9914
telemt_me_reconnect_success_total 6360
telemt_me_reader_eof_total 6670
telemt_me_idle_close_by_peer_total 6670
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 30075
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105194
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 149
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6527
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 6340
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 105199
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 867807172 (827.61 MB)
telemt_user_octets_to_client{user="hello"} 33819195224 (31.50 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 21509.6 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89964
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 1072
telemt_upstream_connect_attempt_total 4964
telemt_upstream_connect_success_total 4941
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 3882
telemt_me_reconnect_success_total 3867
telemt_me_reader_eof_total 4120
telemt_me_idle_close_by_peer_total 4120
telemt_me_route_drop_no_conn_total 23923
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86018
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 325
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3903
telemt_me_writer_restored_same_endpoint_total 3859
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 86016
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 724435192 (690.88 MB)
telemt_user_octets_to_client{user="hello"} 27354364192 (25.48 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 44
```