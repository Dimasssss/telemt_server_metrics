# Server Metrics 2026-03-15 03:01:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 17232.4 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209721
telemt_connections_bad_total 2810
telemt_handshake_timeouts_total 637
telemt_upstream_connect_attempt_total 3672
telemt_upstream_connect_success_total 3658
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2777
telemt_me_reconnect_success_total 2764
telemt_me_reader_eof_total 2919
telemt_me_idle_close_by_peer_total 2919
telemt_me_route_drop_no_conn_total 64774
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185554
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 508
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2795
telemt_me_writer_restored_same_endpoint_total 2753
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 185535
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 1987281012 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 67258024344 (62.64 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 17233.2 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85545
telemt_connections_bad_total 14572
telemt_handshake_timeouts_total 3698
telemt_upstream_connect_attempt_total 5064
telemt_upstream_connect_success_total 5041
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 3855
telemt_me_reconnect_success_total 3835
telemt_me_reader_eof_total 4029
telemt_me_idle_close_by_peer_total 4029
telemt_me_route_drop_no_conn_total 16691
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65118
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3823
telemt_me_writer_restored_same_endpoint_total 3827
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 65414
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 1596194371 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 20270277760 (18.88 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 17233.4 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144455
telemt_connections_bad_total 3007
telemt_handshake_timeouts_total 13316
telemt_upstream_connect_attempt_total 4029
telemt_upstream_connect_success_total 4011
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3126
telemt_me_reconnect_success_total 3114
telemt_me_reader_eof_total 3286
telemt_me_idle_close_by_peer_total 3286
telemt_me_route_drop_no_conn_total 31211
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125401
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3146
telemt_me_writer_restored_same_endpoint_total 3095
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 125311
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 1112155988 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 39278323316 (36.58 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 17233.2 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118930
telemt_connections_bad_total 29270
telemt_handshake_timeouts_total 3323
telemt_upstream_connect_attempt_total 6179
telemt_upstream_connect_success_total 6049
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 6179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8698
telemt_me_reconnect_success_total 5147
telemt_me_reader_eof_total 5420
telemt_me_idle_close_by_peer_total 5420
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 23053
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84554
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5304
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5128
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 84566
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 492166748 (469.37 MB)
telemt_user_octets_to_client{user="hello"} 23315136876 (21.71 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 17233.8 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71691
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 964
telemt_upstream_connect_attempt_total 3972
telemt_upstream_connect_success_total 3954
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3068
telemt_me_reconnect_success_total 3055
telemt_me_reader_eof_total 3247
telemt_me_idle_close_by_peer_total 3247
telemt_me_route_drop_no_conn_total 18560
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68528
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 233
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 167
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3082
telemt_me_writer_restored_same_endpoint_total 3047
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 68528
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 586760716 (559.58 MB)
telemt_user_octets_to_client{user="hello"} 22234214116 (20.71 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 41
```